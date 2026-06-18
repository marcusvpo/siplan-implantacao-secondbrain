---
tipo: Guia
area: Implantação Funcional
fase_implantacao: Geral
responsavel: Coordenação Geral / Implantação
tags:
  - #guia
  - #reuniao
  - #processos
  - #alinhamento
  - #as_is_to_be
  - #gestao_mudanca
created: 2026-06-18
status_atual: #ativo
---

# Guia de Reunião: Alinhamento de Processos e Rollout do Siplan Hub (Pós-Reuniões de 25/05)

Este documento atua como um guia tático de reunião para formalizar as decisões e mudanças de processos de implantação discutidas e acordadas entre os implantadores, coordenação e times correlacionados (Comercial, Conversão, Modelos e TI) na semana de **25/05/2026**.

O foco estratégico deste novo modelo operacional é a **blindagem da equipe de campo (implantadores)**, a **eliminação do retrabalho** e a **descentralização da atualização de dados no backoffice**, utilizando o **Siplan Hub** como o orquestrador invisível das integrações.

---

## 📌 1. Visão Geral da Mudança Cultural: O Siplan Hub como "Orquestrador Invisível"

*   **O Paradoxo da Adoção Forçada:** Ficou definido que não forçaremos o preenchimento de rotinas complexas no Hub por quem está na rua (Implantadores e Comercial). O retrabalho e a barreira cultural geravam mais fricção que benefícios.
*   **O Novo Papel:**
    *   **Implantador (Campo):** O Hub atua como um **Painel de Bordo de Visualização**. O analista de campo consulta a agenda, status das conversões e templates, sem a obrigação de fazer check-ins diários ou preencher logs que já são digitados no SAC 0800. A agenda SAP/0800 continua a oficial.
    *   **Backoffice (TI, Conversão, Modelos e Gestão):** Esses times operam e atualizam o Hub ativamente. As atualizações alimentam o Hub e disparam automações via **n8n** (Outlook/Deep Links e WhatsApp) para notificar as pontas sem tirá-las de seus canais habituais.

---

## 🔄 2. Matriz Comparativa de Processos: AS-IS (Antes) vs. TO-BE (Depois)

Abaixo estão as 8 principais mudanças estruturadas com a comparação detalhada dos cenários e o impacto gerado por cada decisão.

### A. Abertura de Chamado e Passagem de Bastão (Handoff Comercial)

| Dimensão | Cenário Anterior (AS-IS) | Novo Modelo Definido (TO-BE) |
| :--- | :--- | :--- |
| **Padrão de Informação** | O Comercial abria chamados de implantação no SAC 0800 contendo apenas dados administrativos básicos e trâmites de OP desestruturados. | Criação do formulário obrigatório de **Handoff Comercial** no Siplan Hub. |
| **Esforço da Coordenação** | A coordenação de implantação criava os projetos no Hub manualmente e precisava investigar individualmente escopos, modelos e restrições. | O projeto é criado no Hub de forma 100% automatizada via n8n (consumindo views do EPP no 0800). O Comercial apenas complementa o formulário de Handoff no Hub. |
| **Visibilidade Técnica** | Detalhes como contatos-chave, restrições físicas do cartório e sistemas legados de terceiros ficavam dispersos ou ocultos até a viagem. | O output gerado pelo formulário do Hub (bloco padronizado de Passagem de Bastão) é obrigatoriamente colado como trâmite inicial no 0800, alinhando as restrições desde o Dia Zero. |

### B. Processo de Análise de Aderência do Processo de Negócio

| Dimensão | Cenário Anterior (AS-IS) | Novo Modelo Definido (TO-BE) |
| :--- | :--- | :--- |
| **Padronização** | Cada analista utilizava seu próprio checklist em arquivo Word (baseado em modelos antigos do Julio ou Vieira) e preenchia de forma livre, enviando por e-mail. | Unificação de checklists em um template mestre padrão no Siplan Hub, gerado automaticamente conforme o sistema do contrato (Orion TN, PRO ou REG). |
| **Gargalo de Dimensionamento** | Falta de perguntas específicas sobre estrutura física, gerando erros críticos (como enviar uma equipe subdimensionada para um cartório de 5 andares). | O checklist agora integra obrigatoriamente perguntas estruturais: número de andares, dimensão do cartório, distribuição de setores e perfil tecnológico dos usuários. |
| **Execução por Origem** | Não havia distinção de esforço. Análises de bases conhecidas (Siplan/Control-M) tomavam o mesmo tempo de bases concorrentes complexas. | **Diferenciação Metodológica:**<br>• *Sistemas Concorrentes (Externos):* Análise preferencialmente **presencial** (2 a 3 dias) para mapear processos.<br>• *Legados Siplan/Control-M:* Análise **remota e ágil** devido ao conhecimento prévio das tabelas. |
| **Preparação Prévia** | O analista começava a aderência sem qualquer informação da serventia, gerando atrasos em campo. | O Comercial envia ao cliente um questionário simplificado *self-service* logo após o fechamento para coletar dados iniciais e planejar a viagem. |

