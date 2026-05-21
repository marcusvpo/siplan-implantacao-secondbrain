DETALHAMENTO SIPLAN HUB

# Base de Conhecimento Operacional: Siplan Hub

## 1. Visão Geral do Sistema
O Siplan Hub é a plataforma central de gestão operacional interna da Siplan. Seu propósito fundamental é centralizar, orquestrar e monitorar todo o ciclo de vida da jornada do cliente (cartórios), conectando as áreas de Implantação, Conversão de Dados, Comercial e Administração de Equipes. O sistema substitui fluxos descentralizados por um hub unificado, garantindo visibilidade em tempo real do status de cada cartório.

## 2. Módulos Principais e Funcionalidades

### 2.1. [[[Hub] Dashboard e Visão Estratégica|Dashboard e Visão Estratégica]]
O ponto de entrada para acompanhamento diário das operações.
* **Visão Geral:** Apresenta os KPIs operacionais críticos, incluindo SLA Compliance, Tempo Médio de Resolução e a Carga de Trabalho atualizada por cartório. Exibe também métricas de performance em tempo real e o controle de contatos na fila.
* **Quadro Kanban:** Ferramenta de acompanhamento visual do fluxo de trabalho, permitindo que as equipes vejam rapidamente em qual estágio cada projeto se encontra.

### 2.2. [[[Hub] Gestão de Implantação|Gestão de Implantação]]
Módulo dedicado à equipe técnica e de projetos para gerir a entrega dos sistemas nos cartórios.
* **Gerenciar Projetos:** Tabela e formulários para acompanhamento detalhado de projetos ativos. Inclui funcionalidades de auto-save para agilizar a edição de campos durante o atendimento.
* **Próximas Implantações (Deployments):** Agenda centralizada focada no planejamento das futuras instalações de sistemas, definindo status e responsáveis diretos por cada "virada".
* **Comparador de Projetos:** Permite a análise lado a lado de múltiplos cartórios para identificar diferenças de estágio, gargalos ou discrepâncias no progresso da implantação.

### 2.3. [[[Hub] Conversão de Projetos|Conversão de Projetos]] (Migração de Dados)
Módulo crítico para a equipe de banco de dados, responsável por trazer os dados do sistema legado do cartório para os sistemas Siplan.
* **Fila de Conversão e Minha Fila:** Os analistas visualizam uma tabela completa dos projetos em conversão, com filtros por status, responsável, produto e sistema legado. Há uma visão dedicada ("Minha Fila") com cards expandidos detalhando as tarefas exclusivas do usuário logado.
* **Motores de Conversão (Engines):** Painel de controle e monitoramento dos scripts e rotinas (engines) de migração, validando o status e a disponibilidade de cada script em tempo real.
* **Homologação:** Etapa de governança onde a equipe controla os projetos que já passaram pela migração inicial e aguardam validação de dados, aceitação do cartório e resolução de pendências.

### 2.4. Gestão do OrionTN (Modelos Editor)
Um ecossistema dedicado especificamente para gerenciar a complexa etapa de criação e validação de modelos para o sistema OrionTN.
* **Dashboard Específico:** Fornece métricas exclusivas do OrionTN, como o total de cartórios na fila do editor, projetos bloqueados, taxa de conclusão de arquivos e um gráfico de distribuição de progresso (0-100%).
* **Workspace / Editor de Modelos:** Uma área de edição onde o analista pode fazer upload de arquivos JSON, visualizar os modelos enviados ao cliente e utilizar um editor de texto rico integrado para formatar e ajustar as peças.

### 2.5. Relacionamento Comercial (CRM Interno)
Gestão do relacionamento pré e pós-venda, mantendo o histórico do cartório acessível a todas as equipes.
* **Painel de Clientes e Timeline:** Oferece uma visão 360º de cada cliente. A "Visão do Cliente" exibe uma linha do tempo (timeline) completa com o histórico de todas as interações da Siplan com aquele cartório específico.
* **Contatos:** Registro centralizado de interações comerciais com funcionalidade de *click-to-call* integrada para agilizar o contato telefônico.
* **Gestão de Bloqueios (Blockers):** Sistema de rastreamento de impeditivos. Se um cartório trava na implantação por questões contratuais ou financeiras, ele é categorizado aqui com um responsável definido para destravar o processo.

### 2.6. Calendário e Alocação
* **Visão de Projetos e Analistas:** O hub possui um calendário integrado (mensal e semanal) que cruza os eventos dos projetos com a "Agenda dos Analistas", permitindo que os coordenadores visualizem gargalos de alocação da equipe técnica.

### 2.7. Administração e Auditoria
* **Governança de Equipe:** Criação de times, definição de áreas funcionais e controle granular de permissões de acesso (ex: quem pode ver a tela de conversão vs. comercial).
* **Gestão de Férias:** Calendário integrado para registro e aprovação de ausências, essencial para o cálculo real da capacidade produtiva do time de implantação.
* **Logs de Auditoria:** Rastreamento de segurança que registra ações críticas no sistema (quem alterou o status de um projeto, quem modificou um modelo, etc.).

---

## 3. Casos de Uso e Rotinas Práticas no Dia a Dia

Para o mapeamento de processos, considere as seguintes dinâmicas que ocorrem diariamente na plataforma:

* **O Fluxo de Trabalho do Analista de Implantação/Conversão:**
  1. O analista inicia o dia acessando o **Dashboard** para verificar a Carga de Trabalho e os KPIs da sua fila.
  2. Acessa o módulo de **Conversão > Minha Fila** para visualizar apenas os cartórios sob sua responsabilidade.
  3. Ao trabalhar na migração, ele abre a tela de **Motores** para rodar ou verificar o status dos scripts de dados e atualiza o andamento na aba de **Homologação** quando os dados são liberados para o cliente testar.

* **O Fluxo de Gestão de Crise e Bloqueios (Comercial vs. Técnico):**
  1. Durante uma implantação, a equipe técnica identifica que um cartório não enviou a documentação ou há inadimplência.
  2. O projeto é sinalizado no módulo **Comercial > Bloqueios**, acionando a equipe de relacionamento.
  3. O setor Comercial utiliza o **Painel de Clientes** para revisar o histórico da timeline, utiliza o *click-to-call* nos **Contatos** para ligar para o titular do cartório e registrar a nova interação.

* **A Rotina Exclusiva do OrionTN:**
  1. Um analista focado no sistema de notas acessa o **Modelos Editor OrionTN > Dashboard** para verificar quais cartórios estão com status "Não Iniciados".
  2. Ele entra no **Workspace de Edição**, seleciona o cartório na barra lateral de busca, sobe os modelos JSON base e utiliza o Editor Rico para personalizar as peças.
  3. O trabalho é salvo via auto-save, alimentando a barra de progresso (ex: 51-75%) que reflete instantaneamente para os coordenadores.

* **A Rotina de Coordenação e Liderança:**
  1. O coordenador utiliza o **Dashboard > Quadro Kanban** para uma reunião diária (daily) visando identificar cartórios travados em etapas específicas.
  2. Consulta a **Agenda dos Analistas** e o módulo de **Férias** no Admin para distribuir os novos cartórios que acabaram de assinar contrato para as **Próximas Implantações**.
  3. Extrai **Relatórios** em PDF para apresentar métricas de rotinas ativas e inativas para a diretoria.