---
tipo: Recurso
area: Produtos Siplan
tags:
  - #orion
  - #orion_orion_tn
  - #orion_tn_-_certidões_e_ged
status_atual: #ativo
---
# Orion TN - Certidões e GED

Este recurso detalha os procedimentos, rotinas e manuais operacionais do sistema **Orion TN** para a área de **Certidões e GED**.

## D-1.14 - Ativar Inteligência Artificial (OCR e Cadastros)
**Objetivo:** Habilitar funcionalidades de IA para OCR de documentos e automação de cadastros.  
**Tags:** `inteligência artificial`, `ocr`, `automação`, `cadastro`

### Intenções de Busca & Dúvidas Frequentes
- Como o sistema lê automaticamente boletos?
- Como ativar inteligência artificial no caixa?
- ativar ocr
- Como usar OCR para ler notas fiscais?
- habilitar inteligência artificial
- configurar leitura de documentos

### Procedimento / Explicação
#### Descrição:

A inteligência artificial oferece OCR para leitura de documentos (notas fiscais, boletos) e automação de cadastros de despesas e fornecedores.

#### Passo a passo:

1. Acesse **Configurações > Parametrizações > Inteligência Artificial**.

2. Marque as funcionalidades desejadas:

   * **Cadastro de Despesa** - Leitura automática para cadastro

   * **Cadastro de Fornecedores** - Leitura automática para cadastro

   * **OCR** - Leitura de documentos (notas fiscais, boletos)

3. Salve as configurações.

* **Observação Importante:** A IA lê automaticamente os dados e preenche os campos, dispensando digitação manual. A funcionalidade deve estar habilitada na configuração da sua instância.

---

---

## D-3.10 - Fazer Digitalização em Lote de Livros e Folhas
**Objetivo:** Digitalizar páginas de livro em lote, vinculando automaticamente aos protocolos que utilizaram cada folha.  
**Tags:** `digitalização`, `livro`, `folha`, `lote`

### Intenções de Busca & Dúvidas Frequentes
- Como vincular folhas aos protocolos?
- Como fazer digitalização de 100 páginas de uma vez?
- Como digitalizar páginas de livro?
- digitalizar folhas em lote
- processar páginas de livro
- escanear livro

### Procedimento / Explicação
#### Descrição:

Digitalização em lote de livros permite processar grande volume de páginas, vinculando automaticamente aos protocolos que utilizaram cada folha.

#### Passo a passo:

1. Acesse **Firmas > Cadastros > Digitalização em Lote > Livros**.

2. Você pode **digitalizar individual** ou **em lote**.

#### Digitalização Individual:

1. Abra o **protocolo > Anexos**.

2. Clique em **Digitalizar**.

3. **Coloque as páginas** que você utilizou (ex: 58, 59, 60).

4. Clique em **Digitalizar**.

#### Digitalização em Lote:

1. Acesse **Digitalização em Lote > Livros**.

2. Configure:

   * **Número do Livro:** 1

   * **Página Inicial:** 1

   * **Página Final:** 100

3. **Coloque 100 páginas no scanner** em sequência.

4. Clique em **Digitalizar** ou **Importar**.

5. O sistema:

   * **Lê número do livro** de cada página

   * **Lê numeração de cada folha**

   * **Identifica em qual protocolo foi utilizada**

   * **Vincula automaticamente** ao protocolo correto

#### Uso Posterior:

- Necessário para **Certidão Reprográfica** (precisa imagem do livro)

- Necessário para **comunicação CEPHAS e ITBI** (precisam anexar página do livro)

* **Observação Importante:** Grande economia de tempo. Processo automatizado por leitura do número de livro e folha em cada página. Essencial para certidões e comunicações.

---

---

## D-3.16 - Criar Certidão
**Objetivo:** Registrar nova certidão com espécie, natureza, solicitante, custas e gerar recibo com selo digital.  
**Tags:** `certidão`, `criação`, `recibo`, `documento`

### Intenções de Busca & Dúvidas Frequentes
- Como gerar o recibo de certidão?
- gerar recibo de certidão
- lançar certidão
- Como vincular ato à certidão?
- criar nova certidão
- Como criar uma certidão?

### Procedimento / Explicação
#### Descrição:

Certidão é documento específico do sistema, com controle exato de tudo realizado. Requer preenchimento mínimo para gerar recibo.

#### Passo a passo:

1. Acesse **Notas > Certidões > Certidões e Serviços em Aberto**.

2. Clique em **Adicionar** para nova certidão.

3. Preencha **campos obrigatórios**:

   * **Escrevente:** Já selecionado

   * **Tipo de Certidão:** Selecione (ex: Reprográfica)

   * **Ato:** Selecione tipo de ato (ex: Ato Notarial)

   * **Solicitante:** Busque cliente

