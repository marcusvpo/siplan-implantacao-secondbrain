---
tipo: Recurso
area: Produtos Siplan
tags:
  - #legado
  - #sistemas
  - #controlm
  - #migracao
status_atual: #ativo
---
# [Recurso] Sistemas Legados Siplan e Control-M

Este documento serve como a base de conhecimento técnica e operacional exaustiva acerca dos sistemas legados das linhas **Siplan** e **Control-M (CM)**. Compreender essas soluções legadas é essencial para orientar os processos de conversão de banco de dados, mapeamento de regras de negócios antigas e planejamento da migração para a moderna **Arquitetura Orion**.

---

## 📊 1. Tabela Geral de Equivalência e Migração

Abaixo está o mapeamento de correspondência indicando qual sistema moderno da linha Orion (ou solução complementar) substitui cada uma das soluções legadas durante o processo de implantação:

| Nome do Sistema Legado | Especialidade(s) Atendida(s) | Sistema Equivalente / Destino na Linha Orion | Observações de Migração |
| :--- | :--- | :--- | :--- |
| **Control-M Distribuidor** | Distribuidor (Protesto) | [[MOC - Orion PRO\|Orion PRO]] (Módulo Distribuidor) | Importação e retorno de remessas e compensações integradas. |
| **Control-M GED** | Todas as Naturezas | [[MOC - Produtos Siplan\|Orion GED]] | Módulo de digitalização agora integrado com OCR nativo. |
| **Control-M PROT** | PT, TNPT (Pequeno/Médio) | [[MOC - Orion PRO\|Orion PRO]] | Migração de títulos, devedores, históricos de protesto e caixas. |
| **Control-M REG** | RI (Registro de Imóveis) | Orion REG / WEB RI | Conversão da base de matrículas, proprietários e histórico de atos. |
| **Control-M TABNOT** | TN, TNPT (Pequeno/Médio) | [[MOC - Orion TN\|Orion TN]] | Migração de cartões de assinatura, fichas de firmas e atas. |
| **Control-M TDJP** | TDPJ (Pequeno/Médio) | Orion REG | Mapeamento dos registros civis de PJ e livros de Títulos e Documentos. |
| **Siplan PRO** | PT, TNPT (Médio/Grande) | [[MOC - Orion PRO\|Orion PRO]] | Conversão departamental de grandes volumes de protesto e caixas. |
| **Siplan RC** | RC (Registro Civil) | Sem equivalente Orion direto | Suporte à migração pontual sob demanda de bases de registro civil. |
| **SiplanTN** | TN, TNPT (Geral) | [[MOC - Orion TN\|Orion TN]] | Substituição total do balcão de firmas, caixas e escrituração. |
| **WebRI** | RI (Médio/Grande) | Orion REG / WEB RI | Transição das rotinas web e matrículas imobiliárias eletrônicas. |
| **WebTD** | TDPJ (Médio/Grande) | Orion REG | Migração das notificações eletrônicas e registros de sociedades. |

---

## 🔍 2. Análise Detalhada dos Sistemas Legados

### 2.1. Control-M Distribuidor
*   **Tipo de Serventia:** Distribuidor (Serviço de Distribuição de Títulos de Protesto).
*   **Propósito:** Distribuição equitativa e balanceada de títulos de crédito apresentados para protesto em comarcas com múltiplos tabelionatos de protesto, atendendo à Lei Federal nº 9.492/97 e normativas locais (ex: Item 12, Cap. XV das NSCGJ-SP).
*   **Funcionalidades e Fluxos:**
    *   *Critérios de Distribuição:* Distribuição quantitativa e qualitativa parametrizada para bancos (remessas), particulares e controle com base no histórico de "bons pagadores" dos devedores.
    *   *Digitação e Entrada:* Autocompletar para campos operacionais (espécie do título, tipo de protesto, endosso e aceite) e busca automática de CEP.
    *   *Recepção de Remessas:* Carga em lote de arquivos de remessa eletrônica da CRA (Central de Remessa de Arquivos) com validação e identificação de erros de layout.
    *   *Tratamento de Irregularidades:* Controle e bloqueio de títulos duplicados, rotinas automáticas de reingresso e compensação financeira de títulos devolvidos.
    *   *IEPTB:* Conexões diretas com WebProtesto, WebFormulario e E-Formulario.
    *   *Certidões:* Controle integrado de pedidos e emissões de certidões distribuídas.

