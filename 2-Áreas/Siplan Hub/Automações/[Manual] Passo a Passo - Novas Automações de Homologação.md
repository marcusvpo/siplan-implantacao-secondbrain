---
tipo: Manual
area: Siplan Hub
tags:
  - #manual
  - #automacao
  - #n8n
  - #homologacao
  - #email
status_atual: #ativo
---
# 🚀 Guia Passo a Passo: Novas Automações da Esteira de Homologação — Siplan HUB

Este manual técnico orienta a criação e configuração de duas novas automações no **n8n** integradas ao **Supabase** e **Gmail SMTP**, destinadas ao controle e comunicação da esteira de Homologação de bases de dados convertidas.

---

## 🛠️ Automação A: Nova Homologação Pendente

### 1. Descrição do Fluxo
Esta automação é acionada quando um analista de conversão finaliza seu trabalho técnico no HUB e clica no botão **Enviar p/ Homologação** (dentro de `/conversion`). O registro na tabela `conversion_queue` tem seu `queue_status` alterado para `awaiting_homologation`. A automação intercepta essa atualização, identifica o tipo de sistema e notifica a equipe de implantadores responsável por e-mail.

```mermaid
graph TD
    A[Supabase Webhook: UPDATE conversion_queue] --> B[n8n Webhook Node]
    B --> C[IF Node: Validar Transição para Awaiting Homologation]
    C -- Sim --> D[Supabase Node: Buscar Detalhes do Projeto]
    D --> E[Switch Node: Roteamento por Tipo de Sistema]
    E -- Orion TN --> F[Send Email: Ricardo, Brites, Bruno]
    E -- Orion PRO --> G[Send Email: Bruno, Brites, Mizuno]
    E -- Orion REG --> H[Send Email: Julio Araujo]
    E -- WEB RI --> I[Send Email: Fernando Cruz]
```

### 2. Configuração do Webhook no Supabase (Trigger)
Crie um Database Webhook no painel do Supabase com os seguintes parâmetros:
*   **Name:** `n8n_nova_homologacao_pendente`
*   **Table:** `conversion_queue`
*   **Events:** Selecionar `Update`
*   **Method:** `POST`
*   **URL:**
    *   *Testes:* `https://n8n.siplan.com.br/webhook-test/nova-homologacao`
    *   *Produção:* `https://n8n.siplan.com.br/webhook/nova-homologacao`
*   **Headers:** `Content-Type: application/json`

### 3. Configuração dos Nós no n8n

#### Nó 1: Webhook (Gatilho)
*   **Name:** `Webhook - Nova Homologação`
*   **Authentication:** `None`
*   **HTTP Method:** `POST`
*   **Path:** `nova-homologacao`
*   **Response Mode:** `onReceived`
*   **Response Code:** `200`

#### Nó 2: IF (Filtro de Transição)
Este nó garante que a automação só execute se o status da fila foi atualizado especificamente para `"awaiting_homologation"`.
*   **Name:** `IF - Transição de Status`
*   **Conditions -> String:**
    *   **Value 1:** `{{ $json.body.record.queue_status }}`
    *   **Operation:** `Equal`
    *   **Value 2:** `awaiting_homologation`
*   **Conditions -> String (AND):**
    *   **Value 1:** `{{ $json.body.old_record.queue_status }}`
    *   **Operation:** `Not Equal`
    *   **Value 2:** `awaiting_homologation`

#### Nó 3: Supabase (Consulta de Projeto)
Busca dados adicionais do projeto (como o nome do cliente e o número do ticket) utilizando o ID do projeto do payload.
*   **Name:** `Supabase - Detalhes do Projeto`
*   **Credential:** `Supabase API`
*   **Resource:** `Database`
*   **Operation:** `Get`
*   **Table:** `projects`
*   **Row ID:** `{{ $node["Webhook - Nova Homologação"].json.body.record.project_id }}`

#### Nó 4: Switch (Roteamento por Sistema)
Direciona o fluxo com base no tipo de sistema contratado (`system_type`).
*   **Name:** `Switch - Tipo de Sistema`
*   **Data to typecast:** `String`
*   **Value 1:** `{{ $json.system_type }}`
*   **Rules:**
    *   *Valor:* `Orion TN` -> Encaminhar para Saída 0
    *   *Valor:* `Orion PRO` -> Encaminhar para Saída 1
    *   *Valor:* `Orion REG` -> Encaminhar para Saída 2
    *   *Valor:* `WEB RI` -> Encaminhar para Saída 3

