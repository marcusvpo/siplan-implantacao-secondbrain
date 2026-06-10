---
tipo: Recurso
area: Produtos Siplan
tags:
  - #orion
  - #orion_orion_tn
  - #orion_tn_-_balcão_de_firmas
status_atual: #ativo
---
# Orion TN - Balcão de Firmas

Este recurso detalha os procedimentos, rotinas e manuais operacionais do sistema **Orion TN** para a área de **Balcão de Firmas**.

## R-1.1 - Módulo ORION TN: Firmas
**Objetivo:** Apresentar o módulo de Firmas, descrevendo seu propósito para serviços de balcão e o fluxo básico para um reconhecimento de firma.  
**Tags:** `Firmas`, `Reconhecimento`, `Cartões de Assinatura`, `Serviços de Balcão`, `Consultas`, `Cadastros`

### Intenções de Busca & Dúvidas Frequentes
- como funciona o módulo de firmas
- Para que serve o módulo de Firmas no Orion TN?
- Onde eu faço os serviços de balcão, como reconhecimento de assinatura?
- serviços de balcão
- reconhecimento de assinaturas
- módulo de reconhecimento de firma
- Como funciona, de forma geral, a rotina de reconhecimento de firmas?
- tela de firmas

### Procedimento / Explicação
O módulo de Firmas é onde são realizados todos os serviços de balcão. A natureza web do sistema permite a utilização simultânea em diversas abas abertas no navegador, sem a necessidade de fechar a aba anterior. O sistema apresenta submenus como **Consultas** e **Cadastros**.

#### 1.1.1 Rotina de Reconhecimento de Firmas

1.  Realize a busca pelo **nome de uma pessoa**.

2.  O sistema exibirá o cadastro dessa pessoa, incluindo a foto do cartão de assinatura e documentos anexados.

3.  Ao expandir o menu com o nome, o sistema mostrará todas as informações que o cliente já possui no cartão de assinatura.

4.  Para prosseguir com o serviço, clique no sinal de **"+"**.

5.  O sistema habilitará a impressão da etiqueta e permitirá finalizar o serviço.

---

---

## D-1.8 - Ativar Caixa para Firmas e Notas
**Objetivo:** Definir parâmetros gerais de utilização do caixa, incluindo permissões de abertura, fechamento e estorno.  
**Tags:** `caixa`, `parametrização`, `firma`, `nota`, `configuração`

### Intenções de Busca & Dúvidas Frequentes
- ativar rotinas de caixa
- Como permitir abertura de caixa sem troco?
- Como controlar permissão de estorno de pagamentos?
- Como ativar o caixa para firmas e notas?
- Onde configuro as parametrizações gerais do caixa?
- configurar uso do caixa
- parametrizar caixa

### Procedimento / Explicação
#### Descrição:

As parametrizações definem como o caixa será utilizado, incluindo tipos de rotinas (firmas, notas) e permissões especiais.

#### Passo a passo:

1. Acesse **Configurações > Parametrizações**.

2. Clique para **ativar o caixa para rotina de firmas**.

3. Clique para **ativar o caixa para rotina de notas**.

4. Se desejar, marque **Abertura Sem Troco** para permitir abertura do caixa sem valor inicial.

5. Configure a permissão para **Estorno de Pagamentos**:

   * Com ou sem autorização requerida

6. Salve as configurações.

* **Observação Importante:** Estas parametrizações são essenciais para definir o escopo geral de operação do módulo.

---

---

## R-2.0 - Entendendo o Fluxo de Atendimento de Firmas
**Objetivo:** Clarificar a diferença e a relação entre 'Pedido de Firmas' e 'Reconhecimento de Firmas', explicando o fluxo de trabalho padrão no balcão de atendimento do sistema.  
**Tags:** `Fluxo de Trabalho`, `Atendimento`, `Firmas`, `Balcão`, `Pedido de Firmas`, `Reconhecimento de Firmas`

### Intenções de Busca & Dúvidas Frequentes
- como funciona o balcão de firmas
- Qual a diferença entre um Pedido de Firmas e um Reconhecimento de Firma?
- fluxo de trabalho do balcão
- O que é o 'Pedido' no balcão de firmas?
- Preciso lançar 3 reconhecimentos para o mesmo cliente, eu abro 3 pedidos?
- etapas do atendimento de firmas
- o que é um pedido de firmas
- Pode me explicar como funciona o fluxo de atendimento no balcão?
- pedido vs reconhecimento
- diferença entre pedido e reconhecimento

### Procedimento / Explicação
No Orion TN, o atendimento no balcão de firmas segue um fluxo de trabalho que diferencia os conceitos de "Pedido" e "Reconhecimento". Entender essa relação é fundamental para operar o sistema corretamente.

    #### 1. O "Pedido de Firmas": A Ordem de Serviço

    Pense no `Pedido de Firmas` como a **"comanda"** ou a **"ordem de serviço"** do atendimento. É o registro que agrupa todos os serviços que um cliente irá realizar em uma única vinda ao balcão. Um único pedido pode conter múltiplos reconhecimentos e outros serviços.

    * **Criação:** Um pedido é iniciado no pré-atendimento com senha ou diretamente na tela de balcão.

    #### 2. O "Reconhecimento de Firma": O Serviço Executado

    O `Reconhecimento de Firma` é um dos **serviços** que são lançados *dentro* de um Pedido. Outros serviços, como autenticações ou cópias, também são adicionados ao mesmo Pedido.

    * **Exemplo:** Um cliente pode ter **1 Pedido** que contém **3 Reconhecimentos de Firma** e **5 Autenticações**.

    #### 3. A Tela de Trabalho: "Balcão de Firmas"

    A principal tela para este fluxo é o **Balcão de Firmas** (acessada em `Firmas > Balcão de firmas`). É nesta interface que o atendente:

    1.  Inicia um novo **Pedido**.

    2.  Busca os cartões de assinatura das partes.

    3.  Lança os serviços de **Reconhecimento de Firma** e outros.

    4.  Finaliza o **Pedido** para pagamento.

    Em resumo, o **Pedido** é o contêiner, e o **Reconhecimento** é o conteúdo.

---

---

## V-2.0 - Como Realizar a Aquisição de Produtos (Entrada no Estoque)
**Objetivo:** Registrar a entrada de novos produtos no estoque, como lotes de selos ou papéis de segurança, preenchendo os dados de série e sequência para controle do sistema.  
**Tags:** `Aquisição`, `Orion Stock`, `Selos`, `Papel de Segurança`, `Estoque`, `Entrada de Produto`, `Administração`

### Intenções de Busca & Dúvidas Frequentes
- Chegou um novo lote de selos, como registro no sistema?
- alimentar o estoque
- dar entrada em selos
- Preciso cadastrar a série e a sequência inicial/final de selos novos, qual a rotina?
- controlar estoque
- entrada de estoque
- adicionar produto no estoque
- registrar compra de selos
- Onde eu registro a aquisição de papel de segurança no sistema de estoque?
- Como faço para adicionar produtos no Orion Stock?
- cadastrar novo lote de papel de segurança
- recebimento de material
- Como eu dou entrada em um novo lote de selos que acabamos de comprar?

### Procedimento / Explicação
Esta rotina detalha o procedimento para dar entrada (Aquisição) de produtos no módulo Orion Stock, o primeiro passo para o controle de insumos.

    #### Passo a passo para a Aquisição:

    1.  Acesse o módulo **Orion Stock**.

    2.  Navegue até o menu **Administração > Aquisição**.

    3.  Preencha os campos da aquisição. Apenas os campos com asterisco (`*`) são obrigatórios. A **Data de aquisição** pode ser alterada.

    4.  Selecione a **Categoria** do produto (ex: "Selos" ou "Papel de Segurança").

    5.  Selecione o **Produto** específico (ex: "Reconhecimento por autenticidade").

    6.  Preencha o campo **Série**:

        * **Para Selos:** O formato deve seguir o padrão do selo (sigla, prefixo do cartório, série).

        * **Para Papel de Segurança:** O campo é livre, permitindo um preenchimento de acordo com a preferência da serventia.

    7.  Informe a **Sequência inicial** e a **Sequência final** do lote. O sistema calculará a **Quantidade (Qtd)** total automaticamente.

    8.  Informe o **Valor Unitário** do produto, se aplicável.

    9.  Para registrar a entrada de mais de um tipo de produto na mesma operação, clique no botão **"+"** (inserir). Utilize o botão **"-"** para remover uma linha.

    10. Clique em **Concluir** para registrar a entrada dos produtos no estoque.

---

---

## D-2.4_1 - Cadastrar Categoria de Produto
**Objetivo:** Criar categorias de produto para papel de segurança e selos utilizados no cartório.  
**Tags:** `categoria`, `produto`, `cadastro`, `configuração`

### Intenções de Busca & Dúvidas Frequentes
- Quantas categorias posso criar?
- criar categoria de produto
- adicionar tipo de categoria
- Onde configuro as categorias de produto?
- Como cadastro uma nova categoria?
- configurar categorias

### Procedimento / Explicação
#### Descrição:

As categorias normalmente são utilizadas para papel de segurança e selos, sendo as duas categorias padrão. Novas categorias podem ser criadas conforme necessidade.

#### Passo a passo:

1. Acesse **Negócios > Categoria**.

2. O sistema exibirá as categorias já cadastradas (normalmente papel de segurança e selos).

3. Para adicionar uma nova categoria, clique em **Adicionar**.

4. Preencha as **informações necessárias** da categoria.

5. Clique em **Salvar**.

* **Observação Importante:** Normalmente apenas papel de segurança e selos são necessários, mas você pode criar outras categorias conforme demanda.

---

---

## D-2.7 - Cadastrar Produto
**Objetivo:** Registrar produtos utilizados no cartório, como cartões, selos, papel de segurança e certidões, com configuração de distribuição e estoque mínimo.  
**Tags:** `produto`, `cadastro`, `estoque`, `configuração`

### Intenções de Busca & Dúvidas Frequentes
- adicionar novo produto
- Como configurar distribuição de um produto?
- Como definir estoque mínimo?
- Como cadastro um novo produto?
- criar tipo de produto
- Onde configuro alerta de estoque?
- registrar item em estoque

### Procedimento / Explicação
#### Descrição:

O cadastro de produto é essencial para controle de inventário. Cada produto pode ter distribuição personalizada e alerta de estoque mínimo.

#### Passo a passo:

1. Acesse **Negócios > Produto**.

2. O sistema exibirá uma **lista de produtos já cadastrados** com:

   * Quantidade disponível

   * Quantidade distribuída

   * Estoque mínimo

3. Clique em **Adicionar** para cadastrar novo produto.