4. Selecione **custas** (preço da certidão).

5. Clique em **Salvar**.

6. O sistema habilita **Gerar Recibo** quando:

   * Escrevente preenchido

   * Solicitante preenchido

   * Custas preenchidas

7. Clique em **Gerar Recibo**.

8. Sistema realiza:

   * **Geração de recibo**

   * **Geração automática de selo digital** (se configurado)

   * **Comunicação automática ao TJ** (se configurado)

#### Verificação:

- Clique em **Visualizar Selo** para confirmar geração

- Escaneie **QR Code** para consultar no portal TJ

* **Observação Importante:** Certidões são separadas de protocolos para controle específico. Campos mínimos obrigatórios. Comunicação automática ao TJ é configurável.

---

---

## D-3.17 - Vincular Ato a Certidão para Reprografia
**Objetivo:** Localizar ato/protocolo anterior e vincular anexo (livro) para gerar certidão reprográfica.  
**Tags:** `certidão`, `reprografia`, `ato`, `busca`

### Intenções de Busca & Dúvidas Frequentes
- anexar documento
- Como vincular um ato à certidão?
- vincular protocolo
- Como anexar imagem de livro?
- Como buscar protocolo anterior?
- buscar ato para certidão

### Procedimento / Explicação
#### Descrição:

Para certidão reprográfica, é necessário localizar o protocolo anterior e anexar a imagem do livro/documento original.

#### Passo a passo:

1. Na **tela de Certidão**, acesse **seção de busca de atos**.

2. Configure **filtros**:

   * **Data de Lavratura:** Período desejado (ex: outubro)

   * **Por Nome/CPF** (opcional)

3. Clique em **Filtrar**.

4. Sistema traz **protocolos do período**.

5. Visualize **informações do protocolo** selecionado.

6. Verifique se tem **anexo** vinculado.

7. Se **sem anexo**:

   * Clique em anexo

   * **Digitalize ou importe** documento (ex: livro, CNH como exemplo)

   * O sistema registra

8. Clique em **sinal de +** para vincular protocolo à certidão.

9. O ato fica registrado como **anexado**.

#### Próximo Passo:

- Gerar certidão (veja rotina "Gerar Certidão no Editor de  Texto")

* **Observação Importante:** Protocolo deve ter anexo para reprografia. Você pode digitalizá-lo no ato se não tiver.

---

---

## D-3.18 - Gerar Certidão no Editor de  texto
**Objetivo:** Gerar documento final de certidão usando editor integrado com modelo, mescla de informações e QR Code.  
**Tags:** `editor`, `certidão`, `geração`, `modelo`

### Intenções de Busca & Dúvidas Frequentes
- Como visualizar certidão?
- Como gerar o documento da certidão?
- gerar pdf de certidão
- Como imprimir certidão?
- criar documento de certidão
- processar certidão

### Procedimento / Explicação
#### Descrição:

Editor de  texto integrado gera certidão final mescla informações do modelo com dados da certidão, ato anexado e QR Code.

#### Passo a passo:

1. Na **tela de Certidão**, clique em **Certidão** (botão do editor).

2. Sistema carrega **ato/livro vinculado**.

3. Selecione **modelo de certidão** desejado.

4. Sistema **mescla** automaticamente:

   * Folha de capa com informações

   * QR Code do selo digital

   * Informações do selo (datas, valores)

   * Custas da certidão

   * Imagem do documento vinculado

5. Clique em **Visualizar** para ver resultado.

6. Sistema exibe:

   * Folha de informações (data, recibo, etc.)

   * Modelo com selo digital

   * Custas

   * Documento original anexado

7. Se tudo está correto, clique **Salvar e Imprimir**.

#### Observações Importantes:

- Campos em **vermelho** não foram preenchidos (ex: cargo do escrevente)

- Sistema **mescla modelo com dados** automaticamente

- Resultado é certidão **pronta para entrega**

* **Observação Importante:** Qualidade final depende do modelo configurado. Campos obrigatórios em vermelho devem ser revisados.

---

---

## D-3.19 - Estornar Recibo de Certidão
**Objetivo:** Reverter recibo de certidão para fazer edições necessárias no documento.  
**Tags:** `estorno`, `recibo`, `certidão`, `edição`

### Intenções de Busca & Dúvidas Frequentes
- desfazer recibo
- cancelar recibo
- Como cancelar uma certidão?
- Como desfazer um recibo de certidão?
- reverter certidão
- Como editar certidão já finalizada?

### Procedimento / Explicação
#### Descrição:

Estorno reverte a certidão para status anterior, permitindo edições sem cancelamento total.

#### Passo a passo:

1. Na **tela de Certidão**, procure a **opção Estornar Recibo**.

2. Clique para **reverter a certidão**.

