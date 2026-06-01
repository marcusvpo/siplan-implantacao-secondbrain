---
tipo: Diagnóstico
fase_implantacao: Transversal
responsavel: Gestão do Hub
status_atual: Em Análise
tags:
  - #hub
  - #diagnostico
  - #adocao
  - #estrutura
---
# Estrutura de Telas e Diagnóstico de Uso do Siplan Hub

Esta nota documenta o mapeamento detalhado da arquitetura de telas atual do Siplan Hub e a severidade/nível de adoção por parte das equipes. O objetivo deste mapeamento é servir como fundação para a criação de processos fixos e treinamentos que descentralizem o uso do sistema para cada equipe.

## Diagnóstico Atual de Adoção
*   **A "Tela Core" Centralizadora:** A tela de **Implantação > Gerenciar Projetos** é o coração atual do sistema. É utilizada de forma intensiva/crítica pela gestão de implantação para cadastro manual e controle dos projetos.
*   **Problema de Baixa Aderência:** As demais telas foram concebidas para facilitar o dia a dia, porém a adoção pelas equipes operacionais (Comercial, Conversão, Modelos) é praticamente nula (Baixo ou Nunca Usado).
*   **Uso Pela Diretoria:** A diretoria consome o Hub de maneira pontual, para acompanhamento e visão geral de status, mas não atua na operação diária das telas de trabalho.
*   **Meta Futura:** Transformar o uso do Hub em um processo fixo ("by the book") para cada pessoa/equipe, aproveitando a autonomia de desenvolvimento para adaptar e personalizar as interfaces conforme as reais necessidades operacionais reveladas neste diagnóstico.

## Arquitetura de Telas e Nível de Uso

### 🏠 Início
*   **Início:** Tela padrão de busca central. *(Porta de entrada)*

### 📊 Dashboard
*   **Visão Geral:** Visão geral com indicadores, métricas e status dos projetos. **[Uso Baixo]**
*   **Quadro Kanban:** Kanban segmentado por status ("Não Iniciado", "Em Andamento", "Concluído", "Bloqueado"). **[Uso Baixo]**

### 🚀 Implantação
*   **Gerenciar Projetos:** A página principal do Hub. Visão geral de todos os projetos de implantação, cadastro de informações de cada Etapa e dados gerais do projeto. **[Uso Alto/Crítico]** *(Tela Core)*
*   **Relatórios:** Métricas de performance, tendências de saúde e distribuição de carga em tempo real. **[Uso Baixo]**
*   **Próx. Implantações:** Cards com a sequência cronológica dos projetos a serem implantados, baseados nas datas da Etapa 5 (Implantação & Treinamento). **[Uso Médio]**

### 📅 Calendário
*   **Calendário de Projetos:** Calendário interativo baseando-se nas datas cadastradas nas etapas de cada projeto por implantador. **[Uso Baixo]**
*   **Agenda dos Analistas:** Indicador conectado ao Power BI da Siplan; exibe a agenda baseada em atividades diárias puxadas do SAP e do sistema 0800. **[Uso Médio]**

### 💼 Comercial
*   **Painel de Clientes:** Visão da saúde da carteira de clientes (projetos críticos, em atenção, saudáveis), bloqueios e últimas atualizações. **[Uso Baixo]**
*   **Bloqueios:** Detalhamento dos impedimentos (Aderência/Infra) de cada Cliente/Projeto. **[Uso Baixo]**
*   **Contatos:** Agenda de contatos unificada. **[Nunca Usado]**
*   **Form. Nova Implantação:** Formulário de "handoff" do Comercial para Implantação, gerando o output para o 0800. **[Ainda Não Liberado]**

### ⚙️ Conversão
*   **Gestão de Atividades:** Fila de conversão e homologação. **[Uso Baixo]**
*   **Motores:** Conversões aguardando criação ou desenvolvimento do motor. **[Uso Baixo]**
*   **Homologação:** Validação de conversões finalizadas. **[Nunca Usado]**

### 🛠️ Implantadores (Novo)
*   **Editar Form. Aderência:** Editor visual para os formulários de Análise de Aderência padronizados por sistema, gerenciados pelos próprios implantadores. **[Em Desenvolvimento]**
*   **Checklist Homologação:** Editor visual e acompanhamento dos checklists padronizados para homologação de dados convertidos. **[Em Desenvolvimento]**

### 📝 Modelos Editor OrionTN
*   **Dashboard:** Visão geral do estágio de Modelos Editor nos projetos OrionTN (Indicadores, Status, Progresso). **[Uso Baixo]**
*   **Gerenciar Projetos:** Gestão no ecossistema OrionTN por Cliente, Status e Progresso. **[Uso Baixo]**
*   **Editor de Modelos:** Gerenciamento dos arquivos de modelos enviados pelo cliente. **[Uso Baixo]**