### 2.2. Control-M GED (CM GED)
*   **Tipo de Serventia:** Transversal (Atende a todas as naturezas: TN, PT, RI, RC, TDPJ).
*   **Propósito:** Digitalização, indexação, armazenamento seguro e recuperação de imagens e documentos do acervo cartorário, em conformidade com a Lei Federal nº 12.682/12.
*   **Funcionalidades e Fluxos:**
    *   *Captura e Classificação:* Digitalização de livros físicos, documentos de balcão e importação de arquivos digitais (PDF, DOC, e-mails, imagens).
    *   *Busca Multicritério:* Indexação por chaves de pesquisa personalizáveis para localização instantânea do documento.
    *   *Emissão de Certidões:* Visualização e impressão direta do documento no formato oficial de certidão, com inserção automática de cabeçalho, carimbos dinâmicos e cálculo de emolumentos.
    *   *Preservação Digital:* Exportação no padrão de longo prazo PDF/A e preparação de lotes para microfilmagem eletrônica.
    *   *Mapeamento de Transcrições (Livrões):* Visualização de imagens de livros de transcrição antigos integrados com o controle de averbações.

### 2.3. Control-M PROT (CM PROT)
*   **Tipo de Serventia:** Tabelionato de Protesto de Títulos (PT e serventias mistas TNPT), recomendado para serventias de **pequeno e médio porte**.
*   **Propósito:** Automação e simplificação das rotinas internas de recepção, intimação e lavratura de protestos.
*   **Funcionalidades e Fluxos:**
    *   *Integrações:* Comunicação com centrais de protesto (CRA, SELTEC, CENPROT e IEPTB) e consultas restritivas (Serasa e Boa Vista).
    *   *Intimações e Editais:* Geração automática de intimações físicas, envio via correio/telegrama para devedores fora da comarca e geração do Edital Eletrônico para publicação no IEPTB.
    *   *Cobrança Bancária:* Emissão automática de boletos bancários para cobrança de custas de intimação e taxas de cancelamento.
    *   *Livros e Assinaturas:* Assinatura eletrônica ICP-Brasil de livros de protesto, termos de abertura/encerramento, certidões e instrumentos de protesto.
    *   *Integração GED:* Acoplamento com o Control-M GED para formar o dossiê completo de cada título (comprovantes de entrega de intimação, sustações e termos).

### 2.4. Control-M REG (CM REG)
*   **Tipo de Serventia:** Registro de Imóveis (RI).
*   **Propósito:** Gerenciar a recepção de títulos, qualificação registral, acompanhamento de exigências e escrituração de livros obrigatórios de imóveis.
*   **Funcionalidades e Fluxos:**
    *   *Qualificação e Devoluções:* Fluxo de análise de títulos com geração automatizada de Notas Devolutivas (individuais ou em lote).
    *   *Indicadores Registrais:* Alimentação e indexação permanente do Indicador Real (pesquisas por imóvel) e Indicador Pessoal (pesquisas por nome/documento de proprietários e partes).
    *   *Editor de Matrículas:* Editor interno para digitação de atos e matrículas utilizando minutas parametrizadas que importam dados do cadastro inicial do título.
    *   *Integrações externas:* Conexão com Penhora Online, Ofício Eletrônico, e-Protocolo, Central de Indisponibilidades (CNIB) e Certidão Digital.