4. Preencha os **campos do produto**:

   * **Tipo:** Descrição do produto (exemplo: "Selo de Autenticação")

   * **Unidade:** Se é unitário

   * **Estoque Mínimo:** Quantidade que acionará alerta (exemplo: 400)

   * **Distribuição:** Como será distribuído:

     - **Para Todos:** Todos recebem a mesma quantidade

     - **Por Escrevente:** Quantidade separada por escrevente

     - **Por Máquina:** Quantidade separada por máquina

     - **Por Grupo:** Quantidade separada por grupo de usuários/máquinas

5. Configure **campos adicionais** conforme necessário:

   * **Quantidade de Atos:** 1 ou 2 (para selos com ou sem valor)

   * **Códigos de Barras:** Se aplicável

   * **Prefixo:** Série fixa do produto (não necessita preenchimento em aquisições)

6. Clique em **Salvar**.

* **Observação Importante:** O prefixo fixo reduz erros operacionais e impacto em geração de selos digitais. O estoque mínimo dispara alerta quando a quantidade é atingida.

---

---

## V-3.0 - Como Consultar o Estoque de Produtos
**Objetivo:** Verificar o status detalhado de todos os itens do estoque (selos, papéis), utilizando as consultas resumida e detalhada para um controle preciso e para realizar ações como cancelamento e inutilização.  
**Tags:** `Consulta de Estoque`, `Orion Stock`, `Status de Selos`, `Produtos Distribuídos`, `Logs`, `Estorno`, `Relatório`

### Intenções de Busca & Dúvidas Frequentes
- auditoria de estoque de selos
- relatório de estoque
- saber quantos selos ainda tenho
- Como eu faço para cancelar um selo que foi consumido por engano no sistema?
- procurar um selo específico
- Como eu consulto o status de um selo específico para saber se ele já foi usado?
- verificar status dos selos
- Onde eu vejo quantos selos de reconhecimento por autenticidade ainda temos em estoque?
- ver produtos em estoque
- Preciso de um relatório de todo o meu estoque de papel de segurança, onde eu tiro?
- cancelar um selo que foi usado errado
- inutilizar selo no estoque
- Onde eu consigo ver o histórico de um item do estoque, para saber quem usou?
- consultar selos distribuídos

### Procedimento / Explicação
O Orion Stock oferece ferramentas de consulta para rastrear cada item do estoque, seja de forma geral ou detalhada.

    #### Passo a passo para a consulta completa:

    1.  No módulo **Orion Stock**, acesse o menu **Administração > Consultas > estoque**.

    2.  Utilize os filtros disponíveis, como **Categoria**, **Produto**, **Data**, entre outros, para refinar a pesquisa.

    3.  Selecione o **Tipo de Consulta**:

        * **Resumida:** Mostra os intervalos de numeração e seus status de forma consolidada (ex: "Selo 1 a 15, consumido"; "Selo 51 a 100, em estoque").

        * **Detalhada:** Lista cada item (selo ou papel) individualmente com seu status e oferece mais opções de gerenciamento.

    4.  Clique em **Filtrar**.

    5.  Na consulta **Detalhada**, a linha de cada item apresentará opções adicionais, como:

        * **Cancelamento**

        * **Inutilização**

        * **Andamentos (Logs)**

    6.  É possível também estornar um produto específico que já foi utilizado, tornando-o disponível para reutilização.

        * **Observação:** A reutilização de um selo deve ser iniciada primeiro na tela de serviço onde ele foi originalmente utilizado, para depois ser estornado aqui no estoque.

---

---

## D-3.11 - Consultar Reconhecimento de Firmas
**Objetivo:** Fazer consulta rápida de serviços de reconhecimento realizados no dia ou período, visualizando itens utilizados e valores.  
**Tags:** `consulta`, `reconhecimento`, `firma`, `relatório`

### Intenções de Busca & Dúvidas Frequentes
- consultar reconhecimentos
- Como ver itens utilizados nos serviços?
- conferir serviços do balcão
- Onde vejo todos os reconhecimentos feitos?
- ver serviços de firma
- Como consultar serviços do dia?

### Procedimento / Explicação
#### Descrição:

Consulta rápida de serviços de reconhecimento com filtro por período, exibindo detalhes de itens e valores.

#### Passo a passo:

1. Acesse **Firmas > Consultas > Reconhecimento de Firmas**.

2. O sistema exibirá **serviços lançados** no período.

3. Para **expandir detalhe**, clique em um serviço.

4. Visualize:

   * **Itens utilizados** no serviço

   * **Valores** de cada item

   * **Quantidade** consumida

5. Clique em **Andamentos** para ver log (quem fez, quando).

6. Clique em **Abrir Protocolo** para editar.

#### Ações Disponíveis:

- **Reabrir:** Desfazer e lançar novamente

- **Inutilizar:** Marcar como inutilizado

- **Cancelar:** Remover o serviço completamente

* **Observação Importante:** Consulta simples para verificação rápida. Para análises detalhadas, use relatórios.

---

---

## D-3.13 - Fazer Reconhecimento de Firma
**Objetivo:** Realizar serviço de reconhecimento de firma, lançando serviços, consumindo selos e gerando termos automaticamente.  
**Tags:** `reconhecimento`, `firma`, `serviço`, `operação`

### Intenções de Busca & Dúvidas Frequentes
- Como o sistema consome selos automaticamente?
- Como fazer um reconhecimento de firma?
- fazer serviço de reconhecimento
- processar firma
- Como selecionar o tipo de serviço?
- Como gerar termo durante reconhecimento?
- executar autenticação

### Procedimento / Explicação
#### Descrição:

Realização de serviço de reconhecimento com busca de cliente, seleção de serviço, consumo automático de selos e geração de termo.

#### Passo a passo:

1. Acesse **Firmas > Reconhecimento de Firmas** (menu principal).

2. Configure opções de **busca e filtro**:

   * **Por Pedido:** Se cliente já tem pedido aberto

   * **Por Senha SGA:** Se usando sistema de senhas

   * **Por Cartão/Sinal:** Buscar cliente cadastrado

3. **Realize busca simples** (ex: por nome "Henrique").

4. O sistema traz **todos os clientes** com esse nome.

5. Visualize **informações principais** do cadastro.

6. Clique em **nome** para ver resumo de documentos e foto.

7. Para **editar cartão**, clique **Cadastro Completo**.

8. Para **fazer serviço**, clique **ícone de +** para seleção de serviço.

9. **Adicione múltiplas pessoas** para impressão conjunta.

10. Clique em **Impressão** para processar.

11. Selecione **tipo de serviço** (ex: Autenticidade).

12. Clique em **Confirmar**.

#### Resultado Automático:

- Sistema realiza o serviço

- **Selos consumidos automaticamente** (série e sequência preenchidas)

- **Valor lançado automaticamente**

- Se configurado, **abre termo para preenchimento**

#### Preenchimento de Termo com IA:

1. Sistema abre **tela de termo** automaticamente.

2. Clique em **Preencher com IA**.

3. **Digitalize ou importe** DUT (ex: documento de veículo).

4. Sistema **lê automaticamente** informações.

5. **Revise dados** preenchidos.

6. Clique em **Salvar e Imprimir Termo**.

#### Reutilizar/Cancelar Serviço:

- **Reutilizar:** Volta o selo para estoque

- **Cancelar:** Remove serviço e registra como inutilizado no estoque

* **Observação Importante:** Consumo automático de selos requer configuração prévia. Termo abre automaticamente se configurado. IA detecta qualidade de imagem e preenche automaticamente.

---

---

## D-3.4_1 - Estornar Distribuição de Produto
**Objetivo:** Desfazer distribuições de produtos, retornando-os ao estoque para redistribuição.  
**Tags:** `estorno`, `distribuição`, `devolução`, `operação`

### Intenções de Busca & Dúvidas Frequentes
- cancelar distribuição
- Como desfazer entrega de selos?
- Como voltar um produto para estoque?
- Como cancelar uma distribuição?
- reverter entrega
- devolver produto distribuído

### Procedimento / Explicação
#### Descrição:

O estorno de distribuição permite reverter alocações realizadas por erro ou necessidade, retornando o produto ao estoque disponível.

#### Passo a passo:

1. Acesse **Administração > Distribuição**.

2. Na **tela de consulta**, localize a distribuição a estornar.

3. Selecione a **distribuição desejada**.

4. Clique em **Estornar**.

5. A distribuição é removida da tela.

6. O produto retorna imediatamente **disponível para distribuição**.

7. Para confirmar, faça nova consulta - o produto reaparecerá como disponível.

* **Observação Importante:** Estorno é imediato e reverte completamente a distribuição, sem deixar rastro de que foi distribuída.

---

---

## D-3.4_2 - Cadastrar Cartão de Assinatura
**Objetivo:** Registrar cartão de assinatura de cliente com foto, biometria, documentos e anexos, com opção de IA.  
**Tags:** `cartão`, `assinatura`, `cadastro`, `cliente`

### Intenções de Busca & Dúvidas Frequentes
- criar ficha de cartão
- adicionar cartão de assinatura
- cadastrar cliente
- Como usar IA para preencher o cartão?
- Como cadastro um cartão de assinatura?
- Onde anexo fotos e documentos do cartão?
- Como capturar biometria no cartão?

### Procedimento / Explicação
#### Descrição:

Cartão de assinatura é a ficha de cadastro do cliente com identificação, foto, documentos e biometria. Suporta preenchimento por IA.

#### Passo a passo:

1. Acesse **Firmas > Cadastros > Cartão de Assinatura**.

2. Clique em **Buscar** para visualizar cartões já cadastrados.

3. Você pode:

   * **Visualizar:** Ver anexos (cartão, foto, CNH, etc.)

   * **Capturar Biometria:** Scanner de impressão digital

   * **Webcam:** Capturar fotografia no ato

   * **Visualizar Logs:** Histórico desde criação

   * **Editar:** Modificar informações

   * **Bloquear/Ativar:** Restringir acesso (fraude, documento vencido)

4. Para **cadastrar novo**, clique em **Adicionar**.

5. Preencha os **campos do formulário**:

   * Configure campos como **obrigatórios** conforme necessário

   * Nome é obrigatório no exemplo padrão

6. Clique em **Impressão** para gerar relatório.

#### Preenchimento com IA:

1. Na tela de cadastro, clique em **Preencher com IA**.

2. Escolha **Digitalizar** (scanner) ou **Importar** (documento digital).

3. O sistema lê o documento (CNH, RG, etc.) e preenche automaticamente.

4. Revise as informações preenchidas.

5. Clique em **Conclusão** (o documento é reutilizado como anexo automaticamente).

#### Consumo Automático:

- Se configurado, o sistema **consome automaticamente papel de segurança** e **selo** do estoque ao finalizar o cadastro.

