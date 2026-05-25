---
tipo: Hub
modulo: Gestão de Implantação
tags:
  - #hub
  - #implantacao
---
# [Hub] Gestão de Implantação

Módulo do Siplan Hub dedicado à equipe técnica e de projetos.

## Funcionalidades
- **Gerenciar Projetos:** Tabela e formulários com auto-save para acompanhamento de projetos ativos.
- **Próximas Implantações (Deployments):** Agenda centralizada para planejar instalações, status e responsáveis pelas viradas.
- **Comparador de Projetos:** Análise lado a lado de múltiplos cartórios para identificar gargalos e discrepâncias no progresso.

## Processos: AS-IS vs TO-BE

### 1. Atualização Operacional Diária
- **AS-IS:** O controle macro é feito no Hub, mas o detalhamento diário de quem está em campo (implantador) é lançado diretamente no chamado do 0800.
- **TO-BE:** **Decisão Estratégica: Não haverá tela de apontamento diário no Hub para o implantador de campo.** A etapa de implantação presencial continuará sendo documentada no 0800 para evitar retrabalho (já que não há API entre os sistemas). O Hub permanece focado nas etapas **pré-implantação** e para consumo analítico (métricas, acompanhamento) pelos analistas.

### 2. Gestão de Agendas (Calendário vs SAP/0800)
- **AS-IS:** Existem dois calendários paralelos: O "Calendário de Projetos" (no Hub, visão macro da Etapa de Implantação) e a "Agenda dos Analistas" (Puxada do SAP/0800, contendo o registro administrativo e chamados específicos).
- **TO-BE:** As duas agendas **permanecerão separadas**. O Hub será mantido apenas como visualização de previsões (Próximas Implantações), enquanto o cadastro administrativo e a pauta de execução continuarão sendo geridos pela matriz no SAP/0800.
