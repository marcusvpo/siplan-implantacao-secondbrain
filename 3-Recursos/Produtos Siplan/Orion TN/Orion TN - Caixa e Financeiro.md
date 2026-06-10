---
tipo: Recurso
area: Produtos Siplan
tags:
  - #orion
  - #orion_orion_tn
  - #orion_tn_-_caixa_e_financeiro
status_atual: #ativo
---
# Orion TN - Caixa e Financeiro

Este recurso detalha os procedimentos, rotinas e manuais operacionais do sistema **Orion TN** para a área de **Caixa e Financeiro**.

## M-1.0 - Consultar e Gerenciar Mensalistas Existentes
**Objetivo:** Acessar, filtrar e executar ações como editar, inativar e bloquear mensalistas já cadastrados no sistema.  
**Tags:** `Mensalistas`, `Administração`, `Filtro`, `Busca`, `Visualizar`, `Editar`, `Inativar`, `Bloquear`

### Intenções de Busca & Dúvidas Frequentes
- Preciso bloquear um mensalista por falta de pagamento, como faço?
- procurar mensalista
- editar cadastro de mensalista
- Onde eu edito as informações de um cliente mensalista que já está cadastrado?
- Como eu encontro o cadastro de um mensalista específico?
- inativar um mensalista
- consultar cliente mensalista
- buscar mensalista
- bloquear mensalista
- Qual a diferença entre inativar e bloquear um mensalista?

### Procedimento / Explicação
#### Descrição:

A tela de Mensalistas permite a visualização e gerenciamento dos cadastros de mensalistas (Pessoa Física e Pessoa Jurídica) no sistema, com opções de filtro e ações diretas sobre os registros existentes.

#### Passo a passo:

1.  Para acessar a tela de mensalistas, clique no menu **Administração > Mensalistas**.

2.  Na página **Mensalistas**, serão automaticamente filtrados 20 dos mensalistas cadastrados (10 Pessoa Física e 10 Pessoa Jurídica).

3.  Para encontrar outros mensalistas, utilize os campos de busca disponíveis:

    * **Pesquisar por mensalista**: Para buscar um mensalista específico.

    * **Inativos**: Para buscar mensalistas que estão inativos.

    * **Documento**: Para selecionar o tipo de documento (CNPJ ou CPF) para a busca.

    * **Número**: Para digitar o número do documento selecionado no campo **Documento**.

    * **Rótulos**: Para realizar buscas detalhadas utilizando um ou vários rótulos inseridos no cadastro do mensalista.

4.  Após preencher as informações de filtro, pressione a tecla **Enter** ou clique no botão **Filtrar**.

5.  Para limpar os campos de busca preenchidos, clique no botão **Limpar**.

6.  A partir da listagem de mensalistas, é possível executar as seguintes ações:

    * **Visualizar**: Para ver os dados cadastrados do mensalista.

    * **Editar**: Para modificar as informações do mensalista.

    * **Inativar**: Para desativar o cadastro do mensalista.

    * **Bloquear**: Para bloquear o mensalista, impedindo seu uso em serviços, mas mantendo o cadastro ativo.

    * **IMPORTANTE:** Caso o mensalista esteja **Inativado**, não será possível utilizá-lo para apontar serviços.

    * **IMPORTANTE:** Um mensalista **Bloqueado** terá seu cadastro ativo, mas qualquer tentativa de efetuar um serviço com sua conta resultará em uma mensagem de bloqueio e o serviço não será permitido.

---

---

## D-1.1 - Acessar o Módulo Orion Caixa
**Objetivo:** Acessar o módulo Orion Caixa através do ORION TN e visualizar os menus disponíveis conforme o perfil do usuário.  
**Tags:** `acesso`, `orion`, `caixa`, `módulo`

### Intenções de Busca & Dúvidas Frequentes
- Onde fico o módulo de caixa no ORION TN?
- entrar no caixa
- Como acesso o módulo Orion Caixa?
- Como entro no módulo Orion Caixa?
- abrir o módulo de caixa
- acessar orion caixa

### Procedimento / Explicação
#### Descrição:

O módulo Orion Caixa é um dos módulos disponíveis no ORION TN. Após acessar o sistema, você visualizará os módulos liberados para seu perfil.

#### Passo a passo:

1. Acesse o **link do ORION TN** conforme seu acesso.

2. O sistema exibirá os **módulos liberados para seu perfil**.

3. Localize e clique em **Orion Caixa** para abrir o módulo.

4. Você visualizará o **menu principal** com as opções disponíveis.

* **Observação Importante:** O módulo possui um visual limpo, intuitivo e de fácil utilização, similar aos módulos ORION PRO e ORION Estoque.

---

---

## D-1.12 - Cadastrar Conta Bancária para Conciliação
**Objetivo:** Registrar dados bancários do cliente para importação automática de extratos OFX.  
**Tags:** `conciliação`, `conta bancária`, `extrato`, `configuração`

### Intenções de Busca & Dúvidas Frequentes
- adicionar conta bancária
- Onde configuro a conta bancária no sistema?
- configurar conta para conciliação
- Como importar extrato bancário?
- registrar dados bancários
- Como cadastro uma conta bancária para conciliação?

### Procedimento / Explicação
#### Descrição:

O cadastro de conta bancária permite a importação de extratos bancários para conciliação automática.

#### Passo a passo:

1. Acesse **Configurações > Conciliação Bancária**.

2. Preencha os seguintes dados do cliente:

   * **Conta bancária**

   * **Endereço**

   * **Razão social**

   * **CNPJ**

3. Salve os dados cadastrados.

* **Observação Importante:** Estes dados são essenciais para importação correta de extratos bancários em formato OFX.

---

---

## D-1.4 - Cadastrar Formas de Pagamento
**Objetivo:** Registrar todas as formas de pagamento que serão utilizadas no caixa, incluindo integração com Parcela Express.  
**Tags:** `pagamento`, `forma de pagamento`, `cadastro`, `configuração`

### Intenções de Busca & Dúvidas Frequentes
- Onde adiciono as formas de pagamento no caixa?
- adicionar forma de pagamento
- Como cadastro uma nova forma de pagamento?
- configurar tipos de pagamento
- criar método de pagamento
- Como integrar Parcela Express ao caixa?
- Como configurar o Pix Parcela como forma de pagamento?

### Procedimento / Explicação
#### Descrição:

As formas de pagamento definem os métodos pelos quais os clientes podem efetuar pagamentos. O sistema suporta integração com Parcela Express para diversos tipos de pagamento.

#### Passo a passo:

1. Acesse **Configurações > Cadastros Auxiliares > Forma de Pagamento**.

2. O sistema abrirá um **campo de filtro** para localizar formas já cadastradas.

3. Para adicionar uma nova forma, clique em **Adicionar**.

4. Preencha a **descrição** da forma de pagamento.

5. Preencha a **sigla** (exemplo: TE para "Teste").

6. O **código** é opcional.

7. Selecione os campos adicionais conforme necessário:

   * Marque **Forma de Pagamento para Serviço Interno** se for uso exclusivamente interno.

   * Selecione o **Provedor de Pagamento** se for integração Parcela Express.

   * Marque **Exigir Dados Bancários** se a operação exigir dados bancários.

   * Marque **Forma de Pagamento Padrão** se for o método padrão do sistema.

   * Marque **Dados Mensalistas** se for para serviços de mensalista.

8. Clique em **Conclusão** para cadastrar a forma de pagamento.

* **Observação Importante:** O sistema permite cadastro ilimitado de formas de pagamento, incluindo Pix Parcela, Transferência Parcela e todos os tipos de integração Parcela Express. Relatórios específicos do provedor estarão disponíveis após configuração.

---

---

## M-2.0 - Criar um Novo Cadastro de Mensalista
**Objetivo:** Realizar o cadastro completo de um novo mensalista, configurando seus dados, plano de pagamento (pré ou pós-pago), descontos, e-mails para extrato e dias de fechamento.  
**Tags:** `Mensalistas`, `Cadastro`, `Adicionar`, `Novo`, `Pessoa Física`, `Pessoa Jurídica`, `Configurações`, `Plano`, `Desconto`, `Extrato`, `Rótulos`, `Anexos`

### Intenções de Busca & Dúvidas Frequentes
- configurar plano pré-pago
- criar conta de mensalista
- definir dia de fechamento
- adicionar cliente de faturamento
- É possível cadastrar um dia de fechamento específico para a fatura de um mensalista?
- Como eu cadastro um novo mensalista no sistema?
- Onde eu defino se um mensalista será pré-pago ou pós-pago?
- Como eu adiciono o e-mail para envio de extrato no cadastro de um novo mensalista?
- cadastrar novo mensalista

### Procedimento / Explicação
#### Descrição:

Esta rotina permite o cadastro detalhado de novos mensalistas, sejam eles Pessoa Física ou Pessoa Jurídica, com diversas opções de configuração e anexos de documentos.

#### Passo a passo:

1.  Para acessar a tela de cadastro de mensalistas, clique no menu **Administração > Mensalistas**.

2.  Na tela de **Mensalistas**, clique no botão **Adicionar**.

3.  Na tela de **Cadastro de mensalista**, preencha as informações nas seguintes seções:

    * **Dados cadastrais**:

        * Preencha os dados cadastrais de **Pessoa Física** ou **Pessoa Jurídica**.

        * Utilize o campo **Tipo de pessoa** para definir o tipo de pessoa. Os campos exibidos serão atualizados conforme a seleção.

    * **Configurações**: Aplique configurações personalizadas para o mensalista.

        1.  **Plano**: Selecione entre **Pós-pago** e **Pré-pago**.

            * **Pós-pago**: Os serviços serão realizados e o pagamento ocorrerá posteriormente, conforme o fechamento.

            * **Pré-pago**: Os serviços só serão realizados if o mensalista tiver crédito disponível. Caso contrário, o sistema alertará sobre a falta de crédito e impedirá a realização do serviço.

        2.  **Desconto (%)**: Insira o percentual de desconto a ser aplicado sobre o valor total da cobrança no fechamento do mensalista.

        3.  **E-mail (envio de extrato)**: Insira os e-mails dos destinatários que receberão o extrato do mensalista.

            * **IMPORTANTE**: Para inserir múltiplos e-mails, digite o e-mail e pressione a tecla **ENTER** para adicionar o próximo.

        4.  **Dia de fechamento**: Defina o dia de fechamento do mensalista. Este campo pode ser utilizado como filtro para gerar extratos.

            * Não é permitido inserir mais de 3 dias de fechamento.

            * Para inserir mais um dia de fechamento, clique no botão **"+"**.

        5.  **Rótulos**: Crie e adicione rótulos para facilitar a busca e organização dos mensalistas (ex: "bom pagador"). É possível adicionar um ou vários rótulos.

        6.  **Observações**: Insira quaisquer observações relevantes sobre o mensalista.

    * **Arquivos anexos**: Anexe documentos ao cadastro do mensalista.

        1.  **Selecionar documentos**: Clique neste botão para inserir documentos (ex: ficha cadastral, outros documentos).

        2.  **Digitalizar**: Utilize esta opção para digitalizar documentos e anexá-los diretamente ao cadastro.

---

---

## D-2.1 - Gerar Relatório de Caixa
**Objetivo:** Visualizar movimentação do caixa em período específico, com opção de filtros por tipo de pagamento, serviço e outras dimensões.  
**Tags:** `relatório`, `caixa`, `consulta`, `analítico`, `sintético`

### Intenções de Busca & Dúvidas Frequentes
- Como fazer um relatório analítico do caixa?
- Como consultar a movimentação do caixa de hoje?
- gerar relatório de operações
- Como gerar um relatório de caixa?
- Como gerar um relatório sintético de caixa?
- extrair relatório de caixa
- consultar movimentação de caixa

### Procedimento / Explicação
#### Descrição:

O relatório de caixa oferece visualização detalhada ou simplificada das movimentações do dia ou período selecionado.

#### Passo a passo:

1. Acesse **Relatórios > Relatório de Caixa**.

2. Selecione o **tipo de caixa**:

   * **Firmas** - Para serviços de cartório em firmas

   * **Notas** - Para serviços de notas

3. Selecione o **tipo de relatório**:

   * **Analítico** - Detalhado com todos os registros

   * **Sintético** - Resumido com totalizações

4. Configure os **filtros** opcionais:

   * **Data** - Período desejado

   * **Forma de Pagamento** - Filtrar por método específico

   * **Tipo de Serviço** - Filtrar por serviço específico

   * **Caixa** - Selecionar caixa específico

5. Deixe os filtros em branco para visualizar todos os registros.

6. Clique em **Gerar Relatório**.

7. O sistema exibirá a movimentação com:

   * Serviços realizados

   * Itens utilizados

   * Total geral do período

* **Observação Importante:** Você pode fazer o fechamento de caixa diretamente através deste relatório se desejar.

---

---

## D-2.2 - Gerar Relatório de Fechamento de Caixa
**Objetivo:** Criar relatório consolidado para conferência e encerramento formal do caixa.  
**Tags:** `fechamento`, `relatório`, `encerramento`, `conferência`

### Intenções de Busca & Dúvidas Frequentes
- conferir e fechar caixa
- Como gerar um relatório de fechamento de caixa?
- gerar fechamento de caixa
- Como conferir o caixa para fazer fechamento?
- Como unificar fechamento de firmas e notas?
- relatório de encerramento

### Procedimento / Explicação
#### Descrição:

O relatório de fechamento consolida todas as movimentações para conferência final e encerramento do caixa.

#### Passo a passo:

1. Acesse **Relatórios > Relatório de Caixa > Fechamento de Caixa**.

2. Marque **Unificar Fechamento** se desejar trazer firmas e notas juntas.

3. Selecione o **responsável** (usuário que fez as operações).

4. Clique em **Impressão** para imprimir o relatório de conferência.

5. Analise os dados:

   * Serviços de notas

   * Serviços de firmas

   * Valores de abertura

   * Totais por tipo de operação

6. Se tudo estiver correto, clique em **Encerrar Caixa**.

7. O sistema perguntará confirmação - clique **Confirmar**.

8. O caixa será encerrado e não aceitará mais operações.

* **Observação Importante:** Para realizar novas operações após fechamento, é necessário fazer uma nova abertura de caixa.

---

---

## D-2.4 - Gerar Relatório de Provedor de Pagamentos
**Objetivo:** Visualizar todas as operações realizadas através da integração com o provedor de pagamentos.  
**Tags:** `provedor`, `parcela express`, `relatório`, `integração`

### Intenções de Busca & Dúvidas Frequentes
- relatório de parcela express
- consultar operações do provedor
- gerar relatório de integração
- Como gerar um relatório de Parcela Express?
- Onde visualizo transações de Parcela Express?
- Como consultar todas as operações do provedor?

### Procedimento / Explicação
#### Descrição:

Relatório específico para operações realizadas através da integração com provedor de pagamentos (exemplo: Parcela Express).

#### Passo a passo:

1. Acesse **Relatórios > Provedor de Pagamentos**.

2. Configure os **filtros**:

   * **Período** - Selecione o intervalo desejado (exemplo: fechar um mês)

   * **Forma de Pagamento** - Todas ou específica

   * **Status** - Todos ou status específico

   * **Usuário** - Todos ou usuário específico

3. Clique em **Impressão** para gerar relatório.

4. O sistema exibirá todas as transações do provedor.

* **Observação Importante:** Este relatório só exibirá dados se houver integração ativa com o provedor de pagamentos.

---

---

## R-3.0 - Consultar Pedidos em Aberto Sem Pagamento no Caixa
**Objetivo:** Identificar e gerenciar serviços de balcão que foram iniciados mas ainda não tiveram o pagamento processado pelo caixa, para evitar pendências financeiras.  
**Tags:** `Firmas`, `Consultas`, `Pedidos`, `Financeiro`, `Caixa`, `Pagamentos`

### Intenções de Busca & Dúvidas Frequentes
- pedidos pendentes
- Como eu vejo os pedidos do balcão que ainda não foram pagos no caixa?
- verificar pagamentos
- Preciso finalizar o pagamento de um pedido antigo que ficou em aberto, como eu acho ele?
- Como consultar pedidos com status 'Iniciado'?
- pedidos não pagos
- firmas sem pagamento
- relatório de pedidos abertos
- Onde eu tiro um relatório de todos os serviços que estão aguardando pagamento?
- consultar pedidos aguardando pagamento

### Procedimento / Explicação
#### Passo a passo para consultar:

1.  Acesse o menu **Firmas > Consultas > Reconhecimento de Firmas**.

2.  Utilize os filtros de período e, no campo de status, selecione **"Aguardando Pagamento"** e/ou **"Iniciado"**.

3.  O sistema listará todos os pedidos em aberto que correspondem aos filtros.

4.  Para cada pedido listado, é possível abrir, realizar o pagamento no caixa e finalizar o pedido. O pedido só é encaminhado ao Livro Caixa Web após o pagamento.

---

---

## M-3.0 - Consulta e Impressão de Extrato de Mensalistas
**Objetivo:** Consultar e imprimir o extrato detalhado de serviços realizados por um mensalista, aplicando filtros por período ou mês de referência.  
**Tags:** `Mensalistas`, `Extrato`, `Administração`, `Filtro`, `Período`, `Impressão`, `Serviços`

### Intenções de Busca & Dúvidas Frequentes
- consultar cobrança de mensalista
- tirar extrato de mensalista
- Onde eu consulto todos os serviços realizados por um mensalista em um determinado mês?
- ver serviços de mensalista
- Preciso imprimir o extrato de um cliente mensalista, qual a rotina?
- Como eu filtro os serviços de um mensalista pela sua data de fechamento cadastrada?
- imprimir relatório de faturamento
- gerar extrato de faturamento
- Como eu gero o extrato de um mensalista para um período específico?

### Procedimento / Explicação
#### Descrição:

A tela de Extrato de Mensalistas permite pesquisar e visualizar os serviços realizados por mensalistas, aplicando filtros por mensalista, período, mês de referência e data de fechamento, além de oferecer opções de impressão.

#### Passo a passo:

1.  Para acessar a tela de **Extrato de mensalistas**, clique no menu **Administração > Mensalistas > Extrato**.

2.  Na tela de **Extrato de mensalistas**, a pesquisa pode ser realizada utilizando os seguintes filtros:

    1.  **Pesquisar por mensalista**: Para buscar um mensalista específico.

    2.  **Período**: Para realizar uma busca por um intervalo de datas.

    3.  **Mês de referência**: Para buscar todos os serviços realizados em um mês específico (Ex: "Buscar todos os serviços realizados no mês de janeiro").

    4.  **Fechamento**: Para filtrar utilizando a data de fechamento configurada no cadastro do mensalista.

3.  Após preencher as informações para realizar a busca, você pode optar pelas seguintes ações:

    1.  **Limpar**: Clique para limpar os campos preenchidos para a busca.

    2.  **Imprimir**: Clique para imprimir a listagem baseada no resultado da pesquisa.

    3.  **Filtrar**: Clique para aplicar o filtro baseado nos campos que foram preenchidos.

4.  A partir da tela de extrato de mensalistas, também é possível imprimir o extrato com todos os serviços realizados pelo mensalista dentro do período solicitado.

5.  Ao final da sua pesquisa, clique no botão **Voltar** para retornar para a página inicial.

---

---

## D-3.101 - Fazer Abertura de Caixa
**Objetivo:** Abrir o caixa para iniciar as operações do dia, informando o valor inicial e responsável.  
**Tags:** `abertura`, `caixa`, `troco`, `operação`

### Intenções de Busca & Dúvidas Frequentes
- começar operações
- Quem é responsável pela abertura do caixa?
- Como abrir caixa sem valor inicial?
- abrir caixa
- Como abrir o caixa?
- iniciar caixa
- Como informar o valor de abertura?

### Procedimento / Explicação
#### Descrição:

A abertura de caixa é a operação inicial que permite começar a registrar pagamentos e operações financeiras.

#### Passo a passo:

1. Acesse **Administração > Controle de Caixa > Abertura de Caixa**.

2. Se o caixa já estiver aberto, o sistema exibirá mensagem informando.

3. Para fazer nova abertura, primeiro **encerre o caixa atual**.

4. Na tela de abertura, preencha:

   * **Valor inicial** - O dinheiro com que o caixa começa

   * **Valor de cheques** (opcional)

   * **Responsável** - Usuário responsável pela abertura

   * **Observação** (opcional)

5. Clique em **Abrir Caixa**.

6. O caixa agora está disponível para operações.

* **Observação Importante:** Se parametrizado como "Abertura Sem Troco", é possível abrir caixa com saldo zerado. Caso contrário, é obrigatório informar um valor.

---

---

## D-3.14 - Fazer Orçamento Rápido
**Objetivo:** Fazer cálculo rápido de valores de serviço para informar cliente (ITBI, registro, total).  
**Tags:** `orçamento`, `rápido`, `cálculo`, `estimativa`

### Intenções de Busca & Dúvidas Frequentes
- Como saber o valor total de uma escritura?
- Como calcular ITBI?
- estimar costo
- calcular valor de serviço
- fazer orçamento simples
- Como fazer um orçamento?

### Procedimento / Explicação
#### Descrição:

Orçamento rápido é cálculo simples sem registro, ideal para informações ao cliente por telefone.

#### Passo a passo:

1. Acesse **Notas > Orçamento > Rápido**.

2. Preencha:

   * **Tipo de Serviço:** Selecione (ex: Compra e Venda)

   * **Valor Base de Cálculo:** Valor do imóvel/serviço

3. O sistema calcula automaticamente:

   * **ITBI**

   * **Registro de Imóveis**

   * **Valor Total**

4. Clique em **Impressão** para gerar relatório (opcional).

5. Clique em **Voltar** para nova busca.

* **Observação Importante:** Orçamento rápido não salva registro. Usar para informações telefônicas. Para conversão em protocolo, usar orçamento completo.

---

---

## D-3.15 - Fazer Orçamento Completo
**Objetivo:** Fazer orçamento detalhado com múltiplos campos, convertível em protocolo, com envio por WhatsApp e e-mail.  
**Tags:** `orçamento`, `completo`, `detalhado`, `protocolo`

### Intenções de Busca & Dúvidas Frequentes
- Como converter orçamento em protocolo?
- criar orçamento definitivo
- gerar proposta
- Como fazer um orçamento que vira protocolo?
- Como enviar orçamento por WhatsApp?
- fazer orçamento para cliente

### Procedimento / Explicação
#### Descrição:

Orçamento completo é detalhado, permite envio ao cliente e conversão direta em protocolo.

#### Passo a passo:

1. Acesse **Notas > Orçamento > Completo**.

2. Preencha:

   * **Solicitante:** Nome do cliente

   * **E-mail:** Para envio de orçamento

   * **Endereço:** Opcional

   * **Tipo de Cálculo:** Selecione

   * **Valor:** Base de cálculo

3. Clique em **Salvar**.

4. O sistema habilita opções:

   * **Enviar por WhatsApp**

   * **Enviar por E-mail** (se e-mail preenchido)

   * **Impressão** do orçamento

   * **Voltar**

   * **Conclusão** (fechar orçamento)

   * **Reutilizar para Protocolo**

5. Para **converter em protocolo**, clique em **Reutilizar para Protocolo**.

6. O sistema pergunta confirmação.

7. Clique em **Sim**.

8. **Protocolo é criado automaticamente** com número novo.

#### Protocolo Criado:

- Todas as informações do orçamento são trazidas

- Reduz retrabalho de preenchimento

* **Observação Importante:** Orçamento completo economiza tempo ao converter em protocolo. Cliente pode revisar antes de confirmar.

---

---