### 2.5. Control-M TABNOT (CM TABNOT)
*   **Tipo de Serventia:** Tabelionato de Notas (TN e serventias mistas TNPT) de **pequeno e médio porte**.
*   **Propósito:** Gerenciamento dos serviços de firmas e da escrituração de atos notariais.
*   **Funcionalidades e Fluxos:**
    *   *Firebird SQL:* Armazenamento estruturado no banco de dados Firebird SQL, com suporte a servidores Linux em rede local Windows.
    *   *Módulos Internos:* Atendimento (filas), Editor (redação de atos), Firmas (reconhecimento de assinaturas e biometria), Insumos (selos e papéis) e Financeiro (depósitos prévios, repasses e comissões de escreventes).
    *   *Livro Diário:* Emissão e fechamento automatizado do Livro Diário de Receitas e Despesas e do Livro Caixa Fiscal para recolhimento de Imposto de Renda Carnê-Leão.
    *   *Centrais:* Exportação de atos em lote para a CENSEC e geração do arquivo de remessa DOI da Receita Federal.

### 2.6. Control-M TDJP (CM TDPJ)
*   **Tipo de Serventia:** Registro de Títulos e Documentos e Civil de Pessoas Jurídicas (TDPJ) de **pequeno e médio porte**.
*   **Propósito:** Protocolização, qualificação e controle do trâmite de notificações e registros societários de pessoas jurídicas.
*   **Funcionalidades e Fluxos:**
    *   *Notificações:* Acompanhamento do ciclo de diligências físicas e eletrônicas de notificações.
    *   *Carimbos Eletrônicos:* Chancela automatizada de termos nas folhas ou geração de etiquetas em impressoras Slip ou térmicas.
    *   *Pesquisa Alfabética:* Mecanismos de busca por nomes de fundadores, sócios e empresas para emissão ágil de certidões.
    *   *Integração Financeira:* Emissão de estatísticas de faturamento e exportação de dados de repasse para o Control-M Livro Diário.

### 2.7. Siplan PRO (SiplanPro)
*   **Tipo de Serventia:** Tabelionato de Protesto de Títulos (PT e serventias mistas TNPT), dimensionado para cartórios de **médio e grande porte**.
*   **Propósito:** Gerenciamento departamental de altos volumes diários de processamento de títulos de protesto.
*   **Funcionalidades e Fluxos:**
    *   *Processamento Linear:* Fluxo segmentado por departamentos (Recepção, Distribuição, Intimação, Caixa, Edital, Lavratura e Devolução) evitando redigitação de informações.
    *   *Emissão de Boletos Registrados:* Emissão e conciliação bancária automatizada para múltiplos bancos das custas de intimação e taxas de cancelamento.
    *   *Telegramas e Editais:* Módulo de envio de intimações via telegrama (Correios) para devedores fora da comarca e geração automática de editais eletrônicos para o IEPTB.
    *   *Assinatura ICP-Brasil:* Assinatura em lote de termos, livros, certidões e instrumentos de protesto.
    *   *Integração de Notas Fiscais:* Geração automática de RPS e integração com a NF-e da prefeitura local.
    *   *Módulos Estaduais:* Parametrizações normativas customizadas para as Corregedorias de Justiça do Mato Grosso do Sul (TJMS) e de Alagoas (TJAL).

### 2.8. Siplan RC (SiplanRC)
*   **Tipo de Serventia:** Registro Civil das Pessoas Naturais (RC).
*   **Propósito:** Informatizar as rotinas de registros de nascimentos, casamentos, óbitos e comunicações legais.
*   **Funcionalidades e Fluxos:**
    *   *Registros e Livros:* Lavratura de assentos de nascimento, editais de proclamas e casamentos, óbitos, Livro E, Livro de Protocolo e Livro Comercial.
    *   *Maternidades (Unidades Interligadas):* Importação via webservice de pré-cadastros de nascimento realizados em postos de atendimento dentro de maternidades, de acordo com o Provimento nº 13/2010 do CNJ.
    *   *Integração Receita Federal:* Geração de CPF e impressão automática direta nas certidões de nascimento via webservice.
    *   *Casamentos e Proclamas:* Envio de dados de casamento do Livro D para a CRC e integração com o portal E-Proclamas da ARPEN.
    *   *Comunicações Obrigatórias:* Geração de arquivos de comunicação de óbito e casamento para IBGE, SEADE, INSS, TRE, SSP e Ministério da Defesa (Exército).
    *   *Selagem e Fiscalização:* Controle do consumo de papéis de segurança e repasses de taxas de fiscalização estaduais.
    *   *Relação com a Linha Orion:* **Atenção:** Não há um sistema "Orion RC" nativo. A transição de clientes do Siplan RC para novas plataformas é avaliada individualmente pela engenharia e suporte.

