---
tipo: MOC
area: Siplan Hub
tags:
  - #hub
  - #plataforma_interna
---
# Siplan Hub - Base de Conhecimento

O Siplan Hub é a plataforma central de gestão operacional interna da Siplan, substituindo fluxos descentralizados por um hub unificado para Implantação, Conversão, Comercial e Administração.

## Dinâmicas e Desafios de Uso
- **Alimentação Centralizada e Adoção Realista:** Atualmente, o Hub é alimentado quase exclusivamente pela Implantação. O diagnóstico AS-IS/TO-BE concluiu que a estratégia correta **não é forçar a adoção da interface do Hub pelas equipes de campo (Comercial e Implantadores em viagem)**, pois isso geraria retrabalho. 
- **O Hub como "Orquestrador Invisível":** Para as equipes externas, o Hub deve chegar até eles via integrações n8n/Outlook (notificações estruturadas). O uso ativo da interface fica restrito à equipe interna de gestão, fila técnica de Conversão e equipe de Modelos.
- **Potencial de Indicadores:** O Hub possui indicadores de faróis e tempo de demora, com o foco em fornecer previsibilidade e métricas para a Gestão e Diretoria.

## Módulos e Tecnologias
- [[[Processo] Mapeamento AS-IS e TO-BE do Siplan Hub]] *(Estratégia Definitiva de Adoção)*
- [[[Hub] Mapeamento Prático e Funcional do Sistema]] *(Análise Detalhada de Telas e Fluxos)*
- [[[Hub] Dashboard e Visão Estratégica]]
- [[[Hub] Gestão de Implantação]]
- [[[Hub] Conversão de Projetos]]
- [[[Hub] Gestão do OrionTN (Modelos Editor)]]
- [[[Hub] Relacionamento Comercial (CRM Interno)]]

## 🤖 Central de Automações (n8n & Webhooks)
- [[Automações/[Hub] Integrações e Automações n8n|[Hub] Integrações e Automações n8n]] *(Visão Macro do Orquestrador)*
- [[Automações/[Manual] Guia Passo a Passo - Automações de E-mail Siplan HUB|[Manual] Guia Passo a Passo - Automações de E-mail Siplan HUB]] *(Manual Técnico de Configuração)*
- [[Automações/[Manual] Passo a Passo - Novas Automações de Homologação|[Manual] Passo a Passo - Novas Automações de Homologação]] *(Homologação de Bases)*
- [[Automações/[Manual] Passo a Passo - Automação de Configuração de Ambiente|[Manual] Passo a Passo - Automação de Configuração de Ambiente]] *(Preparação de Ambiente)*
- [[Automações/[Conceito] Ideias de Automações Operacionais - Siplan HUB|[Conceito] Ideias de Automações Operacionais - Siplan HUB]] *(Regras e Escopo de Negócio)*

## Rotinas e Dinâmicas
- **Fluxo do Analista:** Inicia no Dashboard, filtra "Minha Fila" em Conversão, opera Motores e Homologação.
- **Gestão de Crise:** Bloqueios acionam o Comercial, que usa Timeline e Click-to-call.
- **Rotina OrionTN:** Analista usa o Workspace de Edição para formatar JSONs com auto-save.
- **Liderança:** Daily via Kanban, alocação de analistas via módulo de Férias e extração de Relatórios.