* **Observação Importante:** Campos obrigatórios são configuráveis. Preenchimento com IA depende da qualidade da imagem do documento. Bloqueios são configuráveis por permissão.

---

---

## D-3.6_1 - Cadastrar Termo de Comparecimento
**Objetivo:** Criar e configurar modelos de termo de comparecimento customizados para diferentes tipos de serviço.  
**Tags:** `termo`, `comparecimento`, `modelo`, `configuração`

### Intenções de Busca & Dúvidas Frequentes
- Onde configuro os campos do termo?
- configurar documento de comparecimento
- Como arrastar variáveis no modelo?
- Como personalizar um termo?
- adicionar termo de comparecimento
- criar modelo de termo
- Como cadastro um termo de comparecimento?

### Procedimento / Explicação
#### Descrição:

Termo de comparecimento é documento customizável com campos variáveis configuráveis por arrastar e soltar.

#### Passo a passo:

1. Acesse **Firmas > Cadastros > Termo de Comparecimento**.

2. Visualize termos já cadastrados (padrão: "Comprador e Vendedor").

3. Clique em **Visualizar** para ver configuração de um termo.

4. O sistema exibe:

   * Campos disponíveis para preenchimento

   * Variáveis que podem ser incluídas

5. Para **criar novo termo**, clique em **Adicionar**.

6. **Configure o modelo**:

   * **Arraste variáveis** para dentro do modelo

   * **Ajuste tamanho** de cada informação

   * **Ordene campos** conforme desejado

   * **Adicione títulos** para cada campo

7. Clique em **Salvar**.

* **Observação Importante:** Sistema é flexível. Você pode criar múltiplos termos (comprador/vendedor, proprietário/ocupante, etc.). Configuração é feita por drag-and-drop.

---

---

## D-3.7 - Fazer Digitalização em Lote por Sequência de Cartão
**Objetivo:** Digitalizar múltiplos cartões de assinatura em sequência numérica, vinculando automaticamente aos cadastros.  
**Tags:** `digitalização`, `lote`, `sequência`, `cartão`

### Intenções de Busca & Dúvidas Frequentes
- Como digitalizar cartões em sequência?
- processar batch de cartões
- Como digitalizar vários cartões de uma vez?
- escanear cartões em lote
- Preciso ter cartões em ordem para digitalizar?
- digitalizar série de cartões

### Procedimento / Explicação
#### Descrição:

Digitalização em lote por sequência permite escanear múltiplos cartões já criados em ordem numérica, vinculando automaticamente.

#### Passo a passo:

1. Acesse **Firmas > Cadastros > Digitalização em Lote**.

2. Clique em **Processar** para iniciar.

3. Selecione **Tipo 1: Digitalização por Sequência de Cartão**.

4. Preencha:

   * **Sequência Inicial:** Primeiro número (ex: 1)

   * **Sequência Final:** Último número (ex: 10)

5. Configure **Quantidade de Páginas por Cartão** (ex: 1 cartão, 2 páginas se incluir CNH).

6. **Coloque os cartões no scanner** em ordem sequencial (1, 2, 3... 10).

7. Clique em **Digitalizar**.

8. O sistema vincula automaticamente a cada ficha cadastrada.

#### Aviso Importante:

- Sistema exibe mensagem se já existe anexo (vai sobrepor).

- **Cartões devem estar em sequência perfeita.**

* **Observação Importante:** Este método requer que os cartões estejam em ordem numérica consecutiva. Ideal para cartões acabados de cadastrar.

---

---

## D-3.9 - Fazer Digitalização em Lote de DUT para CEPHAS
**Objetivo:** Digitalizar documentos de veículos (DUT) em lote com leitura de QR Code para comunicação automática ao CEPHAS.  
**Tags:** `digitalização`, `dut`, `cephas`, `veículo`

### Intenções de Busca & Dúvidas Frequentes
- processar dut em lote
- escanear dut
- digitalizar documentos de veículo
- Como digitalizar DUT para CEPHAS?
- Como o sistema lê QR Code do DUT?
- Como vincular DUT ao termo de forma automática?

### Procedimento / Explicação
#### Descrição:

Digitalização de DUT (Documento Único de Transferência) com leitura automática de QR Code e vinculação ao termo, otimizando comunicação CEPHAS.

#### Passo a passo:

1. Acesse **Firmas > Cadastros > Digitalização em Lote > DUT**.

2. Você tem duas opções:

   * **Digitalizar em Sequência:** Coloque DUTs em sequência no scanner

   * **Importar:** Use DUTs já em arquivo digital

3. Coloque **DUTs no scanner** (contendo selo com QR Code).

4. Clique em **Digitalizar** ou **Importar**.

5. O sistema:

   * **Lê QR Code** do selo colado no DUT via IA/OCR

   * **Lê sequência do selo**

   * **Vincula automaticamente** ao termo onde foi consumido

6. Clique em **Processar**.

#### Funcionamento Automático:

- O sistema **associa cada DUT** ao termo correto baseado no **número do selo** consumido.

- **Otimiza comunicação CEPHAS** em lote (múltiplos DUTs de uma vez).

* **Observação Importante:** Requer selos com QR Code colados. Integração com IA e OCR para leitura. Otimiza significativamente tempo de comunicação.

---

---

## D-4.0 - Cancelamento e Inutilização de Selos com Selo Digital Gerado (Firmas)
**Objetivo:** Orientar sobre o procedimento para cancelar (inutilizar) selos de firmas que já possuem selo digital gerado ou que pertencem a datas anteriores, diferenciando do processo de reutilização.  
**Tags:** `Firmas`, `Selo`, `Cancelamento`, `Inutilização`, `Selo Digital`, `Pedido`, `Estorno`, `Reutilização`

### Intenções de Busca & Dúvidas Frequentes
- cancelar selo de dia anterior
- É possível reutilizar um selo de um pedido feito em dias anteriores?
- cancelar selo consumido
- Qual a diferença entre reutilizar e inutilizar um selo no módulo de Firmas?
- Como faço para inutilizar um selo dentro de um pedido que já está pago?
- reabrir pedido pago para cancelar selo
- Como cancelo um selo de firma do dia anterior que já tem selo digital?
- inutilizar selo com selo digital
- estornar selo de reconhecimento antigo

### Procedimento / Explicação
#### Descrição:

Esta rotina explica como proceder quando é necessário alterar ou cancelar um selo no módulo de Firmas. Existe uma regra importante quanto à data do pedido:

* **Pedidos do dia atual:** É possível **reutilizar** o selo (estornar para o estoque).

* **Pedidos de dias anteriores (ou com Selo Digital gerado):** Não é possível reutilizar. Neste caso, só é possível **inutilizar** o selo.

#### Passo a passo:

1.  Acesse o menu **Firmas** e clique no submenu **Reconhecimento de firmas**.

2.  No campo **Pedido** (canto superior esquerdo), busque pelo número do pedido onde o selo foi consumido.

3.  Verifique o status do pedido:

    * **Se estiver "Pago":** É necessário primeiro estornar o pagamento e depois clicar no botão **Reabrir pedido**.

    * **Se não estiver pago:** Clique apenas no botão **Reabrir pedido**.

4.  Com o pedido aberto, localize o card de "Serviços realizados".

5.  Clique no ícone de **Detalhes** (representado por quatro tracinhos) ao lado do serviço. O sistema abrirá uma tela listando todos os produtos (selos) utilizados.

6.  Na lista de produtos, marque a **caixinha** (checkbox) correspondente ao selo que deseja alterar.

7.  Escolha a ação adequada:

    * Clique no ícone **X** para **Inutilizar** o selo (processo definitivo, usado para selos com selo digital gerado ou datas passadas).

    * Clique no ícone **Flexinha** (seta) para **Reutilizar** o selo (disponível apenas para pedidos do dia atual sem selo digital enviado).

8.  Após clicar na ação desejada, o selo sairá do pedido e o processo será concluído.

---

---

## V-8.0 - Edição de Cartão de Assinatura, Consumo de Papel de Segurança e Selo Digital
**Objetivo:** Gerenciar um cartão de assinatura existente, permitindo a edição de dados, o bloqueio da ficha e o controle de consumo (uso, reutilização, inutilização) do papel de segurança e selo digital associados.  
**Tags:** `Firmas`, `Cartão de Assinatura`, `Edição`, `Busca`, `Papel de Segurança`, `Selo Digital`, `Consumo`, `Relatório`, `Impressão`, `Bloqueio`

### Intenções de Busca & Dúvidas Frequentes
- procurar cartão pelo nome
- Fiz um cartão, mas o papel de segurança estragou. Como eu inutilizo ele e consumo um novo?
- consultar cartão de assinatura
- cancelar selo de uma ficha de firma
- bloquear uma assinatura
- Como eu faço para editar o nome de uma pessoa que está errado no cartão de assinatura?
- Como eu consulto um cartão de assinatura pelo CPF da pessoa?
- reutilizar um papel de segurança de um cartão
- editar ficha de firma
- gerenciar selo digital
- É possível reutilizar um selo digital que foi gerado para um cartão de assinatura por engano?
- Onde eu vejo o histórico de alterações de um cartão de firma?
- gerenciar papel de segurança
- Preciso bloquear a ficha de uma pessoa por ordem judicial. Onde eu faço isso?
- alterar cartão de assinatura

### Procedimento / Explicação
#### Descrição:

Este procedimento detalha como editar cartões de assinatura existentes, realizar buscas avançadas, gerenciar o consumo de papel de segurança e selos digitais, e utilizar as funcionalidades de visualização e impressão.

#### Passo a passo:

1.  Acesse o menu **Firmas > Cadastros > Cartão de Assinatura**.

2.  Na tela de Cartões de Assinatura, utilize os campos de busca para localizar o cartão desejado.

    *   O botão **Filtrar** é habilitado após preencher os campos obrigatórios (com *).

    *   Ao digitar no campo **Nome**, o asterisco dos outros campos some, permitindo a busca apenas por nome.

    *   Para buscar por **CPF**, selecione o tipo **CPF** no campo **Documento** e preencha o campo **Número**.

    *   Pressione **Enter** para realizar a busca. O sistema também sugere resultados enquanto você digita.

    *   Utilize as opções de **busca fonética** ou **"contém"** para refinar a pesquisa.

3.  Os resultados da busca podem ser ordenados clicando nas setas ao lado dos nomes das colunas.

4.  Para gerar um relatório dos resultados da busca, clique em **Imprimir**. Selecione o modelo desejado para abrir o PDF.

5.  Na lista de resultados, você pode:

    *   Visualizar a imagem do cartão de assinatura diretamente (ícone verde indica imagem anexada).

    *   Acessar os **Anexos** para ver todas as imagens vinculadas ao cartão.

    *   Cadastrar a **Biometria** (atalho com ícone de digital).

    *   Verificar se há uma **Foto** capturada (ícone de foto).

    *   Visualizar os **Andamentos** do cartão, incluindo alterações, usuário, data e hora.

