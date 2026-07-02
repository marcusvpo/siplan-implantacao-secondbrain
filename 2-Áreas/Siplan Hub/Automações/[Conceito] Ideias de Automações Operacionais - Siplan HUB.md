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
# 💡 Ideias de Automações Operacionais de Comunicação — Siplan HUB

Este documento reúne propostas de novas automações focadas em notificação, alertas e integração de canais de comunicação baseadas em eventos ocorridos dentro do **Siplan HUB**. O objetivo principal é extinguir gargalos de comunicação ("telefone sem fio"), acelerar o tempo de resposta das equipes e elevar a transparência das etapas para os gestores.

As ideias aprovadas nesta lista serão posteriormente detalhadas com passo a passo de implantação técnica no n8n.

---

## 🎯 1. Fluxo Comercial & Pré-Implantação

### 💡 Ideia 1.1: Alerta Imediato de Blocker Comercial
*   **Como funciona na prática**: Quando um implantador ou comercial insere/ativa um impedimento comercial na tela `/commercial/blockers`, o n8n captura o `INSERT` na tabela `public.commercial_blockers` e envia um e-mail urgente para o gestor e para o vendedor responsável pelo contrato.
*   **Quem é notificado**: Gestor da implantação (Marcus) e o vendedor associado ao cliente.
*   **Benefício**: Evita que projetos fiquem "congelados" por pendências comerciais (ex: falta de assinatura, boleto atrasado) sem que a equipe de vendas saiba.

### 💡 Ideia 1.2: Boas-Vindas e Link Público de Coleta de Infra ao Cliente
*   **Como funciona na prática**: Assim que o formulário de passagem comercial (`deployment_forms`) é submetido, além de criar o projeto ativo, o n8n dispara um e-mail de boas-vindas assinado pela Siplan diretamente para o e-mail da serventia (cartório), contendo instruções e o link único de coleta técnica (`/public/infra-coleta/:id`).
*   **Quem é notificado**: Tabelião / TI do Cartório (Cliente).
*   **Benefício**: Inicia a coleta de especificações físicas do servidor e estações no dia 1, reduzindo em até 5 dias o tempo de início técnico da implantação.

### 💡 Ideia 1.3: Conclusão Automática da Coleta Pública de Infraestrutura
*   **Como funciona na prática**: Quando o cliente finaliza o envio dos arquivos `.txt` pelo portal público (`PublicInfraCollection.tsx`), disparando a gravação de dados, o n8n detecta a mudança e envia uma notificação automática para a equipe de infra da Siplan.
*   **Quem é notificado**: Equipe de Infraestrutura (Alex Silva e Hugo Januário).
*   **Benefício**: A infraestrutura sabe exatamente quando o inventário do cartório foi preenchido, podendo iniciar a análise técnica sem necessidade de cobrança humana.

---

## ⚙️ 2. Engenharia e Conversão de Banco de Dados

### 💡 Ideia 2.1: Solicitação de Motor de Conversão Pendente
*   **Como funciona na prática**: Quando o analista de conversão clica no botão "Enviar para Criação do Conversor" (mudando `engine_status` para `pending_engine`), o n8n dispara um e-mail com os dados do sistema legado e observações anexadas.
*   **Quem é notificado**: Coordenador de Engenharia / Desenvolvimento.
*   **Benefício**: Agiliza a criação ou ajuste de conversores para sistemas legados complexos ou raros (ex: Control-M TABNOT de layouts muito antigos).

### 💡 Ideia 2.2: Alerta de Erros de Conversão Recorrentes por Sistema Legado
*   **Como funciona na prática**: Cron semanal que analisa a quantidade de eventos `homologation_issues` (recusas de homologação) agregados por sistema legado original. Se um determinado legado apresenta mais de 3 recusas na semana, gera um e-mail consolidado para revisão do conversor.
*   **Quem é notificado**: Equipe de Conversão e Coordenação.
*   **Benefício**: Identifica bugs sistêmicos na ferramenta de conversão que estão gerando retrabalho constante.

---

## 📅 3. Planejamento, Agendas e Operação de Campo

### 💡 Ideia 3.1: Alerta de SLA de Projeto Estagnado (Health Alert)
*   **Como funciona na prática**: Cron diário que verifica projetos em andamento (`global_status === 'in-progress'`) cuja data de última atualização (`updated_at`) seja superior a 3 dias (Warning) ou 7 dias (Critical). Envia um e-mail listando os projetos frios e suas respectivas últimas observações de etapa.
*   **Quem é notificado**: Gestores do HUB (Marcus e Maria) e o analista responsável pela etapa estagnada.
*   **Benefício**: Evita o esquecimento ou a falta de atualização ativa de projetos no painel, mantendo os indicadores de saúde sempre confiáveis.

### 💡 Ideia 3.2: Confirmação de Agenda de Go-Live ("Hora Zero")
*   **Como funciona na prática**: Quando a data da virada final (`implementation_phase1.startDate`) é salva ou reagendada no calendário do HUB, o n8n envia um e-mail estruturado detalhando o plano de ação de virada de final de semana e pré-requisitos para o suporte interno e para o cartório.
*   **Quem é notificado**: Suporte de Retaguarda Siplan (Service Desk), Implantador escalado e Cliente.
*   **Benefício**: Garante que o suporte da retaguarda esteja de sobreaviso para atender a serventia em caso de instabilidade na hora da virada.

### 💡 Ideia 3.3: Alerta de Conflito de Agenda ou Férias do Implantador
*   **Como funciona na prática**: Quando um projeto é atribuído a um implantador para viagem, o n8n consulta a tabela de férias (`vacation_management`) e as agendas existentes. Se houver sobreposição de datas de viagem com folgas ou outro go-live, dispara um alerta no e-mail da coordenação.
*   **Quem é notificado**: Coordenação de Implantação (Maria).
*   **Benefício**: Previne erros operacionais de escala de viagens de implantadores de campo.

---

## 📈 4. Pós-Implantação e Qualidade

### 💡 Ideia 4.1: Gatilho de Pesquisa de Satisfação Pós-Implantação
*   **Como funciona na prática**: Assim que o estágio 7 (Pós-Implantação) tem seu status definido como `done`, o n8n aguarda 2 dias e dispara automaticamente um link externo de NPS (Pesquisa de Satisfação de Implantação e Treinamento) para o Tabelião do cartório.
*   **Quem é notificado**: Tabelião do Cartório (Cliente).
*   **Benefício**: Coleta dados de satisfação estruturados de forma impessoal e direta na ferramenta, gerando insumos para melhoria contínua da equipe.

### 💡 Ideia 4.2: Transição para o Suporte / Encerramento do Período de Acompanhamento
*   **Como funciona na prática**: Um cron diário monitora se a data atual ultrapassou o campo `support_end_date` (fim do período de acompanhamento da implantação). Ao expirar, o n8n atualiza o projeto, envia um e-mail ao cliente formalizando a transição definitiva para o Service Desk da Siplan (abrindo chamados via portal/0800 comum) e notifica o time de suporte.
*   **Quem é notificado**: Cliente e Coordenador de Suporte.
*   **Benefício**: Estabelece um limite formal de atendimento preferencial do implantador, educando o cliente a abrir chamados ordinários nos canais de suporte padrão.