#### Nós de Envio de E-mail (SMTP)
Configure os nós de envio para cada uma das saídas do Switch:

##### 🔴 Saída 0 (Orion TN):
*   **To Email:** `ricardo.vieira@siplan.com.br, rodrigo.brites@siplan.com.br, bruno.santos@siplan.com.br`
*   **Subject:** `📥 [SIPLAN HUB] Nova Homologação Orion TN — {{ $node["Supabase - Detalhes do Projeto"].json.client_name }}`
*   **Format:** `HTML`
*   **Body (HTML):**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <style>
    body { font-family: 'Segoe UI', Arial, sans-serif; color: #1e293b; background-color: #f8fafc; margin: 0; padding: 20px; }
    .card { background-color: #ffffff; border-radius: 12px; border: 1px solid #e2e8f0; max-width: 600px; margin: 0 auto; overflow: hidden; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05); }
    .header { background-color: #ad0505; color: #ffffff; padding: 25px; text-align: left; }
    .header h1 { margin: 0; font-size: 20px; font-weight: 800; }
    .content { padding: 30px; }
    .badge { background-color: #fee2e2; color: #ad0505; padding: 6px 12px; border-radius: 50px; font-size: 11px; font-weight: bold; text-transform: uppercase; display: inline-block; margin-bottom: 20px; }
    .info-table { width: 100%; border-collapse: collapse; margin-bottom: 25px; }
    .info-table td { padding: 12px; border-bottom: 1px solid #f1f5f9; font-size: 14px; }
    .info-label { font-weight: bold; color: #64748b; width: 30%; }
    .button-container { text-align: center; margin-top: 30px; }
    .button { background-color: #ad0505; color: #ffffff; padding: 12px 30px; text-decoration: none; border-radius: 6px; font-weight: bold; font-size: 14px; display: inline-block; }
    .footer { background-color: #f8fafc; padding: 20px; text-align: center; font-size: 11px; color: #94a3b8; border-top: 1px solid #f1f5f9; }
  </style>
</head>
<body>
  <div class="card">
    <div class="header">
      <h1>SIPLAN HUB</h1>
    </div>
    <div class="content">
      <span class="badge">📥 Nova Homologação</span>
      <h2 style="margin-top:0; color:#0f172a;">Homologação Pendente de Validação</h2>
      <p>Olá equipe de implantação do <strong>Orion TN</strong>,</p>
      <p>A base de dados do cliente abaixo foi convertida e enviada para homologação. Por favor, realizem os testes e insiram o parecer técnico no painel.</p>
      
      <table class="info-table">
        <tr>
          <td class="info-label">Cliente:</td>
          <td style="font-weight: bold;">{{ $node["Supabase - Detalhes do Projeto"].json.client_name }}</td>
        </tr>
        <tr>
          <td class="info-label">Chamado:</td>
          <td>#{{ $node["Supabase - Detalhes do Projeto"].json.ticket_number }}</td>
        </tr>
        <tr>
          <td class="info-label">Sistema:</td>
          <td><strong style="color: #ad0505;">Orion TN</strong></td>
        </tr>
        <tr>
          <td class="info-label">Enviado por:</td>
          <td>{{ $node["Webhook - Nova Homologação"].json.body.record.sent_by_name }}</td>
        </tr>
      </table>

      <!-- Bloco de Orientação sobre Credenciais e Acessos -->
      <table width="100%" border="0" cellspacing="0" cellpadding="0" style="background-color: #fff5f5; border-radius: 8px; border: 1px dashed #feb2b2; margin: 20px 0; padding: 15px; text-align: left;">
        <tr>
          <td>
            <strong style="color: #ad0505; font-size: 12px; text-transform: uppercase; display: block; margin-bottom: 5px;">🔑 DADOS DE CONEXÃO & SERVIDOR:</strong>
            <span style="font-size: 13px; color: #475569; line-height: 1.5; display: block;">
              Os acessos ao servidor técnico e à base de dados legada variam por projeto. Por favor, <strong>entre em contato diretamente com o responsável pela conversão</strong> (indicado no campo "Enviado por") para obter as credenciais e conexões seguras.
            </span>
          </td>
        </tr>
      </table>

      <!-- Bloco A Bola Está com Você -->
      <table width="100%" border="0" cellspacing="0" cellpadding="0" style="background-color: #fff5f5; border-radius: 8px; border: 1px dashed #feb2b2; margin-top: 20px; padding: 20px; text-align: left;">
        <tr>
          <td>
            <h3 style="color: #ad0505; font-size: 14px; margin: 0 0 12px 0; font-weight: bold; text-transform: uppercase; letter-spacing: 0.5px;">
              🎯 A BOLA ESTÁ COM VOCÊ — PRÓXIMOS PASSOS:
            </h3>
            <ul style="margin: 0; padding-left: 20px; color: #475569; font-size: 14px; line-height: 1.8;">
              <li style="margin-bottom: 8px;"><strong style="color: #ad0505;">🔴 NO HUB:</strong> Acesse a tela de Homologação em `/implantadores/homologation` e clique no botão <strong style="color: #1e293b;">Assumir</strong> na Fila Geral.</li>
              <li style="margin-bottom: 8px;"><strong style="color: #475569;">⚙️ AÇÃO OPERACIONAL:</strong> Entre em contato com o responsável pela Conversão para obter os dados de acesso ao servidor.</li>
              <li style="margin-bottom: 8px;"><strong style="color: #475569;">⚙️ AÇÃO OPERACIONAL:</strong> Efetue os testes operacionais detalhados na base de dados convertida.</li>
              <li style="margin-bottom: 0;"><strong style="color: #ad0505;">🔴 NO HUB:</strong> Preencha o parecer conclusivo no painel e dê seu veredito final (<em style="color: #1e293b; font-style: normal; font-weight: 600;">Aprovado</em> ou <em style="color: #1e293b; font-style: normal; font-weight: 600;">Com Inconsistências</em>).</li>
            </ul>
          </td>
        </tr>
      </table>

      <div class="button-container">
        <a href="https://siplanhub.vercel.app/implantadores/homologation" class="button">Validar no Siplan HUB</a>
      </div>
    </div>
    <div class="footer">
      E-mail automático gerado pelo Siplan HUB. Não responda a este e-mail.
    </div>
  </div>
</body>
</html>
```

##### 🟢 Saída 1 (Orion PRO):
*   **To Email:** `bruno.santos@siplan.com.br, rodrigo.brites@siplan.com.br, rodrigo.mizuno@siplan.com.br`
*   **Subject:** `📥 [SIPLAN HUB] Nova Homologação Orion PRO — {{ $node["Supabase - Detalhes do Projeto"].json.client_name }}`
*   *(HTML idêntico ao TN, alterando apenas a linha do sistema para **Orion PRO**).*

##### 🔵 Saída 2 (Orion REG):
*   **To Email:** `julio.araujo@siplan.com.br`
*   **Subject:** `📥 [SIPLAN HUB] Nova Homologação Orion REG — {{ $node["Supabase - Detalhes do Projeto"].json.client_name }}`
*   *(HTML idêntico ao TN, alterando apenas a linha do sistema para **Orion REG**).*

##### 🟣 Saída 3 (WEB RI):
*   **To Email:** `fernando.lopes@siplan.com.br`
*   **Subject:** `📥 [SIPLAN HUB] Nova Homologação WEB RI — {{ $node["Supabase - Detalhes do Projeto"].json.client_name }}`
*   *(HTML idêntico ao TN, alterando apenas a linha do sistema para **WEB RI**).*

---

## 🛠️ Automação B: Homologação Aprovada ou Reprovada

### 1. Descrição do Fluxo
Esta automação é disparada quando um implantador finaliza o processo de validação em `/implantadores/homologation` e emite o parecer conclusivo. O status do chamado (`queue_status`) transiciona para `done` (Aprovada) ou `homologation_issues` (Reprovada / Com Inconsistências). A automação busca o e-mail do analista de conversão de forma dinâmica e o notifica sobre o veredicto.

```mermaid
graph TD
    A[Supabase Webhook: UPDATE conversion_queue] --> B[n8n Webhook Node]
    B --> C[IF Node: Validar Conclusão / Recusa]
    C -- Sim --> D[Supabase Node: Buscar E-mail do Responsável]
    D --> E[IF Node: Validar se Achou E-mail]
    E -- Não --> F[Code Node: Buscar Fallback no Mapeamento]
    E -- Sim --> G[Merge / Unificar Fluxo]
    F --> G
    G --> H[IF Node: Aprovado vs Reprovado]
    H -- Aprovado --> I[Send Email: Conversão Aprovada]
    H -- Reprovado --> J[Supabase Node: Buscar Parecer de Inconsistências]
    J --> K[Send Email: Conversão Reprovada com Parecer]
```

### 2. Configuração do Webhook no Supabase (Trigger)
Crie um Database Webhook no painel do Supabase com os seguintes parâmetros:
*   **Name:** `n8n_parecer_homologacao`
*   **Table:** `conversion_queue`
*   **Events:** Selecionar `Update`
*   **Method:** `POST`
*   **URL:**
    *   *Testes:* `https://n8n.siplan.com.br/webhook-test/parecer-homologacao`
    *   *Produção:* `https://n8n.siplan.com.br/webhook/parecer-homologacao`
*   **Headers:** `Content-Type: application/json`

### 3. Configuração dos Nós no n8n

#### Nó 1: Webhook (Gatilho)
*   **Path:** `parecer-homologacao`

#### Nó 2: IF (Validação de Status Finais)
Verifica se o status mudou para finalizado (`done`) ou devolvido com inconsistências (`homologation_issues`).
*   **Name:** `IF - Status Final`
*   **Conditions -> String:**
    *   **Value 1:** `{{ $json.body.record.queue_status }}`
    *   **Operation:** `Regex Match`
    *   **Value 2:** `^(done|homologation_issues)$`

#### Nó 3: Supabase (Consulta Perfil do Conversor)
Busca o e-mail do analista associado ao ID `assigned_to` do registro atualizado.
*   **Name:** `Supabase - Buscar Perfil`
*   **Resource:** `Database`
*   **Operation:** `Get`
*   **Table:** `profiles`
*   **Row ID:** `{{ $node["Webhook - Nova Homologação"].json.body.record.assigned_to }}`

#### Nó 4: IF (Verificar e-mail no Perfil)
Valida se a consulta retornou um e-mail válido.
*   **Name:** `IF - Achou E-mail`
*   **Conditions -> String:**
    *   **Value 1:** `{{ $json.email }}`
    *   **Operation:** `Not Empty`

#### Nó 5: Code (Busca estática de Fallback)
Caso o e-mail não esteja cadastrado na tabela de perfis, busca no mapeamento estático a partir do nome do conversor (`assigned_to_name`).
*   **Name:** `Code - Busca Fallback`
*   *(Insira o código JavaScript de fallback disponível no manual [Recurso] Tabela Geral de Mapeamento de E-mails).*

#### Nó 6: Merge (Unificação)
Une as saídas de sucesso do perfil (Nó 4 True) e do fallback (Nó 5) para seguir o fluxo com a variável `resolved_email`.

#### Nó 7: IF (Aprovado vs Reprovado)
*   **Name:** `IF - É Aprovado?`
*   **Conditions -> String:**
    *   **Value 1:** `{{ $node["Webhook - Nova Homologação"].json.body.record.queue_status }}`
    *   **Operation:** `Equal`
    *   **Value 2:** `done`

---

### 4. Configuração dos Modelos de E-mail

#### 🟢 Fluxo 1: Homologação Aprovada (IF True)
*   **To Email:** `{{ $json.resolved_email }}`
*   **Subject:** `🎉 [SIPLAN HUB] Conversão APROVADA! — {{ $node["Supabase - Detalhes do Projeto"].json.client_name }}`
*   **Format:** `HTML`
*   **Body (HTML):**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <style>
    body { font-family: 'Segoe UI', Arial, sans-serif; color: #1e293b; background-color: #f8fafc; margin: 0; padding: 20px; }
    .card { background-color: #ffffff; border-radius: 12px; border: 1px solid #e2e8f0; max-width: 600px; margin: 0 auto; overflow: hidden; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05); }
    .header { background-color: #0f766e; color: #ffffff; padding: 25px; text-align: left; }
    .header h1 { margin: 0; font-size: 20px; font-weight: 800; }
    .content { padding: 30px; }
    .badge { background-color: #ccfbf1; color: #0f766e; padding: 6px 12px; border-radius: 50px; font-size: 11px; font-weight: bold; text-transform: uppercase; display: inline-block; margin-bottom: 20px; }
    .info-table { width: 100%; border-collapse: collapse; margin-bottom: 25px; }
    .info-table td { padding: 12px; border-bottom: 1px solid #f1f5f9; font-size: 14px; }
    .info-label { font-weight: bold; color: #64748b; width: 30%; }
    .footer { background-color: #f8fafc; padding: 20px; text-align: center; font-size: 11px; color: #94a3b8; border-top: 1px solid #f1f5f9; }
  </style>
</head>
<body>
  <div class="card">
    <div class="header">
      <h1>SIPLAN HUB</h1>
    </div>
    <div class="content">
      <span class="badge">✓ APROVADA</span>
      <h2 style="margin-top:0; color:#0f172a;">Parabéns! Conversão Concluída</h2>
      <p>Olá <strong>{{ $node["Webhook - Nova Homologação"].json.body.record.assigned_to_name }}</strong>,</p>
      <p>A homologação da base de dados do cliente foi realizada e **APROVADA** pelo implantador. O estágio de conversão de dados do projeto foi dado como concluído no painel.</p>
      
      <table class="info-table">
        <tr>
          <td class="info-label">Cliente:</td>
          <td style="font-weight: bold;">{{ $node["Supabase - Detalhes do Projeto"].json.client_name }}</td>
        </tr>
        <tr>
          <td class="info-label">Chamado:</td>
          <td>#{{ $node["Supabase - Detalhes do Projeto"].json.ticket_number }}</td>
        </tr>
        <tr>
          <td class="info-label">Homologado por:</td>
          <td>{{ $node["Webhook - Nova Homologação"].json.body.record.homologation_analyst_name }}</td>
        </tr>
      </table>
    </div>
    <div class="footer">
      E-mail automático gerado pelo Siplan HUB. Não responda a este e-mail.
    </div>
  </div>
</body>
</html>
```

---

#### 🔴 Fluxo 2: Homologação Reprovada (IF False)

##### Nó Adicional Necessário antes do Envio de E-mail:
Como a reprovação exige que o analista saiba quais foram as inconsistências, a automação deve buscar o parecer inserido pelo implantador. Este parecer foi salvo na tabela `homologation_events` no campo `notes` (em HTML, incluindo imagens anexadas).
*   **Nó:** `Supabase - Buscar Parecer`
*   **Credential:** `Supabase API`
*   **Operation:** `Get Many` (ou query direta)
*   **Table:** `homologation_events`
*   **Filters:**
    *   `project_id` = `{{ $node["Webhook - Nova Homologação"].json.body.record.project_id }}`
    *   `to_status` = `homologation_issues`
*   **Sort:** `timestamp` Descending (limite `1` para pegar o último evento de recusa).

##### Nó de Envio de E-mail:
*   **To Email:** `{{ $json.resolved_email }}`
*   **Subject:** `⚠️ [SIPLAN HUB] Conversão REPROVADA (Inconsistências) — {{ $node["Supabase - Detalhes do Projeto"].json.client_name }}`
*   **Format:** `HTML`
*   **Body (HTML):**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <style>
    body { font-family: 'Segoe UI', Arial, sans-serif; color: #1e293b; background-color: #f8fafc; margin: 0; padding: 20px; }
    .card { background-color: #ffffff; border-radius: 12px; border: 1px solid #e2e8f0; max-width: 600px; margin: 0 auto; overflow: hidden; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05); }
    .header { background-color: #ad0505; color: #ffffff; padding: 25px; text-align: left; }
    .header h1 { margin: 0; font-size: 20px; font-weight: 800; }
    .content { padding: 30px; }
    .badge { background-color: #fee2e2; color: #ad0505; padding: 6px 12px; border-radius: 50px; font-size: 11px; font-weight: bold; text-transform: uppercase; display: inline-block; margin-bottom: 20px; }
    .info-table { width: 100%; border-collapse: collapse; margin-bottom: 25px; }
    .info-table td { padding: 12px; border-bottom: 1px solid #f1f5f9; font-size: 14px; }
    .info-label { font-weight: bold; color: #64748b; width: 30%; }
    .report-box { background-color: #fff5f5; border: 1px solid #feb2b2; border-radius: 8px; padding: 20px; margin-top: 25px; font-size: 14px; line-height: 1.6; }
    .button-container { text-align: center; margin-top: 30px; }
    .button { background-color: #ad0505; color: #ffffff; padding: 12px 30px; text-decoration: none; border-radius: 6px; font-weight: bold; font-size: 14px; display: inline-block; }
    .footer { background-color: #f8fafc; padding: 20px; text-align: center; font-size: 11px; color: #94a3b8; border-top: 1px solid #f1f5f9; }
  </style>
</head>
<body>
  <div class="card">
    <div class="header">
      <h1>SIPLAN HUB</h1>
    </div>
    <div class="content">
      <span class="badge">⚠️ REPROVADA COM INCONSISTÊNCIAS</span>
      <h2 style="margin-top:0; color:#0f172a;">Ajustes Necessários na Conversão</h2>
      <p>Olá <strong>{{ $node["Webhook - Nova Homologação"].json.body.record.assigned_to_name }}</strong>,</p>
      <p>A base de dados do cliente abaixo retornou da homologação com **inconsistências apontadas pelo implantador**. O projeto foi devolvido para a sua fila em `/conversion` com status pendente de correções.</p>
      
      <table class="info-table">
        <tr>
          <td class="info-label">Cliente:</td>
          <td style="font-weight: bold;">{{ $node["Supabase - Detalhes do Projeto"].json.client_name }}</td>
        </tr>
        <tr>
          <td class="info-label">Chamado:</td>
          <td>#{{ $node["Supabase - Detalhes do Projeto"].json.ticket_number }}</td>
        </tr>
        <tr>
          <td class="info-label">Recusado por:</td>
          <td>{{ $node["Webhook - Nova Homologação"].json.body.record.homologation_analyst_name }}</td>
        </tr>
      </table>

      <div class="report-box">
        <h3 style="margin-top: 0; color: #991b1b; font-size: 14px; text-transform: uppercase;">📋 PARECER TÉCNICO DE INCONSISTÊNCIAS:</h3>
        <!-- Renderiza o HTML das observações escritas pelo implantador no editor rico (incluindo imagens) -->
        {{ $node["Supabase - Buscar Parecer"].json.notes }}
      </div>

      <!-- Bloco A Bola Está com Você -->
      <table width="100%" border="0" cellspacing="0" cellpadding="0" style="background-color: #fff5f5; border-radius: 8px; border: 1px dashed #feb2b2; margin-top: 20px; padding: 20px; text-align: left;">
        <tr>
          <td>
            <h3 style="color: #ad0505; font-size: 14px; margin: 0 0 12px 0; font-weight: bold; text-transform: uppercase; letter-spacing: 0.5px;">
              🎯 A BOLA ESTÁ COM VOCÊ — PRÓXIMOS PASSOS:
            </h3>
            <ul style="margin: 0; padding-left: 20px; color: #475569; font-size: 14px; line-height: 1.8;">
              <li style="margin-bottom: 8px;"><strong style="color: #ad0505;">🔴 NO HUB:</strong> Acesse a Fila de Conversão em `/conversion` e abra o card detalhado do cliente.</li>
              <li style="margin-bottom: 8px;"><strong style="color: #475569;">📋 OPERACIONAL:</strong> Analise o relatório técnico de inconsistências e prints colados pelo implantador acima.</li>
              <li style="margin-bottom: 8px;"><strong style="color: #475569;">⚙️ AÇÃO OPERACIONAL:</strong> Realize os ajustes e correções necessárias na estrutura/conversor do banco.</li>
              <li style="margin-bottom: 0;"><strong style="color: #ad0505;">🔴 NO HUB:</strong> Após testar as correções, reenvie a base para homologação para que o implantador valide novamente.</li>
            </ul>
          </td>
        </tr>
      </table>

      <div class="button-container">
        <a href="https://siplanhub.vercel.app/conversion" class="button">Acessar Fila de Conversão</a>
      </div>
    </div>
    <div class="footer">
      E-mail automático gerado pelo Siplan HUB. Não responda a este e-mail.
    </div>
  </div>
</body>
</html>
```