6.  Para editar o cartão, utilize as opções:

    *   **Visualizar a Ficha** (ícone de olho): Abre o cartão apenas para visualização.

    *   **Canetinha** (ícone de lápis/caneta): Abre o cartão com os campos editáveis.

    *   **Bloquear** (ícone de cadeado): Permite bloquear a ficha com um motivo, que será exibido no reconhecimento.

7.  Para alterar campos que já tiveram reconhecimento (ex: nome, documentos), clique no botão **Editar** ao lado do campo. O sistema solicitará login e senha de supervisor.

8.  Para controlar o **Papel de Segurança**:

    *   Clique em **Consumir**.

    *   Selecione o papel de segurança desejado (pode ser fora de ordem) e clique em **Concluir**. O status mudará para "Reservado" até que o cartão seja salvo.

    *   Ao **Concluir** a edição do cartão, o status do papel de segurança muda para "Consumido".

    *   Para retornar o papel ao estoque, clique na seta de **Reutilizar**.

    *   Para inutilizar o papel, clique no ícone **X** (xizinho).

9.  Para controlar o **Selo Digital**:

    *   O selo pode ser gerado automaticamente (configurável no sistema).

    *   Se não for automático, clique em **Gerar** para gerar o selo manualmente.

    *   As opções de **Reutilizar**, **Cancelar** e **Visualizar QR Code** (para o TJ) estão disponíveis.

    *   O envio do selo digital para cartões de assinatura é facultativo.

10. Para imprimir a ficha editada, clique no botão **Imprimir**. Selecione o modelo e a impressora.

    *   **Nota**: O botão **Imprimir** só aparece na edição da ficha, não durante o cadastro inicial de uma nova ficha.

11. Para efetivar as alterações, clique em **Concluir**.

12. As opções de cadastro e edição de cartão de assinatura também estão disponíveis na tela de **Reconhecimento de Firmas** (**Firmas > Reconhecimento de Firmas**).

    *   Use **Novo Cartão** para cadastrar um novo cartão se a busca não encontrar resultados.

    *   Use **Cadastro Completo** para editar um cartão já existente.

---

# SEÇÃO PRINCIPAL 3: MANUAIS DO PRODUTO - Orion TN
*DESCRIÇÃO DA SEÇÃO: Esta seção contém o conteúdo extraído diretamente dos manuais oficiais do produto Orion TN, disponíveis na intranet da Siplan. As informações aqui são detalhadas e servem como referência técnica completa das funcionalidades do sistema.*

---

## M-8.0 - Consulta e Gerenciamento de Cartão de Assinatura
**Objetivo:** Acessar a tela principal para filtrar e gerenciar cartões de assinatura, permitindo a busca por diversos critérios, visualização de histórico, edição e bloqueio.  
**Tags:** `Firmas`, `Cartão de Assinatura`, `Consulta`, `Filtro`, `Histórico`, `Andamentos`, `Visualizar`, `Editar`, `Bloquear`, `Adicionar`

### Intenções de Busca & Dúvidas Frequentes
- buscar cartão de assinatura
- Onde eu procuro por um cartão de assinatura já existente no sistema?
- Preciso ver o histórico de atos de um cartão de assinatura específico, como faço?
- Como eu busco uma ficha de firma pelo número do RG da pessoa?
- procurar ficha de firma
- gerenciar fichas de firma
- consultar assinaturas
- pesquisar cartão de assinatura
- Qual a tela principal para gerenciar todos os cartões de assinatura?

### Procedimento / Explicação
#### Descrição:

A tela de Cartão de Assinatura permite consultar e gerenciar os cartões cadastrados no sistema, oferecendo diversas opções de filtro para localizar registros específicos e ações para manipular os cartões.

#### Passo a passo:

1.  Para acessar a tela de **Cartão de assinatura**, clique no menu **Firmas > Cadastro > Cartão de assinatura**.

2.  Na página **Cartão de assinatura**, os resultados poderão ser filtrados de acordo com os campos de busca disponíveis:

    1.  **Pesquisar por nome**: Para realizar uma busca de um nome específico. O campo possui auto sugestão.

    2.  **Documento**: Selecione o tipo de documento (CPF ou RG). Após a seleção, o campo **Número** será desbloqueado.

    3.  **Número**: Digite o número do documento (CPF ou RG).

    4.  **Nº Cartão**: Digite o número do cartão para uma busca direta.

    5.  **NFS**: Digite o número do papel de segurança para buscar um cartão de assinatura.

    6.  **Pessoa jurídica**: Informe a Razão Social de uma pessoa jurídica cadastrada para localizar os cartões que a representam. O campo também possui auto sugestão.

    7.  **Rótulo**: Para realizar uma busca utilizando rótulos. Para buscar mais de um rótulo, digite o nome do rótulo e pressione **Enter**.

    8.  **Data digitação**: Para realizar uma busca através da data em que o cartão de assinatura foi cadastrado.

    9.  **Status**: Para realizar a busca por status **Ativo** ou **Bloqueado**.

    10. **Observações**: Para realizar a busca pelas observações descritas no cartão.

3.  Após preencher os campos de busca, selecione uma das ações:

    1.  **Imprimir**: Para realizar a impressão da listagem com o resultado do filtro aplicado.

    2.  **Limpar**: Para limpar todo o conteúdo preenchido nos campos de busca.

    3.  **Filtrar**: Para aplicar o filtro, clique no botão **Filtrar**.

4.  A partir da listagem de cartão de assinatura, é possível executar as seguintes ações:

    1.  **Histórico de atos**: Exibir os atos realizados no balcão de firmas utilizando este cartão de assinatura.

    2.  **Andamentos**: Exibir os andamentos executados no cartão de assinaturas (Ex: edição e alteração do cartão).

    3.  **Visualizar**: Visualizar o cartão de assinatura.

    4.  **Editar**: Alterar os dados do cartão de assinatura.

    5.  **Bloquear**: Bloquear o cartão de assinatura para impedir a realização de novos atos.

    6.  **Voltar**: Voltar para a tela inicial do sistema.

    7.  **Adicionar**: Adicionar um novo cartão de assinatura.

---

---

## M-9.0 - Cadastro Básico de Cartão de Assinatura
**Objetivo:** Realizar o cadastro inicial de um novo cartão de assinatura, focando no preenchimento dos dados pessoais, de contato e endereço da pessoa.  
**Tags:** `Firmas`, `Cadastro`, `Cartão de Assinatura`, `Dados Pessoais`, `Contato`, `Endereço`, `Cônjuge`, `Provimento 88`

### Intenções de Busca & Dúvidas Frequentes
- abrir firma (dados básicos)
- Onde eu preencho os dados pessoais, como nome e CPF, para abrir uma firma?
- cadastrar uma pessoa
- criar ficha de assinatura
- Para que serve a opção 'Novo Cartão' na tela de Reconhecimento de Firmas?
- novo cartão de firma (dados iniciais)
- cadastrar assinatura (informações pessoais)
- Como eu começo o cadastro de um novo cartão de assinatura?

### Procedimento / Explicação
#### Descrição:

Esta é a rotina principal para iniciar o cadastro de um novo cartão de assinatura, focando no preenchimento dos dados essenciais da pessoa. O acesso pode ser feito pelo menu principal ou por um atalho na tela de atendimento para maior agilidade.

#### Passo a passo:

1.  Acesse a tela de cadastro. Existem duas formas:

    * **Menu Principal**: Navegue até **Firmas > Cadastros > Cartão de Assinatura** e clique no botão **Adicionar**.

    * **Atalho no Atendimento**: Na tela de **Reconhecimento de Firmas**, clique na opção **Novo Cartão** para abrir a mesma tela de cadastro.

2.  Na seção **Dados pessoais**, preencha os campos obrigatórios como **Nome** e **CPF**.

    * Utilize a lupa ao lado dos campos para buscar e reaproveitar dados já existentes no sistema.

    * Marque se a pessoa é **politicamente exposta** ou **funcionário público** para atender ao Provimento 88.

    * No campo **Rótulos**, digite o nome de um rótulo e tecle **Enter** para adicionar quantos forem necessários.

3.  Na seção **Contato**, clique no botão **Adicionar** (ícone de **+**) para incluir múltiplos e-mails e telefones. Marque um como **Principal**.

4.  Na seção **Endereço**, clique em **Adicionar** (ícone de **+**) para incluir os endereços da pessoa.

5.  Se o **Estado Civil** for "Casado", a seção **Cônjuge** será exibida para preenchimento opcional dos dados do cônjuge.

6.  Após preencher os dados básicos, prossiga para as rotinas de anexos, vínculo com empresas e consumo de selos para completar o cadastro.

---

---

## M-9.1 - Anexar Documentos, Biometria e Foto em um Cartão de Assinatura
**Objetivo:** Capturar e anexar as informações de identificação a um cartão de assinatura, incluindo a foto da pessoa, o registro da biometria e a digitalização de documentos.  
**Tags:** `Firmas`, `Cartão de Assinatura`, `Anexos`, `Biometria`, `Fotografia`, `Digitalização`, `Documentos`

### Intenções de Busca & Dúvidas Frequentes
- escanear documento para ficha
- capturar foto para cartão
- Como eu anexo a CNH digitalizada em um cartão de assinatura?
- Onde eu capturo a foto e a biometria de uma pessoa ao abrir a firma dela?
- Preciso digitalizar o cartão de assinatura físico e anexar ao cadastro, como faço?
- registrar biometria na ficha
- digitalizar documentos para ficha de assinatura
- anexar CNH no cartão de assinatura

### Procedimento / Explicação
#### Descrição:

Esta rotina detalha como adicionar os elementos de verificação visual e biométrica a um cartão de assinatura, um passo crucial para a segurança do cadastro.

#### Passo a passo:

1.  Durante o cadastro ou edição de um **Cartão de Assinatura**, localize os ícones de captura e a seção de anexos.

2.  Para adicionar a **Fotografia** da pessoa, clique no ícone de câmera e capture a imagem via webcam ou importe um arquivo.

3.  Para registrar a **Biometria**, clique no ícone de digital e utilize um leitor biométrico configurado para capturar as impressões digitais.

4.  Para anexar a imagem do **Cartão de assinatura** físico, clique no ícone de scanner. Você pode:

    * **Selecionar** uma imagem existente.

    * **Capturar** uma foto com a webcam.

    * **Digitalizar** o documento com um scanner.

    * *IMPORTANTE*: Após anexar a imagem do cartão, clique em **Concluir** na janela de captura para vinculá-la.