### C. Gestão e Homologação de Modelos (Orion TN)

| Dimensão | Cenário Anterior (AS-IS) | Novo Modelo Definido (TO-BE) |
| :--- | :--- | :--- |
| **Visibilidade de Progresso** | O processo de edição/parametrização de modelos era uma "caixa preta" sem controle no Hub. O time de campo não sabia o que estava pronto. | O time de Modelos (**Hugo Januário** e **Bruno Fernandes**) é obrigado a utilizar o Hub para subir arquivos finalizados e atualizar o status (Pendente/Pronto). |
| **Escopo de Go-Live** | O cliente enviava dezenas de minutas de uma só vez (muitas vezes mais de 40) e exigia todas prontas na virada, gerando atrasos crônicos de cronograma. | **Estratégia do Top 5:** Foco total na parametrização e homologação dos **5 modelos mais utilizados** pelo cartório para garantir o go-live nas datas acordadas. O restante é adaptado de forma gradual no pós-implantação. |
| **Ação do Comercial** | O Comercial recebia as minutas tardiamente ou não orientava o envio rápido das peças de modelos ao fechar a venda. | O Comercial passa a instruir o cliente a enviar as minutas físicas imediatamente após a assinatura do contrato direto para a fila de Modelos. |

### D. Levantamento de Infraestrutura e Dependência da TI do Cliente

| Dimensão | Cenário Anterior (AS-IS) | Novo Modelo Definido (TO-BE) |
| :--- | :--- | :--- |
| **Qualidade da Informação** | Aceitavam-se respostas vagas da TI terceirizada do cartório (ex: "está tudo OK" ou "máquinas novas") sem dados específicos de hardware. | Exigência técnica de especificações completas (processador, memória, armazenamento livre, modelo de impressoras) preenchidas formalmente na planilha. |
| **Gargalo de Hardware** | Clientes prometiam realizar melhorias no servidor e estações, mas não as faziam até a virada, gerando lentidão no Orion e culpa errônea ao sistema. | **Gate de Verificação de Infraestrutura:** Check-up obrigatório conduzido remotamente na semana anterior à viagem. Se as adequações do servidor não foram de fato realizadas, a viagem é bloqueada. |
| **Bloqueio de Acesso** | Algumas TIs locais barravam o acesso do implantador via TeamViewer e forneciam dados incompletos por formulários manuais. | Se o parceiro de TI local recusar acesso remoto ou omitir dados, o time de implantação aciona o Comercial para notificar o oficial do risco de congelamento do projeto. |

### E. Otimização do Tempo de Campo: Instalação Remota de Estações

| Dimensão | Cenário Anterior (AS-IS) | Novo Modelo Definido (TO-BE) |
| :--- | :--- | :--- |
| **Esforço de Campo** | O analista gastava de 4 a 5 horas presenciais fazendo tarefas manuais e repetitivas: instalando integradores estação por estação e criando atalhos locais. | Divisão de escopo: A equipe de Infraestrutura/Backoffice realiza a instalação do integrador e criação de atalhos em 100% das estações de forma **remota** antes da viagem. |
| **Parametrização de Base** | Configuração manual de perfis e layouts de segurança em campo, devido à impossibilidade de exportar configurações padrão vinculadas ao CNS. | Utilização de bases pré-parametrizadas criadas remotamente por ferramentas automáticas do backoffice (VMs, Docker e bancos otimizados - Kleverson/Diego). |

### F. Mapeamento de Imagens GED e Dimensionamento de Servidor

| Dimensão | Cenário Anterior (AS-IS) | Novo Modelo Definido (TO-BE) |
| :--- | :--- | :--- |
| **Mapeamento de Volume** | Não havia levantamento sistemático do tamanho das imagens legadas. O espaço no servidor era dimensionado apenas para o banco SQL bruto. | O analista de campo mapeia ativamente as pastas físicas de imagens GED legadas na fase de **Análise de Aderência**, estimando o volume total em GB. |
| **Problemas na Virada** | O conversor de imagens (TIF para PDF) e o Docker exigem temporariamente o dobro de espaço. Servidores estouravam o disco na virada, gerando atraso e "rabo técnico". | A informação em GB é cruzada com a Infraestrutura e Conversão de forma antecipada para dimensionamento correto do servidor com margem de segurança antes do final de semana da virada. |

### G. Pré-Homologação e Homologação da Conversão de Dados

