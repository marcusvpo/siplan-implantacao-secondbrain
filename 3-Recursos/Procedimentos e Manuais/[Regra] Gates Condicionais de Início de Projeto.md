---
tipo: Regra
area: Implantação Funcional
tags:
  - #regra
  - #fluxo
  - #arquitetura
---
# [Regra] Gates Condicionais de Início de Projeto

Para evitar desperdício de esforço técnico e retrabalho, o processo de implantação opera sob a regra dos **Gates Condicionais Iniciais**.

## 📋 Cenário Atual (As-Is)

Nenhuma etapa de execução pesada pode ser iniciada antes que as duas etapas primárias sejam concluídas e aprovadas. As etapas ocorrem **em paralelo**:

**1. Gate Técnico: Análise de Ambiente**
- **Objetivo:** Planilhar junto ao TI do cliente a capacidade das máquinas.
- **Execução Real:** Se inadequado, a implantação é pausada e o Comercial acionado. **Não há SLA ou prazo fixo** para o cliente resolver isso. O projeto fica parado aguardando a negociação conduzida exclusivamente pelo Comercial.
- **Contingência (Gargalo de Viagem):** O Implantador **nunca** irá viajar sabendo que o servidor está inadequado. 

**2. Gate de Negócio: Análise de Aderência**
- **Objetivo:** Validar se o Siplan atende 100% ou se falta alguma funcionalidade essencial.
- **Execução Real:** Conduzido por Analistas de Campo. Se inadequado, é escalado para Produtos. O projeto fica retido por semanas ou meses dependendo da complexidade, em estado de "Pausa", pois a implantação nunca é feita pela metade sem a rotina essencial aprovada.
- **Contingência de Acordo Prévio:** O Implantador não viaja com pendências de aderência, **a não ser** que seja pré-acordado com o cliente (ex: no Orion TN, dividir a implantação em duas etapas, primeiro Firmas/Balcão e depois Notas).

**A Virada de Fase (O Paradoxo do Agendamento):**
Embora os Gates ditem que o projeto só avança com Ambiente e Aderência "OK", muitas vezes o Comercial já efetuou um pré-agendamento de data de forma imprevisível. Nesses casos, se os gates não forem superados a tempo, o agendamento é revisto pela Diretoria e Comercial.

## 🚀 Visão de Futuro & Ideias (To-Be)

- **Métricas de Tempo de Retenção:** Criar mecanismos no Hub para alertar e mensurar o tempo em que os projetos ficam "presos" nesses gates (ex: "Projeto X está pausado no Gate Técnico há 45 dias").
- **Melhoria da Previsibilidade do Gate de Negócio:** Estabelecer uma comunicação mais ágil com a equipe de Produtos para devolver ao cliente uma estimativa realista do desenvolvimento faltante.