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

A estratégia futura é expandir o Hub para atuar como o "orquestrador invisível" definitivo. Como as áreas Comercial, Conversão e Pós-Implantação possuem forte aderência aos canais tradicionais, o objetivo **não é forçar a entrada na plataforma**, mas usar o n8n para levar o Hub até o e-mail deles via Deep Links.

**Backlog de Automações Planejadas:**

- **Onboarding de Novo Projeto:** Disparo para a lista da Implantação na criação do card.
- **Acionamento da Fila de Conversão:** Clique no botão "Enviar para Conversão" enviar e-mail via Outlook para a equipe (Luciane, Ademar, Eduardo), trazendo-os para o Hub via link da base.
- **Loop de Retrabalho na Homologação:** Reprovação do analista gerar um e-mail estruturado com inconsistências para a Conversão, contendo um botão "Base Corrigida" direto no e-mail.
- **Handoff para o Pós-Implantação (WhatsApp):** Marcação de "Virada Concluída" disparar um resumo (dossiê) para o time de CS (Henrique/Bruna/Erik) com botão "Criar Grupo de WhatsApp".
- **Alertas de Risco de Agendamento:** Faltando 5 dias para a implantação, se os gates de "Infra OK" ou "Conversão Homologada" não estiverem verdes, disparar e-mail de "Alto Risco" para Comercial e Diretoria.