5.  Na seção **Arquivos anexos**, utilize as mesmas opções (Selecionar, Capturar, Digitalizar) para adicionar outros documentos relevantes, como RG, CNH ou Procurações.

---

---

## M-9.2 - Como Vincular uma Pessoa Jurídica a um Cartão de Assinatura
**Objetivo:** Vincular o cartão de assinatura de uma pessoa física a uma ou mais empresas (Pessoas Jurídicas), definindo-a como representante legal.  
**Tags:** `Firmas`, `Cartão de Assinatura`, `Pessoa Jurídica`, `Representante`, `Vínculo`, `Empresa`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu adiciono o CNPJ da empresa no cartão de assinatura do sócio?
- vincular representante a PJ
- associar pessoa a uma empresa
- cadastrar sócio em ficha
- Uma pessoa representa duas empresas, é possível vincular as duas no mesmo cartão de assinatura?
- adicionar empresa no cartão de assinatura
- Como eu vinculo o cartão de uma pessoa a uma empresa que ela representa?

### Procedimento / Explicação
#### Descrição:

Esta rotina é utilizada quando a pessoa que está abrindo a firma atua como representante de uma ou mais empresas, permitindo que esse vínculo seja registrado oficialmente no sistema.

#### Passo a passo:

1.  Durante o cadastro ou edição de um **Cartão de Assinatura**, localize a seção **Pessoa Jurídica - Representante**.

2.  Clique no botão **Adicionar** (ícone de **+**) para abrir a janela de vínculo.

3.  Preencha os dados da empresa. O campo **CNPJ** é obrigatório.

4.  Repita o passo 2 para vincular a pessoa a múltiplas empresas, se necessário.

5.  Marque a opção **Padrão** para definir qual é a empresa principal que a pessoa representa.

6.  Ao concluir o cadastro do cartão de assinatura, os vínculos serão salvos.

---

---

## M-9.3 - Gerenciar Consumo de Papel de Segurança e Selo Digital no Cartão de Assinatura
**Objetivo:** Gerenciar o consumo do formulário físico (Papel de Segurança) e do Selo Digital durante o cadastro ou a edição de um cartão de assinatura, incluindo as ações de consumir, reutilizar e inutilizar.  
**Tags:** `Firmas`, `Cartão de Assinatura`, `Papel de Segurança`, `NFS`, `Selo Digital`, `Consumo`, `Reutilizar`, `Inutilizar`

### Intenções de Busca & Dúvidas Frequentes
- Preenchi a ficha no papel errado. Como eu faço para inutilizar esse papel e usar outro?
- consumir selo na ficha de assinatura
- reutilizar selo de cartão de assinatura
- gerenciar selo de cartão
- Como eu vinculo um Papel de Segurança (NFS) a um novo cartão de assinatura?
- É possível reutilizar o papel de segurança de um cartão que foi cancelado?
- Onde eu gero o selo digital para um cartão de assinatura?
- dar baixa em papel de segurança
- inutilizar papel de segurança da ficha

### Procedimento / Explicação
#### Descrição:

Esta rotina cobre o processo de vincular e controlar o consumo dos insumos regulados (papel e selo) a um cartão de assinatura, garantindo a rastreabilidade do ato.

#### Passo a passo:

1.  Durante o cadastro ou edição de um **Cartão de Assinatura**, localize as seções **Papel de segurança** e **Selo digital**.

2.  Para gerenciar o **Papel de segurança (NFS)**:

    * O consumo pode ser **Automático**, **Manual** ou **Por digitação**, dependendo da parametrização do sistema.

    * Se manual, clique em **Consumir**, selecione o papel e clique em **Concluir**. O status mudará para "Reservado".

    * Após salvar o cartão de assinatura, o status do papel mudará para "Consumido".

    * **Reutilizar**: Clique no ícone de seta para retornar um papel consumido ao estoque.

    * **Inutilizar**: Clique no ícone **X** para descartar permanentemente um papel.

3.  Para gerenciar o **Selo digital**:

    * A geração pode ser **Automática** ou **Manual**, dependendo da parametrização.

    * Se manual, clique em **Gerar** para criar o selo.

    * **Reutilizar**: Clique para estornar o selo.

    * **Cancelar/Inutilizar**: Clique para cancelar o selo.

    * **Visualizar QR Code**: Clique para ver o QR Code do selo para consulta no TJ.

4.  Após realizar as operações desejadas, clique em **Concluir** na tela principal do cartão de assinatura para salvar todas as alterações.

---

---

## R-10.0 - Abrir Pedido de Firmas
**Objetivo:** Instruir sobre como iniciar um novo pedido para serviços de reconhecimento de firma diretamente na tela de atendimento do balcão.  
**Tags:** `Firmas`, `Pedidos`, `Reconhecimento de Firmas`, `Novo Pedido`

### Intenções de Busca & Dúvidas Frequentes
- novo pedido de firmas
- Onde eu clico para iniciar um novo atendimento no balcão de firmas?
- criar pedido de reconhecimento
- iniciar atendimento de balcão
- Como eu abro um novo pedido na tela de reconhecimento de firmas?
- Preciso começar um novo serviço de reconhecimento, qual o primeiro passo?

### Procedimento / Explicação
#### Como abrir um novo pedido:

1.  Acesse **Orion TN > Firmas > Reconhecimento de firmas**.

2.  Na parte superior da tela, clique no ícone de **"+"** (adicionar novo pedido).

3.  Confirme a criação do novo pedido na mensagem que aparecerá.

---

---

## M-13.0 - Abertura de Pedido de Firmas com Senha (Pré-Atendimento)
**Objetivo:** Iniciar um pedido de firmas na recepção, gerando uma senha de atendimento e incluindo os serviços solicitados antes do atendimento efetivo no balcão.  
**Tags:** `Firmas`, `Pedido`, `Abertura`, `Senha`, `Pré-Atendimento`, `Recepção`

### Intenções de Busca & Dúvidas Frequentes
- atendimento com senha na recepção
- Como funciona o pré-atendimento de firmas com geração de senha?
- abrir pedido na recepção
- Como eu consulto os pedidos que foram abertos na recepção com senha?
- gerar senha para atendimento de firmas
- criar pré-pedido de firmas
- Onde eu lanço os serviços de um cliente na recepção e gero uma senha para ele ir ao balcão?

### Procedimento / Explicação
#### Descrição:

Esta tela é utilizada para iniciar o processo de solicitação de serviços de firmas, atuando como uma recepção ou pré-atendimento. O processo envolve buscar o cliente, incluir os serviços desejados e gerar uma senha que será usada posteriormente no balcão.

#### Passo a passo:

1.  Acesse a tela de pré-atendimento pelo menu **Firmas > Abertura de pedido**.

2.  Busque o cartão de assinatura do cliente utilizando os campos de filtro: **Nome**, **Documento** ou **Mensalista**.

3.  Clique em **Filtrar**. Na janela de resultados, inclua os nomes para o reconhecimento.

4.  Na seção principal da tela, gere uma **Nova senha** para o atendimento. O número da senha, data e hora serão exibidos.

5.  Na área de serviços, inclua todos os serviços que o cliente deseja:

    * Digite o **código do serviço** e a **quantidade**.

    * Selecione o **tipo de cálculo** a ser aplicado.

6.  Após incluir todos os nomes e serviços, clique em **concluir o pedido**. Se parametrizado, o sistema irá imprimir um cupom com a senha para o cliente.

7.  Para consultar pedidos já abertos nesta tela, utilize a opção **Consultar abertura de pedidos**.

---

---

## M-14.0 - Balcão de Firmas: Iniciando um Novo Pedido de Atendimento
**Objetivo:** Detalhar o primeiro passo do atendimento no balcão de firmas, que é a criação de um novo pedido para registrar os serviços que serão realizados.  
**Tags:** `Firmas`, `Balcão`, `Pedido`, `Novo Pedido`, `Iniciar Atendimento`

### Intenções de Busca & Dúvidas Frequentes
- abrir atendimento no balcão
- novo pedido de firmas
- Como eu começo um novo atendimento no balcão de firmas?
- Qual o primeiro passo para fazer um reconhecimento?
- Onde eu clico para abrir um novo pedido?
- iniciar reconhecimento

### Procedimento / Explicação
#### Descrição:

Esta rotina cobre a etapa inicial do atendimento no balcão de firmas: a criação de um novo pedido. Um pedido é o registro que agrupa todos os serviços realizados para um cliente em uma única sessão de atendimento.

#### Passo a passo:

1.  Para acessar a tela de atendimento principal, clique no menu **Firmas > Balcão de firmas**.

2.  Para iniciar um novo atendimento, clique no ícone **+** para criar um **Novo Pedido**.

3.  O sistema irá gerar um número para o novo pedido e preencherá automaticamente os campos **data**, **hora** e **status do pedido**.

4.  Com o novo pedido criado, o próximo passo é buscar e selecionar as partes que terão suas firmas reconhecidas.

---

---

## M-14.1 - Balcão de Firmas: Como Buscar e Selecionar Partes para o Reconhecimento
**Objetivo:** Instruir sobre como localizar e selecionar os cartões de assinatura ou sinais públicos das partes (pessoas) na tela de atendimento do balcão.  
**Tags:** `Firmas`, `Balcão`, `Busca`, `Pesquisa`, `Cartão de Assinatura`, `Sinal Público`, `Biometria`

### Intenções de Busca & Dúvidas Frequentes
- selecionar nomes para etiqueta
- Como eu acho o cartão de assinatura de uma pessoa no balcão?
- Como faço para selecionar a pessoa para o reconhecimento?
- buscar cliente no balcão
- consultar por biometria
- procurar pessoa para reconhecimento
- Onde eu busco por um sinal público?
- É possível buscar pela digital do cliente?

### Procedimento / Explicação
#### Descrição:

Após iniciar um novo pedido, a etapa seguinte é localizar e selecionar as partes (pessoas) que terão suas firmas reconhecidas. O sistema oferece diversas formas de busca para agilizar este processo.

#### Passo a passo:

1.  Com um pedido aberto na tela **Balcão de firmas**, acesse a seção de **Buscas**.

2.  Selecione o **tipo de busca**: **Cartão** (para assinaturas cadastradas no cartório) ou **Sinal público** (para cartórios externos).

3.  Utilize um dos campos de filtro para encontrar a parte desejada (ex: **Nome**, **CPF**, **Nº Cartão**).

4.  Pressione **Enter** ou clique em **Filtrar**.

5.  Na seção **Nomes encontrados**, os resultados serão listados.

6.  Para selecionar uma parte para o reconhecimento, dê um **duplo clique** sobre o nome ou clique no ícone **"+"**. O nome será movido para a lista de **Nomes selecionados**.

7.  Na lista de **Nomes selecionados**, ajuste a **Quantidade de atos** para cada nome, se necessário.

---

---

