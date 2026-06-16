---
tipo: Regra
area: Produtos Siplan
tags:
  - #produtos
  - #regras-negocio
  - #cartorios
  - #padronizacao
status_atual: #ativo
---
# [Regra] Abreviações de Serventias e Mapeamento de Produtos

Esta nota estabelece a taxonomia de abreviações utilizadas para identificar as especialidades cartorárias (serventias extrajudiciais) e define o mapeamento exaustivo de quais softwares e sistemas do portfólio da Siplan (Arquitetura Orion e soluções WEB) atendem a cada tipo de cartório.

---

## 🏛️ 1. Glossário de Abreviações de Serventias Extrajudiciais

No ecossistema Siplan, na comunicação diária com equipes de implantação, e nos logs e registros de projetos, as serventias são comumente identificadas por abreviações numéricas e de especialidade. 

Abaixo está a tabela de correspondência exaustiva das siglas:

| Sigla | Nome por Extenso da Especialidade | Descrição das Atividades Operacionais da Serventia |
| :--- | :--- | :--- |
| **TN** | Tabelionato de Notas | Lavratura de escrituras públicas, procurações, testamentos, atas notariais, reconhecimento de firmas e autenticação de documentos. |
| **PT** | Protesto de Títulos | Recepção, apontamento e cobrança de títulos de crédito não pagos (duplicatas, cheques, notas promissórias, etc.), lavratura e registro de protesto de devedores. |
| **TNPT** | Tabelionato de Notas e Protesto de Títulos | Serventia de natureza mista que acumula as funções de Tabelionato de Notas (TN) e de Protesto de Títulos (PT) na mesma comarca ou distrito. |
| **RC** | Registro Civil das Pessoas Naturais | Registro de atos essenciais da vida civil de cidadãos, incluindo nascimentos, casamentos, óbitos, emancipações, interdições e averbações diversas. |
| **RI** | Registro de Imóveis | Matrícula, registro e averbação de todos os atos translativos, modificativos ou extintivos de direitos reais sobre bens imóveis de determinada circunscrição. |
| **TDPJ** | Registro de Títulos e Documentos e Civil de Pessoas Jurídicas | Registro de contratos, estatutos e atos constitutivos de sociedades civis, associações e fundações, além da guarda e registro de documentos para validade contra terceiros. |

### Exemplos Práticos de Nomenclatura
As identificações de cartórios seguem um padrão que combina o número ordinal da serventia na comarca (caso haja mais de uma), a abreviação do tipo de serventia e o município (comarca) sede:
*   **"1°TNPT Araraquara"**: Significa o *Primeiro Tabelionato de Notas e Protesto de Títulos da Comarca de Araraquara*. Este cartório executa tanto funções de notas quanto de protesto de títulos.
*   **"02 RI Franca"**: Significa o *Segundo Registro de Imóveis da Comarca de Franca*. Este cartório é especializado exclusivamente em registros imobiliários.
*   **"3°TNPT Bauru"**: Significa o *Terceiro Tabelionato de Notas e Protesto de Títulos da Comarca de Bauru*.
*   **"01 TN Campinas"**: Significa o *Primeiro Tabelionato de Notas da Comarca de Campinas*.

---

## 💻 2. Mapeamento de Produtos Siplan por Especialidade

Cada tipo de serventia extrajudicial exige regras de negócio e integrações específicas. Os produtos da Siplan são desenhados de forma modular para se ajustarem perfeitamente à especialidade operacional do cartório.

Abaixo está o mapeamento detalhado da atuação de cada produto:

| Nome do Produto Siplan | Especialidade(s) Atendida(s) | Descrição do Produto e Escopo Operacional |
| :--- | :--- | :--- |
| **Orion TN** | **TN**, **TNPT** | Plataforma web voltada para a gestão de Tabelionatos de Notas. Controla o balcão de firmas (cartões de assinatura, biometria, captura de fotos), DUT (Documento Único de Transferência) com auxílio de Inteligência Artificial, escrituração digital de escrituras públicas, procurações e testamentos com editor LibreOffice integrado, além do controle de selagem digital junto aos Tribunais de Justiça e controle financeiro de caixa. |
| **Orion PRO** | **PT**, **TNPT** | Software web especializado para a automatização das rotinas de Protesto de Títulos. Gerencia a recepção e o envio de arquivos de remessa de títulos de crédito via CRA (Central de Remessa de Arquivos) e CENPROT, emissão de intimações para os devedores, controle de editais, conciliação e repasses financeiros de custas e emolumentos aos credores, e lavratura de instrumentos de protesto. |
| **Orion REG** | **RI**, **TDPJ** | Sistema web para a gestão de Registros de Imóveis (RI) e Registro de Títulos e Documentos e Civil de Pessoas Jurídicas (TDPJ). Trata da recepção de títulos, qualificação registral estruturada, controle de fluxo de exigências e prazos legais, geração de certidões, selagem digital automática dos atos de registro, e escrituração de livros regulamentares. |
| **WEB RI** | **RI** | Solução complementar e de interface web otimizada especificamente voltada para as rotinas e interações de Registro de Imóveis, auxiliando na integração externa e digitalização de fluxos de matrículas. |

### Regra de Coexistência em Cartórios Mistos (TNPT)
Quando uma serventia é classificada como **TNPT** (Tabelionato de Notas e Protesto de Títulos), a operação exige a utilização combinada e integrada dos dois sistemas principais:
1.  **Orion TN** para a retaguarda e atendimento do balcão de notas, escrituras e assinaturas.
2.  **Orion PRO** para a recepção de arquivos de cobrança da CRA/CENPROT, editais e lavratura dos atos de protesto de títulos.
Nesses cenários, os sistemas compartilham base de dados ou possuem módulos de comunicação para conciliação de caixa e compartilhamento de cadastros básicos.
