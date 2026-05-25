---
tipo: Diagnóstico
foco: Processos do Siplan Hub (AS-IS vs TO-BE)
status: Concluído
tags:
  - #hub
  - #processos
  - #as_is_to_be
---
# Mapeamento AS-IS e TO-BE: Operação Siplan Hub

Esta nota sintetiza a análise conduzida com base nas respostas da operação sobre o uso da plataforma interna Siplan Hub. O objetivo principal deste mapeamento é entender como as informações fluem hoje, onde há retrabalho e qual é a visão estratégica definitiva (TO-BE) para o uso da plataforma.

## 1. Visão Estratégica Geral
- **O Fim do Paradigma da Adoção Forçada:** Diferente de outras plataformas, a conclusão crítica deste diagnóstico é que **não devemos forçar o uso da interface do Hub pelas equipes de campo (Comercial e Implantadores)**. O custo do retrabalho e da resistência cultural é maior que o benefício.
- **O "Orquestrador Invisível":** O Hub deve atuar nos bastidores. Para quem está na rua (Comercial e Implantadores), a informação deve chegar e sair via E-mail, WhatsApp e integrações n8n.
- **Foco no "Backoffice":** Apenas as equipes internas (Gestão de Projetos, Conversão e Modelos) utilizarão a interface do Hub de forma ativa (Fila de Trabalho, Timeline, Uploads).

## 2. Diagnóstico por Equipe

### A. Equipe Comercial (Passagem de Bastão e Bloqueios)
*   **AS-IS (Atual):** Handoff de novos projetos e notificações de bloqueio ocorrem via ferramentas dispersas (0800, Teams, E-mail). Informações chegam incompletas.
*   **TO-BE (Futuro):** O Comercial utilizará a interface do Hub apenas para um ritual de início de projeto (preenchimento do **Formulário de Nova Implantação**). Isso amarra escopo e formaliza a entrega. Fora isso, qualquer acionamento do Comercial (ex: cliente sem infraestrutura) será feito via alertas automáticos por e-mail, mantendo a equipe fora do Hub.

### B. Equipe de Conversão (Fila e Homologação)
*   **AS-IS (Atual):** Fila de trabalho dividida via Teams de forma verbal. Homologação da base feita via e-mail e arquivos Word de validação.
*   **TO-BE (Futuro):** Automação cria o gatilho de "Enviar para Conversão", populando a "Gestão de Atividades" da equipe. Analistas assumem bases e postam na Timeline o status ("Posts"). O processo de Homologação, no entanto, mantém-se via e-mail direto com o Implantador para não burocratizar.

### C. Equipe Modelos Editor OrionTN
*   **AS-IS (Atual):** Uso do Editor e status não é feito, gerando "caixa preta" para o projeto. Comunicação com cliente via e-mail e envio massivo de dezenas de modelos de uma vez.
*   **TO-BE (Futuro):** Manter o fluxo externo via e-mail com o cliente e focar em parametrizar o "Top 5" modelos. Porém, internamente, o time de Modelos passa a utilizar obrigatoriamente a interface do Hub para subir os arquivos finalizados e setar status (Pendente/Pronto) para dar visibilidade à equipe de Implantação.

### D. Equipe de Implantação (Campo)
*   **AS-IS (Atual):** Implantadores gerem suas pautas de campo pelo SAP/0800 (Agenda de Analistas) e registram o log diário no chamado.
*   **TO-BE (Futuro):** **Ruptura de paradigma:** O Implantador *não* fará check-ins no Hub enquanto estiver no cliente. A Agenda SAP/0800 continua sendo a oficial para controle diário. O Hub serve de visão macro para a coordenação (Calendário de Projetos) e controle pré-implantação.

### E. Gestão e Diretoria
*   **AS-IS (Atual):** Consumo pontual de projetos específicos.
*   **TO-BE (Futuro):** Manutenção do modelo atual, focando no incentivo à leitura dos Dashboards nativos para análise da saúde da fila.

## 3. Matriz de Priorização (Next Steps)
1.  **Prioridade 1 (Alta/Rápida):** Ligar a automação de e-mail ao clicar em "Enviar para Conversão".
2.  **Prioridade 2 (Alta):** Lançar a obrigatoriedade da tela "Formulário de Nova Implantação" para o Comercial realizar o handoff do projeto, e ligar a automação que distribui esse formulário para o Backoffice.
3.  **Prioridade 3 (Média):** Treinar a equipe de Modelos para registrar o status dos arquivos internamente no Hub, para resolver o problema da "caixa preta".
4.  **Prioridade 4 (Baixa):** Manutenção das agendas separadas e conscientização da diretoria sobre leitura de dashboards.