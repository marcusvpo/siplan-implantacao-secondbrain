---
tipo: Processo
fase_implantacao: "5. Conversão de Dados"
responsavel: Equipe de Conversão
dependencia: "[[[Processo] 3. Análise de Aderência do Processo de Negócio]]"
tags:
  - #conversao
  - #banco_de_dados
  - #cross_conversao
status_atual: #ativo
---
# [Processo] 5. Conversão do Banco de Dados

Migração dos dados históricos do cartório para o novo sistema Siplan.

## 📋 Cenário Atual (As-Is)

**Acionamento e Distribuição:**
- O chamado é encaminhado para a equipe de Conversão logo após superados os Gates iniciais.
- A distribuição de atividades é realizada de forma informal pelo Coordenador (**Marcus**) via Teams (mensagem ou chamada), direcionada pelas especialidades de cada analista:
  - **Luciane:** Especialista em Notas (Orion TN).
  - **Ademar:** Especialista em Protesto (Orion PRO).
  - **Eduardo:** Especialista em Registro (Orion REG).

**Prazos Estimados e Desafios:**
- **Sistemas Siplan/Control-M ou já convertidos:** 2 a 3 dias (uso de motores de conversão existentes).
- **Sistemas novos (inéditos):** 1 a 2 meses ou mais. Exige estudo minucioso da estrutura de tabelas do concorrente para o desenvolvimento do novo motor de conversão (Conversor). Se houver criptografias ou bloqueios de senha, solicita-se suporte à empresa do sistema legado.
- **Bases Corrompidas ou Criptografadas:** A equipe de Conversão entra em contato com a TI do cartório ou com a empresa do sistema legado. O processo é geralmente bem-sucedido, mas o desenvolvimento pode levar meses.

**Contingência de Prazo Estourado (Bases Desconhecidas):**
Quando o cartório possui um sistema cujos dados nunca foram convertidos pela Siplan e a confecção do conversor ultrapassa meses (estourando um possível acordo comercial), a contingência é **institucional**:
- A **Diretoria** entra no circuito para conversar diretamente com o cliente.
- É explicado o lado técnico e a complexidade do novo conversor.
- A própria Diretoria acalma o cliente e reagenda as expectativas de data. A implantação aguarda a finalização técnica antes de qualquer envio a campo.

## 🚀 Visão de Futuro & Ideias (To-Be)

- **Gestão pela Fila do HUB:** 
  - Dentro de cada projeto em "Gerenciar Projetos" (na etapa 3), haverá o botão **"Enviar para Conversão"**.
  - Ao clicar, o projeto cai na fila de Conversão em **"Gestão de Atividades"** como pendente, até que um membro da Conversão assuma o projeto, mudando o status para `in_progress`.
- **Acompanhamento por Timeline interna (Posts):**
  - O analista que assumir a conversão usará um sistema de **posts de andamento (timeline)** no HUB para registrar atualizações técnicas rápidas, eliminando a dependência de e-mails ou mensagens descentralizadas.
- **Formalização da Migração de Dados:** Criar e padronizar o documento de Formalização de Migração de Dados (definindo o que será ou não convertido) para WEBRI, Orion PRO e Orion REG, assim como já existe no Orion TN.
- **Conversor de Imagens:** Avaliar e priorizar a criação de um motor de conversão de imagens dos sistemas legados da Siplan para a linha Orion (e também conversor para o Orion GED).
- **Catálogo de Conversores no Hub:** Criar uma base de dados indexada no Hub com todos os sistemas do mercado e o "Nível de Maturidade" do nosso conversor para cada um. Isso permitirá que o Comercial saiba, *no ato da venda*, se aquele cartório demorará 3 dias ou 3 meses para converter.

**Próxima etapa:** [[[Processo] 6. Homologação da Conversão de Dados]]

- **Relatório de Quantidades:** Exigência de que o processo de conversão emtiar relatórios de batimento (quantidades na origem e no destino) para transparência.
- **Volume de Imagens na Aderência:** O levantamento do tamanho ocupado pelas imagens do cliente (em GB), essencial para dimensionar discos do ambiente Docker, será responsabilidade dos Analistas de Implantação já na fase de Análise de Aderência.
- **Motor GED (Prioridade Absoluta):** Foco emergencial na finalização e estruturação dos conversores de imagens do Control-M PRO e sistemas legados, a fim de eliminar o backlog acumulado de cartórios de protesto sem as imagens migradas.