3. Certidão volta para **status de edição**.

4. Faça as **alterações necessárias**.

5. Clique em **Gerar Recibo** novamente.

* **Observação Importante:** Estorno não cancela a certidão, apenas permite edições adicionais.

---

---

## D-3.20 - Consultar Histórico de Certidões
**Objetivo:** Visualizar todas as certidões criadas no período com detalhes de solicitante, tipo, data e status.  
**Tags:** `consulta`, `certidão`, `histórico`, `relatório`

### Intenções de Busca & Dúvidas Frequentes
- buscar certidão
- Onde vejo todas as certidões do período?
- ver certidões
- listar certidões
- Como consultar certidões já criadas?
- Como buscar uma certidão específica?

### Procedimento / Explicação
#### Descrição:

Consulta exibe todas as certidões do período com filtros para facilitar busca.

#### Passo a passo:

1. Acesse **Notas > Certidões > Consulta**.

2. Configure **filtros** opcionais.

3. Clique em **Filtrar** ou **Consultar**.

4. Sistema traz **todas as certidões** encontradas.

5. Visualize para cada certidão:

   * **Número de recibo**

   * **Nome escrevente**

   * **Natureza**

   * **Solicitante**

   * **Data de geração**

   * **Status**

6. Clique em certidão para **visualizar detalhes**.

* **Observação Importante:** Consulta padrão do sistema para controle de certidões criadas.

---

---

## D-3.30 - Preencher Documentos Apresentados
**Objetivo:** Classificar e registrar documentos apresentados pelo cliente, preparando para envio ao GED.  
**Tags:** `protocolo`, `documento`, `anexo`, `ged`

### Intenções de Busca & Dúvidas Frequentes
- registrar documentos
- preparar para arquivo
- Como registrar documentos apresentados?
- classificar anexos
- Como preparar documentos para arquivo?
- Como enviar para GED?

### Procedimento / Explicação
#### Descrição:

Documentos apresentados registram quais documentos cliente trouxe, facilitando arquivo e comunicação com GED.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Documentos Apresentados**.

2. Clique em **Adicionar documento**.

3. Configure:

   * **Tipo de Documento:** Ex: Averbação, Alvará Judicial

   * **Tipo de Pasta:** Categoria no GED

   * **Responsável:** Quem vai arquivar

   * **Situação:** Status do documento

4. Clique em **Salvar**.

5. Repita para cada documento.

6. Quando **pronto para arquivo**, clique em **Enviar para GED**.

7. Sistema **configura envio** ao ORION GED automaticamente.

* **Observação Importante:** Registro de documentos facilita rastreamento. Envio a GED é opcional mas recomendado para arquivo centralizado.

---

---

## D-3.31 - Solicitar Certidão Dentro de Protocolo
**Objetivo:** Registrar solicitação de certidões necessárias para o protocolo (casamento, nascimento, etc.).  
**Tags:** `protocolo`, `certidão`, `solicitação`, `controle`

### Intenções de Busca & Dúvidas Frequentes
- Onde vejo certidões solicitadas?
- controlar certidões
- pedir certidão
- Como registrar que preciso de certidão?
- Como solicitar certidão no protocolo?
- registrar certidão solicitada

### Procedimento / Explicação
#### Descrição:

Controle de certidões solicitadas dentro de protocolo para rastreamento de documentação necessária.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Solicitar Certidão**.

2. Clique em **Adicionar certidão**.

3. Preencha:

   * **Tipo de Certidão:** Ex: Casamento, Nascimento

   * **Onde Solicitar:** Cartório/Prefeitura

   * **Tipo:** Eletrônica ou Física

   * **Informações adicionais:** Notas

4. Clique em **Salvar**.

5. Repita para cada certidão necessária.

6. Sistema **registra solicitação**.

7. Via outra rotina, você **rastreia entrega** das certidões.

* **Observação Importante:** Controle interno para não esquecer documentação. Relatório posterior mostra todas as certidões solicitadas.

---

---

## D-3.48 - Consultar Editor e Documentos Gerados
**Objetivo:** Visualizar todos os documentos gerados no editor (minuta, livro, traslado) para cada protocolo.  
**Tags:** `consulta`, `editor`, `documento`, `minuta`

### Intenções de Busca & Dúvidas Frequentes
- consultar minuta
- ver documentos
- Como reutilizar minuta?
- buscar traslado
- Como ver documentos já gerados?

### Procedimento / Explicação
#### Descrição:

Consulta de editor mostra todos os documentos gerados permitindo reutilizar ou visualizar.

#### Passo a passo:

1. Acesse **Notas > Consultas > Editor**.

2. O sistema exibe **documentos gerados**.

3. Cada linha mostra:

   * **Tipo:** Minuta, Livro, Traslado, etc.

   * **Status:** Impressão, Edição, etc.

   * **Data**