## D-3.2 - Fazer Suprimento de Caixa
**Objetivo:** Adicionar dinheiro ao caixa durante o dia para aumento de troco ou reposição.  
**Tags:** `suprimento`, `adição`, `dinheiro`, `operação`

### Intenções de Busca & Dúvidas Frequentes
- Como adicionar dinheiro ao caixa?
- fazer reposição
- alimentar caixa
- Como fazer reposição de troco?
- adicionar dinheiro ao caixa
- Onde faço o lançamento de suprimento?

### Procedimento / Explicação
#### Descrição:

O suprimento permite adicionar valores ao caixa sem que sejam registrados como receita, apenas como movimentação interna.

#### Passo a passo:

1. Acesse **Administração > Controle de Caixa > Suprimento e Sangria**.

2. Clique em **Suprimento**.

3. Preencha o **valor** que está sendo adicionado.

4. Preencha a **descrição** (exemplo: "Troco", "Reposição").

5. Clique em **Concluir**.

6. O valor será adicionado ao caixa.

* **Observação Importante:** Suprimento não é receita, apenas movimentação interna de dinheiro.

---

---

## D-3.301 - Fazer Sangria de Caixa
**Objetivo:** Retirar dinheiro do caixa durante o dia por motivo de despesa ou segurança.  
**Tags:** `sangria`, `retirada`, `operação`, `dinheiro`

### Intenções de Busca & Dúvidas Frequentes
- fazer retirada do caixa
- Como retirar dinheiro do caixa?
- fazer sangria
- retirar dinheiro
- Como registrar uma retirada?
- Onde faço a sangria de caixa?

### Procedimento / Explicação
#### Descrição:

A sangria é a retirada de valores do caixa registrada como despesa ou saída.

#### Passo a passo:

1. Acesse **Administração > Controle de Caixa > Suprimento e Sangria**.

2. Clique em **Sangria**.

3. Preencha o **valor** que está sendo retirado.

4. Selecione o **tipo de saída** (deve estar previamente cadastrado).

   * Se nenhum tipo de saída estiver configurado, será obrigatório cadastrar um antes de prosseguir.

5. Clique em **Concluir**.

6. O valor será retirado do caixa e registrado como despesa.

* **Observação Importante:** É obrigatório configurar tipos de saída antes de fazer sangria. A retirada será automaticamente vinculada ao livro caixa conforme tipo configurado.

---

---

## D-3.35 - Visualizar Movimentação Financeira do Protocolo
**Objetivo:** Visualizar todos os lançamentos financeiros (pagamentos, depósitos) do protocolo.  
**Tags:** `protocolo`, `financeiro`, `pagamento`, `saldo`

### Intenções de Busca & Dúvidas Frequentes
- Qual é o saldo do protocolo?
- consultar pagamentos
- Como lançar pagamento?
- ver saldo do protocolo
- visualizar movimentação
- Como ver se o cliente pagou?

### Procedimento / Explicação
#### Descrição:

Seção que mostra toda movimentação financeira do protocolo em tempo real.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Movimentação Financeira**.

2. Sistema exibe:

   * **Lançamentos realizados**

   * **Saldo atual**

   * **Data dos pagamentos**

3. Opcionalmente, clique em **Lançar** para adicionar entrada/saída manual.

* **Observação Importante:** Integração automática com Caixa. Toda baixa de pagamento aparece aqui.

---

---

## D-3.4 - Fazer Transferência de Caixa
**Objetivo:** Transferir dinheiro de um caixa para outro dentro do mesmo estabelecimento.  
**Tags:** `transferência`, `outro caixa`, `operação`, `retirada`

### Intenções de Busca & Dúvidas Frequentes
- Como registrar movimentação entre caixas?
- Onde faço a transferência entre caixas?
- transferir para outro caixa
- Como transferir dinheiro para outro caixa?
- fazer deslocamento de caixa
- passar dinheiro entre caixas

### Procedimento / Explicação
#### Descrição:

A transferência permite deslocar valores entre caixas diferentes dentro do mesmo guichê ou estabelecimento.

#### Passo a passo:

1. Acesse **Administração > Controle de Caixa > Suprimento e Sangria**.

2. Clique em **Transferência de Caixa**.

3. Preencha o **valor** a transferir.

4. Selecione o **caixa destino** para onde o dinheiro será transferido.

5. Clique em **Concluir**.

6. O valor será retirado do caixa atual e adicionado ao caixa destino.

* **Observação Importante:** A transferência é uma movimentação interna, não afetando o saldo consolidado do estabelecimento.

---

---

## D-3.47 - Consultar Movimentação Financeira de Protocolos
**Objetivo:** Visualizar protocolos com saldos pendentes (positivos ou negativos) para cobrança e controle.  
**Tags:** `consulta`, `financeiro`, `saldo`, `a receber`

### Intenções de Busca & Dúvidas Frequentes
- Como ver protocolos com depósito?
- ver saldo de protocolo
- Como saber quais protocolos têm saldo a receber?
- ver movimentação
- consultar a receber

### Procedimento / Explicação
#### Descrição:

Consulta de movimentação financeira mostra saldo de cada protocolo em vermelho (negativo/a receber) ou verde (saldo/depósito).

#### Passo a passo:

1. Acesse **Notas > Consultas > Movimentação Financeira Protocolo**.

2. O sistema exibe **protocolos com saldos**.

3. **Cores indicam**:

   * **Vermelho:** A receber do cliente

   * **Verde:** Depósito prévio ou saldo pago

4. Visualize:

   * **Protocolo**

   * **Saldo**

   * **Data**

5. Use para **cobrança** ou **controle de pré-pagamentos**.

* **Observação Importante:** Integração automática com caixa. Saldos em tempo real.

---

---

## D-3.5 - Realizar Pagamento de Certidões
**Objetivo:** Efetuar pagamento de certidões registradas, processando a baixa financeira e recebimento.  
**Tags:** `pagamento`, `certidão`, `baixa`, `operação`

### Intenções de Busca & Dúvidas Frequentes
- pagar certidão
- Como processar o recebimento de certidão?
- fazer baixa de certidão
- receber pagamento de certidão
- Como realizar pagamento de uma certidão?
- Onde faço a baixa de certidão?

### Procedimento / Explicação
#### Descrição:

Pagamento de certidões envolve buscar a certidão emitida, receber o pagamento e registrar a baixa no sistema.

#### Passo a passo:

1. Acesse **Administração > Menu de Pagamentos**.

2. Selecione **Certidões e Serviços**.

3. Clique em **Localizar Certidão**.

4. Preencha os **filtros** para encontrar a certidão:

   * Número da certidão

   * Período

   * Outras dimensões

5. Clique na certidão desejada para abrir.

6. O sistema carrega o **valor da certidão**.

7. Selecione a **forma de pagamento** (exemplo: dinheiro).

8. Clique para **carregar o valor**.

9. Se necessário, marque **Pagamento Retroativo** (para datas anteriores).

10. Escolha opção de **impressão de recibo** (sim ou não).

11. Clique em **Concluir Pagamento**.

12. O sistema confirma e registra a baixa automaticamente.

* **Observação Importante:** Certidões e notas seguem o mesmo processo de pagamento. A baixa é registrada automaticamente na movimentação financeira.

---

---

## D-3.53 - Fazer Lançamento de Depósito Prévio
**Objetivo:** Registrar depósito prévio do cliente na tela de caixa do protocolo.  
**Tags:** `protocolo`, `pagamento`, `depósito`, `caixa`

### Intenções de Busca & Dúvidas Frequentes
- Como registrar depósito?
- depositar valor
- fazer adiantamento
- lançar pré-pagamento
- Como fazer adiantamento?

### Procedimento / Explicação
#### Descrição:

Depósito prévio registra adiantamento de cliente contra futuros serviços.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Caixa** (botão de caixa).

2. O sistema abre **tela de lançamento**.

3. Preencha:

   * **Tipo de Lançamento:** Depósito Prévio

   * **Valor:** Valor do adiantamento

   * **Forma de Pagamento:** Como foi pago

   * **Observação:** Notas

4. Clique em **Salvar** ou **Confirmar**.

5. Movimento fica **registrado**.

#### Verificação:

- Acesse **Movimentação Financeira** para confirmar saldo em verde.

* **Observação Importante:** Depósito fica em verde (crédito). Quando protocolo é finalizado, saldo é abatido.

---

---

## D-3.54 - Fazer Pagamento do Protocolo no Caixa
**Objetivo:** Dar baixa de pagamento do protocolo registrando recebimento de cliente.  
**Tags:** `protocolo`, `pagamento`, `caixa`, `baixa`

### Intenções de Busca & Dúvidas Frequentes
- Como dar baixa?
- registrar recebimento
- fazer baixa
- Como registrar pagamento?
- receber pagamento

### Procedimento / Explicação
#### Descrição:

Pagamento no caixa do protocolo registra recebimento e zera saldo.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Caixa**.

2. Sistema exibe:

   * **Saldo devido** (vermelho)

   * **Opção de pagar**

3. Clique em **Lançar Pagamento**.

4. Configure:

   * **Valor:** Valor a receber (pode parcelar)

   * **Forma de Pagamento:** Dinheiro, Cheque, PIX, etc.

   * **Data:** Data do recebimento

5. Clique em **Confirmar**.

6. Sistema pergunta se **quer imprimir recibo**.

7. Clique sim ou não.

8. **Pagamento é registrado** e movimentação aparece em Movimentação Financeira.

* **Observação Importante:** Se cliente paga em múltiplas formas, registre cada uma. Sistema calcula o saldo automaticamente.

---

---

## D-3.58 - Registrar Indicação de Mensalista
**Objetivo:** Registrar pessoa que indicou novo mensalista para ganhar comissão sobre ele.  
**Tags:** `mensalista`, `indicação`, `comissão`, `parceria`

### Intenções de Busca & Dúvidas Frequentes
- registrar indicador
- Como ganhar comissão de mensalista?
- indicar mensalista
- Como indicar mensalista?
- ganhar comissão

### Procedimento / Explicação
#### Descrição:

Indicação de mensalista permite que um escrevente ganhe comissão sobre cliente indicado.

#### Passo a passo:

1. Acesse **Administração > Indicação de Mensalistas**.

2. Clique em **Adicionar** indicação.

3. Configure:

   * **Indicador:** Quem indicou (escrevente)

   * **Mensalista:** Cliente novo

   * **Percentual de Comissão:** % sobre serviços

4. Clique em **Salvar**.

#### Apuração:

- Sistema **calcula comissão** automaticamente sobre serviços do mensalista.

- Indicador recebe **percentual configurado** como comissão.

* **Observação Importante:** Incentiva prospecção de novos clientes. Comissão é automática conforme serviços.

---

---

## D-3.6 - Realizar Pagamento de Notas
**Objetivo:** Efetuar pagamento de protocolos e notas registradas, processando valores de ITBI, emolumentos e taxas.  
**Tags:** `pagamento`, `nota`, `protocolo`, `baixa`

### Intenções de Busca & Dúvidas Frequentes
- Como pagar um protocolo?
- pagar nota
- Como realizar pagamento de uma nota?
- fazer baixa de protocolo
- Onde faço a baixa de nota?
- receber pagamento de nota
- Como registrar pagamento com parcelamento?

### Procedimento / Explicação
#### Descrição:

Pagamento de notas envolve buscar o protocolo, processar valores de ITBI e emolumentos, e registrar a baixa financeira.

#### Passo a passo:

1. Acesse **Administração > Menu de Pagamentos**.

2. Selecione **Notas**.

3. Clique em **Localizar Protocolo**.

4. Preencha o **número do protocolo** desejado.

5. O sistema carrega as informações:

---

---

## D-3.60 - Gerar Recolhimento Diário
**Objetivo:** Gerar relatório detalhado diário com registro protocolo, livro, folha e atos.  
**Tags:** `relatório`, `recolhimento`, `diário`, `detalhado`