## M-14.2 - Balcão de Firmas: Lançando Serviços e Imprimindo Etiquetas
**Objetivo:** Detalhar o processo de lançamento de serviços (reconhecimentos, autenticações) e a configuração da impressão das etiquetas no atendimento de balcão.  
**Tags:** `Firmas`, `Balcão`, `Lançar Serviço`, `Impressão`, `Etiqueta`, `Autenticação`

### Intenções de Busca & Dúvidas Frequentes
- imprimir etiqueta de reconhecimento
- como lançar uma autenticação
- Depois de selecionar o nome, como eu imprimo a etiqueta?
- gerar etiqueta de firma
- Como eu configuro o que vai sair na etiqueta?
- Onde eu adiciono o serviço de autenticação de cópia?

### Procedimento / Explicação
#### Descrição:

Com as partes selecionadas, o próximo passo é lançar os serviços solicitados (como reconhecimentos e autenticações) e imprimir as etiquetas que serão afixadas nos documentos.

#### Passo a passo:

1.  Com os nomes já na lista de **Nomes selecionados** na tela **Balcão de firmas**, clique no botão de impressão.

2.  A janela de **Impressão de etiqueta** será aberta. Preencha os seguintes campos:

    * **Tipo**: Selecione o tipo de reconhecimento (ex: Semelhança, Autenticidade).

    * **Modelo**: Selecione o modelo de etiqueta.

    * **Escrevente**: Selecione o escrevente responsável pelo ato.

    * **Impressora**: Selecione a impressora correta.

3.  Clique em **Imprimir**. O selo correspondente será consumido e a etiqueta será gerada.

4.  Para lançar outros serviços, como **Autenticações**, acesse a seção correspondente no painel direito.

5.  Digite o **código do serviço** ou o nome, informe a **quantidade** e pressione **Enter** para adicioná-lo ao pedido.

---

---

## M-14.3 - Balcão de Firmas: Gerenciando Selos (Reutilizar e Inutilizar)
**Objetivo:** Descrever como gerenciar os selos dos serviços já lançados em um pedido, explicando como reutilizar (estornar) ou inutilizar um selo em caso de erro.  
**Tags:** `Firmas`, `Balcão`, `Gerenciamento`, `Selo`, `Reutilizar`, `Inutilizar`, `Estorno`

### Intenções de Busca & Dúvidas Frequentes
- Imprimi uma etiqueta errada, como faço para devolver o selo para o estoque?
- A etiqueta rasgou, como eu dou baixa nesse selo?
- inutilizar selo danificado
- como cancelar um selo que imprimi errado
- O que significa reutilizar um selo?
- estornar selo de reconhecimento

### Procedimento / Explicação
#### Descrição:

Após a impressão de uma etiqueta e o consequente consumo de um selo, podem ocorrer erros. Esta rotina explica como gerenciar esses selos, seja retornando-os ao estoque para um novo uso ou descartando-os permanentemente.

#### Passo a passo:

1.  Na tela do **Balcão de Firmas**, localize o serviço na seção **Últimos serviços realizados** ou expanda a janela de detalhes do pedido.

2.  Para o serviço desejado, as seguintes ações de gerenciamento de selo estão disponíveis:

    * **Reutilizar selo**: Clique nesta opção para estornar o selo (físico ou digital) de volta para o estoque. Esta ação deve ser usada caso a etiqueta tenha sido impressa por engano e o selo não tenha sido danificado.

    * **Inutilizar selo**: Clique nesta opção para inutilizar o selo permanentemente. Esta ação deve ser usada em caso de danos à etiqueta ou ao selo, impedindo seu uso futuro. O selo será baixado do estoque.

---

---

## M-14.4 - Balcão de Firmas: Finalizando o Pedido para Pagamento no Caixa
**Objetivo:** Instruir sobre como finalizar ou cancelar um pedido de atendimento no balcão de firmas, encaminhando-o para o pagamento no módulo de Caixa.  
**Tags:** `Firmas`, `Balcão`, `Finalizar`, `Concluir`, `Pagamento`, `Caixa`, `Cancelar Pedido`

### Intenções de Busca & Dúvidas Frequentes
- cancelar um pedido inteiro
- como concluir o pedido
- Como eu fecho o pedido e envio para o cliente pagar?
- mandar o pedido para o caixa
- O cliente desistiu, como cancelo tudo que foi lançado?
- encerrar atendimento de firmas
- Terminei de lançar os serviços, qual o próximo passo?

### Procedimento / Explicação
#### Descrição:

Após lançar todos os serviços solicitados pelo cliente, o pedido de atendimento deve ser finalizado para que o pagamento possa ser processado no Caixa, ou cancelado em caso de desistência.

#### Passo a passo:

1.  Com todos os serviços lançados no pedido na tela **Balcão de firmas**, utilize uma das ações de finalização:

2.  **Para finalizar o pedido e enviar para pagamento:**

    * Clique no botão **Concluir**.

    * O sistema fechará o pedido atual e, se parametrizado, abrirá automaticamente a tela do **Caixa** com os valores a serem pagos.

3.  **Para cancelar o pedido inteiro:**

    * Clique no botão **Cancelar**.

    * *ATENÇÃO:* Esta ação irá cancelar todos os serviços lançados no pedido e todos os selos consumidos serão automaticamente reutilizados (retornados ao estoque).

---

---

## M-16.8 - Parametrizar Pedido de Firmas e Termo de Comparecimento
**Objetivo:** Configurar o comportamento das rotinas de Pedido de Firmas e Termo de Comparecimento, incluindo captura de biometria, controle do número de pedido, uso de senhas e regras para livros.  
**Tags:** `Configurações`, `Pedido de Firmas`, `Biometria`, `Abertura de Pedido`, `Senha`, `Termo de Comparecimento`, `Livro`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu defino o total de folhas de um livro de Termo de Comparecimento para o sistema controlar?
- configurar biometria
- Como eu habilito a geração de pedido utilizando senha na recepção?
- configurações do balcão
- regras de pedido de firmas
- Onde eu configuro se a captura da biometria deve ser de um dedo ou de todos?
- parametrizar termo de comparecimento
- É possível configurar para o sistema abrir um novo livro de termos automaticamente quando o anterior acabar?

### Procedimento / Explicação
#### Descrição:

Esta seção agrupa todas as parametrizações específicas para as rotinas de balcão de firmas e termos, permitindo uma personalização profunda do fluxo de trabalho.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **8 - Pedido de firmas**.

3.  Configure os **PARÂMETROS DE BIOMETRIA**:

    * **Tipo de captura**: Defina se o sistema deve solicitar todos os dedos ou apenas um.

    * **Tipo de busca**: Defina se a busca biométrica será por comparação ou por pesquisa.

4.  Configure a **ABERTURA DE PEDIDO**:

    * **Tipo**: Defina se a criação de pedidos será **Automática** ou **Manual**.

    * **Controle do número do pedido**: Defina se a sequência será **Única**, zerada **Diário** ou **Anual**.

    * **Cadastro rápido (Cartão e sinal)**: Defina se a tela de cadastro rápido deve exibir campos básicos ou o cadastro completo.

    * Configure outras opções como **Não utiliza pedidos**, **Gerar pedido utilizando senha**, **Utilizar impressão de senha**, **Inserir serviços automaticamente**, **Efetivar serviços com certificado digital**, **Exibir rotina de caixa na conclusão do pedido** e **Divisão automática de etiquetas**.

5.  Configure o **TERMO DE COMPARECIMENTO**:

    * **Livro**: Informe o **Total de folhas**, **Termos por página**, **Termos abertura** e **Termos encerramento** para que o sistema controle os livros corretamente.

    * **Responsável**: Configure opções como **Utilizar frente e verso**, **Sequencia de termo automática** e **Abrir livro automaticamente**.

    * **Geral**: Configure o **Tipo padrão**, **Utiliza impressão de etiqueta**, **Utiliza consumo de etiqueta** e se o **Selo obrigatório**.

---

---

## M-17.0 - Como Consultar Pedidos de Firmas
**Objetivo:** Consultar pedidos de firmas já realizados, aplicando diversos filtros como número do pedido, status, período, mensalista ou usuário para localizar atendimentos específicos.  
**Tags:** `Firmas`, `Pedido`, `Consulta`, `Filtro`, `Busca`, `Status`, `Período`, `Mensalista`, `Usuário`, `Escrevente`, `Histórico`

### Intenções de Busca & Dúvidas Frequentes
- buscar pedido finalizado
- relatório de pedidos de balcão
- Preciso de um relatório de todos os pedidos de um mensalista em um determinado período, como eu gero?
- Como eu encontro um pedido de firmas que já foi finalizado?
- Onde eu posso ver o histórico de todos os atendimentos de balcão de um usuário específico?
- pesquisar pedido de firma
- Como eu busco um pedido de firmas pelo seu número?
- encontrar um reconhecimento de firma
- histórico de atendimentos de balcão

### Procedimento / Explicação
A tela de Consulta de Pedido de Firmas permite buscar e visualizar todos os pedidos de balcão, oferecendo uma variedade de filtros para refinar a pesquisa e ações para inspecionar os detalhes de cada pedido.

    #### Passo a passo para consultar:

    1.  Para acessar a tela, clique no menu **Firmas > Consultas > Pedido de firmas**.

    2.  Utilize os campos de busca disponíveis para localizar os pedidos desejados:

        * **Número do pedido**: Para buscar através do número do pedido.

        * **Status**: Para buscar pelo status do pedido (ex: "Aguardando Pagamento", "Iniciado", "Finalizado").

        * **Período**: Para buscar os pedidos dentro de um determinado intervalo de datas.

        * **Mês de referência**: Para realizar uma busca através de um mês específico.

        * **Mensalista**: Para buscar os pedidos de um mensalista específico.

        * **Requisição Nº**: Para buscar os pedidos através do número de requisição do mensalista.

        * **Usuário**: Para buscar os pedidos criados por um determinado usuário.

        * **Escrevente**: Para buscar os pedidos de um determinado escrevente.

        * **Item**: Para buscar pedidos que contenham um item específico da tabela de custas.

    3.  Após preencher os filtros, clique em **Filtrar**. Para limpar os campos, clique em **Limpar**.

    4.  O sistema exibirá os resultados. Para cada pedido listado, as seguintes ações estão disponíveis:

        * **Mostrar detalhes**: Clique para exibir os itens e serviços que foram incluídos no pedido.

        * **Andamentos**: Clique para visualizar o histórico de ações do pedido (Ex: Pedido iniciado, alterado, concluído).

        * **Visualizar**: Clique para abrir o pedido na tela do Balcão de Firmas.

---

---