4. Clique em documento para **visualizar/reutilizar**.

* **Observação Importante:** Rastreamento de tudo gerado no editor. Evita regeneração desnecessária.

---

---

## D-3.69 - Consultar Certidões Solicitadas
**Objetivo:** Visualizar todas as certidões solicitadas, status de entrega e valores.  
**Tags:** `certidão`, `solicitação`, `controle`, `entrega`

### Intenções de Busca & Dúvidas Frequentes
- consultar status
- Como saber status de certidão solicitada?
- ver certidões
- Onde vejo todas as certidões?
- rastrear certidão

### Procedimento / Explicação
#### Descrição:

Controle centralizado de todas as certidões solicitadas para acompanhamento.

#### Passo a passo:

1. Acesse **Administração > Certidões Solicitadas**.

2. Selecione **período** desejado.

3. Sistema traz **todas as certidões** solicitadas.

4. Visualize:

   * **Protocolo/Protocolo**

   * **Tipo de certidão** solicitada

   * **Status:** Pendente, Entregue, etc.

   * **Data solicitação**

   * **Valor**

5. Para **editar**, clique em certidão.

6. Atualize:

   * **Status:** Marcar como entregue

   * **Valor:** Atualizar preço

   * **Informações:** Cartório, cidade, etc.

7. Clique em **Salvar**.

* **Observação Importante:** Rastreamento de certidões solicitadas. Facilita acompanhamento com cliente.

---

---

## D-3.71 - Importar Arquivo de Protesto ou RC
**Objetivo:** Importar dados de sistema externo de protesto ou RC para unificar em relatórios.  
**Tags:** `importação`, `protesto`, `rc`, `especialidade`

### Intenções de Busca & Dúvidas Frequentes
- Como adicionar RC?
- carregar dados
- adicionar protesto
- Como importar protesto?
- importar xml
- Como unificar relatórios?

### Procedimento / Explicação
#### Descrição:

Importação permite unificar dados de múltiplas especialidades em relatórios consolidados.

#### Passo a passo:

1. Acesse **Administração > Importação de Arquivos**.

2. Clique em **Importar**.

3. Selecione **tipo de arquivo**:

   * **Protesto:** Sistema de protesto

   * **RC:** Reclamações Cíveis

4. Selecione **arquivo** (formato .xml esperado).

5. Clique em **Processar** ou **Importar**.

6. Sistema **integra dados**.

#### Uso em Relatórios:

- Após importação, **relatórios como PEX** mostram:

  * Notas (do ORION)

  * Protesto (do arquivo importado)

  * RC (do arquivo importado)

  * **Total unificado**

* **Observação Importante:** Facilita gestão de múltiplos sistemas. Importante para recolhimento consolidado.

---

---

## D-3.8 - Fazer Digitalização em Lote por Código de Barras do Papel
**Objetivo:** Digitalizar cartões fora de ordem usando código de barras do papel de segurança consumido como identificador.  
**Tags:** `digitalização`, `lote`, `código de barras`, `papel de segurança`

### Intenções de Busca & Dúvidas Frequentes
- Como digitalizar cartões sem sequência?
- Como usar código de barras para digitalizar?
- Preciso ter papel consumido para digitalizar?
- digitalizar por número de segurança
- escanear com código de barras
- processar por código

### Procedimento / Explicação
#### Descrição:

Digitalização em lote por código de barras permite escanear cartões em qualquer ordem, usando o código do papel de segurança consumido para vincular.

#### Passo a passo:

1. Acesse **Firmas > Cadastros > Digitalização em Lote**.

2. Clique em **Processar** para iniciar.

3. Selecione **Tipo 2: Digitalização por Código de Barras**.

4. **Identifique um cartão** já criado com papel consumido:

   * Busque o cartão

   * Visualize **número de segurança consumido** (ex: código 12345)

5. Coloque os **cartões no scanner em qualquer ordem**.

6. Clique em **Digitalizar** ou **Importar** (se já tem documentos digitais).

7. O sistema **lê código de barras** de cada página.

8. **Vincula automaticamente** ao cartão onde aquele código foi consumido.

#### Pré-requisito:

- **Papel de segurança deve estar consumido** no cadastro do cartão (isso ocorre com consumo automático).

* **Observação Importante:** Cartões podem estar fora de ordem. Sistema usa código de barras como chave de vinculação. Requer consumo automático configurado.

---

---

## R-5.0 - Controle Financeiro de Protocolos e Pedidos de Certidão
**Objetivo:** Orientar sobre como realizar consultas financeiras separadas para protocolos de escrituras e para pedidos de certidão, garantindo o controle setorizado.  
**Tags:** `Financeiro`, `Protocolos`, `Certidões`, `Caixa`, `Saldos`