### Intenções de Busca & Dúvidas Frequentes
- Como gerar recolhimento diário?
- preparar relatório
- Como gerar recolhimento detalhado?
- gerar relatório diário
- fazer recolhimento detalhado

### Procedimento / Explicação
#### Descrição:

Recolhimento diário é mais detalhado que PEX, mostrando protocolo a protocolo.

#### Passo a passo:

1. Acesse **Relatórios > Recolhimento Diário**.

2. Selecione **período** (pode ser um dia).

3. Sistema traz **detalhes**:

   * **Protocolo** (ou ato)

   * **Livro** consumido

   * **Folha** consumida

   * **Tipo de ato**

   * **Valor** do ato

   * **Total**

4. Visualize **protocolo a protocolo**.

5. Clique em **Imprimir** para gerar.

* **Observação Importante:** Mais detalhado que PEX. Cada protocolo aparece em linha separada. Útil para conferência.

---

---

## D-3.61 - Gerar Recolhimento Resumido
**Objetivo:** Gerar relatório resumido de recolhimento com totalizações.  
**Tags:** `relatório`, `recolhimento`, `resumido`, `sintético`

### Intenções de Busca & Dúvidas Frequentes
- gerar resumo
- Como gerar recolhimento simples?
- fazer recolhimento simples
- Como gerar resumo de recolhimento?

### Procedimento / Explicação
#### Descrição:

Recolhimento resumido mostra apenas totalizações por tipo de serviço.

#### Passo a passo:

1. Acesse **Relatórios > Recolhimento Resumido**.

2. Selecione **período** desejado.

3. Sistema traz **totalizações**:

   * **Total Firmas**

   * **Total Notas**

   * **Total Certidões**

   * **Total Geral**

4. Clique em **Imprimir**.

* **Observação Importante:** Versão sintética de recolhimento. Ótima para visão rápida de faturamento.

---

---

## D-3.63 - Cadastrar Mensalista
**Objetivo:** Registrar cliente mensalista com informações de boleto, WhatsApp, filiais e configurações.  
**Tags:** `mensalista`, `cliente`, `cadastro`, `contrato`

### Intenções de Busca & Dúvidas Frequentes
- criar cliente
- Como enviar por WhatsApp?
- adicionar mensalista
- Como ativar boleto?
- Como cadastrar mensalista?
- registrar contrato

### Procedimento / Explicação
#### Descrição:

Mensalista é cliente com serviço contínuo. Pode ter boleto, fatura por WhatsApp, e múltiplas filiais.

#### Passo a passo:

1. Acesse **Administração > Mensalistas > Cadastro**.

2. Clique em **Buscar** para visualizar existentes.

3. Para **adicionar novo**, clique em **Adicionar**.

4. Preencha:

   * **Nome/Razão Social** do cliente

   * **Documento**

   * **Endereço**

   * **E-mail** (opcional)

   * **Configurações**:

     - **Usar Boleto:** Ativar faturamento com boleto

     - **Usar WhatsApp:** Enviar fatura por WhatsApp

     - **Cobrar Adiantado/Atrasado:** Pré-pago ou pós-pago

5. Clique em **Salvar**.

#### Recursos Adicionais:

- **Anexar Contrato:** Digitalizar/importar

- **Filiais:** Adicionar múltiplas unidades

- **Lançamentos Manuais:** Ajustes eventuais

- **Extrato:** Ver saldo atual do cliente

* **Observação Importante:** Mensalistas têm faturamento contínuo. Boleto e WhatsApp facilitam cobrança. Filiais permitem múltiplos endereços.

---

---

## D-3.64 - Gerar Fatura de Mensalista
**Objetivo:** Gerar fatura mensal do mensalista consolidando serviços e enviando por e-mail ou WhatsApp.  
**Tags:** `mensalista`, `fatura`, `emissão`, `cobrança`

### Intenções de Busca & Dúvidas Frequentes
- criar fatura
- Como gerar fatura?
- cobrança mensalista
- emitir boleto
- Como enviar fatura por WhatsApp?
- Como enviar boleto?

### Procedimento / Explicação
#### Descrição:

Geração de fatura consolida serviços do período e dispara envio automático.

#### Passo a passo:

1. Acesse **Administração > Mensalistas > Emissão**.

2. Selecione **período** desejado (ex: dezembro).

3. Sistema traz **mensalistas com serviços** nesse período.

4. Visualize:

   * **Nome mensalista**

   * **Serviços realizados**

   * **Total da fatura**

5. **Selecione mensalistas** a faturar.

6. Configure:

   * **Data de Vencimento:** Quando vence

7. Clique em **Gerar Faturas**.

8. Sistema gera e habilita opções:

   * **Enviar por E-mail**

   * **Enviar por WhatsApp** (com boleto)

   * **Entregar Física**

9. Selecione opção desejada.

#### Observação:

- Faturamento só funciona se houver **e-mail cadastrado** (para e-mail) ou **WhatsApp** (para WhatsApp).

* **Observação Importante:** Automatiza faturamento. Cliente recebe fatura pronta. Ideal para gestão de clientes com muitos serviços.

---

---

## D-3.65 - Importar Arquivo de Retorno de Boleto
**Objetivo:** Processar arquivo retornado pelo banco confirmando quais faturas foram pagas.  
**Tags:** `boleto`, `retorno`, `banco`, `conciliação`

### Intenções de Busca & Dúvidas Frequentes
- confirmar pagamento
- Como confirmar pagamento de boleto?
- processar boleto
- importar pagamento
- Como processar arquivo do banco?

### Procedimento / Explicação
#### Descrição:

Importação de retorno automátiza conferência de boletos pagos.

#### Passo a passo:

1. Acesse **Administração > Mensalistas > Boletos > Arquivo de Retorno**.

2. Clique em **Importar** arquivo.

3. Selecione **arquivo de retorno** do banco (formato específico).

4. Clique em **Processar**.

5. Sistema **identifica boletos pagos**.

6. Clique em **Confirmar** ou **Salvar**.

7. Faturas são **automaticamente marcadas como pagas**.

* **Observação Importante:** Economiza tempo de conferência manual. Essencial para gestão de boletos.

---

---

## D-3.66 - Fazer Manutenção de Fatura de Mensalista
**Objetivo:** Registrar pagamento, cancelar ou estornar faturas de mensalista.  
**Tags:** `mensalista`, `manutenção`, `pagamento`, `ajuste`

### Intenções de Busca & Dúvidas Frequentes
- cancelar fatura
- ajustar fatura
- Como cancelar fatura?
- Como estornar?
- dar baixa de fatura
- Como registrar pagamento?

### Procedimento / Explicação
#### Descrição:

Manutenção permite ajustes em faturas emitidas.

#### Passo a passo:

1. Acesse **Administração > Mensalistas > Manutenção**.

2. Filtre **faturas**.

3. Visualize faturas em aberto.

4. Para cada fatura, você pode:

   * **Fazer Pagamento:** Registrar recebimento

   * **Cancelar:** Anular fatura

   * **Estornar:** Reverter lançamento

5. Selecione ação desejada.

6. Configure dados.

7. Clique em **Salvar** ou **Confirmar**.

* **Observação Importante:** Permite ajustes pós-geração de fatura. Importante para correções.

---

---

## D-3.67 - Visualizar Extrato de Saldo de Mensalista
**Objetivo:** Visualizar saldo atual de cliente mensalista (crédito ou débito).  
**Tags:** `mensalista`, `extrato`, `saldo`, `consulta`

### Intenções de Busca & Dúvidas Frequentes
- ver quanto cliente deve
- consultar saldo
- visualizar extrato
- Quanto o cliente me deve?
- Como saber saldo de um mensalista?

### Procedimento / Explicação
#### Descrição:

Extrato mostra saldo corrente de cada mensalista.

#### Passo a passo:

1. Acesse **Administração > Mensalistas > Saldo**.

2. **Selecione mensalista**.

3. Sistema exibe **saldo atual**:

   * **Positivo (Verde):** Cliente tem crédito conosco

   * **Negativo (Vermelho):** Cliente deve conosco

4. Visualize **data** do saldo.

* **Observação Importante:** Visão rápida da situação financeira com cliente. Importante para negociação.

---

---

## D-3.76 - Gerar Livro de Depósito Prévio
**Objetivo:** Gerar relatório/livro de depósito prévio mostrando entradas, saídas e saldo de conta.  
**Tags:** `depósito prévio`, `livro`, `geração`, `controle`

### Intenções de Busca & Dúvidas Frequentes
- conferir depósito
- criar depósito
- Como gerar livro de depósito prévio?
- gerar livro
- Como acompanhar depósito?

### Procedimento / Explicação
#### Descrição:

Livro de depósito prévio consolida todos os movimentos (entrada, saída, conversão) de depósitos.

#### Passo a passo:

1. Acesse **Administração > Depósito Prévio** (ou submenu similar).

2. Selecione **período** (ex: novembro).

3. Configure:

   * **Rascunho:** Sem números de livro/folha (para conferência)

   * **Definitivo:** Com livro/folha (para arquivo)

4. Clique em **Gerar**.

5. Sistema exibe:

   * **Todas as entradas** (depósitos recebidos)

   * **Todas as saídas** (depósitos usados em serviços)

   * **Conversões** (depósito que virou emolumento)

   * **Saldo final** (quanto ainda está em depósito)

6. Clique em **Imprimir** para gerar documento.

#### Validação:

- Valide se saldo bate com sua conta de depósito prévio no caixa.

* **Observação Importante:** Controle de depósito prévio. Importante se você mantém conta separada para depósitos. Rascunho = teste, Definitivo = arquivo.

---

---

## M-4.0 - Lançamentos Manuais e Pesquisa de Lançamentos para Mensalistas
**Objetivo:** Realizar lançamentos financeiros manuais (crédito, débito ou serviços) na conta de um mensalista, e também pesquisar ou estornar esses lançamentos.  
**Tags:** `Mensalistas`, `Lançamentos`, `Crédito`, `Débito`, `Serviços`, `Requisição`, `Forma de Pagamento`, `Estorno`, `Pesquisa`

### Intenções de Busca & Dúvidas Frequentes
- estornar lançamento de mensalista
- Preciso fazer um débito avulso para um cliente mensalista, onde eu vou?
- pesquisar lançamentos manuais
- Onde eu pesquiso todos os lançamentos manuais feitos para um cliente específico?
- lançar crédito para mensalista
- ajuste manual na conta do mensalista
- debitar valor de mensalista
- Como eu lanço um crédito manual na conta de um mensalista?
- Cometi um erro em um lançamento manual na conta de um mensalista. Como eu faço para estornar?

### Procedimento / Explicação
#### Descrição:

A tela de Lançamentos Manuais permite registrar movimentações financeiras diretamente na conta de um mensalista, seja um crédito, um débito ou um serviço. Além disso, é possível pesquisar lançamentos já realizados e estorná-los.

#### Passo a passo para realizar um novo lançamento:

1.  Para acessar a tela de **Lançamentos Manuais**, clique no menu **Administração > Mensalistas > Lançamentos manuais**.

2.  No menu lateral da tela de lançamentos, selecione a opção para realizar um novo lançamento.

3.  Selecione o **Mensalista**. Caso o mensalista possua uma filial cadastrada, o campo para seleção da filial será carregado ao lado.

4.  Na seção de lançamento, preencha os campos necessários:

    1.  **Tipo**: Defina o tipo de lançamento:

        *   **Crédito**

        *   **Débito**

        *   **Serviços**

    2.  **Requisição**: Informe o número de requisição do mensalista que será vinculado ao lançamento.

        *   *Observação:* Caso a sequência esteja parametrizada para ser gerada automaticamente, o campo será preenchido ao final do cadastro.

    3.  **Responsável**: Campo somente leitura, preenchido automaticamente com o nome do usuário logado.

    4.  **Data**: Informe a data em que o lançamento será registrado na conta do mensalista.

    5.  **Hora**: Informe o horário em que o lançamento será registrado na conta do mensalista.

    6.  **CÓD**: Para selecionar a forma de pagamento através do código. Caso não saiba o código, pressione **TAB** para avançar para o campo **"Forma de pagamento"**.

    7.  **Forma de pagamento**: Selecione uma das formas de pagamento cadastradas no sistema.

        *   *Observação:* Se a forma de pagamento exigir dados bancários (Ex: cheque), os campos correspondentes serão exibidos.

    8.  **Valor**: Defina o valor a ser debitado ou creditado na conta do mensalista.

    9.  **Descrição**: Informe uma descrição para o lançamento. Esta descrição será exibida no extrato do mensalista.

    10. Caso seja necessário informar mais de uma forma de pagamento, clique no ícone **"+"**.

