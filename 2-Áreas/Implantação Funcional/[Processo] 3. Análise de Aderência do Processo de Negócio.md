---
tipo: Processo
fase_implantacao: "3. Análise de Aderência"
responsavel: Analista de Implantação
dependencia: "[[[Processo] 2. Levantamento de Infraestrutura]]"
tags:
  - #implantacao
  - #produtos
status_atual: #ativo
---
# [Processo] 3. Análise de Aderência do Processo de Negócio

Com a infraestrutura validada, o foco passa para a compatibilidade dos processos de negócio do cliente com o software Siplan. Atua como um "Gate Condicional" antes da Conversão.

## 📋 Cenário Atual (As-Is)

**Gargalo de Agenda:**
A aderência precisa ocorrer nos dias em que o analista está "entre campos", gerando conflitos. Não há SLA fixo para o agendamento. 

**Execução e Análise:**
A execução se apoia no levantamento da serventia e rotinas essenciais da operação do cartório versus as funcionalidades do sistema.

**Tratamento de Impedimentos (O Gargalo de Desenvolvimento):**
- **Adequado:** O "Gate" é aberto e o projeto segue para a fila de Conversão.
- **Não Adequado (Buraco Negro de Produtos):** O caso é escalado para o time de **Produtos** se faltar uma rotina crítica (ex: integração com prefeitura).
  - **SLA e Fila:** A fila da equipe de Produtos é extensa. Não há SLA de resposta (pode demorar semanas ou meses).
  - **Status do Projeto:** A implantação fica **pausada**. Nunca fazemos a implantação "pela metade" só para cumprir prazo (a não ser se for algo pré-acordado no Orion TN, dividindo Firmas e Notas). 
  - **Contingência Comercial:** O Comercial e a Diretoria negociam com o cliente. Apresentam a realidade de esforço de desenvolvimento para entender se a rotina é realmente imprescindível para a operação do cartório. O projeto dorme na fase de Aderência até que o desenvolvimento seja finalizado.

## 🚀 Visão de Futuro & Ideias (To-Be)

- **Padronização Estrita:** Consolidar o uso de um **Template Unificado e Obrigatório** para todas as aderências (Acesse o rascunho: [[[Modelo] Template - Analise de Aderencia]]), garantindo mapeamento físico completo e mitigando riscos de subdimensionamento. Esta unificação é pauta prioritária da reunião de 25 a 29 de Maio.
- **Gestão da Fila de Produtos:** Melhorar a previsibilidade e criar métricas de estimativa de viabilidade técnica quando uma implantação depende de uma nova feature, para que o cliente não fique com o prazo completamente aberto.

**Próxima etapa:** [[[Processo] 4. Tratamento de Impedimentos da Análise de Aderência]]