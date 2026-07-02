---
tipo: Conceito
area: Siplan Hub
tags:
  - #conceito
  - #automacao
  - #ideias
  - #melhoria
  - #n8n
status_atual: #ativo
---
# 💡 Ideias de Automações Operacionais de Comunicação baseadas em Ações no HUB

Este documento reúne propostas de novas automações focadas em disparos de e-mail gerados exclusivamente a partir de **ações explícitas e interações físicas executadas pelos usuários dentro do Siplan HUB** (clique de botões, alteração de campos críticos, finalização de checklists e bloqueios).

O foco está em eliminar gargalos operacionais e garantir que a próxima pessoa da esteira técnica receba o bastão imediatamente após a conclusão da etapa anterior.

---

## 🏗️ 1. Infraestrutura & Comercial

### 💡 Ideia 1.1: Notificação de Incompatibilidade de Hardware (Botão "Notificar Comercial")
*   **Ação Disparadora no HUB**: O analista de infraestrutura clica no botão físico **Notificar Comercial** (ícone `Megaphone` em [InfraStageForm.tsx](file:///C:/Users/marcu/Desktop/Projects/siplan-hub/src/components/ProjectManagement/Forms/StageForms/InfraStageForm.tsx)).
*   **O que a Automação faz**: Captura o evento (via webhook n8n ativo no HUB) e envia um e-mail urgente para o vendedor responsável pelo cartório contendo o diagnóstico técnico detalhado do servidor local (ex: CPU/RAM insuficiente) e a lista de peças que o cliente precisará adquirir.
*   **Destinatários**: Equipe Comercial / Vendedor do Projeto.
*   **Valor Prático**: Agiliza a renegociação e cobrança de upgrade de hardware com o cliente, evitando que o projeto trave por semanas na infra.

### 💡 Ideia 1.2: Envio do Relatório de Infraestrutura para o Cliente
*   **Ação Disparadora no HUB**: O analista clica no botão de **Enviar Relatório PDF por E-mail** na tela de infraestrutura após analisar os dados importados.
*   **O que a Automação faz**: O n8n gera/anexa o PDF de conformidade técnica e dispara um e-mail formal para o Tabelião e para a TI local da serventia, listando as adequações e instruções técnicas de portas e firewall necessárias antes do go-live.
*   **Destinatários**: E-mail do Cartório (Responsável Serventia / TI).
*   **Valor Prático**: Formalização transparente das obrigações físicas e lógicas que cabem ao cliente realizar.

---

## ⚖️ 2. Análise de Aderência & Produto

### 💡 Ideia 2.1: Notificação de Gap de Produto (Integração Legada Exigida)
*   **Ação Disparadora no HUB**: No formulário de aderência (`ProjectAdherenceForm.tsx`), ao marcar o campo `has_product_gap = true`, preencher a descrição do gap e clicar em "Salvar".
*   **O que a Automação faz**: Dispara um e-mail estruturado detalhando o requisito ou relatório específico do sistema antigo (ex: layouts de boleto CNAB400 customizados) que o Orion não possui nativo para o time de produto e P&D.
*   **Destinatários**: Gerente de Produto (PM) e Líder Técnico de Desenvolvimento.
*   **Valor Prático**: Aciona o desenvolvimento/customização com antecedência, evitando que a virada de sistema (go-live) seja travada por falta de um recurso crítico legado.

---

## ⚙️ 3. Conversão & Modelos Editor

### 💡 Ideia 3.1: Envio de Arquivos de Minutas do Cartório (Modelos Editor)
*   **Ação Disparadora no HUB**: A equipe de passagem comercial ou o cliente faz o upload dos arquivos de minutas notariais no estágio 5 (**Modelos Editor**) em `/projects/:id`.
*   **O que a Automação faz**: O n8n identifica a inclusão de novos arquivos no campo `sent_files` e dispara um e-mail informando que os arquivos do cartório já estão disponíveis no HUB para início das configurações.
*   **Destinatários**: Implantador responsável pela etapa de Modelos Editor.
*   **Valor Prático**: O implantador sabe exatamente quando o cartório enviou seus layouts padrões, podendo iniciar a parametrização de minutas no Orion TN de forma imediata.

---

## 📅 4. Implantação, Viagens & Encerramento

### 💡 Ideia 4.1: Escala e Briefing de Viagem do Implantador
*   **Ação Disparadora no HUB**: O gestor atribui um implantador de campo ao projeto e preenche os dados de data da viagem de implantação física.
*   **O que a Automação faz**: Dispara um e-mail completo para o implantador escalado contendo: dados de contato dos líderes da serventia, resumo dos checklists comerciais preenchidos, diagnóstico de infraestrutura local e a lista de itens obrigatórios para levar na viagem.
*   **Destinatários**: Implantador escalado.
*   **Valor Prático**: Garante que o implantador viaje 100% munido de informações críticas sobre o ambiente e particularidades do cartório que vai atender.

### 💡 Ideia 4.2: Notificação de Bloqueio de Etapa (Blocker Ativado)
*   **Ação Disparadora no HUB**: Qualquer membro da equipe altera o status de uma etapa do projeto para `blocked` e preenche o campo `blocking_reason` (motivo do bloqueio).
*   **O que a Automação faz**: Dispara um alerta de e-mail contendo o nome do projeto, a etapa travada e o motivo do impedimento digitado pelo analista.
*   **Destinatários**: Coordenação de Implantação (Maria) e Gestor (Marcus).
*   **Valor Prático**: Alerta visual instantâneo para a gerência atuar e resolver impedimentos de rede, hardware ou atraso por parte do cartório.

### 💡 Ideia 4.3: Conclusão de Implantação (Checkout Técnico)
*   **Ação Disparadora no HUB**: O implantador de campo finaliza a Fase 2 de Implantação e Treinamento e move o status da etapa para `done`.
*   **O que a Automação faz**: Envia um e-mail consolidado informando o sucesso da virada, contendo em anexo as assinaturas digitais colhidas do termo de implantação/treinamento e liberando o fluxo comercial de faturamento e o onboarding pós-venda.
*   **Destinatários**: Financeiro Siplan, Comercial (Vendedor do Projeto) e Suporte Técnico (Retaguarda).
*   **Valor Prático**: Acionamento formal do faturamento pós-entrega do sistema e passagem de bastão limpa para o suporte ordinário do dia a dia.