5.  Para concluir o lançamento, certifique-se de que o mensalista (ou filial), o tipo de lançamento e o valor (débito, crédito ou serviço) estejam preenchidos, e clique no botão **Salvar**.

#### Passo a passo para pesquisar lançamentos:

1.  Na tela de **Lançamentos Manuais**, no menu lateral, clique em **Pesquisar**.

2.  Utilize os filtros disponíveis para refinar sua busca:

    1.  **Pesquisar por mensalista**: Informe o mensalista desejado. É necessário informar ao menos um mensalista ou filial para aplicar o filtro.

    2.  **Tipo**: Filtre por **Crédito**, **Débito** ou **Serviços**.

    3.  **Período**: Informe o período desejado para a pesquisa. É necessário informar um período para realizar a pesquisa.

    4.  **Responsável**: Busque lançamentos por um responsável específico.

    5.  **Requisição**: Busque um lançamento por um número de requisição.

3.  Para aplicar o filtro, clique no botão **Filtrar**.

#### Passo a passo para estornar um lançamento:

1.  Após realizar uma pesquisa e obter a grid de resultados, localize o lançamento que deseja estornar.

2.  Para realizar um estorno de lançamento (crédito, débito ou serviços), clique no ícone de **"X"** correspondente ao lançamento na grid.

---

---

## M-6.0 - Cadastro de Plano de Comissão
**Objetivo:** Criar um novo plano de comissão, definindo a forma de cálculo (percentual ou valor fixo), configurando os valores por tipo de ato e associando os escreventes participantes.  
**Tags:** `Comissões`, `Planos`, `Cadastro`, `Cálculo`, `Percentual`, `Valor Fixo`, `Tabela de Custas`, `Escreventes`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu defino se a comissão de um plano será por percentual ou valor fixo?
- Como eu seleciono quais atos notariais vão gerar comissão em um novo plano?
- associar escrevente a um plano de comissão
- definir comissão por valor fixo
- Como eu crio um novo plano de comissão do zero?
- criar novo plano de comissão
- Como eu vinculo um escrevente a um plano de comissão durante o cadastro?
- configurar comissão por percentual

### Procedimento / Explicação
#### Descrição:

Esta rotina detalha o processo de criação de um novo plano de comissão, desde a definição da forma de cálculo até a atribuição de valores por item da tabela de custas e a inclusão de escreventes.

#### Passo a passo:

1.  Para acessar a tela de **Cadastro de plano de comissão**, clique no menu **Administração > Comissões > Planos**.

2.  Na tela **Planos de comissões**, clique no botão **Adicionar**.

3.  Para criar um novo plano de comissão, siga os seguintes passos:

    1.  Digite a **Descrição** do plano de comissão.

    2.  Selecione a **Forma de cálculo** que será aplicada a este plano de comissão:

        *   **Percentual**: Será aplicado um valor percentual sobre os itens selecionados.

        *   **Valor fixo**: Será aplicado um valor fixo (R\$) nos itens selecionados.

        *   *IMPORTANTE:* Não é possível configurar mais de uma forma de cálculo no mesmo plano de comissão.

4.  Configure os valores que serão aplicados em cada item da tabela de custas:

    1.  **Pesquisar por natureza**: Utilize este campo para buscar itens específicos da tabela de custas digitando sua descrição. O sistema filtrará automaticamente.

    2.  **Limpar**: Clique para limpar o conteúdo digitado no campo de pesquisa por natureza.

5.  Defina o valor da comissão a ser aplicado sobre cada item da tabela de custas:

    1.  **Aplicar nos itens selecionados**: Digite o valor de comissão que deseja aplicar.

    2.  **Seleção dos itens**: Selecione um ou vários itens da tabela de custas nos quais deseja aplicar o valor digitado.

    3.  Clique no botão **APLICAR NOS ITENS SELECIONADOS**. O valor digitado será aplicado a todos os itens que foram selecionados.

        *   **IMPORTANTE**: Caso selecione para marcar todos os itens e clique no botão **"APLICAR NOS ITENS SELECIONADOS"**, o valor será aplicado em todos os itens da tabela de custas.

6.  Após definir os valores de comissão, inclua escreventes no plano de comissão:

    *   *IMPORTANTE:* Para que o escrevente esteja visível na lista, é necessário que ele esteja selecionado como escrevente no cadastro de usuário. Não é permitido inserir um escrevente em dois ou mais planos de comissões.

    1.  Selecione um escrevente que ainda não pertence a nenhum plano de comissão.

    2.  Clique na **seta de mover para a esquerda** para inserir o escrevente no plano de comissão.

    3.  Clique na **seta de mover para a direita** para remover o escrevente do plano de comissão.

7.  Para finalizar a configuração, clique no botão **CONCLUIR**.

---

---

## R-7.0 - Gerar Orçamento Rápido
**Objetivo:** Criar um orçamento simples e rápido para serviços notariais, ideal para um atendimento de balcão ou por telefone, sem vincular a um protocolo.  
**Tags:** `Orçamento`, `Notas`, `Custas`, `Financeiro`, `Rápido`

### Intenções de Busca & Dúvidas Frequentes
- simulação de valor
- cálculo de custas rápido
- orçamento simples
- Preciso calcular umas custas de forma simples, qual a tela?
- Como eu faço um orçamento rápido para um cliente no balcão?
- Onde eu posso simular o valor de uma escritura sem ter que abrir um protocolo?
- calcular valor de escritura na hora
- orçamento expresso

### Procedimento / Explicação
#### Procedimento:

1.  Acesse o menu **Notas > Orçamento rápido** no Orion TN.

2.  Preencha os campos da tela, como nome, documento e os itens das custas.

3.  O sistema calculará o valor automaticamente.

4.  Clique em **"Gerar orçamento para impressão"** para criar um arquivo .pdf do orçamento.

---

---

## D-7.0 - Atualizar e Reenviar Receitas para o Livro Caixa Web (LCW) Manualmente
**Objetivo:** Realizar o envio manual e imediato das receitas para o Livro Caixa Web (LCW), atualizando os valores sem aguardar a rotina automática diária.  
**Tags:** `Livro Caixa Web`, `LCW`, `Integração`, `Receitas`, `Comunicação`, `Atualização`, `Configurações`, `Produtos Orion`

### Intenções de Busca & Dúvidas Frequentes
- atualizar livro caixa agora
- Como eu forço o envio das receitas para o Livro Caixa Web agora?
- sincronizar lcw
- forçar envio lcw
- O sistema envia as receitas automaticamente, mas como faço para enviar manualmente?
- comunicar livro caixa web manual
- Fiz alterações no caixa e preciso atualizar o LCW imediatamente, como faço?
- reenviar receitas manual

### Procedimento / Explicação
#### Descrição:

O OrionTN realiza o envio de receitas para o Livro Caixa Web automaticamente em horário configurado. No entanto, caso ocorram alterações durante o expediente que precisem ser refletidas imediatamente, é possível forçar essa comunicação manualmente para atualizar os valores.

#### Passo a passo:

1.  Acesse o menu **Configurações** no OrionTN.

2.  Clique no submenu **Parametrizações**.

3.  No menu lateral esquerdo, localize a seção **Produtos Orion** e selecione a opção de integração com o **Livro Caixa Web** (primeiro menu).

4.  Clique no botão **Comunicar**. O sistema fará um novo envio com os valores apurados até o momento.

5.  Após o processamento, clique em **Concluir** no final da tela para finalizar.

---

---

## R-8.0 - Gerar Orçamento Completo
**Objetivo:** Criar um orçamento detalhado e formal para serviços notariais, que pode ser salvo, enviado ao cliente e posteriormente convertido em um protocolo de serviço.  
**Tags:** `Orçamento`, `Notas`, `Custas`, `Financeiro`, `Protocolo`

### Intenções de Busca & Dúvidas Frequentes
- orçamento formal
- Onde eu gero uma proposta de orçamento para enviar por e-mail para o cliente?
- É possível transformar um orçamento que eu fiz em um serviço ativo?
- converter proposta em ato
- Como eu crio um orçamento completo que depois pode virar um protocolo?
- orçamento detalhado
- proposta de serviço
- transformar orçamento em protocolo

### Procedimento / Explicação
#### Como fazer:

1.  Acesse o menu **Notas > Orçamento completo** no Orion TN.

2.  Preencha todos os campos necessários, como espécie, natureza e itens da tabela de custas.

3.  Após preencher, clique em **"Concluir/Gerar orçamento"**.

4.  O sistema oferecerá opções para **Enviar via WhatsApp**, **Enviar por e-mail**, **Imprimir** ou **Gerar protocolo** (que transforma o orçamento em um serviço ativo).

---

---

## D-9.0 - Excluir Movimentação Financeira em Pedido de Certidão
**Objetivo:** Orientar sobre o procedimento para excluir um lançamento financeiro (pagamento ou depósito) realizado incorretamente dentro de um pedido de certidão.  
**Tags:** `Pedido de Certidão`, `Notas`, `Movimentação Financeira`, `Excluir`, `Financeiro`, `Correção`, `Estorno`

### Intenções de Busca & Dúvidas Frequentes
- apagar pagamento errado de certidão
- Lancei um pagamento errado no pedido de certidão, como excluo?
- Onde fica a opção para remover uma movimentação financeira de uma certidão?
- remover lançamento financeiro certidão
- Como faço para estornar um valor lançado na certidão?
- corrigir financeiro de pedido de certidão
- estornar lançamento de certidão
- excluir depósito de certidão

### Procedimento / Explicação
#### Descrição:

Caso um lançamento financeiro tenha sido realizado de forma errônea em um pedido de certidão, é possível excluí-lo diretamente pela tela de edição do pedido, acessando o módulo financeiro integrado.

#### Passo a passo:

1.  No sistema OrionTN, acesse o menu **Notas**, depois **Consulta** e selecione **Consulta de certidões e serviços**.

2.  Utilize os campos disponíveis para filtrar e localizar a certidão específica.

3.  Clique no botão **Editar** (ícone de um lápis) no registro da certidão.

4.  Dentro da certidão, clique no ícone de **Cifrão ($)** localizado no menu superior para abrir as opções de caixa.

5.  Role a tela até o final para visualizar todos os lançamentos financeiros vinculados.

6.  Identifique o lançamento que deseja excluir e clique no ícone **"X"**.

7.  O sistema solicitará uma confirmação; clique em **Confirmar** para finalizar o processo de exclusão.

---

---

## R-13.0 - Lançamento de Depósito Prévio
**Objetivo:** Registrar um valor adiantado (depósito prévio) em um protocolo para garantir o controle financeiro de atos com pagamentos parciais ou antecipados.  
**Tags:** `Depósito Prévio`, `Protocolos`, `Financeiro`, `Custas`, `Caixa`

### Intenções de Busca & Dúvidas Frequentes
- registrar depósito
- dar uma entrada no ato
- Onde eu lanço o sinal que a parte deixou para o ato?
- lançamento de adiantamento
- O cliente pagou uma parte, onde eu coloco esse valor?
- fazer pagamento adiantado
- livro de depósito prévio
- Como eu registro um pagamento que o cliente fez antes de assinar a escritura?
- adiantamento de custas
- deixar um sinal na escritura
- Preciso registrar um depósito prévio em um protocolo, como faço?