### Intenções de Busca & Dúvidas Frequentes
- Qual a diferença entre a consulta financeira de notas e de certidões?
- Como eu verifico se um pedido de certidão já foi pago?
- ver se certidão foi paga
- lançamento financeiro
- consultar saldos de protocolo
- Onde eu consulto o saldo financeiro de um protocolo de escritura?
- verificar pagamento de certidão
- extrato financeiro de escritura

### Procedimento / Explicação
O Orion TN permite um controle financeiro detalhado, diferenciando recebimentos de escrituras (notas) e certidões.

* **Para consultar saldos de protocolos (Escrituras):**

    * Acesse: **Orion TN > Notas > Consultas > Movimentação financeira por protocolo**.

    * Utilize os filtros para identificar o saldo de cada protocolo.

* **Para consultar pagamentos de pedidos de certidão:**

    * Acesse: **Caixa > Administração > Consultas > Certidões e serviços**.

    * Esta tela verifica se o pedido foi pago, mas não exibe saldo.

**Orientações:** Lançamentos de valores devem ser feitos pelo caixa para garantir o controle correto. Ao usar o ícone de cifrão ($) na tela de consulta de certidões, o lançamento é direcionado corretamente para o caixa.

---

---

## M-16.13 - Parametrizar Pedido de Certidão
**Objetivo:** Configurar as regras de negócio para a rotina de Pedido de Certidão, como o controle de estoque de papel de segurança e a definição de um prazo de entrega padrão.  
**Tags:** `Configurações`, `Certidão`, `Pedido`, `Estoque`, `Papel de Segurança`

### Intenções de Busca & Dúvidas Frequentes
- parâmetros de certidão
- Onde eu configuro o consumo de papel de segurança para os pedidos de certidão?
- configurar emissão de certidão
- regras de pedido de certidão
- É possível habilitar ou desabilitar o controle de estoque para a emissão de certidões?
- Como eu defino um prazo de entrega padrão para todas as novas certidões?

### Procedimento / Explicação
#### Descrição:

Esta seção permite definir o comportamento padrão da rotina de Pedido de Certidão.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **13 - Certidão**.

3.  Em **Pedido de certidão**, configure as opções:

    * **Utiliza pedido de certidão** e **Utiliza controle de estoque em notas**.

    * Defina a **Previsão de entrega** padrão.

    * Configure o **Consumo do papel de segurança**, definindo **Categoria**, **Produto** e outras regras.

---

---

## M-16.2 - Parametrizar Captura e Digitalização
**Objetivo:** Configurar o digitalizador (scanner) que será utilizado pelo sistema e definir os diretórios de rede para salvar as imagens digitalizadas por tipo de documento.  
**Tags:** `Configurações`, `Captura`, `Digitalização`, `Scanner`, `Diretório`

### Intenções de Busca & Dúvidas Frequentes
- Como eu configuro o scanner para funcionar com o Orion TN?
- ajustar configurações de digitalização
- configurar scanner
- caminho para salvar documentos escaneados
- É possível definir um diretório diferente para salvar as CNHs e os contratos sociais?
- Onde eu defino em qual pasta da rede as imagens digitalizadas devem ser salvas?
- definir pasta de digitalização

### Procedimento / Explicação
#### Descrição:

Esta seção permite configurar as opções de hardware para digitalização de documentos e os caminhos de armazenamento para as imagens capturadas.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **2 - Captura e digitalização**.

3.  Em **Digitalização**:

    * **Digitalizador**: Selecione o dispositivo de digitalização que será utilizado no sistema.

    * **Dados conexão - Digitalizador Orion**: Caso utilize o digitalizador Orion, informe a **URL de conexão**.

4.  Em **Diretório**:

    * **Documento**: Selecione o tipo de documento para o qual deseja definir um diretório.

    * **Caminho**: Informe o caminho da pasta onde as imagens para este tipo de documento serão salvas.

    * Utilize os botões **Adicionar diretório** ou **Remover diretório** para gerenciar múltiplos caminhos.

---

---

## M-36.0 - Gerenciar Documentos Apresentados
**Objetivo:** Acessar, filtrar e gerenciar os tipos de 'Documentos Apresentados' cadastrados no sistema, permitindo a visualização, alteração e inativação dos registros.  
**Tags:** `Configurações`, `Negócios`, `Cadastros`, `Documento Apresentado`, `Filtros`, `Visualizar`, `Alterar`, `Excluir`

### Intenções de Busca & Dúvidas Frequentes
- Como eu edito a descrição de um tipo de documento apresentado?
- gerenciar lista de documentos
- Preciso inativar um item da lista de documentos apresentados, como faço?
- editar documento apresentado
- Onde eu gerencio a lista de 'Documentos Apresentados' que aparece nos protocolos?
- consultar documentos

