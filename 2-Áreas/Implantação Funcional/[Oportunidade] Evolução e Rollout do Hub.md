---
tipo: Oportunidade
area: Implantação Funcional
tags:
  - #oportunidade
  - #hub
  - #gestao_mudanca
---
# [Oportunidade] Rollout do Siplan Hub (Maio 2026)

**Data Agendada:** Reunião presencial entre 25/05/2026 a 29/05/2026.
**Público-Alvo:** Todos os analistas de implantação e equipe operacional.

## Contexto e Justificativa
Historicamente, os analistas registram suas atividades e atualizações diárias por meio de "Trâmites" complexos e pouco estruturados dentro do sistema legado de chamados (SAC 0800). Isso causa a centralização excessiva de informações na coordenação e prejudica a visibilidade do status real das implantações. A semana presencial de Maio, focada em replanejamento e treinamento, apresenta o cenário ideal para o lançamento oficial (rollout) do **Siplan Hub** como ferramenta central de trabalho.

## Objetivos Estratégicos do Rollout
A adoção do Hub **não visa gerar duplo trabalho** (0800 + Hub). Pelo contrário, a estratégia é blindar a linha de frente:
1. **O Hub como "Painel de Bordo" para a Linha de Frente:** Os Implantadores (analistas de campo) continuarão usando os trâmites do 0800. Para eles, o Hub será estritamente uma ferramenta de **visualização** (acessar a agenda, ver status de aderência, verificar se a conversão terminou). Eles não devem ser sobrecarregados com preenchimentos duplos.
2. **Descentralização no Back-Office:** A verdadeira mudança de processo é exigir que o Comercial, TI (Alex), Conversão (Ademar, Luciane, Eduardo) e Modelos (Hugo/Bruno) atualizem suas respectivas etapas no Hub. O responsável por cada etapa será o Gerenciador daquela informação.
3. **Automação de Entrada:** Atualmente, já existe uma integração via **n8n** (consumindo views do EPP no 0800) que cria automaticamente os projetos no Hub quando um chamado de implantação é aberto. A missão agora é garantir que o **Comercial preencha o formulário de Handoff** no Hub, de modo a injetar as informações complementares (Horas vendidas, Sistema Legado) que o n8n não consegue puxar sozinho.

## Pauta Sugerida para a Reunião Presencial (25 a 29 de Maio)

### 1. Hub Siplan e Transição de Rotina
- **Demonstração do Valor:** Mostrar o Hub não como "mais um sistema para preencher", mas como um "Painel de Comando" que lhes dará previsibilidade sobre as conversões e ambientes sem precisarem cobrar o Back-office no Teams.
- **Treinamento de Visualização (Implantadores):** Foco em ensinar a visualizar a "Minha Fila", interpretar os faróis de risco, acessar a agenda de próximas implantações e ler os resumos gerados pelo Back-office.
- **Treinamento de Operação (Back-office):** Para Alex (TI), Conversão e Modelos, o treinamento deve focar em como atualizar seus status para que os Implantadores tenham a informação em tempo real.
- **Alinhamento do Handoff Comercial:** Apresentar a todos o novo formato padronizado de Passagem de Bastão (injetado via n8n/Formulário), para que saibam exatamente onde encontrar os escopos e as restrições do projeto de forma clara.

### 2. Desenho do Novo Padrão de Análise de Aderência
- **Levantamento de Dores:** Ouvir dos implantadores (Ricardo, Rodrigo, Bruno) quais são os maiores gargalos e informações que sempre "escapam" nas análises atuais.
- **Unificação de Templates:** Utilizar as perguntas vitais do documento de aderência do Julio (Orion REG) — como número de andares, tamanho do cartório e distribuição de setores — como base para padronizar um único documento oficial da Siplan. O objetivo é evitar falhas de dimensionamento físico da equipe (como o caso crítico do cartório de 5 andares).