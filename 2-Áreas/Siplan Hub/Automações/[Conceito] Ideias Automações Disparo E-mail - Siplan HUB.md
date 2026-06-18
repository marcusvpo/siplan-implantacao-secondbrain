---
tipo: Conceito
area: Siplan Hub
tags:
  - #projeto
  - #automacao
  - #email
  - #requisito
status_atual: #concluido
---

## 🔍 Detalhamento das 4 Automações Propostas

Todos os e-mails vindo de disparo das automações devem começar com "[SIPLAN HUB] " para reconhecimento imediato da equipe e de entender que isso é um e-mail relacionado a alguma ação do Hub.

### Automação 1: Criação de Novo Projeto via Automação 0800
Como esta ação ocorre por um integrador externo (via API/Webhook inserindo dados na tabela `projects`), o gatilho será uma **Trigger de Banco de Dados** no Supabase no evento `INSERT` (filtrando apenas novas inserções).

*   **Campos de Dados do Projeto Utilizados:**
    *   Nome do cliente/cartório: `client_name` (mapeado na interface [ProjectV2](file:///c:/Users/marcu/Desktop/Projects/siplan-hub/src/types/ProjectV2.ts#L67-L155) como `clientName`).
    *   Número do chamado: `ticket_number` (mapeado como `ticketNumber`).
    *   Sistema contratado: `system_type` (mapeado como `systemType`, ex: `"Orion TN"`, `"Orion PRO"`).
    *   Horas vendidas: `sold_hours` (mapeado como `soldHours`).
*   **Regra de Disparo (Condição):** `INSERT` na tabela `projects` onde a coluna `external_id` ou dados do chamado estejam preenchidos. Não disparar se for um `UPDATE`.
*   **Mapeamento de E-mails:**
    1.  **Solicitação de Infra:** Enviar para **Marcus, Alex Silva e Hugo Januário**.
        *   *Assunto:* `[SIPLAN HUB] [Infraestrutura] Solicitação de Análise de Infra — {clientName} (#{ticketNumber})`
        * Criar body completo e bem estruturado
    2.  **Agendamento de Aderência:** Enviar para **Marcus e Maria**.
        *   *Assunto:* `[SIPLAN HUB] [Aderência] Agendar Análise — {clientName} (#{ticketNumber}) — Sistema: {systemType}`
        * Criar body completo e bem estruturado
    3.  **Kickoff do Projeto:** Enviar para **Marcus, Marcos Ortiz e Bruno Fernandes**.
        *   *Assunto:* ` [SIPLAN HUB] [Kickoff] Novo Projeto Cadastrado — {clientName} (#{ticketNumber})`
        *   *Destaque no Corpo:* Mostrar `soldHours` (Horas vendidas) e `systemType` (Sistema).
        * Criar body completo e bem estruturado

---

### Automação 2: Análise de Aderência Finalizada
Gatilho acionado no frontend na tela de preenchimento do formulário quando o analista clica em finalizar.

*   **Componente do React:** [ProjectAdherenceForm.tsx](file:///c:/Users/marcu/Desktop/Projects/siplan-hub/src/pages/ProjectAdherenceForm.tsx#L287-L331) na função `handleFinalizeForm`.
*   **Ação no Banco de Dados:** Atualização da coluna `adherence_status` para `'approved'` na tabela `projects` (ou via hook [useUpsertFormResponse](file:///c:/Users/marcu/Desktop/Projects/siplan-hub/src/hooks/useProjectFormResponse.ts) que atualiza o status do formulário de aderência para `approved`).
*   **Campos de Dados Utilizados:**
    *   Metadados: `clientName`, `ticketNumber`, `systemType`.
    *   Analista Executor: `lastUpdatedBy` (ou `adherence_responsible` de [adherence](file:///c:/Users/marcu/Desktop/Projects/siplan-hub/src/types/ProjectV2.ts#L175-L190)) -  GARANTIR QUE PEGUE O CAMPO CORRETAMENTE QUE INDICA O ANALISTA RESPONSÁVEL POR AQUELA ANÁLISE DE ADERÊNCIA.
    *   Parecer Técnico Final (Veredito): `finalVerdict` (Salvo no JSON da coluna `notes` ou `responses` de aderência. Opções padrão: `"Totalmente Aderente"`, `"Aderente com Restrições"` ou `"Não Aderente / Impeditivo"`).
    *   Justificativa / Parecer Técnico: `finalNotes`.
    *   Itens com Impacto: Extraídos de forma dinâmica usando a função técnica `getImpactedItems` (linhas 37–64 do [ProjectAdherenceForm.tsx](file:///c:/Users/marcu/Desktop/Projects/siplan-hub/src/pages/ProjectAdherenceForm.tsx#L37-L64)).
*   **Anexo PDF:** A tela possui um modo de visualização de impressão nativo (`?print=true`) estruturado em HTML limpo nas linhas 425–773 do [ProjectAdherenceForm.tsx](file:///c:/Users/marcu/Desktop/Projects/siplan-hub/src/pages/ProjectAdherenceForm.tsx#L425-L773). O microsserviço de e-mail pode renderizar esta URL via headless browser (ex: Puppeteer) e anexar o PDF gerado.
*   **Destinatários e Condicionais de Sistema (`systemType`):**
    *   **Fixos:** Marcus, Marcos Ortiz, Bruno Fernandes e o analista que enviou (`lastUpdatedBy`).
    *   **Condicional:**
        *   Se `systemType` for `"Orion TN"` ou `"OrionTN"` $\rightarrow$ Incluir **Luan Caldeira** em cópia.
        *   Se `systemType` for `"Orion PRO"` ou `"OrionPRO"` $\rightarrow$ Incluir **Maurilio Camargo** em cópia.
        *   Se `systemType` for `"Orion REG"` ou `"OrionREG"` $\rightarrow$ Incluir **Amanda Flor** em cópia.

---

### Automação 3: Nova Conversão Enviada para a Fila
Gatilho disparado quando o implantador ou gestor clica no botão para enviar o banco de dados do cliente para a fila de migração.

*   **Código do React/Hook:** Função `sendToConversion` no hook [useConversionQueue.ts](file:///c:/Users/marcu/Desktop/Projects/siplan-hub/src/hooks/useConversionQueue.ts#L166-L213).
*   **Ação no Banco de Dados:** Inserção (`INSERT`) na tabela `conversion_queue` com a coluna `queue_status` definida como `'pending'`.
*   **Campos de Dados Utilizados:**
    *   `client_name` e `ticket_number` (obtidos através do join de relacionamento da tabela `projects` com a `conversion_queue`).
    *   `system_type` do cliente.
*   **Destinatários:** **Marcus, Ademar, Luciane, Eduardo Silva e Marcos Ortiz**.
*   **Assunto do E-mail:** `[Fila de Conversão] Nova Conversão Pendente — {clientName} (#{ticketNumber})`

---

### Automação 4: Checklist Comercial Respondido pelo Cliente
Gatilho disparado no portal público externo quando o cliente finaliza o preenchimento de suas informações estruturais.

*   **Componente / Hook:** Função `handleSubmit` ou `handleDynamicSubmit` no hook público [usePublicChecklist.ts](file:///c:/Users/marcu/Desktop/Projects/siplan-hub/src/hooks/usePublicChecklist.ts#L133-L209), que chama `submitChecklist` do [useCommercialChecklists.ts](file:///c:/Users/marcu/Desktop/Projects/siplan-hub/src/hooks/useCommercialChecklists.ts).
*   **Ação no Banco de Dados:** Atualização na tabela `commercial_checklists` mudando a coluna `status` para `'submitted'` e gravando o JSON de respostas na coluna `responses`.
*   **Campos de Dados Utilizados:**
    *   Metadados do projeto: `clientName`, `ticketNumber`, `systemType`.
    *   Respostas Completas: Todas as propriedades salvas no campo `responses`. No caso do formulário padrão (Fallback), ler e formatar os campos estruturais em formato de tabela legível:
        *   Dados de quem preencheu: `fullname` (Nome), `role` (Cargo), `email` e `phones` (Telefones).
        *   Estrutura: `floors` (Andares), `sectors` (Setores existentes), `sectors_distribution` (Distribuição dos setores) e `total_employees` (Total de colaboradores).
        *   Colaboradores Chave: Lista `key_people` contendo nome, cargo e contato dos líderes internos.
        *   Gestão de Mudança: `aware_of_change` (Se a equipe sabe da troca de sistema) e `team_adaptability` (Como lidam com novidades).
*   **Destinatários:** **Marcus, Marcos Ortiz e Bruno Fernandes**.
*   **Assunto do E-mail:** `[SIPLAN HUB] [Checklist] Respostas Enviadas — {clientName} (#{ticketNumber})`

---

TODOS OS EMAILS SÃO OS MESMOS DOS LOGINS/PROFILES NO SIPLAN HUB. PUXAR DE ACORDO COM O NOME DOS DESTINATÁRIOS OS SEUS RESPECTIVOS EMAILS.

---

## 💡 Sugestões de Novos Disparos (Por Evento ou Cron Job)

Seguindo a mesma lógica operacional do Siplan HUB, aqui estão ideias adicionais para otimizar gargalos e alinhamentos diários:

### A) Por Acionamento (Event-driven)

#### 1. Atribuição de Analista na Fila de Conversão
*   **Gatilho:** Quando um analista de dados clica em "Assumir Conversão" na tela de fila (Função `assignToMe` em [useConversionQueue.ts](file:///c:/Users/marcu/Desktop/Projects/siplan-hub/src/hooks/useConversionQueue.ts#L216-L265)).
*   **E-mail para:** Marcus, Bruno Fernandes e Marcos Ortiz.
*   **Objetivo:** Informar à ponta de implantação quem é o analista de conversão responsável por tratar os dados daquele cliente, facilitando a troca direta de informações.
*   **Campos:** Nome do cliente, chamado, nome do analista que assumiu a conversão(`assignedToName`), e data de início - quando assumiu (`startedAt`).

---

## Lista de Emails citados:

Marcus - marcus.vinicius@siplan.com.br
Bruno Fernandes - bruno.fernandes@siplan.com.br
Marcos Ortiz - marcos.ortiz@siplan.com.br
Ademar - ademar.souza@siplan.com.br
Luciane - luciane.lima@siplan.com.br
Eduardo Silva - eduardo.silva@siplan.com.br
Luan Caldeira - luan.caldeira@siplan.com.br
Amanda Flor - amanda.flor@siplan.com.br
Maurilio Camargo - maurilio.camargo@siplan.com.br
Maria - maria.santos@siplan.com.br
Alex Silva - alex.silva@siplan.com.br
Hugo Januário - hugo.santariosi@siplan.com.br
