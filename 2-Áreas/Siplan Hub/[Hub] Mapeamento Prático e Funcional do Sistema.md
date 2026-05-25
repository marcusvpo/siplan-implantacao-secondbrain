---
tipo: Analise Funcional
foco: Telas e Modulos Siplan Hub
status: Concluído
tags:
  - #hub
  - #processos
  - #arquitetura_de_telas
---
# Siplan Hub: Mapeamento Prático e Funcional das Telas

Esta nota detalha o funcionamento prático e arquitetural da plataforma interna Siplan Hub, cruzando as **telas e funcionalidades desenvolvidas no código** com a **realidade operacional da equipe (AS-IS / TO-BE)**. 

O objetivo é entender não apenas o que o software faz, mas *quem usa o quê e como as informações fluem* dentro do ecossistema da Siplan.

## 1. O Paradoxo do Hub: Software vs. Processo Real
A análise do repositório revela um sistema extremamente robusto, composto por mais de 25 páginas e módulos que vão desde CRM até Editor Rico (Tiptap) e Gestão de Capacidade. No entanto, o diagnóstico de adoção operacional revelou uma regra de ouro: **o Hub deve ser um Orquestrador Invisível para quem está no campo**.

Portanto, as funcionalidades do sistema se dividem em dois eixos operacionais:
1. **Uso Ativo (Cockpit):** Equipes de Backoffice (Conversão, Modelos Editor) e Coordenação vivem dentro da interface do Hub.
2. **Uso Passivo (Logs e Automações):** Equipes externas (Comercial, Implantadores na rua) raramente abrem as telas. O Hub captura seus dados via integrações n8n/Outlook e exibe o consolidado para a gestão.

---

## 2. Mapeamento Detalhado de Módulos e Telas

### A. O Cockpit de Gestão e Triagem
Focado em dar visibilidade macro, previsibilidade e apoio à decisão para coordenadores.
*   **Dashboard Principal (`/` e `/dashboard`):** A visão executiva. Traz os KPIs críticos: Carga de Trabalho atualizada por cartório, SLA Compliance e Tempo Médio de Resolução. É aqui que o líder acompanha a saúde geral da fila.
*   **Kanban de Projetos (`/projects-kanban`):** Interface visual de arrastar e soltar (Drag & Drop) para mover projetos entre fases, ideal para a reunião de *Daily* da equipe técnica.
*   **Analytics (`/analytics`) e Comparação (`/compare-projects`):** Gráficos para entender gargalos históricos e uma tela que permite colocar dois ou mais projetos lado a lado para identificar por que um cartório avançou e outro não.

### B. O Coração Operacional: Conversão e Homologação (Uso Intenso)
Este é o módulo com maior taxa de cliques diários. O analista de banco de dados "bate o ponto" aqui.
*   **Fila de Conversão (`/conversion`) e Minha Fila (`/my-queue`):** Tabela robusta com filtros avançados. O analista usa o `/my-queue` para focar exclusivamente nos cartórios sob sua responsabilidade, utilizando *auto-save* nos formulários para não perder anotações rápidas.
*   **Monitor de Motores (`/conversion-engines`):** Tela técnica para acompanhar o status e a disponibilidade dos scripts de migração de dados em tempo real.
*   **Homologação (`/conversion-homologation`):** Tela de governança. Após rodar o motor, o analista anota aqui as pendências, aguardando o aceite formal do cartório para considerar a base "limpa".

### C. A "Fábrica" OrionTN: Módulo de Modelos Editor
Criado para resolver o "Gargalo da Caixa Preta" na formatação de modelos do sistema OrionTN.
*   **Dashboard OrionTN (`/orion-tn-models/dashboard`):** Exibe 5 KPIs específicos (Concluídos, Bloqueados, etc.) e um gráfico de distribuição de progresso (0-100%) em formato SVG.
*   **Workspace de Edição (`/orion-tn-models/:projectId`):** Uma verdadeira fábrica dentro do Hub. Possui uma barra lateral de busca de projetos e um **Editor de Texto Rico (Tiptap)**. O analista sobe arquivos JSON (modelos base) e os formata diretamente na plataforma, salvando o progresso para que a liderança veja a % de conclusão avançar em tempo real.

### D. A Camada Comercial e CRM (O Repositório Invisível)
Embora as telas existam, o Comercial de campo usa essas rotinas indiretamente via notificações.
*   **Visão 360º e Contatos (`/commercial-customers`, `/commercial-contacts`, `/client-overview/:id`):** Mantém o histórico completo e a *timeline* do relacionamento com o cartório. Possui integração *Click-to-call*. Serve para que a implantação entenda o contexto político do cartório antes de assumir o projeto.
*   **Bloqueadores Comerciais (`/commercial-blockers`):** Quando a Implantação/Conversão trava por culpa do cliente (ex: falta de hardware ou boleto não pago), o analista registra o bloqueio aqui. **A Mágica:** Isso dispara um webhook (n8n) que envia um e-mail ao vendedor responsável, que resolve na rua.

### E. A Camada de Campo e Agendamento
Para prever gargalos logísticos e de capacidade da equipe de rua.
*   **Calendário e Agenda de Analistas (`/calendar`, `/agenda-analistas`):** Cruza a disponibilidade técnica com as datas marcadas para os projetos.
*   **Roadmap e Próximas Implantações (`/roadmap`, `/next-deployments`):** Linha do tempo visual de entregas (milestones). O implantador de campo viaja com base nessa data, mas seu *check-in* diário ocorre no SAP/0800, e não aqui.

### F. Administração e RH
*   **Gestão de Times e Permissões (`/admin/teams`, `/admin/users`):** Controle rigoroso de quem acessa o quê (ex: isolar a visão do Editor Orion da visão de Conversão Padrão).
*   **Gestão de Férias (`/admin/vacations`):** Módulo vital para o cálculo de capacidade. Antes de alocar 10 conversões em um mês, a coordenação usa essa tela para garantir que haverá analistas e implantadores disponíveis na época da "virada".
*   **Logs de Auditoria (`/admin/audit-log`):** Rastreia edições críticas (quem mudou o status de uma homologação, quem alterou um modelo), garantindo segurança jurídica nas entregas.

---

## 3. Síntese do Ciclo de Vida do Projeto no Hub

A jornada de uma implantação atravessa o Siplan Hub da seguinte forma:

1.  **Entrada:** O Comercial preenche o Formulário de Handoff (o Hub absorve e cria o Card no Kanban).
2.  **Alocação:** Coordenação usa o `/admin/vacations` e `/agenda-analistas` para planejar e atrelar um responsável.
3.  **Execução (Conversão):** Analista assume em `/my-queue`, aciona `/conversion-engines` e entrega a base no `/conversion-homologation`.
4.  **Execução (OrionTN):** A equipe de modelos atua simultaneamente no `/orion-tn-models` formatando e validando os JSONs no editor interno.
5.  **Exceção (Bloqueio):** Se o cliente falha, marca-se no `/commercial-blockers`, o n8n avisa o Comercial.
6.  **Saída para a Rua:** O cartório entra nas `/next-deployments`. A equipe de implantação assume a viagem (usando SAP/0800).
7.  **Finalização:** Pós-virada, a base de relacionamento (`/client-overview`) fica atualizada para o setor de Suporte.