### 2.9. SiplanTN
*   **Tipo de Serventia:** Tabelionato de Notas (TN e serventias mistas TNPT).
*   **Propósito:** Gestão integrada do balcão de firmas, escrituração de atos notariais e controle financeiro de caixas múltiplos.
*   **Funcionalidades e Fluxos:**
    *   *Gerenciamento de Fila:* Controle integrado de chamadas de painel de senhas por setor.
    *   *Firmas e Selos:* Cadastro de biometria e imagens de cartões de assinatura com controle e vinculação automática de selos físicos/digitais no momento do ato (autenticações e reconhecimentos).
    *   *Editor Notarial:* Elaboração de escrituras, procurações e testamentos em editor de texto integrado alimentado por minutas pré-configuradas.
    *   *Mensalistas e Faturamento:* Faturamento mensal de clientes com emissão automática de NF-e (RPS) e geração de boletos de cobrança.
    *   *Gestão Financeira:* Controle rigoroso de múltiplos caixas simultâneos, contas de depósito prévio de clientes e cálculo de comissões de escreventes sob regime de caixa ou competência.
    *   *Exportação de Dados:* Geração de arquivos para a CENSEC, DOI da Receita Federal e recolhimento de ITBI estaduais/municipais.

### 2.10. WebRI
*   **Tipo de Serventia:** Registro de Imóveis (RI) de **médio e grande porte**.
*   **Propósito:** Processamento e trânsito eletrônico de dados exigidos pelo Registro Eletrônico de Imóveis.
*   **Funcionalidades e Fluxos:**
    *   *Registro Eletrônico:* Aderência ao tráfego eletrônico de centrais de imóveis, suportando e-Protocolo, Penhora Online, Ofício Eletrônico e Central de Indisponibilidades (CENIB).
    *   *Editor Registral:* Editor estruturado de matrículas e atos que ajusta automaticamente a flexão de gênero, estado civil e termos de negócios jurídicos com base na qualificação das partes.
    *   *Gestão Operacional:* Painel gráfico de controle de produtividade dos auxiliares, monitoramento do tempo de andamento dos protocolos e prazos legais de devolução.
    *   *Estoque:* Controle de consumo e estoque de papéis de segurança físicos do cartório.

### 2.11. WebTD
*   **Tipo de Serventia:** Registro de Títulos e Documentos e Registro Civil de Pessoas Jurídicas (TDPJ) de **médio e grande porte**.
*   **Propósito:** Processamento e arquivamento em lote de documentos de RTD e RCPJ e gerenciamento de notificações eletrônicas.
*   **Funcionalidades e Fluxos:**
    *   *Notificações Eletrônicas:* Recepção automática de lotes de arquivos digitais dos apresentantes. Impressão, protocolização, assinatura digital e arquivamento das notificações, com baixa em lote das certidões de notificação via leitor de código de barras.
    *   *Módulo RCPJ:* Organização dos registros históricos de empresas com linha do tempo de alterações societárias. Possibilidade de busca por nomes de sócios mesmo em alterações contratuais arquivadas.
    *   *Integração de Canais:* Interfaces integradas para URA (Unidade de Resposta Audível), webservices e portais de atendimento para consulta e pedidos de certidões com código de validação.