## R-23.0 - Como Realizar a Distribuição de Produtos no Estoque
**Objetivo:** Realizar a distribuição (saída) de produtos do estoque principal, como selos e papéis, para o controle dos usuários, grupos ou máquinas que irão consumi-los.  
**Tags:** `Estoque`, `Distribuição`, `Produto`, `Selos`, `Administração`, `Saída de Estoque`

### Intenções de Busca & Dúvidas Frequentes
- É possível estornar uma distribuição de selos que foi feita errada?
- entregar selos para o escrevente
- Como eu consulto quais selos foram distribuídos para um determinado usuário?
- estornar distribuição
- Onde eu registro a saída de papel de segurança do estoque para um escrevente?
- saída de estoque
- repassar papel de segurança
- Como eu faço para distribuir um lote de selos para um funcionário específico?
- distribuir selos para funcionários
- consultar distribuição de selo

### Procedimento / Explicação
Após a aquisição, a distribuição é o processo de repassar os produtos do estoque principal para o controle dos colaboradores que os utilizarão.

    #### Parte 1: Distribuir Produtos para os Usuários

    1.  No módulo **Orion Estoque**, acesse o menu **Administração > Distribuição**.

    2.  Na aba **"Distribuição"**, selecione a **Categoria** e o **Produto**. O sistema listará os lotes disponíveis em estoque.

    3.  Selecione a série que deseja distribuir e clique na seta para a direita para preencher os campos automaticamente, ou clique no botão `+` para adicionar manualmente a série e a sequência.

    4.  No campo **Portador**, selecione para quem o produto será enviado. É possível direcionar para:

        * **Usuários individuais**

        * **Grupos de usuários**

        * **Máquinas (estações de trabalho)**

    5.  Após revisar todas as informações, finalize o processo clicando no botão **Concluir**.

    #### Parte 2: Consultar ou Estornar uma Distribuição

    1.  Ainda na tela de **Distribuição**, acesse a aba **"Consulta"**.

    2.  Filtre pela categoria, produto, data ou portador para localizar a distribuição desejada.

    3.  O sistema mostrará o resultado e permitirá:

        * **Estornar:** Devolve o produto para o estoque principal, desde que ele ainda não tenha sido utilizado.

        * **Andamentos:** Exibe o histórico de logs daquela distribuição.

---

---

## M-23.0 - Gerenciamento de Tipos de Documento para Termo de Comparecimento
**Objetivo:** Acessar, visualizar, filtrar e gerenciar os tipos de documentos (modelos) utilizados no preenchimento de termos de comparecimento, permitindo a edição e adição de novos.  
**Tags:** `Firmas`, `Cadastros`, `Tipos de Documento`, `Termo de Comparecimento`, `Filtros`, `CRV-SEFAZ`, `Inativos`, `Visualizar`, `Alterar`, `Inativar`, `Adicionar`

### Intenções de Busca & Dúvidas Frequentes
- cadastrar documento para termo
- Onde eu gerencio os diferentes tipos de documentos para o Termo de Comparecimento, como o de DUT/CRV?
- editar tipo de documento de termo
- Como eu edito um modelo de termo de comparecimento existente?
- gerenciar modelos de termo
- Preciso inativar um tipo de documento que não usamos mais, onde faço isso?

### Procedimento / Explicação
#### Descrição:

A tela de Tipos de Documento - Termo de Comparecimento permite a visualização e edição dos documentos que serão utilizados no preenchimento dos termos de comparecimento, facilitando a gestão e organização.

#### Passo a passo:

1.  Para ter acesso à rotina de cadastro dos tipos de documento, acesse o menu **Firmas**, seguido do submenu **Cadastros**, na sequência acesse **Tipos de documento** e por fim acesse o submenu **Tipos de documento - Termo de comparecimento**.

2.  A tela de **Tipos de documento - Termo de comparecimento** permite a visualização e edição dos documentos para utilização no preenchimento dos termos de comparecimento.

3.  Para realizar filtros, utilize as seguintes opções:

    *   **Descrição**: Permite uma busca pela descrição do documento cadastrado. Basta informar uma parte do nome para busca, apertar **Enter** ou clicar no botão **Filtrar**.

    *   **CRV-SEFAZ**: Permite realizar uma busca pela opção **CRV-SEFAZ** selecionada na criação/edição dos documentos, facilitando a busca para os tipos que são enviados à SEFAZ.

    *   **Inativos**: Permite o filtro pelos tipos de documentos inativados.

    *   **Filtrar**: Botão para realizar o filtro com base na pesquisa desejada.

4.  Além das opções de filtro, temos também as seguintes ações em cada um dos registros encontrados:

    *   **Visualizar**: Permite somente visualizar o conteúdo do documento, sem possibilidade de alterações.

    *   **Alterar**: Permite alterar o documento.

    *   **Inativar**: Inativa o documento, não permitindo sua utilização. Se necessário, basta procurá-lo pelo filtro de **Inativos** e ativá-lo novamente através da tela de alteração.

5.  Para adicionar um novo tipo de documento, basta clicar no botão **Adicionar**.

---

---

## R-24.0 - Consumo Manual de Produtos no Estoque
**Objetivo:** Registrar manualmente a baixa (consumo) de um produto do estoque, indicando o portador e a quantidade, para casos onde o consumo não é automático pelo sistema.  
**Tags:** `Estoque`, `Consumo Manual`, `Produto`, `Administração`

### Intenções de Busca & Dúvidas Frequentes
- baixa de estoque manual
- consumo avulso de estoque
- Onde eu informo que um produto do estoque foi consumido sem estar atrelado a um ato?
- Como eu dou baixa manual em um selo que foi usado fora do sistema?
- Preciso registrar o consumo de uma folha de papel de segurança manualmente, como faço?
- dar baixa manual em selo
- registrar uso de papel

### Procedimento / Explicação
#### Passo a passo:

1.  Acesse o menu "**Estoque > Administração > Consumo Manual**".

2.  Ao abrir a tela, serão exibidos os produtos disponíveis para consumo, juntamente com os campos necessários para registrar o consumo manual.

3.  Na parte inferior da tela, preencha os seguintes campos obrigatórios: **Produto**, **Portador**, **Quantidade**, **Data**, **Série**, **Seq. Inicial**, **Seq. Final**, **Status do produto**.

4.  Os botões "**+**" e "**-**" permitem adicionar ou remover registros, caso seja necessário registrar o consumo de mais de um produto.

5.  Após preencher todas as informações, clique em "**Concluir**" para finalizar o processo.

---

---

## M-24.0 - Cadastro de Novo Tipo de Documento para Termo de Comparecimento
**Objetivo:** Criar um novo modelo (tipo de documento) para Termo de Comparecimento, configurando seus campos personalizados, o modelo de impressão e a integração com a SEFAZ-SP (CRV).  
**Tags:** `Firmas`, `Cadastros`, `Tipos de Documento`, `Termo de Comparecimento`, `CRV-SEFAZ`, `Campos`, `Modelo de Impressão`, `Digitalização`, `SEFAZ-SP`

### Intenções de Busca & Dúvidas Frequentes
- Como eu marco um novo tipo de documento para que seja obrigatório digitalizar o anexo antes de concluir?
- Como eu crio um novo tipo de documento para o Termo de Comparecimento?
- cadastrar novo DUT
- Onde eu configuro os campos que devem aparecer em um termo de DUT, como Placa e Renavam?
- configurar campos do termo de comparecimento
- novo tipo de documento para termo
- criar modelo de termo

### Procedimento / Explicação
#### Descrição:

Esta rotina orienta sobre como adicionar e configurar um novo tipo de documento para ser utilizado nos termos de comparecimento, incluindo a definição de campos, modelos de impressão e opções específicas para comunicação com a SEFAZ-SP.

#### Passo a passo:

1.  Para ter acesso à rotina de cadastro dos tipos de documento, acesse o menu **Firmas**, seguido do submenu **Cadastros**, na sequência acesse **Tipos de documento** e por fim acesse o submenu **Tipos de documento - Termo de comparecimento**.

2.  Para adicionar um novo tipo de documento, basta clicar no botão **Adicionar**.

3.  Na tela de cadastro, preencha os seguintes campos:

    *   **Descrição**: Campo obrigatório para cada tipo de documento. Será exibida na tela de termo de comparecimento para seleção. Não permite tipos de documento com a mesma descrição.

    *   **Modelo de impressão (padrão)**: Permite selecionar um modelo padrão para impressão das etiquetas de termo quando este tipo de documento for utilizado. É opcional e pode ser alterado na impressão do termo.

    *   **CRV - SEFAZ SP**: Ao marcar esta opção, o sistema indica que todos os termos criados com este tipo de documento devem ser encaminhados à SEFAZ-SP para comunicação de venda de veículos. Ao marcar esta opção, a seguinte sub-opção é exibida:

        *   **Obrigatório digitalizar antes de concluir**: Caso selecionada, obriga o usuário a realizar a digitalização do termo de comparecimento para poder sair da tela de termo, garantindo que o DUT a ser enviado à SEFAZ não seja esquecido.

4.  Após informar os dados básicos do tipo de documento, prossiga para a criação dos campos. Os tipos de campos disponíveis são:

    *   **Texto**: Permite texto livre na tela do termo, com total de 160 caracteres.

    *   **Número**: Permite valor numérico livre na tela do termo, com total de 30 dígitos.

    *   **CPF**: Permite informar um CPF, com validação e máscara.

    *   **RG**: Permite informar um RG, com máscara.

    *   **CNPJ**: Permite informar um CNPJ, com validação e máscara.

    *   **Placa - SEFAZ SP**: Campo para informar uma placa de veículo, mapeado para envio na comunicação de transferência de veículo para a SEFAZ-SP.

    *   **Renavam - SEFAZ SP**: Campo para informar o Renavam de um veículo, mapeado para envio na comunicação de transferência de veículo para a SEFAZ-SP.

    *   **Espelho - SEFAZ SP**: Campo para informar o espelho de um veículo, mapeado para envio na comunicação de transferência de veículo para a SEFAZ-SP.

    *   **Data da venda - SEFAZ SP**: Campo para informar a data da venda de um veículo, mapeado para envio na comunicação de transferência de veículo para a SEFAZ-SP.

    *   **Data**: Campo para informar uma data livre, com máscara e validação.

    *   **UF**: Campo livre para informar uma Unidade Federativa.

    *   **Cidade**: Campo livre para informar uma cidade, com base na UF selecionada.

5.  Para adicionar os campos ao modelo, arraste-os ou insira-os para o lado direito da tela.

6.  Após inserir um campo, é possível configurá-lo:

    *   Informar uma descrição para a seção, que será exibida na tela do Termo de comparecimento.

    *   Informar uma descrição para o campo.

    *   Remover o campo do modelo.

    *   Aumentar ou diminuir o tamanho do campo em tela.

