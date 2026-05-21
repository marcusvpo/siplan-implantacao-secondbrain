---
tipo: Processo
fase_implantacao: "4. Tratamento de Impedimentos"
responsavel: Comercial, Diretoria e Produtos
dependencia: "[[[Processo] 3. Análise de Aderência do Processo de Negócio]]"
tags:
  - #produtos
  - #implantacao
  - #comercial
status_atual: #ativo
---
# [Processo] 4. Tratamento de Impedimentos da Análise de Aderência

Avaliação do documento de análise de aderência quando funcionalidades ou regras de negócio críticas do cartório não são atendidas atualmente pelo software Siplan.

## 📋 Cenário Atual (As-Is)

Quando a Análise de Aderência mapeia que o cartório exige uma funcionalidade impeditiva, a implantação é forçada a parar. Não existe a prática de seguir com o sistema implantado "pela metade" ou faltando módulos críticos de operação na expectativa de "desenvolver depois".

**Escalonamento e Triagem (A Inserção em Produtos):**
1. O processo reprovado é detalhado pelo Analista de Implantação.
2. A demanda é escalada para o time de **Produtos**, onde será avaliada a viabilidade técnica e esforço de desenvolvimento.
3. Este é um gargalo conhecido: a fila da área de produtos é longa e imprevisível.

**Protocolos de Negociação e Contingência:**
Durante a espera pela resposta e pelo desenvolvimento, a **Diretoria** e o **Comercial** tomam a frente das negociações com o cliente:
- **Esforço Inviável/Impossível:** Caso a funcionalidade exija um esforço muito alto e não seja interessante para o core do produto, o cliente é informado e deve adaptar seus processos. Pode ocorrer a rescisão do contrato se o cliente não ceder.
- **Esforço Aceito (Buraco Negro de Prazo):** Caso o desenvolvimento seja aprovado, não é cobrado nenhum custo adicional (pois é considerado um upgrade aplicável a outros clientes). O projeto fica formalmente em estado de "Pausa", aguardando as semanas ou meses necessários para o desenvolvimento. O tempo não possui um SLA rígido.

## 🚀 Visão de Futuro & Ideias (To-Be)

- **Fluxo Dinâmico de Prioridades:** Criar um painel integrado via Hub (n8n + Trello/Jira de Produtos) para dar total transparência ao Gestor de Implantação de onde, na fila geral de desenvolvimento, encontra-se a funcionalidade daquele cliente. Isso facilitará dar um follow-up quinzenal ao cartório sem depender de telefonemas para os desenvolvedores.
- **Matriz de Impacto:** Implementar uma "Matriz de Contorno" para entender se o impedimento pode ser resolvido com uma configuração paliativa nativa no Orion em vez de necessariamente customizar o código-fonte via Produtos.