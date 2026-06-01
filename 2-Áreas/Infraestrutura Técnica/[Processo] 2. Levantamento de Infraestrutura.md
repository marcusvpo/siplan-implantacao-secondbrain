---
tipo: Processo
fase_implantacao: "2. Levantamento de Infraestrutura"
responsavel: Equipe de Infraestrutura
dependencia: "[[[Processo] 1. Início do Chamado de Implantação]]"
tags:
  - #infraestrutura
  - #cross_infra
status_atual: #ativo
---
# [Processo] 2. Levantamento de Infraestrutura

Após a avaliação inicial, a primeira verificação técnica é determinar se o ambiente tecnológico do cartório cliente possui os requisitos mínimos para a correta operação do software Siplan.

## 📋 Cenário Atual (As-Is)

**Acionamento e Verificação:**
A **Equipe de Infraestrutura** entra em contato com o cartório para realizar o levantamento (remoto ou presencial), avaliando hardware, sistema operacional, rede e periféricos. Os requisitos mínimos exigidos estão presentes no documento de análise de ambiente e já são enviados previamente ao cliente junto da proposta comercial.

**Tratamento de Impedimentos (Limbo da Infraestrutura e Falta de Kill Switch):**
- **Se Adequada:** O projeto avança para a [[[Processo] 3. Análise de Aderência do Processo de Negócio]].
- **Se Inadequada:** O chamado é pausado e devolvido ao Comercial (Veja [[[Regra] Devolução Comercial via SAC 0800]]).
  - **SLA e Prazos:** **Não existe um prazo fixo ou SLA** para a adequação. Cada cliente tem suas particularidades e não existe um "Kill Switch" automático ou multa processual ativada.
  - **Projeto Adormecido:** Basicamente, o projeto fica adormecido/pausado eternamente. Existem casos na Siplan de clientes com contrato assinado aguardando adequação há quase 1 ano. 
  - **Acompanhamento:** A Implantação e a TI nada podem fazer a não ser esperar. A responsabilidade de manter o "follow-up" com o cliente é exclusiva da equipe do Comercial.

## 🚀 Visão de Futuro & Ideias (To-Be)

- **Atualização da Planilha de Infra:** A planilha padrão de Análise de Infraestrutura foi atualizada para incluir a confirmação explícita de servidor em nuvem e a existência de link de internet redundante. A verificação de espaço em disco ocupado pelas imagens foi movida para a equipe de Implantação na Análise de Aderência.
- **Formalização via TI:** Quando o levantamento for realizado diretamente pela TI do cliente, as informações deverão ser preenchidas em um documento formal seguindo nosso padrão. O Comercial deve deixar claro no fechamento que a equipe da Siplan fará esse contato.
- **Check-up Pré-Viagem:** Instituição de uma checagem obrigatória com o cliente na semana anterior à implantação presencial para validar se todas as adequações de ambiente solicitadas foram realizadas com sucesso, evitando surpresas "on-site".
- **Controle de SLA de Retenção e Regra de Rescisão:** Estabelecer uma política ou limite de tempo (ex: 90 dias) para que projetos pausados por infraestrutura recebam um ultimato, evitando contratos zumbis acumulados nos indicadores. Alertas automatizados pelo Hub cobrariam o Comercial periodicamente.
- **Visibilidade no Hub:** Aprimorar o acompanhamento do status dessas pendências de hardware diretamente pelo Siplan Hub, evitando que o Gestor de Implantação precise cobrar ativamente o Comercial por status.