### Procedimento / Explicação
#### Descrição:

A tela de **Documento apresentado** permite gerenciar os cadastros existentes. Ao ser aberta, exibe todos os registros em ordem alfabética, com 10 registros por página por padrão. Possui filtros para facilitar a busca e o gerenciamento dos documentos apresentados.

#### Passo a passo para Gerenciar Documentos Apresentados:

1.  Acesse o menu **Configurações > Negócios > Cadastros > Documento apresentado**.

2.  Na tela de **Documento apresentado**, você pode utilizar os seguintes filtros para refinar sua busca:

    *   **Pesquisar por documento apresentado**: Permite efetuar uma busca pelo documento apresentado. Exemplo: "Ajuste".

    *   **Inativos**: Quando selecionado, permite efetuar uma busca apenas pelos cadastros que foram inativados.

    *   **Quantidade por página**: Permite alterar a quantidade de resultados apresentados em tela.

    *   **Limpar**: Limpa a consulta realizada, retornando a tela para o estado inicial.

    *   **Filtrar**: Quando acionado, realiza o filtro com base nos campos de busca preenchidos.

3.  A seção **Resultados** exibe todos os documentos apresentados cadastrados. Para cada registro, as seguintes ações estão disponíveis:

    *   **Visualizar**: Quando acionado, exibe a tela de consulta, contendo os dados preenchidos do documento apresentado. Não permite alterações.

    *   **Alterar**: Quando acionado, exibe a tela de alteração, contendo os dados preenchidos do documento apresentado, permitindo assim sua edição.

    *   **Excluir**: Quando acionado, inativa o cadastro, tornando-o indisponível para uso. Para localizar os cadastros inativos, basta marcar a opção **Inativos** e realizar o filtro.

---

---

## M-53.0 - Consultar Pedidos de Certidão
**Objetivo:** Acessar a tela de listagem de pedidos de certidão e realizar buscas detalhadas utilizando diversos filtros para localizar registros específicos.  
**Tags:** `Pedidos de Certidão`, `Consultas`, `Notas`, `Filtros`, `Busca`, `Certidão`, `Recibo`, `Escrevente`, `Status`

### Intenções de Busca & Dúvidas Frequentes
- buscar certidão pelo nome
- lista de certidões
- Preciso de uma lista de todos os pedidos de certidão de um determinado período, como faço?
- encontrar certidões emitidas
- Como eu pesquiso um pedido de certidão que já foi feito?
- pesquisar pedidos de certidão
- Onde eu encontro uma certidão pelo nome do solicitante?

### Procedimento / Explicação
#### Passo a passo para acessar a tela de Listagem de Pedidos de Certidão:

1.  Clique no menu **Notas > Consultas > Pedidos de certidão**.

#### Descrição:

Na tela **Pedido de certidão**, o sistema não carrega os registros automaticamente ao abrir a tela. É necessário realizar uma pesquisa por filtro para obter os resultados.

#### Campos de filtro disponíveis:

Os campos disponíveis para filtro são:

1.  **Pesquisar por pedido**: Permite efetuar uma busca pelo número do pedido.

2.  **Data de pedido**: Quando selecionado, permite efetuar uma busca pelo período do pedido de certidão.

3.  **Mês do pedido**: Quando selecionado, permite efetuar uma busca pelo mês do pedido de certidão.

4.  **Data previsão**: Quando selecionado, permite efetuar uma busca pelo período de previsão de entrega do pedido de certidão.

5.  **Tipo de certidão**: Quando selecionado, permite efetuar uma busca pelo tipo de certidão.

6.  **Data recibo**: Quando selecionado, permite efetuar uma busca pelo período do recibo.

7.  **Nome**: Permite efetuar uma busca pelo nome das pessoas que foram informadas nas partes.

8.  **Tipo de Documento**: Quando selecionado, habilita um campo para preenchimento de acordo com o tipo de documento selecionado.

9.  **Livro**: Permite efetuar uma busca pelo número do livro definido para o pedido.

10. **Folha**: Permite efetuar uma busca pelo número da folha consumida pelo pedido.

11. **Escrevente**: Permite efetuar uma busca pelo escrevente responsável pelo cadastro do pedido de certidão.

12. **Status**: Permite efetuar uma busca pelo status do pedido.

13. **Período**: Permite efetuar uma busca de pedido mais rápida por período.

#### Ações disponíveis na tela de Pedidos de Certidão:

1.  **Limpar**: Limpa a consulta realizada, retornando a tela para o estado inicial.

2.  **Filtrar**: Quando acionado, realiza o filtro com base nos campos de busca preenchidos.

3.  **Voltar**: Quando acionado, redireciona o usuário para a tela inicial do sistema.

