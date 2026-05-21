---
tipo: Regra
area: Implantação Funcional
tags:
  - #implantacao
  - #aderencia
  - #padronizacao
---
# [Modelo] Template Padrão - Análise de Aderência

Este é o template unificado e padronizado para a realização da **Análise de Aderência do Processo de Negócio** (Fase 3 do Fluxo de Implantação). Ele foi desenhado para abandonar o antigo formato de "Checklist Simples" e atuar como uma verdadeira investigação técnica e estrutural do cartório, unindo as melhores práticas do modelo Orion REG às especificidades do Orion TN e PRO.

## ── 1. IDENTIFICAÇÃO ──
- **Sistema a implantar:** (ex: OrionTN, OrionREG, OrionPRO)
- **Sistema Legado:**
- **Cidade/Serventia:**
- **Analista Responsável (Siplan):**
- **Responsável pelo Preenchimento (Cartório):** (Nome, Cargo, Telefone/WhatsApp, E-mail)
- **Data do Preenchimento:**

## ── 2. ESTRUTURA FÍSICA E ORGANIZACIONAL ──
*Objetivo: Evitar subdimensionamento de equipe de implantação.*
- Quantos andares possui a serventia? (Detalhe a distribuição dos setores por andar)
- Quais setores existem no estabelecimento? (Recepção, Registro, Financeiro, Digitalização, etc.)
- Qual a quantidade total de colaboradores? E por setor?
- Todos os colaboradores estão cientes da mudança do sistema? Como a equipe costuma lidar com mudanças tecnológicas?

## ── 3. INFRAESTRUTURA LOCAL E PERIFÉRICOS ──
*Objetivo: Identificar bloqueios de hardware antes da viagem (em complemento à Análise de Ambiente TI).*
- **Impressoras/Scanners:** Possuem equipamentos compatíveis? Realizam digitalização de DUTS/Fichas?
- **Periféricos de Identificação (Para Notas/TN):** Utilizam biometria (Griaule/Fingertech)? Utilizam webcams homologadas?
- **Controle de Selos:** O controle e consumo é automático ou manual?

## ── 4. RECEPÇÃO E ATENDIMENTO ──
- Como os protocolos/pedidos são separados na recepção?
- Existe algum sistema de Senhas/Fila de Atendimento integrado?
- O Orçamento/Prévia de custas é realizado no momento do atendimento ou posterior?
- Como é realizado o envio de solicitação de complemento para os clientes? (WhatsApp, E-mail, Telefone?)

## ── 5. ROTINAS DE NEGÓCIO ESPECÍFICAS (Por Sistema) ──
*(O analista deve aplicar o bloco referente ao sistema sendo implantado)*

### Para Orion TN (Notas):
- **Mensalistas:** Utiliza controle de mensalistas? Boleto bancário ou envio de e-mail para cobrança?
- **Sinal Público:** Utiliza cadastro e controle rigoroso de Sinal Público?
- **Fichas e Reconhecimento:** Utiliza consulta de logs nas firmas? Possui relatório manual de NFS para fichas antigas?
- **Escrituras:** Utiliza rotina de Livro de Depósito Prévio? (Bomba-relógio: As minutas foram enviadas para a equipe de Modelos da Siplan?)

### Para Orion REG (Imóveis e TDPJ):
- **Qualificação:** Em que momento ocorre a qualificação das partes? Existe inserção de dados retroativos frequentemente?
- **Controle de Sequência:** Como realiza o controle de sequência dos registros e averbações?
- **Notificações:** Como ocorre a sequência de certificações e controle de prazos das notificações?

## ── 6. FINANCEIRO E CUSTAS ──
- Como é realizado o fechamento diário do caixa? (Ex: Planilha externa, cruzamento de relatórios, caixa cego?)
- O cartório utiliza integração com meios de pagamento? (Pix, Parcela Express)
- Emissão de Nota Fiscal: É gerado RPS para emissão de nota fiscal eletrônica de serviços?
- Repasses: Quais relatórios são usados para cruzamento de selos e repasses a órgãos?

## ── 7. IMAGENS E GED (Gerenciamento Eletrônico de Documentos) ──
- Em que momento ocorre a digitalização dos documentos? (Durante o balcão, no final do processo, terceirizado?)
- Informe o caminho do servidor onde as imagens estão armazenadas (O cliente realiza a migração dos volumes?).

## ── 8. INTEGRAÇÕES E CENTRAIS ──
- **Site Institucional:** A serventia dispõe de site institucional com integração ao sistema para consulta de selos/protocolos?
- **Centrais Estaduais/Nacionais:** (ONR, CENSEC, CRC). Descreva o fluxo de recepção. O registro é feito imediatamente ou somente após o pagamento do orçamento enviado pela central?

## ── 9. MAPEAMENTO DE RISCO ("BOMBAS-RELÓGIO") ──
*Espaço para o analista registrar dependências críticas de terceiros.*
- Existem modelos/minutas a serem convertidas pela equipe técnica da Siplan que o cliente ainda não enviou?
- Existem particularidades graves (ex: uso intensivo de um relatório que o sistema novo não possui nativamente)?