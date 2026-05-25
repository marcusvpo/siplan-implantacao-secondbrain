---
tipo: Hub
modulo: Relacionamento Comercial
tags:
  - #hub
  - #comercial
  - #crm
---
# [Hub] Relacionamento Comercial (CRM Interno)

Gestão do relacionamento pré e pós-venda, mantendo o histórico acessível a todas as equipes.

## Funcionalidades
- **Painel de Clientes e Timeline:** Visão 360º com o histórico de todas as interações.
- **Contatos:** Registro centralizado com funcionalidade de click-to-call.
- **Gestão de Bloqueios (Blockers):** Sistema de rastreamento de impeditivos. Se um cartório trava (ex: financeiro), é categorizado aqui com um responsável definido para destravar o processo.

## Processos: AS-IS vs TO-BE

### 1. Handoff do Projeto (Passagem de Bastão)
- **AS-IS:** O processo é informal. Após o fechamento do contrato, um chamado é aberto no 0800 e, após trâmites administrativos, é repassado para a Implantação. Requisitos são variados e passados via "boca a boca".
- **TO-BE:** Utilização obrigatória da tela **"Form. Nova Implantação"** pelo Comercial. O objetivo é formalizar a passagem de informações de forma estruturada e centralizada no Hub, eliminando o telefone sem fio e a dependência exclusiva do 0800.

### 2. Gestão de Bloqueios e Acionamento do Comercial
- **AS-IS:** O Comercial é acionado informalmente via Teams ou e-mail quando o cliente trava o projeto (ex: falta de infraestrutura). Eles não acessam o Hub.
- **TO-BE:** A diretriz estratégica é **não forçar o Comercial a usar a interface do Hub** (por estarem sempre em campo). A gestão de bloqueios no Hub deverá disparar **notificações padronizadas por e-mail** (via n8n) para o Comercial, mantendo a comunicação onde eles já operam.