4.  **Adicionar**: Quando acionado, redireciona o usuário para a tela de cadastro do pedido de certidão.

---

---

## M-54.0 - Funcionalidades da Tela de Pedido de Certidão
**Objetivo:** Apresentar as funcionalidades principais e ações disponíveis na tela de Pedido de Certidão, como criar, editar, salvar e consultar pedidos, além de gerenciar andamentos e recibos.  
**Tags:** `Pedido de Certidão`, `Notas`, `Gerenciamento`, `Andamentos`, `Inutilizar`, `Recibo`, `Selo digital`

### Intenções de Busca & Dúvidas Frequentes
- gerenciar certidões
- Onde eu vejo o histórico de um pedido de certidão?
- tela de pedido de certidão
- Como eu gero o recibo de uma certidão que já fiz?
- ações do pedido de certidão
- É possível inutilizar um pedido de certidão?

### Procedimento / Explicação
#### Descrição:

A tela de Pedido de Certidão é a área central para a criação e gerenciamento de certidões. Esta rotina descreve as funcionalidades e botões principais disponíveis na interface para o gerenciamento geral dos pedidos.

#### Passo a passo para acessar e utilizar as funcionalidades:

1.  Para acessar a tela, clique no menu **Notas > Pedido de certidão**.

2.  A tela disponibiliza as seguintes funcionalidades no menu superior:

    * **Novo**: Para iniciar o cadastro de um novo pedido de certidão.

    * **Editar**: Para habilitar a edição de um pedido de certidão existente.

    * **Salvar**: Para salvar as alterações realizadas em um pedido.

    * **Pedidos em aberto**: Para consultar todos os pedidos de certidão que ainda não foram finalizados. É possível abrir um pedido da lista para continuar a edição.

    * **Andamentos**: Para visualizar o histórico completo de todas as ações registradas no pedido de certidão selecionado.

    * **Inutilizar**: Utilizado para descartar/cancelar um pedido de certidão que foi criado.

    * **Gerar recibo**: Utilizado para imprimir o recibo gerado para o pedido de certidão.

    * **Selo digital**: Para visualizar os selos digitais que foram gerados para o pedido.

---

---

## M-54.1 - Como Criar um Novo Pedido de Certidão (Dados do Solicitante)
**Objetivo:** Detalhar o preenchimento do card 'Dados do pedido de certidão', a primeira etapa para criar um novo pedido, incluindo a definição do tipo de certidão e os dados do solicitante.  
**Tags:** `Pedido de Certidão`, `Cadastro`, `Solicitante`, `Dados do Pedido`, `Escrevente`, `Status`

### Intenções de Busca & Dúvidas Frequentes
- iniciar um pedido de certidão
- cadastrar pedido de certidão
- preencher dados do solicitante da certidão
- Onde eu informo quem está pedindo a certidão?
- Como eu começo um novo pedido de certidão?
- Quais informações eu preciso preencher para pedir uma certidão?

### Procedimento / Explicação
#### Descrição:

O preenchimento correto dos dados do solicitante é o primeiro passo para criar um novo Pedido de Certidão. Esta rotina detalha cada campo do card "Dados do pedido de certidão".

#### Passo a passo:

1.  Na tela de **Pedido de certidão**, clique em **Novo**.

2.  No card **Dados do pedido de certidão**, preencha as seguintes informações:

    * **Pedido**: Campo preenchido automaticamente com o número do pedido após ser salvo.

    * **Data do pedido**: Informe a data em que o pedido foi realizado.

    * **Previsão de entrega**: Informe a data prevista para a entrega da certidão.

    * **Situação**: Informe a situação atual do pedido (ex: "Iniciado", "Em andamento").

    * **Escrevente**: Informe o escrevente responsável pelo pedido.

    * **Tipo de certidão**: Selecione o tipo de certidão que está sendo criada (ex: "Ata notarial", "Termo de comparecimento").

3.  No bloco **Solicitante**, selecione se o solicitante é **Pessoa Física**, **Pessoa Jurídica** ou **Mensalista** e preencha os dados correspondentes (Nome/Razão Social, CPF/CNPJ).

4.  Preencha os blocos **Endereço** e **Contato** do solicitante. Utilize o botão de adição **(+)** para cadastrar mais de um endereço ou contato.

5.  Após preencher os dados, o próximo passo é realizar a busca do ato original.

---

---

## M-54.2 - Como Realizar a Busca do Ato Original em um Pedido de Certidão
**Objetivo:** Orientar sobre o preenchimento do card 'Busca' em um Pedido de Certidão, que é utilizado para localizar o ato notarial original (a escritura ou procuração) sobre o qual a certidão será emitida.  
**Tags:** `Pedido de Certidão`, `Busca`, `Ato Original`, `Pesquisa`, `Livro`, `Folha`