### Procedimento / Explicação
#### Passo a passo:

1.  Acesse o protocolo desejado em **Notas > Protocolos em aberto**.

2.  Acesse a opção **Lançamento de Depósito Prévio** através do botão de cifrão ($) no protocolo ou diretamente pelo sistema de caixa.

3.  Informe a data (o sistema sugere a data atual, mas pode ser alterada) e o valor a ser depositado.

Em atos com assinaturas em momentos distintos, o valor depositado fica registrado como "em trânsito" e só tem a saída do Livro de Depósito efetuada no momento da emissão do recibo final, garantindo a consistência do controle financeiro.

---

---

## M-16.11 - Parametrizar Faturamento
**Objetivo:** Habilitar e configurar as opções de faturamento do sistema, como a utilização de cobrança por boleto bancário e o envio do extrato juntamente com o boleto.  
**Tags:** `Configurações`, `Faturamento`, `Boleto Bancário`, `Extrato`

### Intenções de Busca & Dúvidas Frequentes
- regras de faturamento
- Onde eu configuro para que o extrato seja sempre enviado junto com o boleto bancário?
- configurar boleto
- habilitar boleto bancário
- Como eu habilito a funcionalidade de cobrança por boleto bancário para mensalistas?

### Procedimento / Explicação
#### Descrição:

Esta seção permite habilitar e configurar as funcionalidades de faturamento do sistema.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **11 - Faturamento**.

3.  Marque a opção **Utilizar cobrança por boleto bancário** para habilitar esta funcionalidade.

4.  Marque a opção **O extrato será enviado juntamente com o boleto bancário** para definir este comportamento.

---

---

## M-16.9 - Parametrizar Comissões e Mensalistas
**Objetivo:** Definir as regras de negócio para o cálculo de comissões de escreventes e para o controle de requisições de mensalistas, como a forma de pagamento e a sequência numérica.  
**Tags:** `Configurações`, `Comissões`, `Mensalistas`, `Pagamento`, `Taxa de Cálculo`, `Requisição`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu configuro se a comissão do escrevente só é creditada após o cliente pagar pelo serviço?
- Em que tela eu seleciono a taxa base para o cálculo das comissões?
- Como eu defino se a numeração da requisição de mensalista será automática ou manual?
- configurar requisição de mensalista
- forma de pagamento de comissão
- regras de comissão

### Procedimento / Explicação
#### Descrição:

Esta seção permite definir as regras financeiras para comissionamento e faturamento de mensalistas.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **9 - Comissões e mensalistas**.

3.  Em **Comissões - Configurações** (para Firmas) e **Comissões - Notas - Configurações**:

    * **Forma de pagamento**: Defina se a comissão será creditada no momento da conclusão do serviço ou apenas após o pagamento pelo cliente.

    * **Taxa para cálculo**: Selecione a taxa base para o cálculo percentual da comissão.

4.  Em **Mensalista - Abertura de requisição**:

    * Selecione se a sequência do número de requisições será **Automática** ou **Manual**.

---

---

## R-28.0 - Realizar Pagamentos no Módulo Caixa
**Objetivo:** Registrar o pagamento de serviços de balcão, notas ou certidões através do módulo Orion Caixa e emitir o respectivo recibo.  
**Tags:** `caixa`, `pagamentos`, `financeiro`, `recibo`, `notas`, `firmas`

### Intenções de Busca & Dúvidas Frequentes
- finalizar pedido no caixa
- fazer pagamento
- Como eu faço para receber o pagamento de um pedido do balcão de firmas?
- Onde eu registro o pagamento de um protocolo de notas?
- emitir recibo de pagamento
- receber do cliente
- Como eu finalizo um pedido e imprimo o recibo para o cliente?
- Qual a tela para dar baixa nos pagamentos?
- baixar pagamento

### Procedimento / Explicação
#### Passo a passo:

1.  Acesse o menu **Orion Caixa > Administração > Pagamentos**.

2.  Na tela exibida, selecione o tipo de pagamento e o setor correspondente, como: **Balcão de Firmas**, **Notas - Protocolo**, ou **Notas - Certidões e Serviços**.

3.  Após escolher o setor, informe o **nº do pedido** desejado. As informações do pedido serão carregadas automaticamente.

4.  Se necessário, utilize as opções para incluir novos serviços no pedido ou registrar valores em **Outros Serviços**.

5.  Informe a **forma de pagamento** e o **valor recebido**.

6.  Clique em **Concluir**.

7.  Após a confirmação, o sistema disponibilizará a opção de **imprimir o recibo** de pagamento.

---

---

## R-29.0 - Consultar e Gerenciar Recibos de Pagamento
**Objetivo:** Localizar, visualizar, estornar ou cancelar recibos de pagamento já emitidos pelo sistema Orion Caixa.  
**Tags:** `recibos`, `caixa`, `consultas`, `estorno`, `cancelamento`, `financeiro`

### Intenções de Busca & Dúvidas Frequentes
- histórico de pagamentos
- Preciso estornar um pagamento que foi feito errado, como faço?
- Como eu encontro um recibo que já foi pago?
- cancelar recibo
- estornar pagamento
- Como eu vejo o histórico de um pagamento?
- buscar recibo
- segunda via de recibo
- Onde eu cancelo um recibo?

### Procedimento / Explicação
#### Passo a passo:

1.  Acesse o menu **Orion Caixa > Administração > Consultas > Recibos**.

2.  Na tela de consulta, utilize os campos de busca, preenchendo informações como: **Data**, **Número do Recibo**, **Solicitante**, **CPF**, entre outros filtros disponíveis.

3.  Após inserir os dados e executar a pesquisa, serão listados os recibos correspondentes.

4.  Para cada recibo listado, é possível realizar ações como: **Estornar pagamento**, **Visualizar andamentos**, **Visualizar detalhes** e **Cancelar pagamento**.

---

---

## M-30.0 - Gerenciamento de Formas de Pagamento
**Objetivo:** Acessar, buscar e gerenciar as formas de pagamento cadastradas no sistema, permitindo a visualização, alteração, exclusão e adição de novos registros.  
**Tags:** `Configurações`, `Negócios`, `Cadastros`, `Formas de Pagamento`, `Filtros`, `Descrição`, `Sigla`, `Código`, `Inativos`, `Visualizar`, `Alterar`, `Excluir`, `Adicionar`

### Intenções de Busca & Dúvidas Frequentes
- Como eu inativo uma forma de pagamento que não usamos mais no cartório?
- gerenciar formas de recebimento
- consultar meios de pagamento
- Onde eu gerencio as formas de pagamento do sistema, como Dinheiro e Cartão de Crédito?
- editar forma de pagamento
- Onde eu vejo a lista de todas as formas de pagamento que estão cadastradas?
- excluir forma de pagamento
- Preciso editar o nome de uma forma de pagamento existente, como eu faço?

### Procedimento / Explicação
#### Descrição:

A tela de Formas de Pagamento permite o gerenciamento completo dos métodos de pagamento aceitos pelo sistema, oferecendo funcionalidades de busca avançada, visualização, edição, exclusão e adição de novas formas de pagamento.

#### Passo a passo:

1.  Para acessar a tela de formas de pagamento, clique no menu **Configurações**, em seguida clique no submenu **Negócios > Cadastros > Formas de pagamento**.

2.  Na tela de formas de pagamentos, são carregados todos os registros por padrão, apresentando 10 registros por página.

3.  Para facilitar a busca de um cadastro, utilize os seguintes filtros:

    *   **A: Pesquisar por descrição**: Permite efetuar uma busca pela descrição da forma de pagamento.

    *   **B: Sigla**: Permite efetuar uma busca pela sigla cadastrada na forma de pagamento.

    *   **C: Código**: Permite efetuar uma busca pelo código cadastrado na forma de pagamento.

    *   **D: Inativos**: Quando selecionado, permite efetuar uma busca apenas pelos cadastros que foram inativados.

    *   **E: Quantidade por página**: Permite alterar a quantidade de resultados apresentados em tela.

    *   **F: Limpar**: Limpa a consulta realizada, retornando a tela para o estado inicial.

    *   **G: Filtrar**: Quando acionado, realiza o filtro com base nos campos de busca preenchidos.

4.  Abaixo dos campos para filtro, temos a lista de resultados. A lista de resultados conta com as seguintes ações para cada registro:

    *   **Visualizar**: Quando acionado, exibe a tela de consulta, contendo os dados preenchidos da forma de pagamento. Não permite alterações.

    *   **Alterar**: Quando acionado, exibe a tela de alteração, contendo os dados preenchidos da forma de pagamento, permitindo assim sua edição.

    *   **Excluir**: Quando acionado, inativa o cadastro, tornando-o indisponível para uso. Para localizar os cadastros inativos, basta marcar a opção **D - Inativos** e realizar o filtro.

5.  Para cadastrar uma nova forma de pagamento, basta clicar no botão **Adicionar**.

---

---

## R-31.0 - Importar e Consultar Arquivos de Receitas de Outras Especialidades
**Objetivo:** Importar arquivos XML contendo receitas de outras especialidades (RC, Protesto) e consultar o histórico de arquivos já importados no sistema.  
**Tags:** `importação`, `arquivos`, `receitas`, `outras especialidades`, `xml`, `consultas`, `rc`, `protesto`

### Intenções de Busca & Dúvidas Frequentes
- subir arquivo de protesto
- receitas de outras especialidades
- Como eu importo um arquivo XML com as receitas de RC e Protesto?
- Como eu pesquiso por uma importação de arquivo feita em uma data específica?
- histórico de importações
- consultar arquivos importados
- Onde eu vejo os arquivos que já foram importados no sistema?
- importar xml de receita

### Procedimento / Explicação
#### Para importar um novo arquivo:

1.  Acesse o menu **Administração > Importação de Arquivos > Novo Arquivo**.

2.  Selecione o arquivo no formato **XML** que deseja importar.

#### Para consultar arquivos já importados:

1.  Acesse o menu **Administração > Importação de Arquivos**.

2.  Para uma **pesquisa simples**, informe a **data do arquivo** e clique em **Filtrar**.

3.  Para uma **pesquisa detalhada**, utilize os campos **período de processamento** e a **especialidade** desejada (Ex: RC, Protesto) para refinar a busca.

---

---

## M-31.0 - Cadastro de Nova Forma de Pagamento
**Objetivo:** Cadastrar uma nova forma de pagamento no sistema, definindo suas características, como descrição, sigla, código e requisitos específicos (ex: exigir dados bancários).  
**Tags:** `Configurações`, `Negócios`, `Cadastros`, `Formas de Pagamento`, `Cadastro`, `Descrição`, `Sigla`, `Código`, `Dados Bancários`, `Mensalistas`, `Espécie`, `Pix`

### Intenções de Busca & Dúvidas Frequentes
- cadastrar pagamento em espécie
- Quero criar uma nova opção de pagamento para o caixa, qual o caminho?
- Como eu cadastro 'PIX' como uma nova forma de pagamento no sistema?
- Onde eu configuro uma forma de pagamento do tipo 'Cheque' para que exija o preenchimento de dados bancários?
- configurar nova forma de recebimento
- adicionar PIX como pagamento
- Como eu marco uma nova forma de pagamento como sendo 'em espécie'?
- criar forma de pagamento

### Procedimento / Explicação
#### Descrição:

Esta rotina detalha o processo de cadastro de uma nova forma de pagamento, explicando cada campo e suas funcionalidades para parametrizar corretamente o método de pagamento no sistema.

#### Passo a passo:

1.  Para acessar a tela de formas de pagamento, clique no menu **Configurações**, em seguida clique no submenu **Negócios > Cadastros > Formas de pagamento**.

2.  Para cadastrar uma nova forma de pagamento, basta clicar no botão **Adicionar**.

