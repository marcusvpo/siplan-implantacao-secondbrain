---
tipo: MOC
area: Orion TN
tags:
  - #orion
  - #orion_tn
  - #notas
status_atual: #ativo
---
# MOC - Orion TN: Tabelionato de Notas

O **Orion TN** é a plataforma de última geração da Siplan para automação de Tabelionatos de Notas. O sistema adota uma arquitetura 100% web com operação via navegador (ex: Chrome), eliminando a necessidade de instalações pesadas em estações locais e reduzindo custos operacionais ao utilizar bancos de dados Open Source. 

Este Mapa de Conteúdo (MOC) organiza o conhecimento operacional, manuais e procedimentos passo a passo do sistema Orion TN em cinco grandes áreas funcionais (módulos).

## 🗂️ Módulos Funcionais e Capacidades

### 1. [[Orion TN - Balcão de Firmas|Balcão de Firmas]]
Centraliza todas as operações de balcão do cartório, com forte ênfase em automação e velocidade no reconhecimento de firmas e autenticações.
- **Principais Rotinas Documentadas:**
  - Consulta e gerenciamento de cartões de assinatura (cadastro básico, pesquisa e inativação).
  - Captura e vinculação de documentos de identificação, fotos e dados biométricos em cartões de assinatura.
  - Processo de digitalização em lote de cartões por sequência física ou códigos de barra.
  - Lavratura e controle de Termos de Comparecimento.
  - Fluxo completo para realizar Reconhecimento de Firmas (pesquisa de fichas, conferência de imagem e confirmação).
  - Reconhecimento automático de assinaturas em DUT (Documento Único de Transferência) com uso de Inteligência Artificial.
  - Consultas rápidas de serviços praticados e auditoria de assinaturas do balcão.

### 2. [[Orion TN - Escrituração de Atos|Escrituração de Atos]]
Gerencia a lavratura, qualificação e redação de escrituras, procurações e outros atos notariais usando minutas inteligentes e editor integrado.
- **Principais Rotinas Documentadas:**
  - Abertura e preenchimento de Protocolo de Notas (prazos, status e bloqueios).
  - Qualificação de partes e dados de imóveis (integração de dados e digitação guiada).
  - Qualificação e importação de partes de outros protocolos ou através de Inteligência Artificial.
  - Editor de Texto Rico integrado (baseado em LibreOffice) para lavratura de escrituras e procurações.
  - Cadastro, organização e aplicação de minutas pré-configuradas e modelos de textos.
  - Revisão ortográfica, gramatical e de minutas com Inteligência Artificial embarcada.
  - Geração de Livros a partir de minutas e emissão de Traslados correspondentes.
  - Parametrização de naturezas de atos, tabelas de custas e trâmites de fluxos de trabalho.

### 3. [[Orion TN - Caixa e Financeiro|Caixa e Financeiro]]
Controla todo o fluxo financeiro da serventia, englobando recebimento de atos de notas e firmas, controle de mensalistas, cobranças por Pix/cartão e conciliação bancária.
- **Principais Rotinas Documentadas:**
  - Processamento de pagamentos no caixa e recebimentos de atos (PIX com QR Code, cartões, links de pagamento).
  - Geração de orçamentos rápidos e orçamentos detalhados de atos e firmas.
  - Controle de mensalistas (cadastro de contas corporativas, parametrização de filiais, fechamentos periódicos e relatórios).
  - Faturamento de mensalistas (geração de faturas, links de pagamento, emissão e envio de boletos por e-mail/WhatsApp).
  - Importação de arquivo de retorno bancário de boletos e conciliação de saldos e faturas.
  - Gerenciamento de comissões de escreventes e funcionários.
  - Lançamento de Depósito Prévio e geração de relatórios de caixa (recolhimento diário, resumido e Livro Caixa).
  - Integração com o Livro Caixa Web (LCW) para exportação automática de receitas e Livro Diário Auxiliar.

### 4. [[Orion TN - Certidões e GED|Certidões e GED]]
Responsável pela emissão de certidões, controle de reprografia e o gerenciamento eletrônico de documentos (GED) integrado.
- **Principais Rotinas Documentadas:**
  - Fluxo de solicitação, criação e controle de pedidos de certidões (dentro de protocolos de notas ou avulsas).
  - Redação e geração de certidões no editor de texto.
  - Emissão de recibos de certidão, histórico de emissões e estornos de recibos.
  - Vinculação de atos a certidões para fins de reprografia.
  - Orion GED: criação de pastas, indexadores, OCR em documentos digitalizados, uploads em lote e assinaturas eletrônicas.
  - Digitalização em lote de livros físicos e folhas soltas.

### 5. [[Orion TN - Selos e Integrações|Selos e Integrações]]
Controla a conformidade regulatória do cartório junto aos tribunais e a interoperabilidade com órgãos externos e centrais eletrônicas.
- **Principais Rotinas Documentadas:**
  - Consulta de indisponibilidade de bens na base nacional (CENIB/CNIB) e vinculação automática ao protocolo.
  - Controle e consumo de Papéis de Segurança do cartório.
  - Geração e controle de Selos Digitais (consumo automático, fechamento e transmissão ao TJ/SP).
  - Configuração de envio automático de selos digitais ao TJ (modo online e offline, rotina de auditoria e contingências).
  - Integrações nativas com centrais: e-Notariado, COAF, SEFAZ, DOIWeb, SIGNO (CEP, CESDI e RCTO) e ONR.
  - Integração com o SGA (Sistema de Gestão de Atendimento) para totens de senhas, chamadas em painéis e solicitação de senhas via web.
  - Cadastro de impedimentos de pessoas ou documentos na base interna.

---

## 📂 Arquivos de Referência Completa
Para buscas exaustivas não segmentadas e consulta aos dados originais estruturados, utilize os seguintes arquivos:
- Documento Analítico de Negócio: [[relatorio_orion_tn_siplan]]
- Base de Conhecimento Bruta: [[Orion_TN_Limpo]]
