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

- **Formulários Estruturados no Siplan HUB:** Consolidação da Análise de Aderência através de formulários técnicos padronizados por sistema dentro do HUB. Foi definida a criação do botão "Gerar Formulário de Aderência" que identificará o sistema e gerará o template apropriado.
- **Gestão de Templates no HUB:** Criação de uma tela "Implantadores" com a subtela "Editar Form. Aderência", permitindo que os próprios implantadores atualizem e adicionem novos pontos aos checklists.
- **Questionário Estrutural e Comercial:** O Comercial passará a enviar, logo no fechamento do contrato, um questionário genérico sobre a estrutura física do cartório, disposição de setores e perfil das pessoas (para identificar precocemente resistências e necessidade de gestão de mudança). O Comercial também deve alinhar com o cliente a necessidade de disponibilizar uma pessoa focada para acompanhar a aderência.
- **Modelo Híbrido:** O cliente preencherá o formulário e o implantador acompanhará e guiará nas perguntas.
- **Verificação de Espaço em Disco (Imagens):** A Análise de Aderência absorveu a responsabilidade de verificar o tamanho total (espaço em disco) ocupado pelas imagens no servidor atual do cliente (demanda da equipe de Conversão).
- **Gestão da Fila de Produtos:** Melhorar a previsibilidade e criar métricas de estimativa de viabilidade técnica quando uma implantação depende de uma nova feature, para que o cliente não fique com o prazo completamente aberto.

**Próxima etapa:** [[[Processo] 4. Tratamento de Impedimentos da Análise de Aderência]]

- **Diferenciação de Execução por Sistema Legado:**
  - **Sistemas de Terceiros (Externos):** A análise de aderência é feita preferencialmente de forma **presencial** (durante 2 a 3 dias de viagem do analista) para mapeamento exaustivo de processos.
  - **Sistemas Legados Siplan/Control-M:** A análise é conduzida de forma **remota** e ágil, por conta do conhecimento prévio da tecnologia e lógicas internas pela equipe de implantação.
- **Modelos do Editor Orion TN:**
  - Caso o cliente contrate o módulo Editor de Modelos (Orion TN), o Comercial deve instruí-lo no fechamento a enviar imediatamente as minutas para a equipe de Modelos (**Hugo Januário** e **Bruno Fernandes**).
  - Para evitar atrasos na implantação, a equipe adaptará inicialmente os **top 5 modelos mais utilizados** pelo cartório para que o treinamento e go-live iniciem com estas peças homologadas. O restante dos modelos (caso haja grande volume, ex: mais de 40) será adaptado gradualmente após o go-live.
- **Padronização e Formato:** Os checklists de aderência serão centralizados num template mestre no HUB (baseado no do Vieira).
- **Questionário Prévio:** O Comercial enviará um questionário self-service simplificado logo após o fechamento para coletar dados da infraestrutura e perfis, preparando a ida presencial.