3.  A tela de cadastro de forma de pagamento contém os seguintes campos para preenchimento:

    *   **Descrição**: Campo destinado para preenchimento da descrição da forma de pagamento (exemplo: **Cheque**).

    *   **Sigla**: Campo destinado para preenchimento de uma sigla, com até três letras, para abreviar a forma de pagamento em algumas telas e relatórios.

    *   **Código**: Permite informar um código, diferente para cada forma de pagamento, o qual é usado na rotina de caixa para facilitar a escolha da forma de pagamento.

    *   **Exige dados bancários**: Quando marcado, parametriza a forma de pagamento para exigir os dados bancários no momento da utilização da forma de pagamento (informações como banco, agência, conta, etc.).

    *   **Forma de pagamento padrão**: Quando marcado, parametriza a forma de pagamento para ser definida como padrão.

    *   **Exige dados mensalistas**: Quando marcado, parametriza a forma de pagamento para exigir os dados de mensalistas no momento da utilização da forma de pagamento.

    *   **Forma de pagamento em espécie**: Quando marcada, parametriza a forma de pagamento para ser realizada por meio de dinheiro.

    *   **Forma de pagamento em Pix**: Quando marcada, parametriza a forma de pagamento para ser realizada por meio de Pix.

4.  Para finalizar o cadastro, clique no botão **Concluir**.

---

---

## M-33.1 - Como Consultar o Extrato de um Mensalista
**Objetivo:** Detalhar o procedimento para consultar, filtrar, imprimir e enviar por e-mail o extrato de serviços de um mensalista ou de uma de suas filiais.  
**Tags:** `Mensalista`, `Faturamento`, `Extrato`, `Consulta`, `Filtro`, `Impressão`, `Envio`

### Intenções de Busca & Dúvidas Frequentes
- enviar extrato por e-mail
- consultar extrato mensalista
- Preciso reenviar o extrato de um mensalista por e-mail, como eu faço?
- Como eu consulto o extrato detalhado de um mensalista para conferência?
- Onde eu gero o extrato de uma filial específica de um mensalista?
- ver extrato de faturamento
- gerar segunda via de extrato

### Procedimento / Explicação
#### Descrição:

Esta funcionalidade é utilizada para consultar o extrato detalhado de um mensalista específico, exibindo todas as movimentações (créditos, débitos e serviços) em um determinado período.

#### Passo a passo:

1.  Acesse a tela de Faturamento do mensalista através do menu **Administração > Mensalista > Faturamento**.

2.  No menu lateral, clique em **Extrato**.

3.  Para aplicar o filtro, é necessário preencher:

    * **Mensalista**: Selecione o mensalista desejado. Caso ele possua filiais, um campo para selecioná-las será aberto.

    * **Período**: Informe o intervalo de datas utilizando o campo de período personalizado ou os filtros rápidos disponíveis.

4.  Após preencher os campos, clique no botão **Filtrar**.

5.  O sistema exibirá um resumo acima da lista de resultados, contendo:

    * **Período solicitado**.

    * **Saldo anterior**: Saldo positivo ou negativo da conta anterior ao período solicitado.

    * **Saldo no período**: O saldo total das movimentações, já considerando o saldo anterior.

6.  A partir da tela de extrato, as seguintes ações estão disponíveis:

    * **Imprimir**: Clique para gerar uma versão impressa do extrato exibido.

    * **Enviar**: Clique para enviar o extrato para o(s) e-mail(s) cadastrados no mensalista ou filial.

        * *Observação:* Se não houver e-mail cadastrado, o sistema solicitará que um seja informado no momento do envio e o salvará no cadastro do mensalista para futuros envios.

---

---

## M-33.2 - Como Emitir Novas Faturas para Mensalistas
**Objetivo:** Instruir sobre o processo de emissão de faturas para mensalistas, incluindo a filtragem de débitos, geração em lote, definição de data de vencimento e tratamento de faturas existentes.  
**Tags:** `Mensalista`, `Faturamento`, `Emissão`, `Fatura`, `Boleto`, `Filtro`, `Lote`

### Intenções de Busca & Dúvidas Frequentes
- Como eu defino a data de vencimento ao gerar as faturas em lote?
- emitir boleto para mensalista
- gerar fatura mensalista
- Onde eu emito a fatura (e o boleto, se configurado) para um mensalista específico?
- faturamento em lote
- Como eu gero as faturas para todos os mensalistas de uma só vez?
- criar cobrança para mensalista

### Procedimento / Explicação
#### Descrição:

Esta rotina é utilizada para realizar a emissão das faturas que serão enviadas aos mensalistas e filiais com base nos débitos acumulados em um período.

#### Passo a passo:

1.  Acesse a tela de Faturamento do mensalista através do menu **Administração > Mensalista > Faturamento**.

2.  No menu lateral, clique na opção **Emissão**.

3.  Utilize os campos de filtro para localizar os mensalistas com débitos a faturar. É obrigatório informar um período ou mês de referência.

    * **Pesquisar por mensalista**: Para emitir a fatura de um mensalista específico.

    * **Período**: Para faturar os débitos ocorridos em um intervalo de datas.

    * **Mês de referência**: Para faturar todos os débitos de um mês completo.

    * **Fechamento**: Para filtrar mensalistas com base no dia de fechamento definido em seu cadastro.

4.  Clique no botão **Filtrar**. O sistema listará todos os mensalistas que possuem débito no período, exibindo o valor na coluna **"A faturar"**.

5.  Selecione os mensalistas para os quais deseja gerar a fatura (por padrão, todos vêm selecionados).

6.  Clique no botão **Gerar**.

    * *IMPORTANTE:* Se faturas já tiverem sido geradas para o mesmo período, o sistema alertará e permitirá que você cancele ou prossiga regerando as faturas.

7.  Informe a **data de vencimento** que será aplicada a todas as faturas e clique em **Concluir**.

8.  Aguarde o progresso da geração. Ao final, uma tela de resumo exibirá o status de cada fatura gerada, o número da fatura, o número do boleto (se aplicável) e o valor.

9.  Após a geração, as seguintes ações em lote ficam disponíveis:

    * **Imprimir**: Para imprimir TODAS as faturas e boletos gerados.

    * **Enviar**: Para enviar as faturas por e-mail para TODOS os mensalistas processados.

    * **Baixar arquivo de remessa**: Para baixar o arquivo de remessa dos boletos eletrônicos a ser enviado ao banco.

---

---

## M-33.3 - Manutenção de Faturas Emitidas (Pagamento, Envio e Cancelamento)
**Objetivo:** Detalhar as ações de manutenção para faturas já emitidas, como realizar a baixa de pagamento manual, reenviar por e-mail, alterar a data de vencimento e cancelar uma fatura.  
**Tags:** `Mensalista`, `Faturamento`, `Manutenção`, `Fatura`, `Pagamento`, `Estorno`, `Cancelamento`, `Vencimento`

### Intenções de Busca & Dúvidas Frequentes
- dar baixa em fatura
- cancelar fatura de mensalista
- Preciso alterar a data de vencimento de uma fatura que já foi emitida, onde eu faço isso?
- Como eu cancelo uma fatura de mensalista que foi gerada com o valor errado?
- registrar pagamento de fatura
- alterar vencimento de boleto
- Onde eu vejo o histórico de andamentos de uma fatura específica?
- Um mensalista pagou a fatura. Como eu faço para dar baixa no pagamento manualmente no sistema?

### Procedimento / Explicação
#### Descrição:

Esta funcionalidade é utilizada para realizar a manutenção em faturas que já foram emitidas, permitindo ações como pagamento manual, alteração de vencimento, reenvio e cancelamento.

#### Passo a passo:

1.  Acesse a tela de Faturamento do mensalista através do menu **Administração > Mensalista > Faturamento**.

2.  No menu lateral, clique na opção **Manutenção**.

3.  Utilize os diversos filtros para localizar a fatura desejada: **mensalista**, **período de emissão**, **período de vencimento**, **status**, **número da fatura**, etc.

4.  Clique no botão **Filtrar**.

5.  Para cada fatura listada na grid de resultados, as seguintes ações estão disponíveis:

    * **Baixa de pagamento**: Para registrar o pagamento da fatura de forma manual. Uma janela será aberta para informar o valor e a forma de pagamento. O status do boleto será alterado para **Pago**.

    * **Enviar a fatura por e-mail**: Para reenviar a fatura para o e-mail cadastrado.

    * **Imprimir fatura/boleto**: Para reimprimir o documento.

    * **Alterar vencimento**: Permite alterar a data de vencimento de uma fatura. Esta ação pode ser feita em lote. *Observação:* Não é possível alterar o vencimento de boletos eletrônicos por esta tela.

    * **Andamentos da fatura**: Para visualizar o histórico completo de ações realizadas na fatura.

    * **Visualizar fatura**: Para abrir uma visualização da fatura/boleto.

    * **Cancelar fatura**: Para cancelar uma fatura gerada. *Observação:* Boletos eletrônicos não podem ser cancelados por esta tela.

---

---

## M-45.0 - Gerenciar Orçamentos
**Objetivo:** Acessar, filtrar e gerenciar os orçamentos cadastrados, permitindo a busca por diversos critérios, impressão, conversão em protocolo, visualização de andamentos, alteração e cancelamento.  
**Tags:** `Notas`, `Consultas`, `Orçamentos`, `Filtros`, `Imprimir`, `Gerar Protocolo`, `Andamento`, `Visualizar`, `Alterar`, `Excluir`, `Desistência`

### Intenções de Busca & Dúvidas Frequentes
- Na tela de consulta, como eu faço para converter um orçamento em um protocolo?
- gerenciar propostas
- Preciso cancelar um orçamento que não foi aprovado, onde eu faço isso?
- consultar orçamentos
- buscar orçamento
- Onde eu consulto todos os orçamentos que foram feitos no sistema?
- cancelar orçamento
- converter orçamento em protocolo
- Como eu encontro um orçamento específico pelo nome do solicitante?

### Procedimento / Explicação
#### Descrição:

A tela de **Orçamentos** permite gerenciar os orçamentos existentes. Ao ser aberta, o sistema carrega todos os registros, apresentando por padrão 10 registros por página. Possui diversos filtros para facilitar a busca e o gerenciamento dos orçamentos.

#### Passo a passo para Gerenciar Orçamentos:

1.  Acesse o menu **Notas > Consultas > Orçamentos**.

2.  Na tela de **Orçamentos**, você pode utilizar os seguintes filtros para refinar sua busca:

    *   **Pesquisar por nº do orçamento**: Permite efetuar uma busca pelo número do orçamento.

    *   **Pesquisar por período**: Permite efetuar uma busca pelos orçamentos que foram feitos no período delimitado.

    *   **Pesquisar por mês de referência**: Permite efetuar uma busca pelo mês de referência do orçamento.

    *   **Pesquisar por solicitante**: Permite efetuar uma busca pelo solicitante do orçamento.

    *   **Pesquisar por escrevente**: Permite efetuar uma busca pelo escrevente do orçamento.

    *   **Pesquisar por status**: Permite efetuar uma busca pelo status do orçamento.

    *   **Imprimir**: Quando acionado, imprime um relatório com os resultados filtrados.

    *   **Limpar**: Limpa a consulta realizada, retornando a tela para o estado inicial.

    *   **Filtrar**: Quando acionado, realiza o filtro com base nos campos de busca preenchidos.

3.  A seção **Resultados** exibe todos os orçamentos cadastrados. Para cada registro, as seguintes ações estão disponíveis:

    *   **Gerar protocolo**: Quando acionado, realiza a conversão do orçamento em um novo protocolo.

    *   **Andamento**: Quando acionado, exibe uma lista dos andamentos do orçamento.

    *   **Visualizar**: Quando acionado, exibe a tela de consulta, contendo os dados preenchidos do orçamento. Não permite alterações.

    *   **Alterar**: Quando acionado, exibe a tela de alteração, contendo os dados preenchidos do orçamento, permitindo assim sua edição.

    *   **Excluir**: Quando acionado, cancela o item.

    *   **Desistência**: Quando acionado, realiza a desistência do item.

---

---

