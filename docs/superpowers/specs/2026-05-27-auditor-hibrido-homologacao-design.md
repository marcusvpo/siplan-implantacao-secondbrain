# Design: Auditor Híbrido de Homologação (IA + n8n)

## Contexto e Problema
No processo de implantação da Siplan, a **Fase 6 (Homologação da Conversão de Dados)** é o momento crítico onde o Analista de Implantação valida se os dados do sistema legado foram corretamente convertidos para o banco do Siplan (Orion/etc). 
Atualmente, este processo é:
- **Manual e por Amostragem:** O analista abre as telas dos dois sistemas para comparar os dados.
- **Lento e Propenso a Erros:** Textos de certidões truncados, erros financeiros e perda de vínculos entre entidades podem passar despercebidos na amostragem e explodir apenas na semana de virada (Go-Live).

## Visão da Solução
Uma arquitetura híbrida combinando um utilitário local (para acesso seguro aos bancos no cliente) com a inteligência do n8n na nuvem (para processamento em massa e auditoria via IA).

---

## Fluxo Prático Passo a Passo

### 1. O Extrator de Homologação (Ação Local)
Para evitar expor os bancos de dados do cartório à internet, o processo se inicia no ambiente seguro do cliente.

- **Ação do Analista:** O implantador acessa o servidor do cartório via conexão remota e executa um script leve (ex: `extrator_siplan.exe`).
- **Input:** O analista informa as credenciais do banco de origem (Legado) e do banco destino (Siplan provisório).
- **Extração em Lote:** O script roda queries pré-definidas (via catálogo de conversores) buscando milhares de registros pareados através da chave de conversão (ex: Ato ID 1000 no Legado corresponde ao Ato ID 5050 no Siplan).
- **Envio Seguro:** O script não avalia nada. Ele empacota os dados estruturados (valores, datas, chaves) e os textos (conteúdo da averbação/certidão) em um JSON e envia via `POST HTTPS` para um webhook seguro do n8n da Siplan.

### 2. Gatilho e Triagem no n8n (A Nuvem)
- **Recepção:** O fluxo do n8n recebe o payload enviado pelo extrator.
- **Separação de Rotas:** O n8n divide os dados recebidos em duas trilhas paralelas:
  1. Trilha de Dados Rígidos (Validação Lógica)
  2. Trilha de Textos Livres (Auditoria via IA)

### 3. Trilha de Dados Rígidos (Rápida, sem IA)
Nem tudo precisa de IA. Dados exatos são validados por código nativo no n8n.
- **Validação Financeira:** `Emolumentos Legado == Emolumentos Siplan?`
- **Validação Estrutural:** `Ato migrou com a Data correta? Selos estão preenchidos?`
- O n8n acumula os erros lógicos encontrados em uma lista temporária.

### 4. Trilha de Auditoria Semântica (A Mágica da IA)
Aqui a Inteligência Artificial resolve o que a lógica simples não consegue.
- **Loteamento (Batching):** O n8n agrupa os textos de certidões e atos em pequenos lotes e envia para a API de um LLM (como OpenAI, Anthropic ou Gemini).
- **O Prompt Estrito:** O n8n envia a seguinte instrução para a IA:
  > *"Atue como um auditor de migração de dados de cartório. Compare o Texto de Origem com o Texto de Destino. Verifique se houve truncamento (texto cortado no final), perda de informações vitais (nomes, datas, valores) ou quebra grave de formatação (caracteres estranhos). Ignorar mudanças cosméticas (ex: tudo maiúsculo vs capitalizado). Retorne um JSON com: status ('Erro' ou 'OK') e justificativa."*
- **Retorno:** A IA devolve as avaliações estruturadas. Se o texto da averbação quebrou na linha 5 ou perdeu um CPF no meio da conversão, a IA flagra.

### 5. Geração do Doc de Inconsistências
- **Consolidação:** O n8n junta os erros estruturais (Passo 3) e os erros semânticos encontrados pela IA (Passo 4).
- **Criação do Relatório:** Utilizando um nó de formatação (ou gerador de PDF/Excel no n8n), o fluxo compila o **Doc de Inconsistências**.
- **Entrega e Alerta:** 
  - O n8n envia o documento diretamente por e-mail para o Analista de Implantação e para o responsável da Equipe de Conversão.
  - Automaticamente, atualiza a etapa no **Siplan Hub**, alterando o status da implantação para "Pendente de Correção na Conversão".

---

## Vantagens
- **100% de Cobertura:** Substitui a amostragem humana pela validação de todo o lote extraído.
- **Segurança:** O script local não abre portas; apenas envia dados ativamente para a nuvem Siplan.
- **Escalabilidade:** A inteligência não roda na máquina do cartório, não impactando a performance deles.
- **Registro:** O Siplan Hub passa a ter um histórico rastreável do que deu errado em cada homologação, alimentando melhorias para futuros conversores.
