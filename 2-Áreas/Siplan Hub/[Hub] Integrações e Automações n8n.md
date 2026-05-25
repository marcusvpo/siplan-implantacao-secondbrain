---
tipo: Hub
area: Siplan Hub
tags:
  - #hub
  - #automacao
  - #n8n
  - #outlook
---
# [Hub] Integrações e Automações n8n

O Siplan Hub é a plataforma projetada para atuar como o orquestrador da operação, conectando áreas via n8n e Outlook.

## 📋 Cenário Atual (As-Is)

Atualmente, o Hub possui um nível básico de integração e o impacto em caso de falhas tecnológicas é mínimo, pois as automações ativas atuam apenas como pequenas facilitações do dia a dia.

**Automações Ativas Hoje:**
1. **Criação de Projetos (Cron Job):** Uma rotina diária às 08h que cria ou atualiza os projetos no Hub com base na view do banco de dados do SAC 0800.
2. **Alerta de Infraestrutura Inadequada:** Um botão na etapa de Análise de Infraestrutura que, ao ser finalizada a análise com pendências, dispara um e-mail estruturado para o Comercial informando as necessidades de adequações.

Caso ocorram falhas nestes webhooks (como o servidor n8n fora do ar), o processo manual continua funcionando normalmente sem paralisar a operação.

## 🚀 Visão de Futuro & Ideias (To-Be)

A estratégia futura é expandir o Hub para atuar como o "orquestrador invisível" definitivo. Como as áreas Comercial e de Implantação (em campo) não devem ser sobrecarregadas com o uso de novas interfaces ("evitar retrabalho"), o objetivo **não é forçar a entrada na plataforma**, mas usar o n8n para levar o Hub até eles (via Outlook/E-mail) com notificações acionáveis.

**Backlog de Automações Planejadas (Design Operacional):**

- **Acionamento da Fila de Conversão:** Ao clicar no botão "Enviar para Conversão" (na Gestão de Implantação), o n8n dispara um e-mail padronizado via Outlook para a equipe de banco de dados, avisando que o projeto caiu na fila deles.
- **Notificação de Handoff (Comercial -> Implantação):** Ao preencher o "Form. Nova Implantação" no Hub, um gatilho dispara os dados resumidos e alinhamentos de escopo (ex: pacotes de Modelos) para a equipe de projetos.
- **Alertas de Risco e Bloqueios (Comercial):** Como o Comercial não operará o Hub, qualquer status de "Bloqueio" (Blocker) marcado pela Implantação deve disparar um e-mail estruturado de alerta imediato para a conta do executivo de contas.
- **Loop de Retrabalho na Homologação:** Reprovação do analista gerar um e-mail estruturado com inconsistências para a Conversão, contendo um botão "Base Corrigida" direto no e-mail.
- **Handoff para o Pós-Implantação (WhatsApp):** Marcação de "Virada Concluída" disparar um resumo (dossiê) para o time de CS (Henrique/Bruna/Erik) com botão "Criar Grupo de WhatsApp".
- **Alertas de Risco de Agendamento:** Faltando 5 dias para a implantação, se os gates de "Infra OK" ou "Conversão Homologada" não estiverem verdes, disparar e-mail de "Alto Risco" para Comercial e Diretoria.