| Dimensão | Cenário Anterior (AS-IS) | Novo Modelo Definido (TO-BE) |
| :--- | :--- | :--- |
| **Garantia de Qualidade** | A equipe de Conversão entregava a base bruta e o analista de campo validava sem checklist padrão, encontrando erros críticos tardiamente ou em campo. | **Fluxo de Pré-Homologação Interna (Conversão):** A equipe de Conversão roda rotinas quantitativas de batimento (registros de origem vs destino) antes de liberar a base. |
| **Ritual de Validação** | Validação no "De-Para" visual e inconsistências apontadas de maneira informal por e-mails com Words avulsos. | Uso obrigatório do checklist de homologação guiado por fluxos (top-down) no Siplan Hub. O analista de implantação gera a lista de ajustes diretamente no sistema. |
| **Controle de SLA** | O analista homologava a base na semana da viagem de forma apressada por falta de tempo. | Prazo estendido para homologação funcional remota, garantindo que a base provisória esteja testada e corrigida com antecedência confortável antes do agendamento final. |

### H. Transição para o Pós-Implantação e Linha de Defesa

| Dimensão | Cenário Anterior (AS-IS) | Novo Modelo Definido (TO-BE) |
| :--- | :--- | :--- |
| **Evidência de Treinamento** | Não havia documento mandatório com assinatura física. Clientes alegavam ao suporte que "o analista não ensinou" rotinas, gerando retrabalhos injustos. | **Obrigatoriedade do Formulário de Treinamento:** Coleta obrigatória de assinaturas dos escreventes no checklist de rotinas ensinadas e exceções identificadas (ex: falta de certificado digital). |
| **Evidência de ROI para o Titular** | O tabelião (tomador de decisão ausente na rotina) ouvia reclamações de funcionários resistentes à mudança, gerando percepção ruim do Orion. | Apresentação obrigatória do **Relatório de Ganhos Operacionais** ao Titular no fim do projeto, evidenciando dados de eficiência obtidos com o novo sistema. |
| **Abertura do Canal de Suporte** | O grupo de WhatsApp com o Pós-Implantação era criado na sexta-feira à tarde, momento em que o analista de campo estava incomunicável em deslocamento. | O grupo de WhatsApp do Pós-Implantação é criado na **quinta-feira à tarde**, garantindo uma janela de transição ativa e conjunta na sexta-feira enquanto o analista está no local. |
| **Corte do Cordão Umbilical** | Grupos de WhatsApp de pós permaneciam ativos indefinidamente, sobrecarregando os analistas e impedindo a centralização dos atendimentos. | O pós-implantação via WhatsApp dura estritamente **2 semanas** (estendendo-se em serventias excepcionais). Após o prazo, o grupo é encerrado e o cliente migra para o SAC 0800. |

---

## 🛠️ 3. Regras de Conduta e Padrões Operacionais Confirmados

### I. Postura Profissional perante Falhas Sistêmicas
Quando ocorrerem bugs ou instabilidade no cliente, o analista deve manter uma postura corporativa de foco na solução:
*   ❌ **O que NÃO dizer:** *"Isso é problema do conversor da equipe do Ademar"* ou *"A equipe de produtos do Hugo não arrumou esse bug ainda"*.
*   👍 **O que dizer:** *"Nossa equipe técnica interna já está analisando essa situação para liberar um ajuste rápido. O problema é da nossa empresa e vamos resolver em conjunto"*.

### II. Protocolo de Rollback em Horários Alternativos
Se ocorrer uma falha crítica na virada do banco de dados (corrupção) durante a madrugada do final de semana e a Diretoria estiver inalcançável:
1. O analista de campo **não tem autonomia** para decretar o Rollback unilateral por conta própria.
2. A orientação técnica primária é manter o ambiente seguro, aguardar o primeiro horário da manhã seguinte e comunicar imediatamente a Diretoria.
3. As equipes de suporte técnico e conversão serão acionadas para análise de contenção rápida antes de formalizar o retrocesso.

---

## 📅 4. Próximos Passos e Metas de Implantação (Roadmap de Adoção)

1.  **Lançamento do Handoff Comercial:** Comercial inicia o uso obrigatório do formulário do Hub para passagens de bastão de novas OPs.
2.  **Atualização de Status de Modelos:** Hugo e Bruno passam a preencher a tela de minutas do Hub semanalmente para dar transparência ao time de campo.
3.  **Checklist de Homologação e Aderência:** Unificação definitiva dos formulários de análise de aderência (incorporando a estimativa de GB de imagens) e validação da conversão de dados.
4.  **Treinamento no Aplicativo Siplan On-Field:** Homologação do uso de gravação de áudios diários pelos analistas de campo para geração automatizada dos relatórios finais de viagem.