## M-46.0 - Cadastrar Orçamento Completo
**Objetivo:** Realizar o cadastro de um orçamento detalhado e formal, preenchendo informações do solicitante, espécie, natureza e itens de custas, com a opção de convertê-lo em protocolo.  
**Tags:** `Notas`, `Orçamentos`, `Cadastro`, `Solicitante`

### Intenções de Busca & Dúvidas Frequentes
- criar proposta de serviço
- Qual a diferença entre a tela de 'Orçamento Rápido' e a de 'Orçamento Completo'?
- orçamento para virar protocolo
- fazer orçamento formal
- Como eu crio um orçamento completo, preenchendo todos os detalhes do ato notarial?
- novo orçamento completo
- Onde eu faço um orçamento que posso depois enviar por WhatsApp ou e-mail ao cliente?

### Procedimento / Explicação
#### Passo a passo para cadastrar um orçamento completo:

1.  Acesse o menu **Notas > Orçamentos > Orçamento completo**.

2.  Preencha as informações do solicitante do orçamento.

3.  Clique em **Concluir** para finalizar o orçamento.

---

---

## M-47.0 - Cadastrar Orçamento Rápido
**Objetivo:** Realizar o cadastro e a impressão de um orçamento de forma rápida e simplificada, ideal para simular custos de atos notariais durante um atendimento de balcão ou por telefone.  
**Tags:** `Notas`, `Orçamentos`, `Orçamento Rápido`, `Cadastro`, `Item`, `Descrição`, `Cálculo`, `ITBI`, `Outros Serviços`, `Impressão`

### Intenções de Busca & Dúvidas Frequentes
- cálculo rápido de escritura
- Como eu faço um cálculo rápido de custas, incluindo ITBI, sem precisar criar um orçamento formal?
- simular custas
- orçamento de balcão
- Preciso dar um valor aproximado de uma escritura para um cliente no telefone, qual tela eu uso?
- estimativa de valor de ato
- Onde fica a tela de orçamento rápido que posso gerar um PDF para impressão?
- novo orçamento rápido

### Procedimento / Explicação
#### Descrição:

A tela de **Orçamento rápido** permite a criação ágil de orçamentos, oferecendo campos para detalhar itens, cálculos, impostos e outros serviços, além de opções para impressão e cancelamento.

#### Passo a passo para cadastrar um orçamento rápido:

1.  Acesse o menu **Notas > Orçamentos > Orçamento rápido**.

2.  Na tela de cadastro de orçamento rápido, preencha os seguintes campos:

    *   **Item**: Informe o identificador do ato (número). É um campo obrigatório e por padrão vem com o número **1**.

    *   **Descrição**: Informe a descrição do ato. É um campo obrigatório e por padrão vem com o valor **"Escritura com valor declarado"**, mas existem outras opções.

    *   **Qtd. Adicional**: Informe a quantidade adicional do ato. Este campo fica disponível dependendo da opção escolhida no campo **Descrição**.

    *   **Cálculo**: Informe o cálculo do ato. É um campo obrigatório e por padrão vem com o valor **"Integral"**.

    *   **Base de cálculo**: Informe a base de cálculo do ato. Por padrão vem com o valor **"R\$ 0,00"**.

    *   **Cidade**: Informe a cidade do ato.

    *   **% ITBI**: Informe a porcentagem dos Impostos de Transmissão de Bens Imóveis do ato.

        *   **Calcular ITBI**: Se selecionado, calcula o ITBI.

    *   **Descrição** (Outros serviços): Campo para informar a descrição de um outro serviço, podendo ser criada outra descrição a partir do botão ao lado do campo.

    *   **Valor** (Outros serviços): Campo para informar o valor de um outro serviço.

    *   **Deletar item**: Ao ser acionado, exclui o item na seção "Outros serviços".

    *   **Adicionar item**: Ao ser acionado, adiciona um novo item na seção "Outros serviços".

    *   **Observações**: Caso o orçamento possua alguma informação adicional, deve ser informada neste campo.

3.  Observe as seções de resumo:

    *   **Itens**: Exibe os itens adicionados.

    *   **Valor**: Exibe o valor monetário calculado de cada item.

    *   **Subtotal**: Exibe o valor total calculado dos itens.

    *   **Total**: Exibe o valor total calculado dos itens do orçamento e, em adicional, os valores dos outros serviços, ITBI e registro de imóveis, se informados.

4.  Selecione a **Impressora** que realizará a impressão do orçamento rápido (necessário estar parametrizado para realizar a impressão).

5.  Para finalizar, escolha uma das seguintes ações:

    *   **Cancelar**: Cancela o orçamento rápido.

    *   **Imprimir**: Finaliza e imprime o orçamento rápido.

---

---

## M-57.0 - Consultar e Gerenciar Movimentação Financeira por Protocolo
**Objetivo:** Consultar e gerenciar as movimentações financeiras de um protocolo, como depósitos prévios, pagamentos e saldos, utilizando diversos filtros para a busca.  
**Tags:** `Notas`, `Consultas`, `Movimentação Financeira`, `Protocolo`, `Filtros`, `Depósito Prévio`, `Financeiro`

### Intenções de Busca & Dúvidas Frequentes
- extrato financeiro do protocolo
- ver saldo de protocolo
- movimentação financeira de protocolo
- Preciso imprimir o extrato financeiro de um protocolo específico, como faço?
- consultar depósito prévio
- Onde eu consulto a movimentação financeira detalhada de um protocolo?
- Como eu vejo o saldo de um protocolo que recebeu um depósito prévio?

### Procedimento / Explicação
#### Descrição:

A tela de Movimentação financeira por protocolo oferece ferramentas para consultar e gerenciar os registros financeiros de protocolos. Ao ser aberta, a tela exibe automaticamente os registros com crédito ou débito diferente de zero, ordenados por protocolo e com 10 registros por página.

#### Passo a passo:

1.  Para acessar a tela, acesse o menu **Notas > Consultas > Movimentação financeira por protocolo**.

2.  Utilize os campos de filtro disponíveis para refinar sua busca:

    *   **Pesquisar por protocolo**: Permite efetuar uma busca pelo número do protocolo.

    *   **Data de recepção**: Permite efetuar uma busca pela data de recepção do protocolo.

    *   **Status**: Permite efetuar uma busca pelo status.

    *   **Tipo de mov. financeira**: Permite efetuar uma busca pelo tipo de movimentação financeira.

    *   **Tipo de lançamento**: Permite efetuar uma busca pelo tipo de lançamento.

    *   **Escrevente**: Permite efetuar uma busca pelo escrevente.

    *   **Pago por**: Permite efetuar uma busca por quem pagou o depósito prévio.

    *   **CPF**: Permite efetuar uma busca pelo CPF.

    *   **Espécie**: Permite efetuar uma busca pela espécie de protocolo.

    *   **Natureza**: Permite efetuar uma busca pela natureza.

    *   **Quantidade por página**: Permite alterar a quantidade de resultados apresentados em tela.

3.  Após preencher as informações desejadas, clique no botão **Filtrar**.

4.  Para limpar a consulta realizada e retornar a tela ao estado inicial, clique no botão **Limpar**.

5.  Para imprimir um relatório com os resultados filtrados, clique no botão **Imprimir**.

6.  O campo **Saldo total** exibe o valor total do saldo dos resultados filtrados.

7.  Na grid de resultados, é possível realizar as seguintes ações:

    *   Clique em **Movimentação detalhada** para abrir os detalhes das movimentações financeiras realizadas no protocolo.

    *   Clique em **Visualizar** para visualizar as movimentações financeiras realizadas no protocolo.

    *   Clique em **Editar** para editar uma das movimentações financeiras que foram lançadas no protocolo.

    *   Clique em **Imprimir extrato** para imprimir o extrato detalhado de toda movimentação financeira que foi realizada no protocolo.

8.  Caso deseje voltar para a tela inicial, clique no botão **Voltar**.

---

---

## M-64.0 - Gerenciar Tipo de Movimentação Financeira
**Objetivo:** Acessar e gerenciar os 'Tipos de Movimentação Financeira' (ex: 'Depósito Prévio'), permitindo a consulta, alteração e exclusão dos registros existentes.  
**Tags:** `Configurações`, `Geral`, `Cadastros auxiliares`, `Tipo de Movimentação Financeira`, `Cadastro`, `Filtros`

### Intenções de Busca & Dúvidas Frequentes
- editar movimentação financeira
- excluir tipo de movimentação
- É possível excluir um tipo de movimentação financeira?
- gerenciar tipos de lançamento
- Como eu edito a descrição de um tipo de movimentação?
- Onde eu gerencio os Tipos de Movimentação Financeira cadastrados?

### Procedimento / Explicação
#### Descrição:

A tela de Tipo de Movimentação Financeira exibe uma tabela com todos os tipos de movimentação financeira cadastrados no sistema, organizados em ordem alfabética. É possível realizar buscas específicas e gerenciar os registros existentes.

#### Passo a passo:

1.  Para acessar a tela, clique no menu **Configurações > Geral > Cadastros auxiliares > Tipo de movimentação financeira**.

2.  Ao carregar a página Tipo de Movimentação Financeira, será apresentada uma tabela de dados com todos os tipos de movimentação financeira cadastradas.

3.  Caso seja necessária uma busca específica, você poderá realizá-la preenchendo os campos de filtro disponíveis em tela.

4.  Na tela de tipo de movimentação financeira, também é possível realizar as seguintes ações:

    *   **Consultar**: Clique para visualizar o tipo de movimentação financeira.

    *   **Alterar**: Clique para alterar o tipo de movimentação financeira.

    *   **Excluir**: Clique para excluir o tipo de movimentação financeira.

---

---

## M-65.0 - Adicionar Novo Tipo de Movimentação Financeira
**Objetivo:** Cadastrar um novo 'Tipo de Movimentação Financeira', definindo sua descrição, sigla, tipo de lançamento (crédito ou débito) e se ele se refere a um depósito prévio.  
**Tags:** `Configurações`, `Geral`, `Cadastros auxiliares`, `Tipo de Movimentação Financeira`, `Cadastro`, `Adicionar`

### Intenções de Busca & Dúvidas Frequentes
- criar tipo de lançamento financeiro
- cadastrar lançamento de crédito
- novo tipo de movimentação
- Como eu crio um tipo de movimentação específico para 'Depósito Prévio'?
- Onde eu defino se um novo tipo de movimentação será de 'crédito' ou 'débito'?
- Como eu cadastro um novo Tipo de Movimentação Financeira?

### Procedimento / Explicação
#### Descrição:

Este procedimento detalha como adicionar um novo tipo de movimentação financeira, configurando seus atributos como descrição, sigla, tipo de lançamento (crédito ou débito) e a flag de depósito prévio.

#### Passo a passo:

1.  Para acessar a tela, clique no menu **Configurações > Geral > Cadastros auxiliares > Tipo de movimentação financeira**.

2.  Ao carregar a tela de tipos de movimentação financeira, clique no botão **Adicionar** (disponível abaixo da tabela apresentada).

3.  Na tela de cadastro de tipo de movimentação financeira, preencha os seguintes campos:

    *   **Descrição**: Informe uma descrição obrigatória para o tipo de movimentação financeira, que será exibida na tela para seleção (Exemplo: Iniciado).

    *   **Sigla**: Preencha um campo destinado a uma sigla, com até três letras, para abreviar o tipo de movimentação financeira em algumas telas.

    *   **Tipo lançamento**: Defina o tipo de lançamento da movimentação financeira, podendo ser **crédito** ou **débito**.

    *   **Flag Depósito prévio**: Quando marcado, parametriza o tipo de lançamento como "Crédito".

    *   **Observação**: Campo destinado a anotações gerais ou observações sobre o tipo de movimentação financeira que está sendo cadastrado.

4.  Para finalizar o cadastro, clique no botão **Concluir**.

5.  Para voltar para a tela com a lista de tipos de movimentações financeiras cadastradas, clique no botão **Voltar**.

---

---