7.  Por fim, basta clicar em **Concluir** para finalizar o cadastro do tipo de documento.

---

---

## M-29.0 - Como Criar um Termo de Comparecimento (Fluxo Padrão)
**Objetivo:** Detalhar o procedimento padrão para a criação de um novo Termo de Comparecimento, desde o acesso à tela, preenchimento dos dados, seleção de participantes, até o salvamento e impressão.  
**Tags:** `Termo de Comparecimento`, `Cadastro`, `Reconhecimento por Autenticidade`, `Firmas`, `Livro Físico`, `DUT`, `CRV`, `SEFAZ`, `Participantes`

### Intenções de Busca & Dúvidas Frequentes
- Qual o passo a passo para preencher e salvar um termo de DUT?
- fazer DUT
- lançar termo
- A tela do termo abriu automaticamente após o reconhecimento por autenticidade, o que eu preencho agora?
- termo de transferência de veículo
- Como eu crio um novo Termo de Comparecimento para uma transferência de veículo?
- Como eu adiciono um 'não comparecente' em um termo de comparecimento?
- preencher termo de DUT
- cadastrar CRV
- criar termo de comparecimento

### Procedimento / Explicação
Esta rotina detalha o fluxo padrão para criar um Termo de Comparecimento, registrando as partes envolvidas em um ato notarial, configurando o tipo de termo, associando a um livro e gerenciando os participantes.

    #### Como Acessar a Tela de Criação de Termo

    Existem três caminhos para abrir a tela:

    * **Automaticamente:** Se o parâmetro estiver habilitado, a tela do termo será aberta automaticamente após a execução de um serviço de **Reconhecimento por Autenticidade**.

    * **Via Pedidos:** Nas telas de **Pedidos de Firmas** e/ou **Abertura de senhas**, o botão **"Termos"** dá acesso aos termos do pedido e permite a criação de novos.

    * **Via Serviços Praticados:** Na consulta de **Serviços praticados**, ao buscar um serviço, é possível acessar os termos associados a ele.

    #### Passo a passo para o Cadastro

    1.  Na tela de termos, preencha os campos principais na parte superior:

        * **Tipo de termo / Modelo**: Selecione o tipo de documento cadastrado (ex: "DUT CRV"). Cada tipo pode ter campos diferentes para preenchimento.

        * **Livro**: Selecione um livro físico com status "Aberto" ao qual o usuário logado tenha acesso.

        * **Escrevente**: Selecione o escrevente responsável pelo termo.

        * **Termo subsequente**: Marque esta opção se o termo for parte de uma sequência, onde apenas o último termo será assinado no livro físico.

    2.  Gerencie os **Participantes** do termo:

        * A pessoa do reconhecimento já virá listada. Marque a caixa **"Comparece"** para indicar sua presença (é necessário no mínimo um comparecente).

        * Defina a **Participação** de cada comparecente (ex: Comprador, Vendedor, Representante).

        * Para incluir pessoas físicas ou jurídicas que não estavam presentes, utilize a opção **"Adicionar não comparecente"**.

    3.  Se a participação escolhida for **"Representante"**, o sistema permitirá informar quem a parte está representando (o **representado**), buscando os dados no cadastro de cartões.

    4.  Para termos do tipo **CRV - SEFAZ SP**, quando a participação for **"Comprador"**, o sistema exibirá uma seção para preencher o endereço do comprador e os **dados do veículo** (Renavam, placa, valor, etc.).

    5.  Após preencher todos os campos obrigatórios, clique em **Salvar e imprimir**.

        * Esta ação irá consumir uma posição do livro físico selecionado (folha, lado, posição).

        * Se o parâmetro **Utiliza impressão de etiqueta** estiver ativo, o sistema também exibirá uma janela com os modelos para impressão do termo.

---

---

## M-29.2 - Como Criar Termos de Comparecimento em Lote
**Objetivo:** Instruir sobre como usar a funcionalidade de criação em lote para gerar múltiplos Termos de Comparecimento de forma rápida e automatizada a partir de vários reconhecimentos de firma.  
**Tags:** `Termo de Comparecimento`, `Criar em Lote`, `Lote`, `Automação`, `Geração em Massa`, `Firmas`

### Intenções de Busca & Dúvidas Frequentes
- Para que serve o botão 'Criar em lote' na tela de Termos de Comparecimento?
- gerar DUTs em lote
- criação automática de termos
- Como eu configuro a quantidade de selos por termo na criação em lote?
- termo em lote
- Um cliente assinou 10 documentos. Tem como criar os 10 termos em lote?
- criar vários termos de uma vez
- gerar termos em massa
- Como eu gero vários termos de comparecimento de uma só vez?

### Procedimento / Explicação
Quando há necessidade de criar diversos termos de comparecimento para os mesmos participantes, a funcionalidade de criação em lote agiliza o processo, gerando os termos automaticamente com base nas configurações definidas.

    #### Passo a passo para criar termos em lote:

    1.  Na tela de Termos de Comparecimento de um pedido existente, clique no botão **"Criar em lote"**.

    2.  A tela de criação em lote agrupa a visão por parte comparecente.

    3.  Defina o **"Tipo de termo"** que será aplicado a todos os termos gerados nesta operação.

    4.  Para cada comparecente, informe a **"Qtd. Selos por termo"**. Este campo define como os reconhecimentos serão agrupados.

        * **Exemplo:** Se uma parte possui 10 selos a serem reconhecidos e você informa "Qtd. Selos por termo" = 1, o sistema criará 10 termos separados, cada um com um selo. Se informar 2, criará 5 termos com 2 selos cada.

    5.  Assim como na tela principal, é possível montar as partes, informando **representados** e **não comparecentes** que serão aplicados a todos os termos gerados em lote.

    6.  Após configurar, clique no botão **"Gerar termos"**. O sistema criará automaticamente todos os termos e os listará na seção "Termos" da tela principal, prontos para serem gerenciados individualmente.

---

---

## M-32.2 - Como Cadastrar um Certificado Digital A1 para Assinatura de Lotes
**Objetivo:** Instruir sobre o procedimento para cadastrar um certificado digital do tipo A1 (arquivo .pfx) no sistema, tornando-o disponível para a assinatura digital de lotes de comunicação.  
**Tags:** `Administração`, `Comunicações`, `Certificado Digital`, `A1`, `Configuração`, `Assinatura Digital`, `Cadastro`

### Intenções de Busca & Dúvidas Frequentes
- Para assinar os lotes da SEFAZ, preciso primeiro cadastrar o certificado A1. Onde faço isso?
- instalar certificado digital A1
- Como eu cadastro o meu certificado digital A1 (.pfx) no sistema para poder assinar os lotes?
- adicionar arquivo .pfx
- Onde eu informo o caminho e a senha do meu certificado A1?
- configurar certificado A1
- cadastrar senha do certificado A1

### Procedimento / Explicação
Esta rotina detalha o procedimento para cadastrar um certificado digital do tipo A1 (arquivo .pfx), para que ele possa ser selecionado durante o processo de assinatura de lotes de comunicação (como os da SEFAZ).

    #### Passo a passo:

    1.  Durante o processo de geração de um novo lote, na tela de **Seleção de Certificado Digital**, clique na opção **"Cadastrar certificado A1? Clique aqui!"**.

    2.  Na janela de cadastro que será exibida, preencha os seguintes dados:

        * **Arquivo**: Informe o caminho onde o arquivo **.PFX** do certificado A1 está armazenado na sua máquina ou rede.

          * **IMPORTANTE:** O arquivo deve estar em um diretório que não será alterado ou movido, caso contrário a configuração precisará ser refeita.

          * Para facilitar, clique no botão **"Selecionar"** para navegar pelas pastas e encontrar o arquivo.

        * **PIN**: Digite a senha (PIN) do seu certificado A1.

    3.  Após preencher as informações, clique no botão **Salvar** e confirme o cadastro.

    4.  Feche a janela de cadastro.

    5.  De volta à tela de **Seleção de Certificado Digital**, clique no **botão de atualização** (geralmente um ícone de setas circulares) para recarregar a lista.

    6.  O certificado A1 recém-cadastrado agora será exibido na lista, pronto para ser selecionado para a assinatura.

---

---

## M-32.3 - Gerando Lote SEFAZ - Assinatura Digital e Processamento Final
**Objetivo:** Instruir sobre a etapa final da geração de lotes para a SEFAZ, incluindo o download das imagens, a seleção do certificado digital, a assinatura dos documentos e o tratamento de falhas no processamento.  
**Tags:** `Administração`, `Comunicações`, `SEFAZ`, `Lotes`, `Processamento`, `Certificado Digital`, `Assinatura`, `Erros`, `Log`

### Intenções de Busca & Dúvidas Frequentes
- processar lote SEFAZ
- O que eu faço se der um erro no processamento do lote?
- Onde eu baixo o arquivo de log para ver os erros da comunicação?
- assinar lote da SEFAZ
- Depois de filtrar os termos, como eu assino o lote para a SEFAZ?
- O sistema pede um certificado digital, como funciona?
- ver erros no lote de comunicação
- como usar o certificado digital para enviar o lote

### Procedimento / Explicação
#### Descrição:

Esta é a etapa final e técnica para a geração do lote de comunicação com a SEFAZ. Ela envolve o processamento dos termos validados, a assinatura digital dos documentos e a finalização do lote, incluindo a verificação de possíveis erros.

#### Passo a passo:

1.  Após filtrar e validar os termos pendentes (conforme rotina M-32.1), clique no botão **Processar**.

2.  O sistema iniciará o download das imagens digitalizadas dos DUTs que serão assinadas. Uma tela de progresso será exibida.

3.  Em seguida, a tela de seleção de **Certificado Digital** será aberta, listando os certificados instalados na estação (tipo A3 ou A1 previamente cadastrado).

4.  Selecione o certificado correto, informe a senha (PIN) e clique em **Confirmar**.

    * *Observação Importante:* O tipo de assinatura deve ser sempre **"Todos em CAdES"** para que os arquivos sejam gerados no formato esperado pela SEFAZ.

5.  O sistema iniciará o processo de assinatura de todas as imagens, que serão salvas no formato **.PDF.P7s**.

6.  Uma barra de progresso indicará o status para cada termo. Se algum termo apresentar falha, clique no ícone de interrogação ao lado para visualizar o motivo do erro.

7.  Ao final do processamento, as seguintes ações estarão disponíveis:

    * **Baixar log**: Efetua o download de um arquivo de log com os detalhes do processamento de todos os termos, incluindo os erros.

    * **Abrir pasta**: Abre o diretório no seu computador onde os lotes foram salvos.

    * **Finalizar**: Conclui o processo. Se houver termos com falha, o sistema avisará e manterá na tela apenas os termos que precisam de correção para serem reprocessados.

---

---