### Intenções de Busca & Dúvidas Frequentes
- procurar escritura para certidão
- Depois de preencher os dados do cliente, como eu acho a escritura original?
- Como faço a busca da pessoa no pedido de certidão?
- como achar o ato para certificar
- buscar por livro e folha na certidão
- Onde eu coloco o número do livro e da folha para a certidão?

### Procedimento / Explicação
#### Descrição:

Para emitir uma certidão, é fundamental localizar o ato original nos livros do cartório. O card 'Busca' é a ferramenta utilizada para realizar essa pesquisa dentro do Pedido de Certidão.

#### Passo a passo:

1.  Com os dados do solicitante já preenchidos, acesse o card **Busca**.

2.  Utilize os campos de filtro para localizar o ato original. Você pode pesquisar por:

    * **Tipo de pessoa**, **Nome** e **CPF/CNPJ** da parte envolvida no ato.

    * **Período de lavratura** do ato.

    * **Livro**, **Folha inicial** e **Folha final** onde o ato foi registrado.

3.  Após preencher os filtros, clique no botão **Filtrar** para executar a busca.

4.  Se a busca retornar resultados, selecione o ato correto para vincular ao pedido de certidão.

5.  Para iniciar uma nova pesquisa, clique no botão **Limpar**.

---

---

## M-54.3 - Como Lançar as Custas em um Pedido de Certidão
**Objetivo:** Instruir sobre o preenchimento do card 'Custas' em um Pedido de Certidão, detalhando como adicionar itens da tabela de custas e calcular os valores do serviço.  
**Tags:** `Pedido de Certidão`, `Custas`, `Tabela de Custas`, `Cálculo`, `Emolumentos`

### Intenções de Busca & Dúvidas Frequentes
- calcular o valor da certidão
- Como o sistema calcula o total a pagar pela certidão?
- Como eu adiciono os itens da tabela de custas no pedido?
- como adicionar as custas no pedido
- Onde eu coloco o valor a ser cobrado pela certidão?
- lançar emolumentos da certidão

### Procedimento / Explicação
#### Descrição:

O card de 'Custas' é utilizado para detalhar e calcular todos os valores e emolumentos relativos a um Pedido de Certidão.

#### Passo a passo:

1.  Acesse o card **Custas** em um Pedido de Certidão.

2.  **Item de custas**: Insira o código do item da tabela de custas referente ao serviço de certidão. A **Descrição** será preenchida automaticamente.

3.  **Qtd. Cálculo**: Informe a quantidade de vezes que o item será cobrado (padrão é 1).

4.  **Cálculo**: Selecione o divisor a ser aplicado ao valor do item, se houver (ex: para atos com desconto).

5.  O campo **Total** exibirá o valor calculado para o item.

6.  Utilize o **botão de adição (+)** para inserir mais itens de custas no mesmo pedido, se necessário.

7.  Utilize o **botão de exclusão (X)** para remover um item lançado incorretamente.

8.  Após lançar todas as custas, salve o pedido e prossiga para a geração do recibo.

---

---

## M-58.0 - Gerenciar Importação de Arquivos
**Objetivo:** Acessar e gerenciar o histórico de arquivos que foram importados para o sistema, permitindo filtrar por data e especialidade para localizar uma importação específica.  
**Tags:** `Administração`, `Importações de arquivos`, `Filtros`, `Arquivos`

### Intenções de Busca & Dúvidas Frequentes
- Como eu encontro um arquivo que foi importado em uma data específica?
- histórico de importações
- consultar arquivos importados
- ver logs de importação
- Para que serve a tela de 'Importações de arquivos'?
- Onde eu vejo um histórico de todos os arquivos que foram importados no sistema?

### Procedimento / Explicação
#### Descrição:

A tela de Importação de Arquivos permite visualizar e gerenciar os arquivos que foram importados no sistema. É possível utilizar diversos filtros para refinar a busca por arquivos específicos e realizar novas importações.

#### Passo a passo:

1.  Para acessar a tela, clique no menu **Administração > Importações de arquivos**.

2.  Ao carregar a página de Importação de Arquivos, utilize os campos de filtro disponíveis para realizar uma busca específica:

    *   **Data do arquivo**: Permite filtrar pela data em que o arquivo foi importado.

    *   **Período de processamento**: Permite filtrar pelo período a que o arquivo se refere.

    *   **Especialidade**: Permite filtrar pela especialidade a que o arquivo se refere.

3.  Após preencher os filtros desejados:

    *   Clique no botão **Filtrar** para aplicar a busca.

    *   Clique no botão **Limpar** para remover os filtros aplicados e retornar à visualização padrão.

4.  Para iniciar a importação de novos arquivos, clique no botão **Novo arquivo**.

---

---

