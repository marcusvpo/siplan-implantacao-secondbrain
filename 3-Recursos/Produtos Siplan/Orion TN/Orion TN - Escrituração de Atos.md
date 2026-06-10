---
tipo: Recurso
area: Produtos Siplan
tags:
  - #orion
  - #orion_orion_tn
  - #orion_tn_-_escrituração_de_atos
status_atual: #ativo
---
# Orion TN - Escrituração de Atos

Este recurso detalha os procedimentos, rotinas e manuais operacionais do sistema **Orion TN** para a área de **Escrituração de Atos**.

## R-1.0 - Visão Geral do Sistema ORION TN
**Objetivo:** Apresentar uma visão geral sobre a arquitetura, os módulos e a interface do sistema Orion TN, destinado a cartórios de notas.  
**Tags:** `Orion TN`, `Sistema`, `Cartório de Notas`, `Web`, `Nuvem`, `Módulos Integrados`

### Intenções de Busca & Dúvidas Frequentes
- módulos do sistema
- conhecendo o sistema
- Quais são os módulos que integram o Orion TN?
- Pode me dar uma visão geral do sistema?
- sobre o Orion
- O Orion TN funciona na nuvem ou precisa de servidor local?
- principais funcionalidades
- O que é o sistema Orion TN?
- visão geral Orion
- o que é o Orion TN

### Procedimento / Explicação
O **ORION TN** é um sistema desenvolvido para cartórios de notas, operando em ambiente web. Isso permite que seja hospedado tanto em nuvem quanto no servidor local do cartório, oferecendo flexibilidade de acesso. Por ser web, o sistema pode ser utilizado em qualquer navegador de preferência, facilitando a usabilidade. Ao acessar o sistema com um usuário, é possível visualizar os módulos integrados:

* **ORION Stock**

* **ORION TN**

* **ORION Caixa**

* **ORION GED**

* **Livro de Depósito Prévio**

O módulo principal do **ORION TN**, que abrange os sistemas de firmas e notas, apresenta um layout *clean* e moderno, intuitivo e com menus de fácil acesso, garantindo uma usabilidade simplificada para o colaborador.

---

---

## V-1.0 - Como Cadastrar e Gerenciar o Sinal Público
**Objetivo:** Registrar um novo sinal público de outro cartório, consultar os registros existentes e gerenciar as informações, como editar, inativar e visualizar anexos.  
**Tags:** `Cadastro`, `Sinal Público`, `Firmas`, `Consulta`, `Anexos`, `Digitalização`, `Gerenciamento`, `Cartório`

### Intenções de Busca & Dúvidas Frequentes
- consultar sinal público
- verificar sinal público recebido
- conferir escrevente de outro cartório
- Chegou um documento para reconhecer firma, mas a assinatura é de outro cartório. Onde eu cadastro?
- adicionar escrevente de outra cidade
- Onde eu anexo o cartão de assinaturas que recebemos de outro cartório?
- cadastrar sinal de outro cartório
- gerenciar sinal público
- Preciso verificar se o sinal público de um escrevente já está no sistema, onde eu consulto?
- cadastrar cartório correspondente
- Como eu faço para cadastrar o sinal público de um cartório de outra cidade?
- Como inativar um sinal público de um escrevente que não trabalha mais no outro cartório?
- validar assinatura de fora

### Procedimento / Explicação
Esta rotina orienta sobre o fluxo completo de gerenciamento do Sinal Público, desde o cadastro de um novo registro até a consulta e manutenção dos sinais existentes.

    #### Parte 1: Cadastrar um Novo Sinal Público

    1.  Acesse o menu **Firmas > Cadastros > Sinal Público**.

    2.  Na tela de consulta, clique no botão **Adicionar**.

    3.  Preencha as informações do cartório de origem. Os campos marcados com um asterisco (`*`) são de preenchimento obrigatório.

        * Defina se o sinal público é **recebido** ou **enviado**.

        * Informe a **data de recebimento/envio**.

        * Ao inserir o **CEP**, o sistema preencherá automaticamente os campos de endereço (Logradouro, Cidade, UF, etc.).

    4.  Na aba **"Pessoas"**, preencha o nome e o cargo do escrevente. Para adicionar mais de um, clique no botão `+`.

    5.  Na aba **"Arquivos Anexos"**, você pode:

        * Clicar em **Selecionar** para anexar documentos já existentes (PDF, JPG, etc.).

        * Clicar em **Capturar** para tirar uma foto do escrevente com a webcam.

        * Clicar em **Digitalizar** para escanear um documento na hora.

    6.  Após preencher todas as informações, clique em **Concluir**.

    #### Parte 2: Consultar e Gerenciar Sinais Públicos

    1.  Acesse o menu **Firmas > Cadastros > Sinal Público**.

    2.  Utilize os campos de filtro na parte superior da tela para buscar o registro desejado. As opções de busca incluem:

        * **Pesquisar por cartório**

        * **Pesquisar por nº sinal público**

        * **Pesquisar por data de digitação**

        * **Inativos**

    3.  Clique em **Filtrar** para aplicar a busca.

    4.  O sistema listará os resultados abaixo. Na linha de cada registro, você encontrará ícones de atalho para:

        * **Andamentos:** Visualizar o histórico de logs do cadastro.

        * **Anexos:** Ver os documentos anexados.

        * **Visualizar:** Abrir o cadastro em modo de leitura.

        * **Editar:** Alterar as informações do cadastro.

        * **Inativar:** Desativar o sinal público.

---

---

## D-1.10 - Configurar Impressora e Modelos Padrão
**Objetivo:** Definir impressora padrão, modelo de impressão padrão e máquinas de Parcela Express padrão.  
**Tags:** `impressora`, `modelo`, `impressão`, `configuração`

### Intenções de Busca & Dúvidas Frequentes
- definir modelo padrão
- configurar dispositivo de impressão
- Como configurar a impressora padrão?
- Como definir um modelo de impressão padrão?
- configurar impressora
- Onde configuro as máquinas de Parcela padrão?

### Procedimento / Explicação
#### Descrição:

Configuração de dispositivos e modelos padrão para agilizar operações do caixa.

#### Passo a passo:

1. Acesse **Configurações > Parametrizações > Impressora, Modelos e Impressão**.

2. Selecione a **impressora padrão** que será utilizada.

3. Selecione o **modelo padrão** de impressão.

4. Na seção de **Maquininhas do Parcela**, selecione a **máquina padrão** que será sugerida.

5. Se desejar adicionar mais máquinas, clique em **Adicionar**.

6. Salve as configurações.

* **Observação Importante:** As configurações padrão serão sempre sugeridas pelo sistema, agilizando as operações diárias.

---

---

## D-1.11 - Configurar Painel de Atalhos
**Objetivo:** Personalizar atalhos para rotinas específicas, permitindo acesso rápido às telas mais utilizadas.  
**Tags:** `atalho`, `configuração`, `acesso rápido`

### Intenções de Busca & Dúvidas Frequentes
- Como criar atalhos personalizados?
- Onde configuro o painel de atalhos?
- configurar acesso rápido
- criar atalho personalizado
- personalizar painel de atalhos
- Como deixar um acesso rápido para uma rotina?

### Procedimento / Explicação
#### Descrição:

O painel de atalhos permite criar acessos rápidos para rotinas utilizadas frequentemente, aumentando a produtividade.

#### Passo a passo:

1. Acesse **Configurações > Parametrizações > Painel de Atalhos**.

2. Selecione as rotinas desejadas para aparecer como atalhos.

3. Configure a ordem de exibição conforme preferência.

4. Salve as configurações.

* **Observação Importante:** O painel de atalhos oferece grande flexibilidade para personalização conforme o hábito de trabalho de cada usuário.

---

---

## D-1.15 - Consultar Histórico de Ações
**Objetivo:** Visualizar registro detalhado de todas as ações realizadas no módulo, incluindo usuário, data, hora e tipo de alteração.  
**Tags:** `histórico`, `log`, `auditoria`, `consulta`

### Intenções de Busca & Dúvidas Frequentes
- consultar auditoria
- Como saber quem fez uma alteração e quando?
- ver log de ações
- Onde fico o log de alterações?
- visualizar histórico de mudanças
- Como visualizar o histórico de ações do sistema?

### Procedimento / Explicação
#### Descrição:

O histórico registra todas as ações realizadas no módulo com controle rigoroso de quem fez o quê e quando.

#### Passo a passo:

1. Acesse **Configurações > Históricos**.

2. O sistema abrirá uma tela de consulta mostrando o registro de ações.

3. Filtre pelo **usuário específico** ou visualize **todos os usuários**.

4. Observe as colunas:

   * **Data e Hora** - Quando a ação foi realizada

   * **Usuário** - Quem realizou a alteração

   * **Tipo de Alteração** - Qual foi a modificação

5. Clique em um registro para visualizar detalhes.

* **Observação Importante:** O histórico é um controle rigoroso e essencial para auditoria. Todos os registros incluem data, hora exata e usuário responsável.

---

---

## R-1.2 - Módulo ORION TN: Notas
**Objetivo:** Descrever as funcionalidades do módulo de Notas, utilizado para a lavratura de atos notariais, incluindo cadastro de protocolos, qualificação de partes e geração de documentos.  
**Tags:** `Notas`, `Protocolo`, `Cadastro`, `Editor de Texto`, `Minuta`, `Livro`, `Traslado`

### Intenções de Busca & Dúvidas Frequentes
- Como o Orion organiza as informações dentro de um protocolo de escritura?
- Onde eu faço a lavratura de atos notariais?
- módulo de escrituras
- cadastro de protocolo
- Para que serve o módulo de Notas?
- gerar minuta e traslado
- O sistema tem um editor de texto próprio para gerar a minuta ou o traslado?
- lavratura de atos
- editor de texto do Orion

### Procedimento / Explicação
O módulo de Notas possui submenus para diversas consultas e cadastros, como **Consulta de Certidões e Serviços**, **Consulta de Índice** e **Consulta de Protocolos**.

#### 1.2.1 Rotina de Cadastro de Protocolo

A tela de cadastro de protocolo se adapta a diversas configurações de monitor, otimizando o trabalho do usuário.

1.  As informações dentro do protocolo são separadas em **cartões** (Dados Protocolo, Qualificação das Partes, etc.).

2.  É possível expandir apenas os dados necessários para o preenchimento, mantendo o ambiente *clean* e de fácil acesso.

#### 1.2.2 Editor de Texto Integrado

O editor de texto é integrado diretamente no sistema **ORION**.

1.  Ao expandir o ícone do editor, é possível selecionar a geração de **Minuta**, **Livro** ou **Traslado**.

2.  Para gerar esses documentos, é necessário que os dados de qualificação das partes e do imóvel estejam preenchidos.

3.  Após o preenchimento, o usuário pode gerar os documentos em poucos minutos diretamente no editor.

---

---

## D-1.2 - Configurar Dados de Cartório
**Objetivo:** Registrar e manter os dados cadastrais do cartório, incluindo informações do estabelecimento e do cliente.  
**Tags:** `cartório`, `configuração`, `dados`

### Intenções de Busca & Dúvidas Frequentes
- configurar informações de cartório
- atualizar dados cartoriais
- Como configurar os dados do meu cartório no Orion Caixa?
- Onde fico os dados de cartório do sistema?
- Como cadastro as informações do cartório?
- cadastrar dados do cartório

### Procedimento / Explicação
#### Descrição:

Os dados de cartório armazenam informações essenciais do estabelecimento e cliente, sendo a base para as operações do módulo.

#### Passo a passo:

1. No menu principal, acesse **Configurações > Dados de Cartório**.

2. Preencha os campos com as informações do cartório cadastrado.

3. Configure os dados do cliente conforme necessário.

4. Salve as alterações.

* **Observação Importante:** Estes dados são fundamentais para o correto funcionamento de outras rotinas do sistema.

---

---

## R-1.3 - Integração com Inteligência Artificial (IA)
**Objetivo:** Demonstrar como a Inteligência Artificial (OCR) é utilizada no sistema para automatizar o preenchimento de informações a partir de documentos digitalizados.  
**Tags:** `IA`, `Inteligência Artificial`, `Preenchimento Automático`, `OCR`, `Digitalização`

### Intenções de Busca & Dúvidas Frequentes
- preenchimento inteligente
- preenchimento automático de qualificação
- Onde fica a função de OCR para preenchimento automático?
- importar dados da CNH
- O sistema consegue ler um documento e cadastrar as partes automaticamente?
- Tem como importar os dados de um arquivo Word para dentro do protocolo?
- Leitura automática de documento
- OCR
- ler documento com IA
- Como eu uso a inteligência artificial para preencher os dados de uma pessoa a partir da CNH dela?

### Procedimento / Explicação
Um grande diferencial do sistema **ORION** é a integração com funcionalidades de inteligência artificial nas rotinas de notas e firmas.

#### 1.3.1 IA no Módulo de Notas (Protocolo)

1.  Dentro do protocolo, é possível preencher as partes utilizando a IA.

2.  Ao clicar no botão de preenchimento, basta importar ou digitalizar um documento.

3.  O sistema fará a leitura das informações (OCR) e as preencherá dentro do protocolo.

4.  A IA também pode ler um documento Word pronto e preencher as informações de qualificação de imóvel e partes que encontrar.

#### 1.3.2 IA no Módulo de Firmas (Cartão de Assinatura/DUT)

1.  A IA auxilia no cadastro de cartão de assinatura e no preenchimento de **DUT**.

2.  O usuário importa o documento, e o sistema realiza a leitura, inserindo as informações nos campos correspondentes.

---

---

## D-1.3 - Configurar Modelos de Impressão
**Objetivo:** Definir os modelos de impressão para relatórios, pagamentos de caixa e fechamento de caixa.  
**Tags:** `impressão`, `modelo`, `relatório`, `configuração`

### Intenções de Busca & Dúvidas Frequentes
- Como personalizar a impressão de caixa?
- definir modelo de relatório
- Onde configuro os modelos de impressão?
- configurar layout de impressão
- criar modelo de impressão
- Como criar um modelo de impressão de relatório?

### Procedimento / Explicação
#### Descrição:

Os modelos de impressão permitem personalizar o layout dos documentos gerados pelo módulo, como relatórios, pagamentos e fechamentos de caixa.

#### Passo a passo:

1. Acesse **Configurações > Modelo de Impressão**.

2. Clique no **campo de filtro** para localizar modelos já cadastrados.

3. Caso não encontre o modelo desejado, clique em **Adicionar**.

4. Selecione o **tipo de modelo** (exemplo: modelo de retiradas).

5. Complete o cadastro e configuração do modelo conforme necessário.

6. Salve as alterações.

* **Observação Importante:** Múltiplas abas podem ser utilizadas simultaneamente sem necessidade de fechar a aba em trabalho.

---

---

## R-1.4 - Funcionalidades da Barra Superior
**Objetivo:** Descrever as funcionalidades de acesso rápido disponíveis na barra superior do sistema, como comunicação de selos, notificações, calendário e integração com o sistema de senhas.  
**Tags:** `Selo Digital`, `Notificações`, `Alertas`, `Calendário`, `Siplan SGA`

### Intenções de Busca & Dúvidas Frequentes
- atalhos rápidos
- chamar senha de atendimento
- ícones da barra de cima
- Como eu chamo a próxima senha de atendimento pelo sistema?
- Onde eu vejo as notificações e alertas do sistema?
- Para que servem os ícones na barra superior do Orion?
- Tem algum atalho para a comunicação de selo digital?
- menu superior
- notificações do sistema

### Procedimento / Explicação
* **Acesso Rápido a Selo Digital:** Com apenas um clique, o usuário abre a rotina de comunicação de selo digital.

* **Notificações do Sistema:** O sistema envia alertas de pedidos abertos, facilitando o controle diário.

* **Calendário:** Permite adicionar e gerenciar feriados e outras datas importantes.

* **Integração com Siplan SGA:** O sistema possui integração com o **Siplan SGA** (sistema de gerenciamento de senhas), permitindo que cada usuário chame os atendimentos.

---

---

## R-1.5 - Segurança, Controle e Auditoria
**Objetivo:** Detalhar as ferramentas de segurança, controle e auditoria do Orion TN, incluindo auditoria de selos, relatórios gerenciais, dashboards e logs de atividades de usuários.  
**Tags:** `Segurança`, `Controle`, `Auditoria`, `Selos`, `Relatórios`, `Dashboard`, `Logs`

### Intenções de Busca & Dúvidas Frequentes
- log de usuário
- ver o que um usuário fez
- Onde eu consigo ver um log de tudo que um determinado usuário fez no sistema?
- Como acesso o manual de ajuda de uma tela específica?
- relatórios gerenciais
- auditoria de selo
- conferir selos com o TJ
- O sistema tem algum painel para ver os protocolos que estão perto de vencer?
- ferramentas de segurança
- Como eu faço para auditar os selos do sistema e comparar com os do TJ?
- dashboard de controle

### Procedimento / Explicação
O **ORION TN** possui um rigoroso sistema de controle e segurança.

* **Auditoria de Selos:** Oferece uma rotina para comparar os dados de selos do sistema com os do TJ, verificando pendências e divergências.

* **Relatórios para Recolhimento:** Disponibiliza diversos relatórios para fins de recolhimento e controle, como PEX, PEC Selos, e Auditorias de Selo.

* **Dashboard de Controle Estratégico:** Exibe protocolos em aberto, classificando-os por cores e status para alertar sobre prazos.

* **Manuais de Ajuda Integrados:** Cada tela possui um ícone de ajuda (?) que dá acesso rápido ao manual da respectiva rotina.

* **Logs e Históricos de Segurança:** O sistema registra todas as ações realizadas pelos usuários, permitindo buscas por período, usuário e atividade para garantir a segurança.

---

---

## D-1.5 - Cadastrar Tipos de Saída
**Objetivo:** Definir tipos de saída de valores para movimentações financeiras como devoluções e retiradas.  
**Tags:** `saída`, `tipo de saída`, `retirada`, `devolução`

### Intenções de Busca & Dúvidas Frequentes
- criar tipo de saída
- configurar saída de dinheiro
- Como cadastro um tipo de saída para devoluções?
- adicionar tipo de retirada
- Como criar uma saída personalizada?
- Onde configuro os tipos de saída no caixa?

### Procedimento / Explicação
#### Descrição:

Os tipos de saída definem as categorias de movimentações financeiras de saída, como devoluções e retiradas, permitindo rastreamento através do livro caixa.

#### Passo a passo:

1. Acesse **Configurações > Cadastros Auxiliares > Tipos de Saída**.

2. Clique em **Adicionar**.

3. Preencha o **tipo de saída** (exemplo: "Devolução").

4. Opcionalmente, selecione **Vincular ao Livro Caixa** se desejar que a saída seja contabilizada automaticamente.

5. Se vinculado ao livro caixa, configure:

   * A **conta** de saída

   * A **despesa** relacionada

6. Clique em **Conclusão** para cadastrar o tipo de saída.

* **Observação Importante:** Quando vinculado ao livro caixa, toda utilização dessa saída será automaticamente registrada na conta e despesa especificadas.

---

---

## R-1.6 - Outros Módulos Integrados
**Objetivo:** Apresentar brevemente os outros módulos que se integram ao Orion TN: GED (documentos), Stock (selos) e Caixa (financeiro).  
**Tags:** `Módulos`, `Integração`, `GED`, `Stock`, `Caixa`

### Intenções de Busca & Dúvidas Frequentes
- módulo GED
- módulo Stock
- Orion Stock
- integração de módulos
- O que eu faço no Orion Caixa?
- Orion Caixa
- Orion GED
- O que o módulo Orion Stock controla?
- módulo Caixa
- Para que serve o módulo Orion GED?

### Procedimento / Explicação
Os módulos **ORION Caixa**, **ORION Stock** e **ORION GED** compartilham o mesmo layout *clean* e intuitivo.

* **ORION GED:** Sistema de armazenamento e anexos de documentos do ORION.

* **ORION Stock:** Permite o controle de aquisição, consumo e distribuição de selos e materiais.

* **ORION Caixa:** Oferece gestão financeira completa, com controle de pagamentos, conciliação bancária, relatórios e mais.

---

---

## D-1.6 - Cadastrar Outros Serviços
**Objetivo:** Registrar tipos de serviços adicionais com opção de valor fixo ou aberto, para lançamento em pagamentos.  
**Tags:** `serviço`, `outros serviços`, `taxa`, `valor fixo`

### Intenções de Busca & Dúvidas Frequentes
- criar serviço adicional
- cadastrar taxa de serviço
- Como cadastro um serviço como 'Taxi'?
- adicionar tipo de serviço
- Onde adiciono outros serviços no caixa?
- Como definir um serviço com valor fixo?
- Como criar um serviço com valor variável?

### Procedimento / Explicação
#### Descrição:

Outros serviços permite cadastrar tipos de serviços adicionais com valor fixo ou variável, que estarão disponíveis durante o lançamento de pagamentos.

#### Passo a passo:

1. Acesse **Configurações > Cadastros Auxiliares > Outros Serviços**.

2. Clique em **Adicionar**.

3. Preencha o **nome do serviço** (exemplo: "Taxi").

4. Escolha se o serviço terá **valor fixo ou valor variável**:

   * **Valor Fixo:** O sistema trará sempre o mesmo valor pré-definido.

   * **Valor Variável:** O sistema deixará o campo aberto para digitação do valor na hora do pagamento.

5. Se valor fixo, preencha o **valor padrão**.

6. Clique em **Conclusão** para cadastrar o serviço.

* **Observação Importante:** Serviços com valor variável apresentam campo aberto para digitação do valor no momento do pagamento. Serviços com valor fixo sempre exibem o valor pré-cadastrado.

---

---

## R-1.7 - Change Log e Inovação Tecnológica
**Objetivo:** Explicar a funcionalidade de Change Log, que permite aos usuários acompanhar as atualizações, melhorias e correções implementadas em cada nova versão do sistema.  
**Tags:** `Change Log`, `Atualizações`, `Melhorias`, `Correções`, `Versões`

### Intenções de Busca & Dúvidas Frequentes
- log de alterações
- Onde eu vejo o que mudou na última atualização do sistema?
- Onde fica o log de atualizações do software?
- histórico de versões
- o que mudou na atualização
- Como sei quais correções foram feitas na nova versão do Orion?
- novidades do sistema
- notas da versão

### Procedimento / Explicação
O **Change Log**, presente em todos os sistemas, é uma aba que mostra todas as versões mais recentes, detalhando as melhorias, implementações e correções realizadas em cada uma.

---

---

## D-1.9 - Configurar Integração Parcela Express
**Objetivo:** Registrar dados da integração com Parcela Express e cadastrar máquinas de pagamento associadas.  
**Tags:** `parcela express`, `provedor de pagamento`, `maquininha`, `integração`

### Intenções de Busca & Dúvidas Frequentes
- Como configurar a integração com Parcela Express?
- integrar parcela express
- Como cadastro uma maquininha de pagamento?
- configurar maquininha de pagamento
- cadastrar provedor de pagamento
- Onde configuro as credenciais do provedor de pagamento?

### Procedimento / Explicação
#### Descrição:

A integração com Parcela Express permite processar pagamentos através do provedor, com cadastro de múltiplas máquinas de pagamento.

#### Passo a passo:

1. Acesse **Configurações > Parametrizações > Provedor de Pagamento**.

2. Clique para **selecionar o provedor** (Parcela Express).

3. Preencha os **dados de cadastro** do provedor conforme fornecido.

4. Na seção de **Maquininhas**, clique em **Adicionar** para cadastrar uma nova máquina.

5. Selecione o **tipo de máquina** (Firmas, Notas, etc.).

6. Preencha a **descrição** (exemplo: "Firmas 1", "Firmas 2", "Notas Escreventes").

7. Salve cada máquina cadastrada.

* **Observação Importante:** A descrição das máquinas facilita a localização durante o processamento de pagamentos. Múltiplas máquinas podem ser cadastradas conforme necessário.

---

---

## D-2.1_1 - Acessar o Módulo Orion Estoque
**Objetivo:** Acessar o módulo Orion Estoque através do ORION TN e visualizar os menus disponíveis conforme o perfil do usuário.  
**Tags:** `acesso`, `orion`, `estoque`, `módulo`

### Intenções de Busca & Dúvidas Frequentes
- entrar no módulo de estoque
- abrir orion estoque
- Onde fico o módulo de estoque no ORION TN?
- acessar sistema de estoque
- Como acesso o módulo Orion Estoque?
- Como entro no Orion Estoque?

### Procedimento / Explicação
#### Descrição:

O módulo Orion Estoque é um dos módulos integrados no ORION TN, oferecendo visual limpo, intuitivo e dinâmico para controle de inventário.

#### Passo a passo:

1. Acesse o **link do ORION TN** através do navegador de sua preferência.

2. Realize login com **seu usuário e senha**.

3. O sistema exibirá os **módulos liberados para seu perfil**.

4. Clique em **Orion Estoque** para abrir o módulo.

5. Você visualizará os **menus principais** e **submenus** disponíveis.

* **Observação Importante:** O módulo oferece uma interface web com fácil visualização. Você pode ajustar o zoom conforme necessário para melhor visualização.

---

---

## D-2.10 - Registrar Dados do Cartório
**Objetivo:** Manter registro geral de todos os campos e informações do cartório no módulo de estoque.  
**Tags:** `cartório`, `cadastro`, `dados`, `configuração`

### Intenções de Busca & Dúvidas Frequentes
- Onde fico as informações do cartório no estoque?
- Como atualizar dados cartoriais?
- cadastrar dados cartoriais
- registrar cartório
- Como cadastro os dados do meu cartório?
- configurar informações do cartório

### Procedimento / Explicação
#### Descrição:

Os dados do cartório centralizam todas as informações gerais do estabelecimento no módulo de estoque.

#### Passo a passo:

1. Acesse **Cadastros > Cartório**.

2. Preencha as **informações gerais** do cartório.

3. Clique em **Salvar**.

* **Observação Importante:** Estes dados servem como referência para todas as operações do módulo.

---

---

## D-2.11 - Configurar Modelos de Impressão
**Objetivo:** Criar modelos de impressão para relatórios e consultas do módulo de estoque.  
**Tags:** `modelo`, `impressão`, `relatório`, `configuração`

### Intenções de Busca & Dúvidas Frequentes
- definir modelo de relatório
- Como criar um modelo de impressão?
- Onde configuro os modelos de relatório?
- Como personalizar a impressão de listagem?
- configurar layout de impressão
- criar modelo de impressão

### Procedimento / Explicação
#### Descrição:

Os modelos de impressão permitem customizar o layout dos relatórios e consultas gerados pelo módulo.

#### Passo a passo:

1. Acesse **Cadastros > Modelos**.

2. O sistema exibirá os **modelos já cadastrados**.

3. Se nenhum modelo estiver configurado, clique em **Adicionar** para criar.

4. Configure as **informações** do modelo de impressão.

5. Clique em **Salvar**.

* **Observação Importante:** Se nenhum modelo estiver cadastrado, você não conseguirá imprimir relatórios até criar um. A configuração de modelo é essencial para relatórios em papel.

---

---

## D-2.12 - Configurar Parametrizações do Estoque
**Objetivo:** Definir parâmetros gerais de utilização do módulo de estoque, incluindo automação de consumo.  
**Tags:** `parametrização`, `configuração`, `estoque`, `operação`

### Intenções de Busca & Dúvidas Frequentes
- Onde configuro as parametrizações do estoque?
- parametrizar estoque
- Como ativar consumo manual ou automático?
- definir modo de operação
- Como configurar consumo automático?
- configurar parâmetros

### Procedimento / Explicação
#### Descrição:

As parametrizações definem como o estoque será operado, incluindo consumo automático ou manual.

#### Passo a passo:

1. Acesse **Cadastros > Parametrizações**.

2. Configure as **opções de consumo**:

   * **Automático:** Sistema consome automaticamente conforme serviços realizados

   * **Manual:** Consumo realizado manualmente pelo usuário

3. Configure outras **opções operacionais** do cartório conforme necessidade.

4. Clique em **Salvar**.

* **Observação Importante:** Consumo automático integra ORION TN e ORION Estoque, usando a próxima sequência disponível. Você pode fazer consumo manual mesmo com automático ativo.

---

---

## D-2.2_1 - Configurar Grupos de Permissões
**Objetivo:** Criar e configurar grupos de permissões com controle granular sobre acesso às telas e rotinas do módulo.  
**Tags:** `permissão`, `grupo`, `usuário`, `acesso`

### Intenções de Busca & Dúvidas Frequentes
- gerenciar grupos de usuário
- Como transferir um usuário de um grupo para outro?
- criar grupo de acesso
- configurar perfil de permissões
- Onde configuro as permissões por grupo?
- Como separar um usuário para um grupo específico?
- Como criar um novo grupo de permissões?

### Procedimento / Explicação
#### Descrição:

Os grupos de permissões permitem segmentar usuários e controlar o acesso a cada tela e rotina do módulo Estoque.

#### Passo a passo:

1. Acesse **Configurações > Usuários e Permissões > Grupos de Permissões**.

2. O sistema exibirá todos os menus e submenus com suas **telas e rotinas**.

3. Clique em **Criar Novo Grupo** para adicionar um grupo.

4. Visualize os usuários:

   * **Lado esquerdo:** Usuários COM permissão no grupo

   * **Lado direito:** Usuários SEM permissão no grupo

5. Selecione cada **tela e rotina** para indicar qual será liberada ou restrita.

6. Clique em **Salvar** para aplicar as permissões do grupo.

7. Para transferir um usuário, **remova-o do grupo atual** e **adicione-o ao novo grupo** com as permissões desejadas.

* **Observação Importante:** O controle de permissões é rigoroso. Você pode fazer configuração granular por tela e rotina dentro de cada menu.

---

---

## D-2.3 - Consultar Controle de Cheques
**Objetivo:** Visualizar registro e controle de todos os cheques recebidos no caixa.  
**Tags:** `cheques`, `controle`, `relatório`, `consulta`

### Intenções de Busca & Dúvidas Frequentes
- Onde fico o relatório de controle de cheques?
- ver controle de cheques
- Como consultar os cheques recebidos?
- relatório de cheques
- consultar cheques
- Como controlar cheques no caixa?

### Procedimento / Explicação
#### Descrição:

O relatório de controle de cheques permite acompanhar todos os cheques recebidos nos serviços.

#### Passo a passo:

1. Acesse **Relatórios > Controle de Cheques**.

2. Configure os **filtros** desejados:

   * **Período**

   * **Status**

   * **Outras dimensões**

3. Clique em **Gerar Relatório**.

4. O sistema exibirá lista de cheques com informações completas.

* **Observação Importante:** Se nenhum cheque foi lançado, o relatório retornará vazio.

---

---

## D-2.3_1 - Cadastrar Novo Usuário
**Objetivo:** Registrar novo usuário no módulo com dados básicos e definir suas permissões.  
**Tags:** `usuário`, `cadastro`, `acesso`, `permissão`

### Intenções de Busca & Dúvidas Frequentes
- criar novo usuário
- Como cadastrar um novo usuário?
- Como criar acesso para um novo colaborador?
- adicionar usuário
- Onde adiciono um novo usuário no estoque?
- registrar acesso de usuário

### Procedimento / Explicação
#### Descrição:

O cadastro de usuário permite registrar novos acessos ao módulo com informações básicas.

#### Passo a passo:

1. Acesse **Configurações > Usuários e Permissões > Usuários**.

2. Clique em **Adicionar**.

3. Preencha os **campos principais** de informação do usuário.

4. Clique em **Salvar**.

5. O usuário será criado e poderá ser incluído em grupos de permissões.

* **Observação Importante:** Após criar o usuário, você deve atribuí-lo a um grupo de permissões para definir seu acesso às funcionalidades.

---

---

## D-2.5 - Cadastrar Fornecedor
**Objetivo:** Registrar fornecedores fixos para aquisição de selos digitais e papel de segurança.  
**Tags:** `fornecedor`, `cadastro`, `aquisição`, `negócios`

### Intenções de Busca & Dúvidas Frequentes
- Como registrar fornecedores de selos?
- adicionar fornecedor
- registrar fornecedor
- Onde adiciono um novo fornecedor?
- cadastrar empresa fornecedora
- Como cadastro um fornecedor?

### Procedimento / Explicação
#### Descrição:

O cadastro de fornecedor permite registrar empresas e pessoas fornecedoras dos produtos utilizados no estoque.

#### Passo a passo:

1. Acesse **Negócios > Fornecedores**.

2. Clique em **Adicionar**.

3. Preencha os **campos de informação** do fornecedor.

4. Clique em **Salvar**.

* **Observação Importante:** Fornecedores cadastrados podem ser rapidamente selecionados em aquisições futuras.

---

---

## D-2.6 - Configurar Grupos de Distribuição
**Objetivo:** Criar grupos de distribuição e definir se a distribuição será por máquina ou por usuário.  
**Tags:** `distribuição`, `grupo`, `máquina`, `usuário`

### Intenções de Busca & Dúvidas Frequentes
- Como distribuir por usuário?
- Como distribuir por máquina?
- Como criar um grupo de distribuição?
- criar grupo de distribuição
- configurar distribuição
- Onde configuro os grupos de distribuição?
- adicionar grupo de máquinas

### Procedimento / Explicação
#### Descrição:

Os grupos de distribuição determinam como os produtos serão distribuídos entre usuários ou máquinas específicas do cartório.

#### Passo a passo:

1. Acesse **Negócios > Grupos de Distribuição**.

2. Clique em **Adicionar** para criar novo grupo.

3. Preencha o **nome do grupo**.

4. Escolha o **tipo de distribuição**:

   * **Por Usuário:** Selecione os usuários que receberão produtos deste grupo

   * **Por Máquina:** Selecione as máquinas que receberão produtos deste grupo

5. Selecione os **usuários ou máquinas** disponíveis para incluir no grupo.

6. Clique em **Salvar**.

* **Observação Importante:** As distribuições realizadas para este grupo estarão disponíveis apenas para os usuários ou máquinas cadastrados nele.

---

---

## D-2.8 - Cadastrar Tipo de Documento
**Objetivo:** Registrar tipos de documento aceitos no cartório, como CPF e outros documentos de identidade.  
**Tags:** `documento`, `cadastro`, `tipo`, `configuração`

### Intenções de Busca & Dúvidas Frequentes
- Como adicionar CPF como tipo de documento?
- Onde configuro os tipos de documento?
- Como cadastrar um tipo de documento?
- adicionar tipo de documento
- criar documento
- registrar tipo de identificação

### Procedimento / Explicação
#### Descrição:

Os tipos de documento permitem parametrizar quais identificações são aceitas para serviços.

#### Passo a passo:

1. Acesse **Negócios > Tipo de Documento**.

2. Visualize os **tipos já cadastrados** (exemplo: CPF).

3. Clique em **Adicionar** para criar novo tipo.

4. Preencha as **informações** do tipo de documento.

5. Clique em **Salvar**.

* **Observação Importante:** Você pode criar múltiplos tipos de documento conforme necessidade operacional.

---

---

## D-2.9 - Cadastrar Unidade de Medida
**Objetivo:** Registrar unidades de medida para controle de produtos, como unidade para selos e papel de segurança.  
**Tags:** `unidade`, `medida`, `cadastro`, `produto`

### Intenções de Busca & Dúvidas Frequentes
- Como usar unidade para controlar selos?
- registrar unidade
- adicionar unidade de medida
- Onde configuro as unidades de medida?
- Como cadastrar uma unidade de medida?
- criar tipo de medida

### Procedimento / Explicação
#### Descrição:

As unidades de medida definem como os produtos serão contabilizados. Normalmente usa-se "unidade" para selos e papel de segurança.

#### Passo a passo:

1. Acesse **Negócios > Unidade de Medida**.

2. Visualize a **unidade padrão** já cadastrada ("Unidade").

3. Para criar nova unidade, clique em **Adicionar**.

4. Preencha os **dados** da unidade de medida.

5. Clique em **Salvar**.

* **Observação Importante:** A unidade padrão é suficiente para a maioria dos cartórios, mas você pode criar outras conforme demanda.

---

---

## D-3.12 - Consultar Serviços Praticados
**Objetivo:** Fazer consulta detalhada de serviços com múltiplos filtros (CEPHAS, período, livro, termo, placa, RENAVAM).  
**Tags:** `consulta`, `serviço`, `detalhado`, `filtro`

### Intenções de Busca & Dúvidas Frequentes
- consultar detalhes de serviço
- buscar serviço praticado
- filtrar por tipo de serviço
- Como saber se tem certidão de um serviço?
- Como buscar um serviço específico?
- Como buscar por número de livro?
- Como filtrar por CEPHAS?

### Procedimento / Explicação
#### Descrição:

Consulta avançada de serviços com filtros específicos para encontrar serviços por tipo, período, livro, termo, veículo, etc.

#### Passo a passo:

1. Acesse **Firmas > Consultas > Serviços Praticados**.

2. Configure **filtros**:

   * **Tipo de Serviço:** Ex: termos CEPHAS

   * **Período:** Data desejada

   * **Número de Livro:** Livro específico

   * **Número de Termo:** Termo específico

   * **Placa:** Placa de veículo

   * **RENAVAM:** Número RENAVAM

3. Clique em **Consultar** ou **Filtrar**.

4. O sistema exibe serviços encontrados com:

   * **Data realizada**

   * **Serviço utilizado**

   * **Sequência de selo** utilizada

#### Ações Disponíveis (dentro de cada serviço):

- **Carimbo:** Visualizar carimbo impresso

- **Etiqueta de Ressalva:** Criar etiqueta especial

- **Consultar Selo no TJ:** Abrir diretamente no portal TJ

- **Editar/Excluir Termo:** Editar documento associado

- **Visualizar Anexo do Termo:** Ver documentação

* **Observação Importante:** Filtros trabalham em combinação. Você pode buscar apenas por período sem especificar outras dimensões.

---

---

## D-3.2_1 - Consultar Histórico de Aquisição
**Objetivo:** Visualizar todas as aquisições realizadas com filtros por usuário e detalhes de registro.  
**Tags:** `aquisição`, `consulta`, `histórico`, `relatório`

### Intenções de Busca & Dúvidas Frequentes
- ver histórico de aquisições
- Como consultar as aquisições realizadas?
- Onde visualizo o histórico de compras?
- consultar compras realizadas
- Como filtrar aquisições por usuário?
- filtrar aquisições por usuário

### Procedimento / Explicação
#### Descrição:

A consulta de aquisição permite rastrear todas as compras com detalhes de quem as fez e quando.

#### Passo a passo:

1. Acesse **Administração > Aquisição**.

2. Na **primeira tela de consulta**, visualize:

   * Aquisições já realizadas

   * Quantidade adquirida

   * Disponibilidade para distribuição

3. Clique no **botão de registro** para ver detalhes de quem fez, quando e qual foi a distribuição.

4. Clique em **Visualizar** para revisar o preenchimento da aquisição.

5. Use **filtros** para refinar a busca:

   * Filtrar por **usuário específico** que realizou a aquisição

6. Clique em **Filtrar** para aplicar.

* **Observação Importante:** O histórico completo rastreia cada aquisição e distribuição, fornecendo auditoria completa.

---

---

## D-3.2_2 - Visualizar Dashboard de Protocolos
**Objetivo:** Visualizar todos os protocolos em aberto no cartório com status e codificação de urgência por dias abertos.  
**Tags:** `dashboard`, `protocolo`, `visualização`, `status`

### Intenções de Busca & Dúvidas Frequentes
- O que significam as cores dos protocolos?
- Como visualizar todos os protocolos abertos?
- Onde vejo o status de cada protocolo?
- conferir status de protocolo
- visualizar atos em aberto
- ver painel de protocolo
- Como saber quantos dias um protocolo está aberto?

### Procedimento / Explicação
#### Descrição:

O dashboard exibe visualmente todos os protocolos em aberto com codificação por cores indicando tempo de conclusão.

#### Passo a passo:

1. Acesse **Dashboard > Protocolos** (primeira opção do menu).

2. O sistema exibirá **todos os protocolos abertos** com status de cada um.

3. Observe as **cores dos protocolos**:

   * **Cinza:** 0 a 5 dias em aberto

   * **Amarelo:** 6 a 30 dias em aberto (sinal de atenção)

   * **Vermelho:** Acima de 30 dias em aberto (atenção urgente)

4. Configure **filtros** para refinar a visualização:

   * **Status do Protocolo:** Filtrar por status específico

   * **Situação do Protocolo:** Filtrar por situação cadastrada

   * **Natureza:** Tipo de ato

   * **Escrevente:** Quem está trabalhando no protocolo

   * **Dias em Aberto:** Período específico

#### Ações Disponíveis:

- **Editar:** Clique no ícone de lápis para abrir e editar o protocolo

- **Trâmite:** Clique para notificar escreventes ou enviar mensagens internas

  * Digite a mensagem (ex: "Coletar documento do cliente")

  * Selecione usuários a notificar

  * Clique em **Conclusão** para enviar

  * Usuários selecionados receberão alerta de **Notificações** no sistema

- **Andamentos:** Visualize o log completo do protocolo (quem fez, quando, IP da máquina)

- **Movimentação Financeira:** Visualize ou lance entrada/saída de valores

* **Observação Importante:** Situações podem ser personalizadas (ex: "Documento faltante", "Liberado para conferência", "Aguardando parte"). As cores alertam sobre tempo de conclusão.

---

---

## D-3.21 - Criar Protocolo de Nota
**Objetivo:** Registrar novo protocolo com espécie, natureza, solicitante e informações complementares para elaboração de escritura.  
**Tags:** `protocolo`, `nota`, `criação`, `registro`

### Intenções de Busca & Dúvidas Frequentes
- Como criar um protocolo?
- criar protocolo novo
- abrir protocolo
- registrar nota
- O que é espécie e natureza?
- Como preencher as informações iniciais?

### Procedimento / Explicação
#### Descrição:

Protocolo é o registro principal de nota. Sistema organiza em cards para facilitar preenchimento gradual.

#### Passo a passo:

1. Acesse **Notas > Protocolos > Novo Protocolo**.

2. Preencha **campos iniciais obrigatórios**:

   * **Espécie:** Tipo de documento (ex: compra e venda)

   * **Natureza:** Categoria específica

   * **Solicitante:** Busque ou crie cliente

3. Clique em **Salvar**.

4. Sistema libera **próximos campos** em cards:

   * **Dados Principais do Protocolo**

   * **Informações Complementares**

   * **Qualificação das Partes**

   * **Imóvel**

   * **Custas**

   * **Editor de  texto** (minuta, livro, traslado)

5. **Abra cada card** conforme necessário.

6. **Feche cards** para visualização limpa.

7. Preencha campos em **qualquer ordem**.

#### Cards Principais:

- **Dados Principais:** Info base do protocolo

- **Complementares:** Informações adicionais

- **Qualificação Partes:** Dados dos contratantes

- **Imóvel:** Descrição do bem

- **Custas:** Valores de serviço

- **Editor:** Gerar minuta/livro

* **Observação Importante:** Organização em cards evita poluição visual. Preencha em ordem de preferência.

---

---

## D-3.22 - Preencher Qualificação de Parte
**Objetivo:** Registrar dados completos de cada contratante (alienante, adquirente, etc.) com suporte a IA.  
**Tags:** `protocolo`, `parte`, `qualificação`, `informações`

### Intenções de Busca & Dúvidas Frequentes
- qualificar pessoa
- Como usar IA para preencher dados?
- adicionar parte
- Como alterar modelo de qualificação?
- preencher dados de contratante
- Como preenchimatos de uma parte?

### Procedimento / Explicação
#### Descrição:

Qualificação de parte registra dados completos de contratantes com flexibilidade de modelos e preenchimento por IA.

#### Passo a passo:

1. Na **tela do Protocolo**, abra card **Qualificação das Partes**.

2. Clique em **Qualificar** para primeira parte.

3. Sistema abre **formulário de qualificação** com:

   * Modelo selecionado (ex: Pessoa Física)

   * Campos a preencher

4. Você pode:

   * **Alterar modelo:** Clique no dropdown para mudar (ex: para Casado Comunhão)

   * **Preencher manualmente:** Digite informações

   * **Usar IA:** Clique em **Preencher com IA**

#### Preenchimento com IA:

1. Clique em **Preencher com IA**.

2. **Digitalize ou importe** documento (CNH, RG, etc.).

3. Sistema **lê documento** e preenche automaticamente.

4. **Revise informações** preenchidas.

5. Clique em **Subscrever** para aceitar.

6. Clique em **Salvar**.

#### Campos Obrigatórios:

- Campos em **vermelho** são obrigatórios

- Campos em **branco** são opcionais

7. Repita para **cada parte** do protocolo (alienante, adquirente, cônjuge, etc.).

8. Salve cada uma.

* **Observação Importante:** Modelos de qualificação são configuráveis. IA depende de qualidade de imagem. Múltiplas partes podem ser adicionadas.

---

---

## D-3.23 - Preencher Dados de Imóvel
**Objetivo:** Registrar dados do imóvel (endereço, matrícula, cartório, página, alienante/adquirente) com suporte a IA.  
**Tags:** `protocolo`, `imóvel`, `qualificação`, `matrícula`

### Intenções de Busca & Dúvidas Frequentes
- Como configurar dados bancários?
- Como preencher dados do imóvel?
- adicionar propriedade
- Como usar IA para ler matrícula?
- preencher dados do imóvel
- qualificar imóvel

### Procedimento / Explicação
#### Descrição:

Dados de imóvel registram localização, matrícula, cartório e porcentagens de transferência com suporte a IA.

#### Passo a passo:

1. Na **tela do Protocolo**, abra card **Imóvel**.

2. Você pode:

   * **Preencher manualmente** os campos

   * **Usar IA para buscar matrícula:** Clique para digitalizar/importar

#### Preenchimento com IA:

1. Clique em **botão de IA** no card de imóvel.

2. **Digitalize ou importe** matrícula (documento de registro).

3. Sistema **lê matrícula** e preenche automaticamente.

4. **Revise informações** preenchidas.

5. Clique em **Salvar**.

#### Campos do Imóvel:

- **Informações Principais:** Endereço, cidade, Estado

- **Matrícula:** Número do registro

- **Cartório:** Qual cartório registrou

- **Tipo:** Rural ou Urbano

- **Página:** Tipo de página

- **Alienante/Adquirente:** Percentual de transferência

- **Dados Bancários:** Contas para comunicação

3. Preencha os **cards separados** conforme necessário:

   * Dados do imóvel (endereço, etc.)

   * Matrícula e informações de registro

   * Alienante/adquirente (percentuais)

   * Dados bancários

4. Clique em **Salvar** para cada seção.

#### Observação:

- Campos em **vermelho** no formulário de qualificação são obrigatórios

- Campos em **branco** são opcionais

* **Observação Importante:** Dados de imóvel não são obrigatórios para gerar recibo, mas essenciais para minuta/livro. IA lê matrícula automaticamente. Percentuais usados em comunicação.

---

---

## D-3.24 - Registrar Custas do Protocolo
**Objetivo:** Registrar tipos de atos e seus valores para cálculo total de emolumentos.  
**Tags:** `custas`, `protocolo`, `atos`, `valores`

### Intenções de Busca & Dúvidas Frequentes
- adicionar custas
- registrar atos
- preencher valores
- Como preencher custas?
- Como definir valor declarado?
- Como adicionar mais de um ato?

### Procedimento / Explicação
#### Descrição:

Custas registram os atos realizados e seus valores. Necessárias para gerar recibo e selos digitais.

#### Passo a passo:

1. Na **tela do Protocolo**, abra card **Custas**.

2. O sistema exibe **campos de custas** já preenchidos.

3. Configure:

   * **Tipo de Escritura:** Ex: Compra e Venda

   * **Valor Declarado:** Valor do imóvel/serviço

4. Para **adicionar atos adicionais**, clique em **adicionar**.

5. Selecione **tipo de ato adicional** (ex: Traslado, Segunda Escritura).

6. Sistema calcula **totalizações automaticamente**.

7. Clique em **Salvar**.

#### Campos Obrigatórios para Recibo:

- **Livro:** Número do livro (consumo de papel)

- **Folha:** Número da folha

- **Solicitante**

- **Custas** (tipo e valor)

* **Observação Importante:** Livro e folha são consumidos automaticamente se configurado consumo automático. Necessários para gerar selo digital.

---

---

## D-3.25 - Gerar Recibo de Protocolo
**Objetivo:** Gerar recibo oficial do protocolo com número, data e informações de custas, disparando geração de selo digital.  
**Tags:** `recibo`, `protocolo`, `geração`, `selo digital`

### Intenções de Busca & Dúvidas Frequentes
- Como gerar o recibo?
- O que é lavrado?
- Quando posso gerar recibo?
- criar recibo
- gerar número de protocolo
- lavrar protocolo

### Procedimento / Explicação
#### Descrição:

Recibo é geração oficial que dispara criação de número de protocolo, geração e comunicação de selo digital.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Gerar Recibo**.

2. Sistema **valida campos obrigatórios**:

   * Solicitante

   * Custas

   * Livro e Folha

3. Se algum campo obrigatório falta, sistema **bloqueia** com mensagem.

4. Se tudo está ok, clique **Confirmar**.

5. Sistema realiza:

   * **Gera número de protocolo** automaticamente

   * **Muda status para Lavrado**

   * **Gera selo digital** (se configurado)

   * **Comunica ao TJ** (se configurado)

6. Visualize o **novo número de protocolo** na tela.

7. Acesse **Visualizar Selo Digital** para confirmar geração.

#### Após Recibo:

- Cliente pode fazer pagamentos (via Caixa)

- Escrevente pode usar editor para minuta/livro

- Terceiros podem preencher índices

* **Observação Importante:** Gerar recibo antes de estar tudo preenchido resultará em protocolo com status de andamento. Alguns campos podem ser preenchidos depois se não forem obrigatórios.

---

---

## D-3.26 - Duplicar Protocolo
**Objetivo:** Criar novo protocolo com as mesmas informações de um protocolo existente.  
**Tags:** `protocolo`, `duplicação`, `cópia`, `atalho`

### Intenções de Busca & Dúvidas Frequentes
- Como duplicar um protocolo?
- Como criar protocolo similar?
- replicar protocolo
- copiar protocolo
- duplicar estrutura

### Procedimento / Explicação
#### Descrição:

Duplicação cria novo protocolo copiando todas as informações do anterior, economizando tempo.

#### Passo a passo:

1. Na **tela do Protocolo** já aberto, clique em **Duplicar**.

2. Sistema cria **novo protocolo** com:

   * Mesmas partes

   * Mesmo imóvel

   * Mesmas custas

   * Mesmas informações complementares

3. Novo protocolo recebe **novo número** ao gerar recibo.

4. Edite conforme necessário.

* **Observação Importante:** Duplicação economiza tempo em operações repetidas (ex: retificações, comunicações). Novo protocolo é completamente independente.

---

---

## D-3.27 - Preencher Protocolo com IA
**Objetivo:** Usar inteligência artificial para preencher automaticamente dados de protocolo a partir de minuta ou matrícula.  
**Tags:** `protocolo`, `ia`, `preenchimento`, `minuta`

### Intenções de Busca & Dúvidas Frequentes
- usar ia
- preencher com documento
- Como preencher protocolo com IA?
- Como digitalizar minuta para IA?
- ler minuta
- Como o sistema lê documentos?

### Procedimento / Explicação
#### Descrição:

Preenchimento por IA importa minuta/matrícula e preenche automaticamente partes, imóvel e informações.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Preencher com IA**.

2. **Digitalize ou importe** documento:

   * Minuta de escritura

   * Matrícula

   * Outro documento

3. Sistema **lê documento** via IA/OCR.

4. Sistema traz **informações extraídas**.

5. **Revise e confirme** preenchimento.

6. Clique em **Salvar**.

7. Informações são **inseridas nos cards** apropriados:

   * Partes → Card Qualificação

   * Imóvel → Card Imóvel

   * Etc.

* **Observação Importante:** Qualidade de resultado depende de qualidade da imagem. Minuta em bom estado = melhor leitura. Sempre revise dados preenchidos.

---

---

## D-3.3 - Visualizar Dashboard de Envio para Registro
**Objetivo:** Acompanhar protocolos encaminhados para registro de nomes, visualizando status de envio, exigências e retorno.  
**Tags:** `dashboard`, `registro`, `envio`, `acompanhamento`

### Intenções de Busca & Dúvidas Frequentes
- consultar protocolos registrados
- ver status de registro
- Como saber se há exigências de registro?
- Onde vejo se um protocolo foi registrado?
- acompanhar envio para registro
- Como acompanhar protocolos enviados para registro?

### Procedimento / Explicação
#### Descrição:

Dashboard específico para controle de protocolos encaminhados para registro de nomes, com visualização de status e exigências.

#### Passo a passo:

1. Acesse **Dashboard > Envio para Registro** (segunda opção do menu).

2. O sistema exibirá controle de tudo encaminhado para registro.

3. Utilize **filtros** para refinar:

   * **Escrevente:** Quem encaminhou

   * **Período:** Intervalo de datas

   * **Status:** Pendente de envio, retornado com exigência, registrado

4. Visualize informações de acompanhamento e facilmente identifique pendências.

* **Observação Importante:** Este dashboard é apenas para acompanhamento visual de registros. Funcionalidades completas de envio estão em Administração.

---

---

## D-3.32 - Visualizar Andamentos do Protocolo
**Objetivo:** Ver registro completo de tudo realizado no protocolo (quem, quando, o quê, IP).  
**Tags:** `protocolo`, `log`, `histórico`, `auditoria`

### Intenções de Busca & Dúvidas Frequentes
- visualizar ações
- consultar histórico
- Como ver o que foi feito no protocolo?
- Quem fez uma alteração?
- Quando foi feita uma ação?
- ver log do protocolo

### Procedimento / Explicação
#### Descrição:

Andamentos registram rigorosamente todas ações no protocolo com usuário, data, hora e IP da máquina.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Andamentos**.

2. Sistema exibe **histórico completo**:

   * **Por Usuário:** Quem realizou a ação

   * **Data e Hora:** Quando foi realizado

   * **Observação:** O que foi feito

   * **IP da Máquina:** De onde foi realizado

3. Visualize em **ordem cronológica**.

4. Use para **auditar** qualquer alteração ou **rastrear** evolução.

* **Observação Importante:** Registro rigoroso para auditoria e conformidade. Impossível falsificar ou ocultar ações.

---

---

## D-3.33 - Anexar Documento no Protocolo
**Objetivo:** Adicionar documentos digitalizados, fotografados ou importados ao protocolo.  
**Tags:** `protocolo`, `anexo`, `documento`, `digitalização`

### Intenções de Busca & Dúvidas Frequentes
- importar arquivo
- Posso capturar com webcam?
- Como anexar documentos?
- Posso digitalizar na hora?
- adicionar anexo
- digitalizar documento

### Procedimento / Explicação
#### Descrição:

Sistema permite anexar documentos por digitalização, webcam ou importação de arquivo.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Anexos**.

2. Você tem opções:

   * **Digitalizar:** Colocar no scanner

   * **Importar:** Selecionar arquivo

   * **Webcam:** Capturar fotografia

3. Escolha opção desejada.

4. Sistema **registra documento**.

5. Visualize anexos já adicionados.

* **Observação Importante:** Múltiplos anexos podem ser adicionados. Essencial para certidão reprográfica e comunicações.

---

---

## D-3.34 - Configurar Trâmites do Protocolo
**Objetivo:** Registrar comunicações internas no protocolo para notificar equipe sobre pendências.  
**Tags:** `protocolo`, `trâmite`, `comunicação`, `interna`

### Intenções de Busca & Dúvidas Frequentes
- adicionar observação
- notificar escrevente
- enviar recado
- Como enviar recado no protocolo?
- Como notificar alguém?

### Procedimento / Explicação
#### Descrição:

Trâmites registram comunicações internas para orquestração de equipe.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Trâmites**.

2. Digite **mensagem** (ex: "Revisar qualificação das partes").

3. Selecione **usuários a notificar**.

4. Clique em **Conclusão**.

5. Usuários selecionados recebem **alerta de notificação**.

* **Observação Importante:** Facilita comunicação interna sem sair do sistema.

---

---

## D-3.36 - Bloquear/Desbloquear Protocolo
**Objetivo:** Bloquear protocolo em caso de fraude ou ordem judicial, impedindo qualquer edição.  
**Tags:** `protocolo`, `bloqueio`, `judicial`, `segurança`

### Intenções de Busca & Dúvidas Frequentes
- bloquear ato
- aplicar bloqueio
- Como desbloquear?
- bloquear por fraude
- Como bloquear um protocolo?

### Procedimento / Explicação
#### Descrição:

Bloqueio judicial/fraude impede qualquer edição do protocolo.

#### Passo a passo:

1. Na **tela do Protocolo**, localize **opção de Bloqueio**.

2. Clique para **aplicar bloqueio**.

3. Sistema marca protocolo como **bloqueado**.

4. Ninguém consegue **editar ou alterar** o protocolo.

5. Para **desbloquear**, clique novamente.

* **Observação Importante:** Bloqueio é proteção contra fraude ou por determinação judicial.

---

---

## D-3.38 - Consumir Papel de Segurança
**Objetivo:** Registrar consumo de papel de segurança usado na escritura.  
**Tags:** `protocolo`, `papel`, `consumo`, `estoque`

### Intenções de Busca & Dúvidas Frequentes
- Como registrar papel que usei?
- controlar papel
- registrar papel consumido
- lançar papel
- Como controlar papel de segurança?

### Procedimento / Explicação
#### Descrição:

Consumo de papel integra protocolo com estoque para rastreamento.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Consumo de Papel**.

2. Sistema **lista papel disponível** para consumo.

3. Configure:

   * **Série**

   * **Sequência**

   * **Quantidade**

4. Clique em **Salvar**.

5. Papel é **debitado do estoque** automaticamente.

* **Observação Importante:** Se consumo automático está configurado, papel já foi consumido ao gerar recibo.

---

---

## D-3.40 - Qualificar Partes no Editor
**Objetivo:** Finalizar qualificação de partes para gerar minuta no editor de  texto.  
**Tags:** `editor`, `qualificação`, `parte`, `minuta`

### Intenções de Busca & Dúvidas Frequentes
- preparar para livro
- Como qualificar partes para gerar minuta?
- qualificar para minuta
- O que acontece na qualificação?

### Procedimento / Explicação
#### Descrição:

Qualificação final prepara partes para inserção na minuta com modelo apropriado.

#### Passo a passo:

1. No **Editor de  texto**, abra card **Qualificação de Partes**.

2. Clique em **botão de qualificação** para cada parte.

3. Sistema traz **dados preenchidos**.

4. Você pode **alterar modelo** de qualificação (Pessoa Física, Casado, etc.).

5. Selecione **modelo apropriado** para tipo de contratante.

6. Clique em **Salvar**.

7. Repita para **cada parte**.

* **Observação Importante:** Qualificação no editor garante que dados apareçam corretamente na minuta.

---

---

## D-3.41 - Qualificar Imóvel no Editor
**Objetivo:** Finalizar qualificação de imóvel para inserção na minuta.  
**Tags:** `editor`, `imóvel`, `qualificação`, `minuta`

### Intenções de Busca & Dúvidas Frequentes
- Como qualificar imóvel na minuta?
- qualificar bem
- preparar imóvel

### Procedimento / Explicação
#### Descrição:

Qualificação de imóvel finaliza dados para apresentação na minuta.

#### Passo a passo:

1. No **Editor de  texto**, abra card **Qualificação de Imóvel**.

2. Clique em **botão de qualificação**.

3. Sistema traz **dados de imóvel** cadastrado.

4. Você pode **alterar modelo** de apresentação.

5. Revise **campos** preenchidos.

6. Clique em **Salvar**.

* **Observação Importante:** Imóvel deve ter dados mínimos preenchidos antes de qualificar.

---

---

## D-3.42 - Adicionar Minuta no Editor
**Objetivo:** Adicionar modelo de minuta ao protocolo para gerar documento de escritura.  
**Tags:** `editor`, `minuta`, `modelo`, `geração`

### Intenções de Busca & Dúvidas Frequentes
- Como mesclar dados na minuta?
- Como gerar uma minuta?
- Como escolher modelo?
- gerar minuta
- criar documento
- adicionar escritura

### Procedimento / Explicação
#### Descrição:

Adição de minuta mescla dados qualificados com modelo escolhido para gerar documento.

#### Passo a passo:

1. No **Editor de  texto**, abra card **Minuta**.

2. Clique em **Adicionar** minuta.

3. **Selecione modelo** desejado (ex: Compra e Venda).

4. Sistema **mescla** automaticamente:

   * Partes qualificadas

   * Imóvel qualificado

   *  texto modelo

5. Clique em **Visualizar** para ver resultado.

6. Sistema exibe **minuta completa** com todos os dados.

7. Você pode:

   * **Fazer edição manual:** Clicar em ícone de edição

   * **Enviar via WhatsApp:** Para cliente revisar

   * **Baixar:** Fazer download em PDF

   * **Assinar digitalmente**

   * **Excluir:** Se desejar nova minuta

8. Quando aprovado, clique em **Concluir**.

#### Próximo Passo:

- Gerar livro a partir da minuta

* **Observação Importante:** Minuta é documento intermediário. Pode ser enviada ao cliente para revisão antes de lavrar no livro. Modelo é configurável.

--

---

---

## D-3.43 - Gerar Livro a partir de Minuta
**Objetivo:** Gerar livro final mescla minuta com modelo de livro, preparando para assinatura e entrega.  
**Tags:** `editor`, `livro`, `geração`, `assinatura`

### Intenções de Busca & Dúvidas Frequentes
- O que entra no livro?
- Como gerar o livro?
- processar livro
- gerar documento final
- Como assinar livro?
- criar livro

### Procedimento / Explicação
#### Descrição:

Livro é documento final que mescla minuta com modelo de livro, incluindo assinaturas e selos.

#### Passo a passo:

1. Na **tela do Editor**, com **minuta pronta**, clique em **Gerar Livro**.

2. Sistema **mescla**:

   * Abertura do livro (com modelo)

   * Minuta (partes e imóvel)

   * Encerramento (com assinaturas e QR Codes)

   * Informações de selos digitais

3. Sistema traz **livro completo** para visualização.

4. Você pode:

   * **Transcrever Valores:** Converter números em palavras (ex: 500 mil = "quinhentos mil")

   * **Formatar Documento:** Auto-formatar conforme configuração

   * **Gerar Traslado:** Próximo passo

   * **Visualizar:** Ver prévia com marca d'água

   * **Imprimir:** Impressão definitiva (bloqueia edição se configurado)

   * **Alterar Status de Impressão**

#### Transcrição de Valores:

1. Localize campo com valor (ex: "500.000,00")

2. Clique em **Transcrição de Valores**.

3. Selecione **tipo de conversão** (Reais, etc.)

4. Sistema insere  texto: "500.000,00 (quinhentos mil reais)"

5. Clique em **Salvar**.

* **Observação Importante:** Livro é documento oficial. Marca d'água aparece em prévia. Impressão definitiva pode bloquear edição.

---

---

## D-3.44 - Gerar Traslado do Livro
**Objetivo:** Gerar cópia do livro (traslado) para entrega ao cliente, sem assinaturas de partes.  
**Tags:** `editor`, `traslado`, `cópia`, `entrega`

### Intenções de Busca & Dúvidas Frequentes
- preparar entrega
- Qual é a diferença entre livro e traslado?
- gerar cópia
- Como gerar traslado?
- criar traslado

### Procedimento / Explicação
#### Descrição:

Traslado é cópia do livro preparada para entrega, sem assinaturas de partes (apenas cartório).

#### Passo a passo:

1. Na **tela do Editor**, com **livro pronto**, clique em **Gerar Traslado**.

2. Sistema **cria traslado** excluindo:

   * Assinaturas de partes

   * Mantendo tudo mais do livro

3. Sistema muda **início e final** para modelo de traslado.

4. Visualize o **traslado resultante**.

5. Você pode:

   * **Editar:** Fazer ajustes

   * **Imprimir:** Impressão para entrega

   * **Formatar:** Auto-formatar

6. Quando pronto, **salve**.

#### Entrega:

- Traslado é o que você **entrega ao cliente**

- Livro fica no cartório

* **Observação Importante:** Traslado é diferente de livro. Exclui assinaturas de contratantes, mantém tudo mais.

---

---

## D-3.45 - Consultar Protocolos
**Objetivo:** Fazer busca avançada de protocolos com múltiplos filtros (número, escrevente, período, status).  
**Tags:** `consulta`, `protocolo`, `busca`, `filtro`

### Intenções de Busca & Dúvidas Frequentes
- Como buscar um protocolo?
- buscar protocolo
- localizar protocolo
- Como filtrar protocolos?
- Como ver todos os protocolos de um período?
- pesquisar ato

### Procedimento / Explicação
#### Descrição:

Consulta avançada de protocolos com múltiplos filtros para encontrar rapidamente.

#### Passo a passo:

1. Acesse **Notas > Consultas > Protocolos**.

2. Configure **filtros disponíveis**:

   * **Período:** Data desejada

   * **Natureza:** Tipo de ato

   * **Escrevente:** Quem fez

   * **Status:** Andamento, Lavrado, etc.

3. Clique em **Consultar** ou **Filtrar**.

4. Sistema traz **protocolos encontrados**.

5. Para cada protocolo, visualize:

   * **Número**

   * **Status**

   * **Interessado**

   * **Natureza**

   * **Livro/Folha**

6. Clique em protocolo para **visualizar/editar**.

* **Observação Importante:** Filtros trabalham em combinação. Pesquisa é rápida mesmo com grande volume.

---

---

## D-3.46 - Consultar Índices de Protocolos
**Objetivo:** Consultar protocolos por livro/folha para geração de índices e comunicações.  
**Tags:** `consulta`, `índice`, `livro`, `folha`

### Intenções de Busca & Dúvidas Frequentes
- buscar por livro
- Como gerar índice?
- Como buscar protocolos de um livro específico?
- ver índices
- pesquisar por folha

### Procedimento / Explicação
#### Descrição:

Consulta de índice mostra quais protocolos utilizaram cada livro e folha.

#### Passo a passo:

1. Acesse **Notas > Consultas > Índice**.

2. Configure **filtros**:

   * **Período:** Data desejada

   * **Livro:** Número do livro (opcional)

   * **Folha:** Número da folha (opcional)

3. Clique em **Consultar**.

4. Sistema traz **protocolos por livro/folha**.

5. Visualize:

   * **Protocolo**

   * **Interessado**

   * **Natureza**

   * **Livro/Folha utilizados**

6. Clique para **abrir protocolo**.

* **Observação Importante:** Essencial para gerar índices e conferir utilização de livros.

---

---

## D-3.49 - Configurar Natureza de Ato
**Objetivo:** Criar e configurar tipos de natureza de ato com centrais de comunicação, partes e participações.  
**Tags:** `configuração`, `natureza`, `ato`, `cadastro`

### Intenções de Busca & Dúvidas Frequentes
- adicionar natureza
- Como criar uma natureza nova?
- Como configurar centrais de comunicação?
- configurar tipo de ato
- criar natureza

### Procedimento / Explicação
#### Descrição:

Configuração de natureza define tipos de atos e suas comunicações.

#### Passo a passo:

1. Acesse **Configurações > Natureza**.

2. Clique em **Adicionar** nova natureza.

3. Configure:

   * **Nome:** Tipo de ato (ex: Compra e Venda)

   * **Centrais de Comunicação:** Quais centrais recebem este ato

   * **Partes:** Quais tipos de partes (alienante, adquirente, etc.)

   * **Participações:** Detalhamento para centrais

4. Arraste **partes** para dentro se quiser customizar.

5. Clique em **Salvar**.

* **Observação Importante:** Totalmente customizável. Cada cartório configura conforme necessário.

---

---

## D-3.50 - Configurar Modelos de Minuta/Livro/Traslado
**Objetivo:** Criar e configurar modelos de minuta, livro e traslado com variáveis e layout.  
**Tags:** `configuração`, `modelo`, `editor`, `texto`

### Intenções de Busca & Dúvidas Frequentes
- adicionar variável
- Como criar um modelo novo?
- Como configurar fonte?
- criar modelo de minuta
- configurar layout
- Como adicionar variáveis?

### Procedimento / Explicação
#### Descrição:

Modelos são  textos com variáveis que o sistema substitui com dados do protocolo.

#### Passo a passo:

1. Acesse **Configurações > Modelos** (ou similar, conforme sua permissão).

2. Clique em **Adicionar** modelo.

3. Digite ** texto base** do seu modelo.

4. Ao digitar, **variáveis disponíveis** aparecem para inserir (ex: {{nome_cliente}}, {{valor}}, etc.).

5. **Selecione variáveis** desejadas para substituição automática.

6. Configure **estilo**:

   * Fonte

   * Tamanho

   * Espaçamento

7. Clique em **Salvar**.

* **Observação Importante:** Modelos são base da minuta/livro. Cada cartório tem seus próprios. Variáveis são substituídas automaticamente.

---

---

## D-3.51 - Configurar Tabela de Custas
**Objetivo:** Definir valores de serviços e atos para cálculo automático de emolumentos.  
**Tags:** `configuração`, `custas`, `tabela`, `preços`

### Intenções de Busca & Dúvidas Frequentes
- Como definir valores?
- adicionar custo
- Como mudar preço de serviço?
- criar tabela
- configurar preços

### Procedimento / Explicação
#### Descrição:

Tabela de custas centraliza todos os preços para cálculo automático.

#### Passo a passo:

1. Acesse **Configurações > Custas** (ou similar).

2. Visualize **tabela de custas** existente.

3. Para **adicionar novo**, clique em **Adicionar**.

4. Configure:

   * **Tipo de Ato/Serviço:** Qual serviço

   * **Valor:** Preço unitário

   * **Cálculo:** Como calcula (fixo, percentual, etc.)

5. Clique em **Salvar**.

6. Para **editar existente**, clique em ato e altere.

* **Observação Importante:** Alterações de custas afetam novos protocolos. Histórico é mantido.

---

---

## D-3.52 - Visualizar Change Log do Sistema
**Objetivo:** Acompanhar novidades, correções e melhorias do sistema ORION TN nas últimas versões.  
**Tags:** `sistema`, `atualização`, `novidade`, `versão`

### Intenções de Busca & Dúvidas Frequentes
- Como saber quais são as novidades?
- ver atualizações
- Onde vejo as correções?
- consultar versão
- ver novidades
- Como saber qual versão estou usando?

### Procedimento / Explicação
#### Descrição:

Change Log mostra histórico de todas as atualizações, correções e melhorias do sistema.

#### Passo a passo:

1. Na **tela inicial**, procure **versão** no canto inferior direito.

2. Ao lado, clique em **link do Change Log**.

3. Sistema abre **página com histórico completo**.

4. Visualize:

   * **Versão** do sistema

   * **Data de lançamento**

   * **Novidades** implementadas

   * **Correções** realizadas

   * **Melhorias** efetuadas

5. Fique **atualizado** de funcionalidades novas.

* **Observação Importante:** Importante acompanhar para conhecer novas funcionalidades. Atualizações são frequentes.

---

---

## D-3.57 - Gerenciar Comissões de Escreventes
**Objetivo:** Configurar planos de comissão diferenciados para firmas, notas e mensalistas.  
**Tags:** `comissão`, `configuração`, `escrevente`, `plano`

### Intenções de Busca & Dúvidas Frequentes
- configurar percentual
- adicionar escrevente
- Como configurar comissão?
- Como definir percentual?
- criar plano de comissão

### Procedimento / Explicação
#### Descrição:

Plano de comissão define percentual sobre serviços que escrevente realiza.

#### Passo a passo:

1. Acesse **Administração > Comissões**.

2. Clique em **Adicionar** novo plano.

3. Configure:

   * **Escrevente:** Quem recebe

   * **Percentual Firmas:** % de comissão em reconhecimentos

   * **Percentual Notas:** % de comissão em escrituras

   * **Percentual Mensalista:** % de comissão em mensalistas

4. Clique em **Salvar**.

#### Consulta de Comissões:

1. Acesse **Consulta de Comissões**.

2. Selecione **período desejado**.

3. Busque **escrevente**.

4. Sistema calcula:

   * **Valor realizado** (serviços do período)

   * **Comissão** (percentual aplicado)

   * **Total devido** (quanto pagar)

5. Você pode **lançar manualmente** se ajuste necessário.

* **Observação Importante:** Comissões são calculadas automaticamente a partir dos serviços realizados. Planos podem ser diferentes por tipo de serviço.

---

---

## D-3.59 - Gerar Relatório PEX
**Objetivo:** Gerar relatório PEX com emolumentos separados por tipo de serviço para recolhimento.  
**Tags:** `relatório`, `pex`, `recolhimento`, `emolumentos`

### Intenções de Busca & Dúvidas Frequentes
- Como preparar para recolher?
- preparar relatório
- gerar pex
- fazer recolhimento
- Como gerar relatório PEX?

### Procedimento / Explicação
#### Descrição:

Relatório PEX consolida emolumentos de todos os serviços para recolhimento ao sistema de justiça.

#### Passo a passo:

1. Acesse **Relatórios > PEX**.

2. Selecione **período desejado** (ex: primeira quinzena de dezembro).

3. Sistema traz **emolumentos consolidados** com:

   * **Por tipo de serviço** (Firmas, Notas, Protesto, etc.)

   * **Valores separados** por tipo

   * **Total geral**

4. Se tiver **importações** (RC, Protesto), clique em **Importar** e adicione arquivo.

5. Sistema **unifica** todas as especialidades.

6. Clique em **Gerar** ou **Imprimir**.

7. Relatório está pronto para **recolhimento**.

#### Importação:

- Se você tem **sistema de Protesto** ou **RC** separado:

  1. Exporte arquivo XML

  2. Clique em **Importar**

  3. Selecione arquivo

  4. Sistema **incorpora** dados

  5. Relatório mostra **tudo unificado**

* **Observação Importante:** PEX é relatório oficial para recolhimento. Deve ser preciso. Importação facilita consolidação de múltiplos sistemas.

---

---

## D-3.62 - Cadastrar Livro para Consumo
**Objetivo:** Registrar livros a serem utilizados no sistema para consumo automático de folhas.  
**Tags:** `livro`, `cadastro`, `configuração`, `consumo`

### Intenções de Busca & Dúvidas Frequentes
- configurar livro
- adicionar livro de notas
- Como cadastrar um livro novo?
- criar livro
- Como ativar abertura automática?

### Procedimento / Explicação
#### Descrição:

Cadastro de livro permite rastreamento de folhas utilizadas e abertura automática ao encerrar livro anterior.

#### Passo a passo:

1. Acesse **Administração > Livros** (ou **Configurações > Livros**).

2. Clique em **Adicionar** novo livro.

3. Configure:

   * **Número do Livro:** Ex: 1, 2, 3

   * **Tipo:** Ato Notarial, Termo de Comparecimento, etc.

   * **Numeração Inicial:** Primeira folha

   * **Numeração Final:** Última folha

   * **Abertura Automática:** Ativar para auto-abrir próximo livro

4. Clique em **Salvar**.

#### Abertura Automática:

- Se ativada: ao terminar última folha do livro 1, sistema **abre livro 2** automaticamente.

- Sistema **preenche data de encerramento**.

* **Observação Importante:** Essencial para rastreamento de folhas. Abertura automática otimiza fluxo.

---

---

## D-3.68 - Registrar Serviço Interno
**Objetivo:** Registrar serviços realizados internamente entre escreventes (não faturáveis).  
**Tags:** `serviço interno`, `lançamento`, `escrevente`, `controle`

### Intenções de Busca & Dúvidas Frequentes
- Como controlar serviços entre escreventes?
- Como lançar serviço interno?
- adicionar atividade
- registrar trabalho
- lançar serviço

### Procedimento / Explicação
#### Descrição:

Serviços internos são atividades não faturáveis para controle e documentação.

#### Passo a passo:

1. Acesse **Administração > Serviços Internos**.

2. Clique em **Adicionar**.

3. Configure:

   * **Escrevente:** Quem realiza

   * **Serviço:** Qual atividade

   * **Quantidade:** Quantas vezes

   * **Data**

4. Se serviço **pré-configurado**, sistema **carrega valor automaticamente**.

5. Clique em **Salvar**.

#### Consulta de Extrato:

1. Acesse **Extrato de Serviços Internos**.

2. Visualize todos os serviços registrados.

* **Observação Importante:** Controle interno. Não gera receita, mas documenta atividades.

---

---

## D-3.72 - Enviar Protocolo para Registro de Imóvel
**Objetivo:** Registrar envio de protocolo para cartório de registro de imóvel com previsão de retorno.  
**Tags:** `registro`, `envio`, `imóvel`, `controle`

### Intenções de Busca & Dúvidas Frequentes
- Como acompanhar protocolo enviado?
- enviar para registro
- acompanhar registro
- Como registrar envio para registro de imóvel?
- controlar envio

### Procedimento / Explicação
#### Descrição:

Controle de envio para registro imobiliário com rastreamento de status e valor.

#### Passo a passo:

1. Acesse **Administração > Envio para Registro**.

2. Clique em **Adicionar** novo envio.

3. Configure:

   * **Protocolo:** Número ou busque

   * **Tipo de Envio:** Físico ou Eletrônico

   * **Data de Envio**

   * **Cartório de Destino:** Qual cartório de registro

   * **Número de Protocolo (Registro):** Se já tem

   * **Previsão de Retorno**

   * **Valor:** Quanto custou envio

   * **Status:** Caminhando, Retornado, etc.

4. Clique em **Salvar**.

#### Acompanhamento:

1. Retorne a **tela de envio**.

2. **Filtre por status**:

   * **Caminhando:** Ainda com registro

   * **Retornado:** Veio de volta

   * **Registrado:** Pronto

3. Para **editar**, clique no envio.

4. Atualize **status** conforme evolução.

5. Adicione **trâmite** se precisar comunicar equipe.

* **Observação Importante:** Controle interno apenas. Rastreamento de documentos enviados. Facilita follow-up com registro de imóvel.

---

---

## D-3.78 - Configurar Comunicação Automática ao TJ
**Objetivo:** Configurar sistema para comunicar automaticamente selos gerados ao TJ em horário específico.  
**Tags:** `configuração`, `comunicação`, `tj`, `selo digital`

### Intenções de Busca & Dúvidas Frequentes
- automatizar envio
- ativar comunicação
- Como definir horário?
- configurar horário
- Como ativar comunicação automática?

### Procedimento / Explicação
#### Descrição:

Comunicação automática dispara envio de selos sem intervenção manual, conforme horário configurado.

#### Passo a passo:

1. Acesse **Configurações > Comunicações Automáticas** (ou similar).

2. Configure **horários**:

   * **Selo Digital:** Ex: 21h (9 da noite)

   * **Notariado:** Ex: 19h (7 da noite)

   * **Outras centrais:** Conforme necessidade

3. Clique em **Salvar** ou **Ativar**.

#### Resultado:

- **Diariamente** no horário configurado, sistema **envia automaticamente** selos gerados

- Você **não precisa fazer nada**

- No dia seguinte, apenas **valide** se tudo foi ok

#### Notificações:

- Sistema pode **notificar por e-mail** se há comunicações pendentes

- Alertas para **comunicações com falha**

* **Observação Importante:** Economia de tempo. Recomenda-se ativar. Sempre revise no dia seguinte para garantir sucesso.

---

---

## R-4.0 - Alterar Configuração da Comunicação de uma Participação
**Objetivo:** Ajustar como a participação de uma parte em um ato notarial (ex: comprador, vendedor) será comunicada às centrais eletrônicas integradas como DOI e CESDI.  
**Tags:** `Configurações`, `Participação`, `Comunicação`, `Centrais`, `DOI`, `CESDI`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu altero as configurações de comunicação de uma participação para as centrais?
- configurar centrais
- mudar tipo de comunicação
- Como eu configuro se um 'vendedor' deve ser enviado para a DOI?
- ajustar envio DOI
- editar comunicação de participação
- Preciso ajustar o envio de uma participação para a CESDI, como faço?
- configurar envio para centrais

### Procedimento / Explicação
#### Procedimento detalhado:

1.  Acesse o caminho: **Orion TN > Configurações > Geral > Cadastros auxiliares > Participação**.

2.  Pesquise a participação desejada e clique no ícone de lápis (**Alterar**).

3.  Na tela de edição, acesse a aba **"Comunicações - Configurações"**.

4.  Para cada central listada (CEP, CESDI, DOI, etc.), configure se a participação deve ser enviada e qual a descrição adequada.

5.  Clique em **"Concluir"** para salvar as alterações.

6.  **IMPORTANTE:** Se um protocolo estiver aberto em outra aba, pressione **F5** para atualizar a página e aplicar as novas configurações.

---

---

## M-5.0 - Gerenciamento de Planos de Comissões
**Objetivo:** Acessar a tela de gerenciamento para filtrar, visualizar, editar, remover ou adicionar novos planos de comissões para os escreventes.  
**Tags:** `Comissões`, `Planos`, `Administração`, `Filtro`, `Visualizar`, `Editar`, `Remover`, `Adicionar`

### Intenções de Busca & Dúvidas Frequentes
- consultar planos de comissionamento
- listar planos de comissão
- gerenciar comissões
- Como eu faço para editar um plano de comissão que já existe?
- editar plano de comissão
- excluir plano de comissão
- Onde eu gerencio os planos de comissões dos escreventes?
- Preciso remover um plano de comissão, qual o caminho?
- Onde eu vejo a lista de todos os planos de comissão cadastrados?

### Procedimento / Explicação
#### Descrição:

A tela de Planos de Comissões permite o gerenciamento completo dos planos de comissão cadastrados, oferecendo funcionalidades para pesquisa, visualização, edição, remoção e adição de novos planos.

#### Passo a passo:

1.  Para acessar a tela de **Planos de comissões**, clique no menu **Administração > Comissões > Planos**.

2.  A tela será carregada automaticamente com todos os planos de comissão cadastrados.

3.  Para filtrar e localizar um plano de comissão específico:

    1.  Digite a descrição do plano de comissão no campo **Pesquisar por planos**.

    2.  Clique no botão **Filtrar**.

    3.  Para limpar o filtro e retornar ao estado inicial da página, clique no botão **Limpar**.

4.  A partir da tela de planos de comissões, é possível realizar as seguintes ações:

    1.  **Visualizar**: Para ver as configurações definidas no plano de comissão.

    2.  **Editar**: Para modificar as configurações do plano de comissão selecionado.

    3.  **Remover**: Para excluir o plano de comissão selecionado.

    4.  **Adicionar**: Para criar um novo plano de comissão.

    5.  **Voltar**: Para retornar à página inicial do sistema.

*   **IMPORTANTE**: Caso confirme a exclusão do plano de comissão, todas as configurações do plano, incluindo os escreventes selecionados, serão perdidas.

---

---

## R-6.0 - Geração do Relatório Justiça Aberta (CNJ)
**Objetivo:** Gerar o relatório semestral com os valores arrecadados para preenchimento e envio manual ao portal Justiça Aberta do CNJ.  
**Tags:** `Relatórios`, `Justiça Aberta`, `CNJ`, `Financeiro`

### Intenções de Busca & Dúvidas Frequentes
- enviar dados Justiça Aberta
- relatório de arrecadação semestral
- Onde fica a rotina para tirar o relatório de valores para o CNJ?
- Preciso preencher os dados no portal Justiça Aberta, onde o Orion gera esse relatório?
- Como eu gero o relatório do Justiça Aberta para o CNJ?
- gerar arquivo para o CNJ
- relatório CNJ

### Procedimento / Explicação
#### Passo a passo para gerar o relatório:

1.  Acesse o menu **Relatórios > PEX - TJ/SP** no Orion TN.

2.  Selecione o tipo de relatório **"Justiça Aberta"**.

3.  Informe o período desejado (normalmente o semestre).

4.  Clique em **"Concluir"** para gerar o relatório na tela.

5.  Após conferir os valores, utilize este relatório para preencher as informações manualmente no portal do CNJ.

---

---

## D-6.0 - Importar Partes de Outro Protocolo
**Objetivo:** Permitir a importação automática dos dados de participantes de um protocolo existente para um novo, evitando o preenchimento manual repetitivo.  
**Tags:** `Protocolo`, `Notas`, `Importação`, `Partes`, `Participantes`, `Qualificação`, `Reuso`

### Intenções de Busca & Dúvidas Frequentes
- aproveitar partes de protocolo antigo
- Como eu importo as partes de um protocolo antigo para um novo?
- reutilizar cadastro de protocolo
- puxar dados de outro ato
- Consigo copiar os dados do comprador e vendedor de uma escritura anterior?
- importar vendedor e comprador
- Onde fica o botão para puxar participantes de outro protocolo?
- Tenho que digitar todos os dados de novo se já fiz um protocolo para essas pessoas?
- copiar partes de outra escritura

### Procedimento / Explicação
#### Descrição:

Esta funcionalidade agiliza a lavratura de atos ao permitir que o usuário busque um protocolo anterior e selecione quais participantes deseja copiar para o protocolo atual, importando todos os dados de qualificação sem necessidade de digitação manual.

#### Passo a passo:

1.  Acesse o novo protocolo e selecione o card **Qualificações das partes**.

2.  No canto direito, clique no ícone **Importar participantes** (representado por uma seta apontada para baixo).

3.  Uma tela de busca será aberta. Utilize os filtros disponíveis para localizar o protocolo de origem:

    * **Número de protocolo**

    * **Data de recepção**

    * **Nº recibo**

    * **Data do recibo**

    * **Nome** ou **Documento**

4.  Após realizar a busca e o sistema carregar as participações disponíveis, selecione a **caixinha** (checkbox) ao lado dos nomes que deseja importar.

5.  Clique no botão **Importar**.

6.  As informações serão carregadas no novo protocolo automaticamente.

---

---

## M-7.0 - Consulta de Comissões
**Objetivo:** Consultar as comissões geradas no sistema, aplicando filtros por escrevente, período ou plano de comissão para visualizar e imprimir os resultados.  
**Tags:** `Comissões`, `Consulta`, `Administração`, `Filtro`, `Escrevente`, `Período`, `Plano`, `Impressão`

### Intenções de Busca & Dúvidas Frequentes
- Como eu consulto o valor de comissão de um escrevente em um determinado mês?
- ver comissão de escrevente
- extrato de comissão
- relatório de comissões
- Preciso imprimir o extrato de comissões de um funcionário, onde eu vou?
- consultar comissões a pagar
- Onde eu tiro um relatório de todas as comissões geradas por um plano específico?

### Procedimento / Explicação
#### Descrição:

A tela de Consulta de Comissões permite buscar e visualizar as comissões registradas no sistema, utilizando diversos filtros para refinar a pesquisa e oferecendo a opção de imprimir os resultados.

#### Passo a passo:

1.  Para acessar a tela de **Consulta de comissões**, clique no menu **Administração > Comissões > Consultas**.

2.  Na página **Consulta de comissões**, os resultados poderão ser filtrados de acordo com os campos de busca disponíveis:

    1.  **Escrevente**: Para buscar as comissões de apenas um escrevente específico.

    2.  **Período**: Para buscar as comissões dentro de um determinado intervalo de datas.

    3.  **Mês de referência**: Para realizar uma busca através de um mês específico.

    4.  **Plano**: Para filtrar as comissões de apenas um plano de comissão.

3.  Após preencher os campos de busca, selecione uma das ações:

    1.  **Imprimir**: Para imprimir os resultados apresentados na busca.

    2.  **Limpar**: Para limpar todo o conteúdo preenchido nos campos de busca e os resultados em tela.

    3.  **Filtrar**: Para aplicar o filtro baseado nos campos que foram preenchidos.

---

---

## D-8.0 - Configurar Cálculo Automático de Registro de Imóveis (RI)
**Objetivo:** Habilitar a configuração para que o sistema calcule automaticamente os valores referentes ao Registro de Imóveis (RI) em orçamentos e protocolos.  
**Tags:** `Configurações`, `Parametrizações`, `Protocolo`, `Orçamento`, `Custas`, `Registro de Imóveis`, `RI`, `Cálculo Automático`

### Intenções de Busca & Dúvidas Frequentes
- valor do registro de imóveis no orçamento
- automação de custas de registro
- Tem como o protocolo puxar o valor do Registro de Imóveis sozinho?
- configurar cálculo de RI
- incluir RI automaticamente no protocolo
- Onde habilito o cálculo automático de RI para os orçamentos?
- calcular RI automático
- Como configuro o sistema para calcular o valor do Registro de Imóveis automaticamente?

### Procedimento / Explicação
#### Descrição:

Esta rotina permite parametrizar o sistema para que o cálculo das custas do Registro de Imóveis seja realizado de forma automática tanto na geração de orçamentos quanto na criação de protocolos.

#### Passo a passo:

1.  Acesse o sistema OrionTN.

2.  Navegue até o menu **Configurações** e, em seguida, clique no menu **Parametrizações**.

3.  No menu lateral esquerdo, acesse a opção **Protocolo**.

4.  Localize o card denominado **Custas**.

5.  Neste menu, selecione as caixas de seleção (checkboxes) desejadas:

    * Uma opção para calcular o valor do Registro de Imóveis automaticamente nos **Orçamentos**.

    * Outra opção para o cálculo nos **Protocolos**.

6.  Para salvar as alterações, clique no botão **Concluir** localizado no fim da tela, no canto inferior direito.

---

---

## R-14.0 - Encaminhar e Controlar Escrituras para o Registro de Imóveis (R.I.)
**Objetivo:** Explicar como utilizar o sistema para registrar o envio de uma escritura ao Registro de Imóveis (R.I.) e como acompanhar e atualizar o status desse processo.  
**Tags:** `Escrituras`, `Registro de Imóveis`, `Controle`, `Protocolos`, `RI`

### Intenções de Busca & Dúvidas Frequentes
- controle de RI
- mandar escritura para o RI
- Como eu marco no sistema que uma escritura foi enviada para o Registro de Imóveis?
- andamento no registro de imóveis
- Preciso informar o número do protocolo do R.I. em uma escritura, onde faço isso?
- enviar para registro
- Onde eu controlo o andamento das escrituras que estão no R.I.?
- acompanhar escritura no RI

### Procedimento / Explicação
#### Como encaminhar a escritura:

1.  No Orion TN, localize o protocolo que deseja enviar (ele deve ter um imóvel cadastrado).

2.  No menu superior do protocolo, clique no botão **"Encaminhar para controle do R.I"**.

3.  O botão mudará para **"Estornar encaminhamento RI"**, confirmando o envio.

#### Como controlar as escrituras enviadas:

1.  Acesse **Administração > Envio de escrituras para registro**.

2.  Utilize os filtros para buscar os protocolos enviados.

3.  Para cada protocolo listado, preencha os campos de controle, como Data de envio, Cartório de R.I., Número do protocolo no R.I., Status, etc.

4.  Utilize os ícones no final da linha para salvar, editar, inserir trâmites ou anexos. O escrevente deve manter o status atualizado.

---

---

## M-16.1 - Parametrizações Gerais do Sistema
**Objetivo:** Definir as regras globais do sistema para consumo de papel de segurança (NFS), geração de selo digital, método de arredondamento de custas e controle de numeração de guias.  
**Tags:** `Configurações`, `Geral`, `NFS`, `Papel de Segurança`, `Selo Digital`, `Cálculo de Custas`, `Arredondamento`, `Controle de Guia`

### Intenções de Busca & Dúvidas Frequentes
- regras gerais do sistema
- Onde eu configuro se o consumo de Papel de Segurança (NFS) do cartão de assinatura será automático ou manual?
- Onde eu defino se a comunicação do selo digital será online (automática) ou offline (manual)?
- parametrizar arredondamento de custas
- definir geração de selo digital manual
- Como eu altero a regra de arredondamento para o cálculo de custas no sistema?
- configurar consumo de selo automático

### Procedimento / Explicação
#### Descrição:

Esta seção permite configurar os parâmetros gerais do sistema, que afetam o comportamento de rotinas de Cartão de Assinatura, comunicação de selos e cálculo de custas.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **1 - Geral**.

3.  Configure o **Cartão de assinatura - Consumo de NFS**:

    * **Tipo**: Defina como será controlado o consumo da NFS, com as opções:

        * **Automático**: O consumo será realizado automaticamente ao iniciar o cadastro de um novo cartão.

        * **Desativado**: O consumo da ficha não será controlado pelo estoque.

        * **Manual**: O consumo será controlado pelo estoque, mas deverá ser solicitado manualmente.

        * **Por digitação**: O consumo não é controlado pelo estoque, mas o campo do número da NFS fica disponível para digitação.

    * **Buscar todos os registros**: ...

    * **Qtd. na busca**: ...

    * **Produto**: ...

4.  Configure o **Consumo selo digital**:

    * **Tipo**: Defina como será a comunicação dos selos digitais, com as opções:

        * **Automático**: Os selos serão gerados e comunicados automaticamente no ato do serviço.

        * **Desativado**: Os selos digitais não serão gerados.

        * **Manual**: A geração e o envio dos selos serão realizados manualmente.

5.  Configure o **Cálculo de custas**:

    * Defina o tipo de arredondamento para o valor total das custas:

        * **Arredondamento para menos**: (Ex: R$ 5,656 se torna R$ 5,65).

        * **Arredondamento para mais**: (Ex: R$ 5,656 se torna R$ 5,66).

        * **Arredondamento truncado**: (Ex: R$ 5,6568978 se torna R$ 5,65).

6.  Configure o **Controle de Guia**:

    * Defina como o número da guia será incrementado: **Diário**, **Semanal** ou **Mensal**.

    * Marque **Zera anualmente** para que a numeração da guia reinicie a cada ano.

---

---

## M-16.10 - Parametrizar E-mail
**Objetivo:** Configurar as opções gerais de notificação por e-mail do sistema para diferentes eventos e rotinas.  
**Tags:** `Configurações`, `E-mail`, `Notificações`

### Intenções de Busca & Dúvidas Frequentes
- Como eu ajusto as configurações de notificação por e-mail?
- configurar envio de e-mail
- Onde eu configuro os parâmetros gerais para envio de e-mail pelo sistema?
- ajustar notificações por e-mail
- parâmetros de e-mail

### Procedimento / Explicação
#### Descrição:

Esta seção permite configurar os parâmetros de envio de e-mail do sistema.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **10 - E-mail**.

3.  Ajuste os parâmetros disponíveis, como **Serviço realizado X Serviços solicitados** e outras configurações de **E-mail**.

---

---

## M-16.12 - Parametrizar Protocolo de Notas
**Objetivo:** Definir as regras de negócio para a tela de Protocolo, incluindo o valor mínimo para COAF, débito automático na lavratura, autorização para recibos e consumo de papel de segurança.  
**Tags:** `Configurações`, `Protocolo`, `Notas`, `COAF`, `Lavratura`, `Recibo`, `Estoque`, `Escrituras`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu defino o valor mínimo de um ato para que ele seja enquadrado no COAF?
- regras de lavratura
- É possível exigir uma autorização de supervisor para que um escrevente possa emitir um recibo de nota?
- configurar tela de protocolo
- Como eu configuro o sistema para consumir o papel de segurança automaticamente ao salvar um protocolo?
- valor mínimo COAF
- parâmetros de notas

### Procedimento / Explicação
#### Descrição:

Esta seção centraliza as configurações que governam o fluxo de trabalho e as regras de negócio da tela de Protocolo.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **12 - Protocolo**.

3.  Em **COAF**, defina o **Valor mínimo para enquadramento no COAF**.

4.  Em **Lavratura**, configure opções como **Débito automático ao salvar o protocolo**, **Necessário autorização para emissão de recibo (nota)** e o envio de e-mail de notificação.

5.  Em **Movimentação financeira**, defina as regras de **Confirmação de pagamento**.

6.  Em **Assistente**, habilite o **Assistente para validação de protocolos**.

7.  Em **Estoque**, configure o **Consumo de papel de segurança**, definindo **Categoria**, **Produto**, e outras regras.

8.  Em **Escrituras para registro**, configure o encaminhamento automático e o **Cartório** e **Tipo de envio** padrão.

---

---

## M-16.3 - Configurar Parâmetros por Estação de Trabalho
**Objetivo:** Definir configurações que se aplicam apenas à estação de trabalho local, como impressoras e escreventes padrão para as telas de Firmas e Notas.  
**Tags:** `Configurações`, `Estação de Trabalho`, `Impressora`, `Padrão`, `Pedido de Firmas`, `Protocolo`

### Intenções de Busca & Dúvidas Frequentes
- escrevente padrão
- configurações locais do computador
- Onde ficam as configurações que afetam apenas a minha máquina?
- Como eu defino uma impressora padrão para imprimir etiquetas apenas no meu computador?
- É possível deixar um escrevente pré-selecionado por padrão na minha tela de protocolo?
- definir impressora padrão
- configurar minha estação

### Procedimento / Explicação
#### Descrição:

Esta seção permite personalizar o comportamento do sistema para a máquina local, otimizando o fluxo de trabalho do usuário ao pré-definir impressoras e escreventes.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **3 - Parâmetros por estação**.

3.  O campo **Estação** exibirá o nome da máquina local onde os parâmetros serão aplicados.

4.  Em **Impressoras**, selecione uma impressora padrão para cada tipo de serviço listado.

5.  Em **Pedido de firmas - Serviços**:

    * **Reconhecimento**: Selecione o tipo de reconhecimento padrão para a tela de pedido de firmas.

    * **Outros serviços**: Selecione o tipo de "outros serviços" padrão.

    * **Escrevente**: Selecione o escrevente padrão para a tela de pedido de firmas.

6.  Em **Protocolo - Notas**:

    * **Escrevente padrão**: Selecione o escrevente que será selecionado automaticamente ao criar um novo protocolo.

---

---

## M-16.4 - Gerenciar Sequências Automáticas do Sistema
**Objetivo:** Definir e controlar a numeração sequencial automática para diversos registros do sistema, como protocolos, recibos, cartões de assinatura e pedidos.  
**Tags:** `Configurações`, `Sequência`, `Numeração`, `Cartão de Assinatura`, `Sinal Público`, `Pedido de Firmas`, `Protocolo`, `Recibo`, `Fatura`

### Intenções de Busca & Dúvidas Frequentes
- zerar numeração de recibo
- Onde eu defino qual foi o último número de recibo utilizado para o sistema continuar a partir dele?
- Como eu configuro a sequência de numeração dos cartões de assinatura?
- controle de sequência numérica
- Preciso ajustar o número do próximo protocolo a ser gerado, onde eu faço isso?
- ajustar último número de protocolo
- configurar numeração automática

### Procedimento / Explicação
#### Descrição:

Esta seção permite definir o último número utilizado para cada tipo de documento no sistema, garantindo que a próxima numeração automática siga a sequência correta.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **4 - Sequência**.

3.  Para cada item listado (Cartão de assinatura, Sinal público, Pedido de firmas, Requisição mensalista, Termo, Recibo caixa, Protocolo, etc.), informe o número da **Última sequência utilizada**.

    * *Exemplo:* Se o campo para **Protocolo** for preenchido com o número 10, o próximo protocolo criado será o 11.

4.  Para alguns itens, como **Pedido de firmas** e **Guia**, informe também a **Data da última sequência** para um controle mais preciso.

---

---

## M-16.6 - Definir Campos Obrigatórios por Tela
**Objetivo:** Personalizar o sistema definindo quais campos devem ser de preenchimento obrigatório em diferentes telas, a fim de garantir a consistência e a qualidade dos dados inseridos.  
**Tags:** `Configurações`, `Campos Obrigatórios`, `Validação`, `Tela`

### Intenções de Busca & Dúvidas Frequentes
- tornar campo obrigatório
- Como eu faço para tornar o campo 'Profissão' obrigatório no cadastro do cartão de assinatura?
- Onde eu defino as regras de campos que são obrigatórios para os usuários preencherem?
- validar preenchimento de campo
- obrigar campo
- regras de preenchimento
- É possível obrigar o preenchimento de um campo específico em uma tela do sistema?

### Procedimento / Explicação
#### Descrição:

Esta funcionalidade permite aumentar a rigidez do sistema, forçando o preenchimento de campos importantes em telas específicas.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **6 - Campos obrigatórios**.

3.  Em **Tela**, selecione a tela do sistema que deseja configurar.

4.  Na **Seleção de campos**, clique para selecionar um ou mais campos que deseja tornar obrigatórios.

5.  Clique em **Incluir na lista de campos obrigatórios** para mover os campos selecionados para a lista de obrigatoriedade.

6.  Para remover a obrigatoriedade, selecione um campo na lista da direita e clique em **Retirar da lista de campos obrigatórios**.

---

---

## M-16.7 - Configurar Atalhos do Teclado
**Objetivo:** Criar e configurar atalhos de teclado personalizados (CTRL + ALT + Tecla) para acionar funções específicas do sistema e agilizar o trabalho do usuário.  
**Tags:** `Configurações`, `Atalhos`, `Teclado`, `Produtividade`

### Intenções de Busca & Dúvidas Frequentes
- teclas de atalho
- criar atalho
- É possível configurar teclas de atalho personalizadas no Orion TN?
- Onde fica o painel para configurar os atalhos do teclado do sistema?
- Como eu crio um atalho de teclado para abrir a tela de 'Novo Cartão'?
- personalizar teclado
- atalhos de produtividade

### Procedimento / Explicação
#### Descrição:

Esta seção permite associar combinações de teclas a funções do sistema para otimizar a produtividade e a navegação.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **7 - Painel de atalhos**.

3.  Em **Tela**, selecione a tela para a qual deseja configurar o atalho.

4.  Em **Complemento**, informe qual tecla será usada em combinação com "CTRL + ALT" para acionar a função desejada.

    * *Exemplo:* Se informar a tecla "i", a combinação "CTRL + ALT + i" acionará a função "Adicionar cartão".

---

---

## R-18.0 - Alterar o Valor de um 'Outro Serviço'
**Objetivo:** Ajustar o preço de um serviço avulso cadastrado no sistema, definindo se ele terá um valor fixo padrão ou se o valor poderá ser inserido manualmente a cada uso.  
**Tags:** `Outros Serviços`, `Cadastro`, `Valores`, `Configurações`, `Edição`

### Intenções de Busca & Dúvidas Frequentes
- editar valor de serviço
- cadastrar serviço com valor variável
- Onde eu defino um preço fixo para um serviço avulso?
- mudar preço de outro serviço
- configurar preço de diligência
- Quero que o valor de um serviço possa ser digitado na hora, como eu configuro?
- Como eu altero o valor de um serviço que está cadastrado em 'Outros Serviços'?

### Procedimento / Explicação
#### Passo a passo:

1.  Acesse o caminho: **Orion TN > Configurações > Geral > Cadastros auxiliares > Outros serviços**.

2.  Localize o serviço desejado e clique no botão **"Editar"** (ícone de lápis).

3.  Para permitir que o valor seja inserido manually a cada uso, marque a opção **"Sem valor fixo"**.

4.  Para definir um preço padrão, desmarque a opção "Sem valor fixo" e insira o valor no campo **"Valor"**. Este valor não poderá ser alterado na tela de serviço, apenas neste cadastro.

---

---

## M-18.0 - Consulta de Serviços Praticados
**Objetivo:** Consultar detalhadamente os serviços individuais praticados no balcão de firmas, utilizando filtros como tipo de serviço, período, número do selo, termo ou mensalista.  
**Tags:** `Firmas`, `Consultas`, `Serviços Praticados`, `Filtro`, `Pedido`, `Cartão`, `Selo`, `Termo`, `Usuário`, `Mensalista`, `Carimbo`, `QR-Code`, `DUT`

### Intenções de Busca & Dúvidas Frequentes
- encontrar autenticação específica
- histórico de reconhecimentos
- relatório de serviços de firmas
- pesquisar serviços de balcão
- Como eu encontro um reconhecimento de firma específico pelo número do selo que foi utilizado?
- Como eu pesquiso por um serviço praticado usando o número do termo de comparecimento?
- Onde eu posso ver todos os serviços feitos por um escrevente no balcão?
- Preciso de um relatório de todas as autenticações feitas em um dia, onde eu tiro?

### Procedimento / Explicação
#### Descrição:

A tela de Serviços Praticados permite realizar buscas detalhadas sobre os serviços executados no balcão de firmas, oferecendo uma ampla gama de filtros para localizar informações específicas e ações para visualizar os detalhes de cada serviço.

#### Passo a passo:

1.  Para acessar a tela de **Serviços praticados**, clique no menu **Firmas > Consultas > Serviços praticados**.

2.  Na página de **Serviços praticados**, os resultados poderão ser filtrados de acordo com os campos de busca disponíveis, sendo eles:

    1.  **Serviço**:

    2.  **Período**: Para buscar os serviços praticados dentro de um determinado período.

    3.  **Mês de referência**: Para realizar uma busca através de um mês específico.

    4.  **Nº Pedido**: Para realizar uma busca através do número do pedido utilizado no serviço praticado.

    5.  **Nome**:

    6.  **Nº Cartão**: Para encontrar um serviço praticado através do número do cartão.

    7.  **Hash**: Para realizar uma busca através do hash de autenticidade.

    8.  **Número do Carimbo**:

    9.  **Série**: Para realizar a busca do serviço praticado através da série do selo que foi consumido (necessário estar habilitado o consumo do selo).

    10. **Sequência**: Para realizar a busca do serviço praticado através da sequência do selo que foi consumido (necessário estar habilitado o consumo do selo).

    11. **Usuário**: Para realizar uma busca através do usuário que praticou o serviço solicitado.

    12. **Escrevente**: Para realizar uma busca através do escrevente que praticou o serviço solicitado.

    13. **Cód. Mensalista**: Para realizar uma busca pelo código de mensalista específico.

    14. **Mensalista**: Para realizar os serviços praticados para um mensalista específico.

    15. **Requisição N°**: Para realizar uma busca do serviço praticado através do número de requisição do mensalista.

    16. **Código do termo**: Para realizar uma busca do serviço praticado através do código do termo.

    17. **Número do termo**: Para realizar uma busca do serviço praticado através do número do termo.

    18. **Número do livro**: Para realizar uma busca do serviço praticado através do número do livro.

    19. **Número da folha**: Para realizar uma busca do serviço praticado através do número da folha.

    20. **Lado**: Para realizar uma busca do serviço praticado através do lado da folha, sendo **F** para Frente e **V** para Verso.

    21. **Flag Exibir cancelados**: Para realizar uma busca dos serviços praticados que estão com o status de cancelado.

    22. **Flag Com termos**: Para realizar uma busca dos serviços praticados que estão com termos e/ou status de cancelado.

3.  Após preencher os campos de busca, selecione uma das ações:

    1.  **Imprimir**: Para imprimir os resultados apresentados na busca.

    2.  **Limpar**: Para limpar **TODO** o conteúdo preenchido nos campos de busca e os resultados em tela.

    3.  **Filtrar**: Para aplicar o filtro após preencher os campos necessários.

4.  As ações disponíveis para cada pedido na tela de consultas são:

    1.  **Visualizar carimbo**: Clique para visualizar o carimbo que foi gerado no serviço praticado.

    2.  **Visualizar QR-Code**: Clique para visualizar o QR-Code que foi gerado para o serviço praticado.

    3.  **Visualizar termo de comparecimento**: Visualizar o termo de comparecimento que foi gerado para o ato praticado.

    4.  **Visualizar o DUT**: Visualizar o DUT que foi digitalizado no ato praticado.

---

---

## R-19.0 - Configurar Plano de Comissões para o Notas
**Objetivo:** Cadastrar e configurar um plano de comissões para os escreventes do setor de notas, definindo a forma de cálculo, as naturezas de atos aplicáveis e os usuários participantes.  
**Tags:** `Comissões`, `Notas`, `Configuração`, `Plano`, `Administração`, `Cálculo`

### Intenções de Busca & Dúvidas Frequentes
- criar comissão
- Como eu adiciono um escrevente a um plano de comissões existente?
- Como eu crio um plano de comissão para os escreventes do setor de notas?
- Onde eu defino a porcentagem de comissão para cada tipo de escritura?
- plano de comissionamento
- regras de comissão para notas
- calcular comissão de escrevente

### Procedimento / Explicação
#### Passo a passo:

1.  Acesse o menu: **Administração > Comissões > Planos de Comissões**.

2.  Clique no botão **Adicionar**.

3.  Preencha a **Descrição**, a **Forma de Cálculo** ("Percentual" ou "Valor Fixo") e a vigência.

4.  Selecione as naturezas de atos que entrarão no cálculo da comissão.

5.  No campo **"Aplicar nos itens selecionados"**, insira o valor ou percentual da comissão.

6.  Selecione os usuários que farão parte do plano.

7.  Clique em **Concluir** para salvar a configuração.

---

---

## M-19.0 - Consultar e Gerenciar Pessoas Jurídicas Existentes
**Objetivo:** Acessar, filtrar e executar ações como visualizar, editar e inativar os cadastros de Pessoas Jurídicas (empresas) existentes no sistema.  
**Tags:** `Administração`, `Pessoa Jurídica`, `Consulta`, `Filtro`, `CNPJ`, `Inativar`, `Editar`, `Gerenciamento`

### Intenções de Busca & Dúvidas Frequentes
- buscar empresa
- editar cadastro de PJ
- Como eu busco o cadastro de uma empresa pelo CNPJ?
- Preciso inativar o cadastro de uma empresa, como proceder?
- consultar CNPJ
- gerenciar empresas
- inativar pessoa jurídica
- Onde eu edito os dados de uma Pessoa Jurídica que já está cadastrada?

### Procedimento / Explicação
#### Descrição:

A tela de Pessoa Jurídica permite visualizar, buscar e gerenciar os cadastros de pessoas jurídicas existentes no sistema, oferecendo opções de filtro e ações para manipular os registros.

#### Passo a passo:

1.  Para acessar a tela de **Pessoa jurídica**, clique no menu **Administração > Pessoa Jurídica**.

2.  Na tela, serão listadas automaticamente as pessoas jurídicas cadastradas recentemente.

3.  Para localizar um registro específico, utilize os campos de busca e clique em **Filtrar**:

    * **Nome fantasia**: Para buscar pelo nome fantasia.

    * **Razão social**: Para buscar pela razão social.

    * **CNPJ**: Para realizar uma busca por CNPJ.

    * **Inativos**: Para buscar os cadastros que foram inativados.

4.  A partir da listagem de pessoas jurídicas, é possível executar as seguintes ações:

    * **Visualizar**: Para visualizar os dados cadastrados da pessoa jurídica.

    * **Editar**: Para editar as informações do cadastro.

    * **Inativar**: Para inativar o cadastro.

        * *IMPORTANTE:* Caso o cadastro esteja inativado, não será possível utilizá-lo para vínculo aos cartões de assinatura, termos de comparecimento e atos notariais.

5.  Para criar um novo cadastro, utilize a rotina "Criar um Novo Cadastro de Pessoa Jurídica" (M-20.0).

---

---

## M-20.0 - Criar um Novo Cadastro de Pessoa Jurídica
**Objetivo:** Realizar o cadastro completo de uma nova Pessoa Jurídica (empresa), incluindo dados de identificação, endereço, contato, anexos e gerenciamento de seus representantes.  
**Tags:** `Pessoa Jurídica`, `Cadastro`, `Adicionar`, `Novo`, `Administração`, `CNPJ`, `Razão Social`, `Anexos`, `Representantes`, `Webcam`

### Intenções de Busca & Dúvidas Frequentes
- criar cadastro de PJ
- adicionar pessoa jurídica
- Após cadastrar uma PJ, como eu vejo a lista de pessoas que a representam?
- Onde eu preencho a razão social e o CNPJ de uma nova empresa?
- Como eu faço para cadastrar uma nova empresa (Pessoa Jurídica) no sistema?
- incluir nova empresa no sistema
- cadastrar nova empresa

### Procedimento / Explicação
#### Descrição:

Esta rotina detalha o processo de criação de um novo registro de Pessoa Jurídica, incluindo o preenchimento de dados de identificação, contato, documentos anexados e a associação de representantes.

#### Passo a passo:

1.  Para acessar a tela de pessoa jurídica, clique no menu **Administração > Pessoa Jurídica**.

2.  Para criar um novo cadastro de pessoa jurídica, clique no botão **Adicionar**.

3.  Preencha os campos obrigatórios para o cadastro, que são:

    * **Razão social**

    * **CNPJ**

4.  Preencha os demais dados disponíveis, se necessário:

    * **Nome fantasia**

    * **Inscrição estadual**

    * **Endereço completo**

    * **Telefone**

    * **E-mail**

    * **Site**

5.  Na seção de **Anexos**, adicione documentos referentes à pessoa jurídica. É possível **Selecionar** um arquivo, **Capturar** via webcam ou **Digitalizar** via scanner.

    * *IMPORTANTE:* Para utilizar a **Webcam**, é preciso permitir seu uso no navegador.

6.  Após preencher os campos obrigatórios, clique no botão **Concluir**.

7.  Após salvar o cadastro, a seção **Representantes** ficará visível, listando todos os cartões de assinatura que representam esta pessoa jurídica.

---

---

## M-21.0 - Consultar e Gerenciar Livros Existentes
**Objetivo:** Buscar, filtrar e executar ações como visualizar, alterar e inativar os livros (ex: Termo de Comparecimento) já cadastrados no sistema, controlando seu status (aberto/encerrado).  
**Tags:** `Livros`, `Administração`, `Consulta`, `Filtros`, `Visualizar`, `Alterar`, `Inativar`, `Status`

### Intenções de Busca & Dúvidas Frequentes
- inativar livro
- Como eu sei se um livro ainda está aberto ou se já foi encerrado?
- consultar livros de termos
- editar dados de um livro
- buscar livro
- Onde eu consulto os livros de Termo de Comparecimento que estão cadastrados?
- Como eu faço para alterar a data de abertura de um livro?
- encerrar livro
- Preciso inativar um livro que foi cadastrado errado, como eu faço?

### Procedimento / Explicação
#### Descrição:

Esta tela permite gerenciar todos os registros de livros no sistema, oferecendo funcionalidades de consulta detalhada, modificação e controle de status (aberto ou encerrado).

#### Passo a passo:

1.  Para acessar a tela de Livros, acesse o menu **Administração > Livro**.

2.  Ao acessar a tela, são carregados automaticamente todos os livros cadastrados com a situação **ativo**.

3.  Para realizar consultas e localizar um livro específico, utilize os seguintes campos de filtro:

    * **Número**: Busca livros pelo número de identificação.

    * **Período de abertura**: Busca livros com base na data em que foram abertos.

    * **Período de encerramento**: Busca livros com base na data em que foram encerrados.

4.  Após preencher os dados para busca, clique no botão **Filtrar** para aplicar a consulta.

5.  A coluna **Status** informa se o livro em questão está **aberto** ou **encerrado**.

6.  Para cada registro de livro na lista, as seguintes ações estão disponíveis:

    * **Visualizar**: Permite consultar o cadastro completo do Livro em modo de exibição, sem permitir alterações.

    * **Alterar**: Permite consultar e modificar os dados do Livro.

        * *IMPORTANTE:* Tenha atenção nas alterações, pois impactarão no consumo deste livro em sua rotina.

    * **Inativar**: Permite inativar um Livro, impedindo sua utilização.

        * *IMPORTANTE:* Livros com data de encerramento também não podem ser usados, mas continuam com o status ativo.

7.  Para adicionar um novo livro, utilize a rotina "Criar um Novo Livro e Configurar seus Parâmetros" (M-22.0).

---

---

## M-22.0 - Criar um Novo Livro e Configurar seus Parâmetros
**Objetivo:** Realizar o cadastro de um novo livro no sistema (ex: Termo de Comparecimento), definindo seu tipo, numeração, páginas, proprietários e outros parâmetros de consumo.  
**Tags:** `Livros`, `Cadastro`, `Adicionar`, `Novo`, `Administração`, `Tipo Livro`, `Sigla`, `Número Livro`, `Página Inicial`, `Posição Inicial`, `Nº Termo`, `Termo de Comparecimento`, `Parâmetros`

### Intenções de Busca & Dúvidas Frequentes
- configurar livro novo
- criar livro TC
- abrir livro de termo de comparecimento
- É possível restringir o acesso a um livro para um escrevente específico?
- Onde eu defino o número do livro, a página inicial e o lado inicial (Frente/Verso)?
- Como eu cadastro um novo livro de Termo de Comparecimento no sistema?
- cadastrar novo livro

### Procedimento / Explicação
#### Descrição:

Esta rotina detalha o processo de adição de um novo livro ao sistema, explicando cada campo de preenchimento e suas implicações, especialmente para livros do tipo "Termo de Comparecimento".

#### Passo a passo:

1.  Acesse o menu **Administração > Livro**.

2.  Na tela de gerenciamento de livros, clique no botão **Adicionar** para cadastrar um novo livro.

3.  Preencha os seguintes campos para o novo livro:

    * **Tipo livro**: Campo obrigatório. Atualmente, a opção principal é **"Termo de comparecimento"**.

    * **Sigla**: Campo obrigatório para diferenciar livros (ex: **TC** para Termo de Comparecimento).

    * **Número do livro**: Campo obrigatório para o identificador numérico.

    * **Página inicial**: Informe a página inicial para o consumo. O sistema pode sugerir um valor com base nos parâmetros do sistema para Termos de Comparecimento.

    * **Lado inicial**: Informe o lado inicial (**F** para frente ou **V** para verso). Esta opção depende do parâmetro "Utilizar frente e verso".

    * **Posição inicial**: Informe a posição inicial na página/lado.

    * **Nº termo**: Controle da numeração de termo por livro. Este campo só é habilitado se a "sequência de termo automática" estiver desabilitada nos parâmetros.

    * **Data de abertura**: Informe a data de abertura do livro (pode ser retroativa).

    * **Data de encerramento**: Informe a data de encerramento. O sistema preencherá automaticamente quando todas as páginas forem consumidas.

    * **Proprietário**: Defina quais usuários terão acesso ao livro (**Escrevente**, **Todos** ou **Usuário** específico).

    * **Responsável**: Exibe o usuário logado que está realizando o cadastro.

4.  Após preencher os dados necessários, clique no botão **Concluir** para finalizar o cadastro.

---

---

## M-25.0 - Gerenciamento de Configurações de Impressão
**Objetivo:** Acessar e gerenciar as configurações de impressão de etiquetas, permitindo a busca, visualização, edição, remoção e adição de novos modelos de formatação física.  
**Tags:** `Configurações`, `Impressão`, `Modelos`, `Busca`, `Visualizar`, `Editar`, `Remover`, `Adicionar`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu gerencio as configurações de tamanho das etiquetas, como largura e altura?
- ver modelos de etiqueta
- cadastrar formato de etiqueta
- Preciso editar uma configuração de impressão existente, como eu faço?
- Como eu vejo todos os formatos de etiqueta que estão cadastrados no sistema?
- gerenciar tamanho de etiqueta
- editar configuração de impressão

### Procedimento / Explicação
#### Descrição:

A tela de Configuração de Impressão permite aos usuários buscar, visualizar, editar, remover e adicionar configurações de tamanho de etiqueta, facilitando a gestão dos modelos de impressão.

#### Passo a passo:

1.  Para acessar a tela de Configuração de impressão, clique no menu **Configurações**, no submenu clique em **Modelos de impressão** e por fim clique em **Configuração de impressão**.

2.  Na tela de configuração de impressão, é possível realizar uma busca das configurações criadas. Para realizar uma pesquisa, siga os passos abaixo:

    1.  Preencha o campo de **descrição**.

    2.  Clique no botão **Filtrar**.

    3.  Clique para limpar o conteúdo digitado e iniciar uma nova busca.

3.  A partir dessa tela, é possível realizar as seguintes ações para cada configuração:

    *   **Visualizar configuração**

    *   **Editar configuração**

    *   **Remover configuração**

4.  Clique em **Adicionar** caso deseje criar uma nova configuração de tamanho de etiqueta, ou clique no botão **Voltar** para ir para a página inicial.

---

---

## R-26.0 - Imprimir Relatório de Índice por Livro
**Objetivo:** Gerar e imprimir um relatório de índice de atos notariais, organizado e ordenado por livro, folha, nome ou natureza.  
**Tags:** `Relatórios`, `Índice`, `Livro`, `Impressão`

### Intenções de Busca & Dúvidas Frequentes
- Como eu faço para imprimir o índice de um livro específico?
- imprimir índice de escrituras
- Preciso de uma listagem de todos os atos de um determinado livro, como eu tiro?
- consultar índice de atos
- relatório de índice
- Onde eu gero um relatório de índice de escrituras ordenado por nome das partes?
- listagem por livro

### Procedimento / Explicação
#### Passo a passo:

1.  Ao acessar o sistema OrionTN, vá em **Relatórios > Índice por livro**.

2.  Na tela que será aberta, preencha o **Período** o qual irá conciliar as informações para impressão e o **Livro inicial/final**.

3.  Além disso, você poderá ordenar por **Nome**, **Natureza** ou **Livro e folha**.

4.  Por fim, basta clicar no botão "**Imprimir**" e o relatório será impresso em uma nova guia.

---

---

## M-26.0 - Cadastro de Nova Configuração de Impressão de Etiquetas
**Objetivo:** Criar uma nova configuração de impressão de etiquetas, definindo suas dimensões físicas como largura, altura, espaçamento (salto) e margens para diferentes impressoras.  
**Tags:** `Configurações`, `Impressão`, `Etiquetas`, `Cadastro`, `Largura`, `Altura`, `Salto`, `Margens`

### Intenções de Busca & Dúvidas Frequentes
- configurar nova etiqueta
- cadastrar tamanho de etiqueta
- Como eu cadastro uma nova configuração para um tamanho de etiqueta diferente que compramos?
- A impressão está saindo torta. Onde eu ajusto as margens da configuração de impressão?
- criar modelo de impressão
- ajustar margens de impressão
- Onde eu defino a largura, altura e as margens de uma nova etiqueta?

### Procedimento / Explicação
#### Descrição:

Esta rotina detalha o processo de criação de uma nova configuração de impressão de etiquetas, permitindo definir as dimensões físicas da etiqueta e as margens de impressão para adequação a diferentes impressoras.

#### Passo a passo:

1.  Para acessar a tela de Cadastro de Configuração de impressão, clique no menu **Configurações**, no submenu clique em **Geral**, no submenu **Modelos de impressão** e por fim clique em **Configuração de impressão**.

2.  Clique no botão **Adicionar**.

3.  Para criar uma nova configuração de impressão de etiquetas, siga os passos abaixo:

    *   Preencha o campo **descrição**.

    *   Informe a **largura** da etiqueta que será impressa (Unidade de medida: cm).

    *   Informe a **altura** da etiqueta (Unidade de medida: cm).

    *   Preencha o **salto** da etiqueta (Espaçamento entre uma etiqueta e outra - Unidade de medida: cm).

    *   Se for necessário, informe a **margem superior** (Unidade de medida: cm).

    *   Se for necessário, informe a **margem esquerda** (Unidade de medida: cm).

4.  Caso sua impressora tenha um limite pré-definido para iniciar a impressão na etiqueta, poderão ser definidas as seguintes medidas:

    *   Informe a **margem superior** que deseja aplicar.

    *   Informe a **margem inferior** que deseja aplicar.

    *   Informe a **margem esquerda** que deseja aplicar.

    *   Informe a **margem direita** que deseja aplicar.

5.  Para concluir o cadastro, clique no botão **Concluir**.

6.  Caso deseje voltar para a página inicial, clique em **Voltar**.

7.  Caso deseje excluir a configuração cadastrada, clique no botão **Excluir**.

---

---

## M-29.1 - Como Gerenciar Termos Salvos (Reimprimir, Inutilizar, Digitalizar)
**Objetivo:** Descrever as ações de gerenciamento disponíveis para um Termo de Comparecimento já salvo, como reimprimir, reutilizar, inutilizar, copiar, digitalizar e visualizar anexos.  
**Tags:** `Termo de Comparecimento`, `Gerenciamento`, `Manutenção`, `Imprimir`, `Reutilizar`, `Inutilizar`, `Digitalizar`, `Copiar`, `Anexo`

### Intenções de Busca & Dúvidas Frequentes
- digitalizar DUT
- Como eu faço para reimprimir a etiqueta de um termo de comparecimento?
- Preciso digitalizar o DUT e anexar ao termo que já foi salvo, onde eu faço isso?
- O que acontece quando eu 'inutilizo' um termo de comparecimento?
- reutilizar termo
- gerenciar termo
- reimprimir termo
- cancelar termo
- Fiz um termo de comparecimento errado. Como eu faço para reutilizar a folha do livro?
- É possível copiar os dados de um termo já existente para criar um novo?
- inutilizar termo de comparecimento
- copiar dados de um termo

### Procedimento / Explicação
Após um Termo de Comparecimento ser salvo, ele é listado na seção "Termos" dentro do pedido, onde diversas ações de manutenção podem ser executadas.

    #### Passo a passo para gerenciar termos salvos:

    1.  Acesse a tela de Termos de Comparecimento de um pedido existente.

    2.  Na seção **Termos**, localize o termo que deseja gerenciar na lista. Ao clicar sobre ele, suas informações são carregadas na tela para uma possível edição.

    3.  Utilize os ícones de ação na linha do termo para executar as seguintes operações:

        * **Copiar**: Se houver reconhecimentos disponíveis no pedido, esta ação permite copiar os dados de um termo existente para criar um novo rapidamente.

        * **Imprimir/Reimprimir**: Permite realizar a impressão ou a reimpressão da etiqueta de um termo de comparecimento já salvo.

        * **Reutilizar**: Efetua a reutilização completa do termo. As posições do livro e os nomes dos reconhecidos são liberados para a criação de um novo termo. O sistema também perguntará se o papel de segurança (se houver) deve ser reutilizado.

        * **Inutilizar**: Efetua a inutilização do termo. Os nomes dos reconhecidos são liberados, mas as posições utilizadas no livro são mantidas como inutilizadas. O sistema também perguntará se o papel de segurança deve ser inutilizado.

        * **Digitalizar**: Permite anexar a imagem digitalizada do termo (DUT/CRV). Para termos do tipo **CRV SEFAZ-SP**, esta ação segue os parâmetros de captura configurados no sistema.

        * **Visualizar Anexo**: Permite ver o documento que foi digitalizado e anexado ao termo.

---

---

## R-30.0 - Reutilizar Posição de Livro Inutilizada
**Objetivo:** Recuperar uma posição (folha/lado/posição) de um livro que foi marcada como 'inutilizada', tornando-a disponível para uso novamente.  
**Tags:** `livros`, `administração`, `controle de livros`, `reutilização`, `inutilizado`

### Intenções de Busca & Dúvidas Frequentes
- estornar posição de livro
- Como eu reverto a inutilização de uma posição no livro de termos?
- recuperar folha de livro
- Onde eu vejo as posições de livro que foram inutilizadas?
- Inutilizei uma folha do livro por engano, como faço para poder usá-la de novo?
- reverter inutilização
- liberar folha inutilizada

### Procedimento / Explicação
#### Passo a passo:

1.  Acesse o menu **Administração > Controle de Livros**.

2.  Informe o **número do livro** desejado e clique no ícone do livro pequeno para abrir os detalhes.

3.  Na janela que será exibida, acesse a aba **Inutilizados**.

4.  Selecione a posição que deseja recuperar.

5.  Utilize as setas de movimentação para transferir a posição de volta para uso.

6.  A posição selecionada retornará para o controle do sistema e ficará disponível para consulta na aba **Reutilizadas**.

---

---

## R-32.1 - Erro 'O serviço local não foi encontrado' nas Comunicações
**Objetivo:** Solucionar o erro 'O serviço local não foi encontrado' que ocorre ao tentar realizar comunicações com serviços externos como SIGNO, ITCMD e DOI.  
**Tags:** `erro`, `serviço local`, `integrador local`, `comunicação`, `signo`, `itcmd`, `doi`

### Intenções de Busca & Dúvidas Frequentes
- erro de comunicação
- O que é o Integrador Local e como eu o abro?
- serviço local não funciona
- falha no integrador
- integrador local não encontrado
- problema com signo
- Apareceu a mensagem 'O serviço local não foi encontrado', o que eu faço?
- Por que não consigo comunicar com o SIGNO, ITCMD ou DOI?

### Procedimento / Explicação
#### Descrição:

Essa mensagem pode ser exibida no sistema OrionTN durante o processo de comunicação com órgãos e serviços externos, como SIGNO, ITCMD, DOI, entre outros.

#### Causa:

O erro ocorre quando o **Integrador Local** não está aberto ou não está instalado na estação de trabalho do usuário.

#### Passo a passo para corrigir:

1.  Verifique se o aplicativo **Integrador Local** está aberto em sua máquina.

2.  Caso não esteja aberto, simplesmente inicie o programa e tente realizar o processo de comunicação novamente.

3.  Se o **Integrador Local** não estiver instalado em seu computador, entre em contato com a equipe de atendimento para que seja realizada a instalação.

---

---

## R-33.0 - Como Consultar Protocolos de Notas
**Objetivo:** Realizar buscas por protocolos de notas específicos utilizando uma variedade de filtros como data, livro, folha, escrevente ou natureza do ato.  
**Tags:** `consultas`, `protocolos`, `notas`, `busca`, `relatório`

### Intenções de Busca & Dúvidas Frequentes
- pesquisar protocolos
- Preciso encontrar um protocolo antigo, como eu faço a busca?
- buscar ato notarial
- encontrar escritura
- filtrar protocolos
- relatório de protocolos
- Onde eu busco por uma escritura usando o nome da parte envolvida?
- Como eu gero um relatório de protocolos de um certo período?
- Como eu faço para consultar um protocolo específico?

### Procedimento / Explicação
#### Passo a passo:

1.  Acesse o caminho: **OrionTN > Notas > Consultas > Protocolos**.

2.  Na tela que será aberta, preencha os filtros necessários de acordo com o resultado que espera em sua consulta, como: **data do recibo**, **data de recepção**, **livro**, **folha**, **escrevente**, **natureza**, etc.

3.  Clique no botão **"filtrar"** e o resultado da sua busca será exibido em tela.

4.  Se desejar imprimir um relatório dos protocolos consultados, clique no botão **"imprimir"** e selecione o modelo disponível.

* **Observação Importante:** Se o sistema informar que não há modelo de impressão cadastrado, entre em contato com a equipe de atendimento para que seja realizada a configuração do modelo.

---

---

## R-34.0 - Como Consultar o Índice de Escrituras e Procurações
**Objetivo:** Realizar buscas no índice de atos notariais (escrituras e procurações) utilizando diversos critérios para localizar registros específicos.  
**Tags:** `consultas`, `índice`, `escrituras`, `procurações`, `busca`

### Intenções de Busca & Dúvidas Frequentes
- índice de atos
- pesquisar no índice
- Como eu consulto o índice de atos?
- buscar escritura antiga
- Como eu acho uma procuração antiga pelo número do livro e da folha?
- Onde eu procuro por uma escritura usando o nome de uma das partes?
- achar protocolo antigo
- consultar procuração pelo nome

### Procedimento / Explicação
#### Passo a passo:

1.  Acesse o caminho: **OrionTN > Notas > Consultas > Índice de escrituras e procurações**.

2.  Na tela que será aberta, preencha os filtros necessários de acordo com o resultado que espera em sua consulta, como: **data do recibo**, **data de recepção**, **livro**, **folha**, **escrevente**, **natureza**, **tipo de participação**, **nome/documento do solicitante**, etc.

3.  Clique no botão **"filtrar"** e o resultado da busca será exibido em tela.

---

---

## M-34.0 - Gerenciar Tipos de Anexo
**Objetivo:** Acessar, filtrar e gerenciar os tipos de anexo cadastrados no sistema (ex: 'Documento de Identidade'), permitindo a visualização, alteração e inativação dos registros.  
**Tags:** `Configurações`, `Negócios`, `Cadastros`, `Tipos de Anexo`, `Filtros`, `Visualizar`, `Alterar`, `Excluir`

### Intenções de Busca & Dúvidas Frequentes
- tipos de documentos para anexar
- configurar anexo
- Como eu inativo um tipo de anexo que não é mais utilizado?
- Onde eu gerencio os tipos de anexo que posso usar no sistema, como 'Comprovante de Endereço'?
- Preciso editar o nome de um tipo de anexo, como eu faço?
- cadastro de anexo
- gerenciar categorias de anexo

### Procedimento / Explicação
#### Descrição:

A tela de **Tipos de Anexo** permite gerenciar os cadastros existentes. Ao ser aberta, exibe todos os registros em ordem alfabética, com 10 registros por página por padrão. Possui filtros para facilitar a busca e o gerenciamento dos tipos de anexo.

#### Passo a passo para Gerenciar Tipos de Anexo:

1.  Acesse o menu **Configurações > Negócios > Cadastros > Tipos de anexo**.

2.  Na tela de **Tipos de Anexo**, você pode utilizar os seguintes filtros para refinar sua busca:

    *   **Pesquisar por descrição**: Permite efetuar uma busca pela descrição do tipo de anexo.

    *   **Inativos**: Quando selecionado, permite efetuar uma busca apenas pelos cadastros que foram inativados.

    *   **Quantidade por página**: Permite alterar a quantidade de resultados apresentados em tela.

    *   **Limpar**: Limpa a consulta realizada, retornando a tela para o estado inicial.

    *   **Filtrar**: Quando acionado, realiza o filtro com base nos campos de busca preenchidos.

3.  A seção **Resultados** exibe todos os tipos de anexo cadastrados. Para cada registro, as seguintes ações estão disponíveis:

    *   **Visualizar**: Quando acionado, exibe a tela de consulta, contendo os dados preenchidos do tipo de anexo. Não permite alterações.

    *   **Alterar**: Quando acionado, exibe a tela de alteração, contendo os dados preenchidos do tipo de anexo, permitindo assim sua edição.

    *   **Excluir**: Quando acionado, inativa o cadastro, tornando-o indisponível para uso. Para localizar os cadastros inativos, basta marcar a opção **Inativos** e realizar o filtro.

---

---

## R-35.0 - Gerar Relatório de ISS
**Objetivo:** Gerar e imprimir o relatório de valores de ISS (Imposto Sobre Serviços) de um período específico.  
**Tags:** `Relatórios`, `ISS`, `Financeiro`, `Impostos`, `Impressão`

### Intenções de Busca & Dúvidas Frequentes
- tirar relatório de ISS
- relatório de imposto sobre serviço
- imprimir relatório ISS
- Preciso imprimir o relatório de ISS, qual o caminho?
- Como eu gero o relatório de ISS no Orion?
- consultar valores de ISS
- Onde eu tiro o relatório de Imposto Sobre Serviço para um período?

### Procedimento / Explicação
#### Passo a passo:

1.  No sistema OrionTN, acesse o caminho: **Relatórios > Relatório ISS**.

2.  Na tela que será aberta, informe o **período** para o qual deseja visualizar os valores de ISS.

3.  Após informar o período, clique no botão **"imprimir"**.

4.  Por fim, uma nova aba será aberta no navegador com a impressão do relatório.

---

---

## M-35.0 - Cadastrar Novo Tipo de Anexo
**Objetivo:** Realizar o cadastro de um novo tipo de anexo no sistema, definindo sua descrição e sigla para categorizar os documentos que serão digitalizados.  
**Tags:** `Configurações`, `Negócios`, `Cadastros`, `Tipos de Anexo`, `Adicionar`, `Descrição`, `Sigla`, `Observações`

### Intenções de Busca & Dúvidas Frequentes
- Quero criar uma nova categoria para os documentos que anexo nos protocolos, qual o caminho?
- novo tipo de documento para anexar
- adicionar categoria de anexo
- criar tipo de anexo
- Como eu cadastro um novo tipo de anexo, como por exemplo 'Procuração'?

### Procedimento / Explicação
#### Passo a passo para cadastrar um novo tipo de anexo:

1.  Acesse o menu **Configurações > Negócios > Cadastros > Tipos de anexo**.

2.  Na tela de **Tipos de anexo**, clique no botão **Adicionar**.

3.  Na tela de cadastro de tipos de anexo, preencha os seguintes campos:

    *   **Descrição**: Informe uma descrição obrigatória para o tipo de anexo. Esta será exibida na tela para seleção. Exemplo: "Documento de identidade".

    *   **Sigla**: Preencha com uma sigla de até três letras, para abreviar o tipo de anexo em algumas telas e relatórios. Exemplo: "RG".

    *   **Observações**: Caso o tipo de anexo possua alguma informação adicional, informe neste campo.

4.  Clique em **Concluir** para finalizar o cadastro.

---

---

## R-36.0 - Imprimir Relatório do Livro de Protocolo
**Objetivo:** Gerar e imprimir o relatório do Livro de Protocolo para um período específico, com opções para rascunho ou impressão definitiva por livro e folha.  
**Tags:** `Relatórios`, `Livro Protocolo`, `Protocolo`, `Impressão`, `Conciliação`

### Intenções de Busca & Dúvidas Frequentes
- relatório de conciliação de protocolo
- Como eu imprimo o relatório do Livro de Protocolo?
- livro de protocolo rascunho
- gerar livro protocolo
- É possível imprimir um rascunho do Livro de Protocolo?
- imprimir livro de protocolo
- Onde eu tiro a conciliação dos protocolos em formato de livro?
- Como eu gero o Livro de Protocolo de um livro e folha específicos?

### Procedimento / Explicação
#### Passo a passo:

1.  No sistema OrionTN, acesse o caminho: **Relatórios > Livro Protocolo**.

2.  Na tela que será aberta, informe o **período** no qual queira visualizar a conciliação dos protocolos.

3.  Defina o tipo de impressão:

    * **Para Rascunho:** Marque a flag referente a "rascunho".

    * **Para Impressão Definitiva:** Se não for um rascunho, informe o **livro** e a **folha** que serão impressos.

4.  Após, clique no botão **"Imprimir"**.

5.  Por fim, uma nova aba será aberta com a impressão do relatório.

---

# SEÇÃO PRINCIPAL 2: TRANSCRIÇÕES FORMATADAS DAS VIDEOAULAS - Orion TN
***DESCRIÇÃO DA SEÇÃO:** Esta seção compila as transcrições já formatadas das videoaulas do Orion TN, incluindo metadados úteis para contextualização e busca.*

---

## M-37.0 - Cadastrar Novo Documento Apresentado (Cadastros Auxiliares)
**Objetivo:** Cadastrar um novo tipo de 'Documento Apresentado' no sistema, preenchendo as informações de descrição, sigla e observações para ser usado nas telas de protocolo.  
**Tags:** `Configurações`, `Geral`, `Cadastros Auxiliares`, `Documento Apresentado`, `Adicionar`, `Descrição`, `Sigla`, `Observação`

### Intenções de Busca & Dúvidas Frequentes
- novo tipo de documento
- adicionar documento na lista
- Onde eu cadastro um novo tipo de documento para que ele apareça como opção nos protocolos?
- criar documento apresentado
- Como eu adiciono um novo item à lista de 'Documentos Apresentados'?

### Procedimento / Explicação
#### Descrição:

A tela de **Documentos Apresentados** exibe uma tabela com os tipos de documentos já cadastrados. Para adicionar um novo, é necessário preencher os campos específicos para o registro.

#### Passo a passo para cadastrar um novo documento apresentado:

1.  Acesse o menu **Configurações > Geral > Cadastros Auxiliares > Documento Apresentado**.

2.  Na tela **Documentos Apresentados**, clique no botão **Adicionar**.

3.  Preencha os seguintes campos para o novo documento apresentado:

    *   No campo **Descrição**, preencha o título do documento apresentado que está cadastrando.

    *   No campo **Sigla**, preencha a sigla para o documento que está cadastrando.

    *   No campo **Observação**, preencha com as observações que deseja.

4.  Clique em **Concluir** para finalizar o cadastro.

---

---

## M-38.0 - Gerenciar Situação do Protocolo
**Objetivo:** Acessar, filtrar e gerenciar as 'Situações de Protocolo' cadastradas (ex: 'Em andamento', 'Aguardando Documentos'), permitindo visualizar, alterar e inativar os registros.  
**Tags:** `Configurações`, `Geral`, `Cadastros Auxiliares`, `Situação do Protocolo`, `Filtros`, `Visualizar`, `Alterar`, `Excluir`

### Intenções de Busca & Dúvidas Frequentes
- inativar situação
- Como eu edito o nome de uma situação de protocolo existente?
- editar situação de protocolo
- Onde eu gerencio as opções de 'Situação do Protocolo' que aparecem na tela de notas?
- Preciso inativar uma situação de protocolo que não usamos mais. Como proceder?
- gerenciar status de protocolo

### Procedimento / Explicação
#### Descrição:

A tela de **Situação do protocolo** permite gerenciar os cadastros existentes. Ao ser aberta, exibe todos os registros em ordem de cadastro, com 10 registros por página por padrão. Possui filtros para facilitar a busca e o gerenciamento das situações de protocolo.

#### Passo a passo para Gerenciar Situação do Protocolo:

1.  Acesse o menu **Configurações > Geral > Cadastros auxiliares > Situação do protocolo**.

2.  Na tela de **Situação do protocolo**, você pode utilizar os seguintes filtros para refinar sua busca:

    *   **Pesquisar por descrição**: Permite efetuar uma busca pela descrição da situação.

    *   **Inativos**: Quando selecionado, permite efetuar uma busca apenas pelos cadastros que foram inativados.

    *   **Quantidade por página**: Permite alterar a quantidade de resultados apresentados em tela.

    *   **Limpar**: Limpa a consulta realizada, retornando a tela para o estado inicial.

    *   **Filtrar**: Quando acionado, realiza o filtro com base nos campos de busca preenchidos.

3.  A seção **Resultados** exibe todas as situações cadastradas. Para cada registro, as seguintes ações estão disponíveis:

    *   **Visualizar**: Quando acionado, exibe a tela de consulta, contendo os dados preenchidos. Não permite alterações.

    *   **Alterar**: Quando acionado, exibe a tela de alteração, contendo os dados preenchidos, permitindo assim sua edição.

    *   **Excluir**: Quando acionado, inativa o cadastro, tornando-o indisponível para uso. Para localizar os cadastros inativos, basta marcar a opção **Inativos** e realizar o filtro.

---

---

## M-39.0 - Cadastrar Nova Situação de Protocolo
**Objetivo:** Cadastrar uma nova 'Situação de Protocolo' no sistema, definindo sua descrição para ser utilizada como uma etapa ou status no andamento dos atos notariais.  
**Tags:** `Configurações`, `Negócios`, `Cadastros`, `Situação do Protocolo`, `Adicionar`, `Descrição`, `Observações`

### Intenções de Busca & Dúvidas Frequentes
- nova etapa para protocolo
- adicionar status de andamento
- Como eu cadastro uma nova 'Situação de Protocolo', como por exemplo 'Aguardando Assinatura'?
- Onde eu crio novas opções para o campo 'Situação' dentro de um protocolo?
- criar situação de protocolo

### Procedimento / Explicação
#### Passo a passo para cadastrar uma nova situação de protocolo:

1.  Acesse o menu **Configurações > Negócios > Cadastros > Situação do Protocolo**.

2.  Na tela de **Situação do Protocolo**, clique no botão **Adicionar**.

3.  Na tela de cadastro de status, preencha os seguintes campos:

    *   **Descrição**: Informe uma descrição obrigatória para o status, a qual será exibida na tela para seleção. Exemplo: "Iniciado".

    *   **Observações**: Caso o status possua alguma informação adicional, informe neste campo.

4.  Clique em **Concluir** para finalizar o cadastro.

---

---

## M-40.0 - Gerenciar Alíquotas
**Objetivo:** Acessar, filtrar e gerenciar as alíquotas de impostos (ex: ITBI) cadastradas por cidade no sistema, permitindo a visualização, alteração e limpeza dos valores.  
**Tags:** `Configurações`, `Geral`, `Cadastros Auxiliares`, `Alíquotas`, `Filtros`, `Visualizar`, `Alterar`, `Limpar Alíquota`

### Intenções de Busca & Dúvidas Frequentes
- configurar alíquotas por cidade
- editar alíquota de imposto
- A alíquota de ITBI de uma cidade mudou. Como eu faço para alterar no sistema?
- Onde eu gerencio as alíquotas de ITBI por cidade?
- Como eu consulto qual a alíquota cadastrada para um determinado município?
- gerenciar ITBI

### Procedimento / Explicação
#### Descrição:

A tela de **Alíquota** permite gerenciar os cadastros existentes. Ao ser aberta, exibe todos os registros, com 10 registros por página por padrão. Possui filtros para facilitar a busca e o gerenciamento das alíquotas.

#### Passo a passo para Gerenciar Alíquotas:

1.  Acesse o menu **Configurações > Geral > Cadastros auxiliar > Alíquotas**.

2.  Na tela de **Alíquota**, você pode utilizar os seguintes filtros para refinar sua busca:

    *   **Pesquisar por UF**: Permite efetuar uma busca pela UF da alíquota. Exemplo: "SP".

    *   **Pesquisar por cidade**: Permite efetuar uma busca pela cidade da alíquota.

    *   **Quantidade por página**: Permite alterar a quantidade de resultados apresentados em tela.

    *   **Limpar**: Limpa a consulta realizada, retornando a tela para o estado inicial.

    *   **Filtrar**: Quando acionado, realiza o filtro com base nos campos de busca preenchidos.

3.  A seção **Resultados** exibe todas as alíquotas cadastradas. Para cada registro, as seguintes ações estão disponíveis:

    *   **Visualizar**: Quando acionado, exibe a tela de consulta, contendo os dados preenchidos da alíquota. Não permite alterações.

    *   **Alterar**: Quando acionado, exibe a tela de alteração, contendo os dados preenchidos da alíquota, permitindo assim sua edição.

    *   **Limpar**: Quando acionado, limpa o valor da alíquota.

---

---

## M-41.0 - Cadastrar Área de Atuação
**Objetivo:** Realizar o cadastro de uma nova 'Área de Atuação' no sistema, preenchendo um código numérico e a descrição da área.  
**Tags:** `Configurações`, `Negócio`, `Cadastros`, `Área de Atuação`, `Adicionar`, `Código`, `Descrição`

### Intenções de Busca & Dúvidas Frequentes
- cadastrar setor
- Como eu cadastro uma nova Área de Atuação no sistema?
- nova área de atuação
- adicionar área no sistema
- Onde eu defino o código e a descrição de uma nova área de atuação?

### Procedimento / Explicação
#### Descrição:

A rotina permite adicionar novas áreas de atuação ao sistema, definindo um código único e uma descrição para cada uma.

#### Passo a passo para cadastrar uma área de atuação:

1.  Acesse o menu **Configurações > Negócio > Cadastros > Área de Atuação**.

2.  Na tela de **Área de Atuação**, clique no botão **Adicionar**.

3.  Na tela de **Cadastro de uma área de atuação**, preencha as seguintes informações:

    *   **Código**: Informe um número de 3 dígitos para a Área Cadastrada.

    *   **Descrição**: Informe o nome da área de atuação que será cadastrada.

4.  Após o preenchimento das informações, clique em **Concluir** para cadastrar a nova área de atuação.

*   **IMPORTANTE:** Para o cadastro de uma nova área de atuação, é obrigatório que todos os campos dessa etapa sejam preenchidos corretamente.

---

---

## M-42.0 - Gerenciar Modelos de Etiqueta
**Objetivo:** Acessar e gerenciar os modelos de etiqueta cadastrados no sistema, utilizando filtros para pesquisa e realizando ações como visualização, edição e inativação.  
**Tags:** `Configurações`, `Negócios`, `Modelos`, `Etiqueta`, `Filtros`, `Visualizar`, `Editar`, `Inativar`, `Adicionar`

### Intenções de Busca & Dúvidas Frequentes
- consultar etiquetas cadastradas
- gerenciar layouts de etiqueta
- Onde eu gerencio os modelos de etiqueta para reconhecimento de firma?
- Como eu edito um modelo de etiqueta que já está cadastrado?
- Preciso inativar um modelo de etiqueta antigo, como eu faço?
- editar modelo de etiqueta

### Procedimento / Explicação
#### Descrição:

A tela de **Modelos etiqueta** exibe uma listagem dos modelos de etiqueta cadastrados no sistema, permitindo a aplicação de filtros para pesquisa e a execução de ações sobre os registros.

#### Passo a passo para Gerenciar Modelos de Etiqueta:

1.  Acesse o menu **Configurações > Negócios > Modelos > Etiqueta**.

2.  Após acessar a tela, você terá acesso à listagem de modelos de etiqueta, onde:

    *   Em **A** e **B** (conforme indicação no sistema, se houver) estão os filtros disponíveis para pesquisa.

    *   Em **C** (conforme indicação no sistema, se houver) são exibidos os modelos cadastrados.

    *   Em **D** (conforme indicação no sistema, se houver) estão as ações disponíveis para cada modelo: **visualização**, **edição** e **inativação**.

3.  Para adicionar novos modelos, clique no botão **Adicionar**.

---

---

## M-43.0 - Gerenciar Perfil de Partes
**Objetivo:** Acessar, filtrar e gerenciar os perfis de partes (conjuntos pré-definidos de participantes), permitindo a visualização, alteração e inativação dos registros.  
**Tags:** `Configurações`, `Negócios`, `Cadastros`, `Perfil de Partes`, `Filtros`, `Visualizar`, `Alterar`, `Excluir`

### Intenções de Busca & Dúvidas Frequentes
- gerenciar perfis de participantes
- Onde eu gerencio os perfis de partes, como o perfil 'Compra e Venda' ou 'Procuração'?
- Como eu edito um perfil de partes para adicionar ou remover uma participação?
- Preciso inativar um perfil de partes que não é mais utilizado, como faço?
- editar perfil de partes
- inativar perfil de partes
- consultar perfis de atos

### Procedimento / Explicação
#### Descrição:

A tela de **Perfil de partes** permite gerenciar os cadastros existentes. Ao ser aberta, o sistema carrega todos os registros em ordem alfabética. Possui filtros para facilitar a busca e o gerenciamento dos perfis de partes.

#### Passo a passo para Gerenciar Perfil de Partes:

1.  Acesse o menu **Configurações > Negócios > Cadastros > Perfil de partes**.

2.  Na tela de **Perfil de partes**, você pode utilizar os seguintes filtros para refinar sua busca:

    *   **Pesquisar por descrição**: Permite efetuar uma busca pela descrição do perfil de partes. Exemplo: "Compradores".

    *   **Inativos**: Quando selecionado, permite efetuar uma busca apenas pelos cadastros que foram inativados.

    *   **Limpar**: Limpa a consulta realizada, retornando a tela para o estado inicial.

    *   **Filtrar**: Quando acionado, realiza o filtro com base nos campos de busca preenchidos.

3.  A seção **Resultados** exibe todos os cadastros. Para cada registro, as seguintes ações estão disponíveis:

    *   **Visualizar**: Quando acionado, exibe a tela de consulta, contendo os dados preenchidos do perfil de partes. Não permite alterações.

    *   **Alterar**: Quando acionado, exibe a tela de alteração, contendo os dados preenchidos do perfil de partes, permitindo assim sua edição.

    *   **Excluir**: Quando acionado, inativa o cadastro, tornando-o indisponível para uso. Para localizar os cadastros inativos, basta marcar a opção **Inativos** e realizar o filtro.

---

---

## M-44.0 - Cadastrar Novo Perfil de Partes
**Objetivo:** Cadastrar um novo perfil de partes no sistema, definindo sua descrição e vinculando as participações desejadas para agilizar a qualificação em protocolos.  
**Tags:** `Configurações`, `Negócios`, `Cadastros`, `Perfil de Partes`, `Adicionar`, `Descrição`, `Participações`

### Intenções de Busca & Dúvidas Frequentes
- criar perfil de partes
- novo perfil de participantes
- Como eu crio um novo perfil de partes para agilizar o preenchimento dos protocolos?
- adicionar perfil de ato
- Onde eu defino quais participações (ex: comprador, vendedor) farão parte de um novo perfil?
- Quero criar um perfil chamado 'Doação' com 'Doador' e 'Donatário' pré-definidos, como faço?
- configurar grupo de partes

### Procedimento / Explicação
#### Descrição:

Esta rotina permite o cadastro de novos perfis de partes, onde é possível definir um nome para o perfil e associá-lo a participações específicas.

#### Passo a passo para cadastrar um novo perfil de partes:

1.  Acesse o menu **Configurações > Negócios > Cadastros > Perfil de Partes**.

2.  Ao carregar a página **Perfil de partes**, clique no botão **Adicionar**, disponibilizado abaixo da lista de perfis cadastrados.

3.  Para cadastrar um novo perfil de partes, preencha os seguintes campos e utilize as opções:

    *   **Descrição**: Informe o nome do perfil que será cadastrado.

    *   **Lista de participações Cadastradas**: Esta lista contém todas as participações que poderão ser vinculadas ao perfil que está sendo cadastrado.

    *   **Lista de participações Selecionadas**: Esta lista contém todas as participações que foram selecionadas pelo usuário para serem vinculadas ao perfil que está sendo cadastrado.

    *   **Botão Voltar**: Clique neste botão para retornar à tela com a lista de perfis cadastrados.

4.  Ao preencher todos os campos e selecionar as participações, clique no botão **Concluir** para cadastrar o perfil.

---

---

## M-48.0 - Acessar e Gerenciar Filiais
**Objetivo:** Acessar a tela de gerenciamento de filiais de mensalistas, permitindo a busca por registros específicos e a execução de ações como visualização, alteração, inativação e bloqueio.  
**Tags:** `Filiais`, `Mensalista`, `Administração`, `Consulta`, `Filtro`, `Visualizar`, `Alterar`, `Inativar`, `Bloquear`

### Intenções de Busca & Dúvidas Frequentes
- Preciso bloquear uma filial para que não possam mais lançar serviços para ela, como faço?
- Onde eu gerencio as filiais de um cliente mensalista?
- gerenciar filiais
- bloquear filial
- Como eu busco uma filial específica pelo seu CNPJ?
- editar filial
- inativar filial
- buscar filiais de mensalista

### Procedimento / Explicação
#### Descrição:

Ao acessar a tela de Filiais, será apresentada uma tabela de dados em ordem alfabética com todas as filiais cadastradas no sistema.

#### Passo a passo para acesso e filtragem:

1.  Para acessar a tela de filiais, clique no menu **Administração > Mensalista > Filiais**.

2.  Caso seja necessária uma busca específica, preencha os campos de filtro disponíveis em tela:

    *   **Mensalista**: Para pesquisa por um mensalista específico.

    *   **Pesquisa por Filial**: Para pesquisa por uma filial específica.

    *   **Documento**: Para realizar uma busca por documento (CNPJ ou CPF).

    *   **Número**: Para digitar o número do documento selecionado no item **Documento**.

    *   **Status**: Para buscar por um status específico.

    *   **Rótulos**: Para realizar buscas mais detalhadas através dos rótulos que foram inseridos no cadastro do mensalista. É possível utilizar um ou vários rótulos.

3.  Após preencher as informações necessárias para realizar o filtro, pressione a tecla **Enter** ou clique no botão **Filtrar**.

4.  Para limpar as informações preenchidas, clique no botão **Limpar**.

*   **Observação**: Caso a opção **CPF** ou **CNPJ** seja selecionada no campo **Documento**, a busca só será possível se o campo **Número** for preenchido corretamente.

#### Ações disponíveis na listagem de filiais:

A partir da listagem de filiais é possível executar as seguintes ações:

1.  **Visualizar Filial**: Para visualizar os dados cadastrados da filial.

2.  **Alterar Filial**: Para editar as informações da filial cadastrada.

3.  **Inativar Filial**: Para inativar a filial cadastrada.

    *   **IMPORTANTE**: Caso a filial esteja inativada, ela não aparecerá no momento de executar o serviço solicitado.

4.  **Bloquear Filial**: Para bloquear a filial.

    *   **IMPORTANTE**: Caso a filial esteja bloqueada, não será possível apontar esta filial no momento de executar o serviço de notas ou balcão de firmas.

---

---

## M-49.0 - Cadastrar Nova Filial
**Objetivo:** Realizar o cadastro de uma nova filial, preenchendo seus dados cadastrais, vinculando-a a um mensalista principal e definindo suas configurações específicas de faturamento.  
**Tags:** `Filiais`, `Cadastro`, `Mensalista`, `Configurações`, `Plano`, `Desconto`, `E-mail`, `Dia de fechamento`, `Rótulos`, `Observações`, `Arquivos anexos`

### Intenções de Busca & Dúvidas Frequentes
- nova filial de mensalista
- É possível uma filial ter um dia de fechamento diferente da matriz mensalista?
- vincular filial a mensalista
- Como eu cadastro uma nova filial e a vinculo a um mensalista que já existe?
- adicionar filial
- Onde eu cadastro uma nova filial para um cliente de faturamento?
- cadastrar filial

### Procedimento / Explicação
#### Passo a passo para cadastrar uma nova filial:

1.  Para acessar a tela de filiais, clique no menu **Administração > Mensalista > Filiais**.

2.  Na tela de **Filiais**, clique no botão **Adicionar** (disponível abaixo da lista de filiais).

#### Seções da tela de Cadastro de Filiais:

Na tela de **Cadastro de filiais**, o preenchimento das informações está separado por seções:

*   **Dados cadastrais**: Para preenchimento dos dados cadastrais da filial.

*   **Mensalista**: Utilizado para definir o mensalista ao qual essa filial será vinculada.

#### Configurações:

Para aplicar configurações personalizadas em cada Filial:

1.  **Plano**: Seleção de plano pós-pago e pré-pago. A seleção do plano influencia no momento da lavratura do ato.

    *   **Pós-pago**: Os serviços serão realizados, e posteriormente será realizado o pagamento de acordo com o seu fechamento.

    *   **Pré-pago**: Os serviços só serão realizados para a Filial se o Mensalista a ele Vinculado tiver crédito disponível para ser consumido. Caso não tenha crédito, no momento de realizar o ato, o sistema alertará que este mensalista não possui crédito e não é possível prosseguir com a realização do serviço.

2.  **Desconto (%)**: O percentual de desconto será aplicado no momento de fechamento do mensalista. O desconto será aplicado sobre o valor total da cobrança que será gerado para o mensalista.

3.  **E-mail (envio de extrato)**: Serão os destinatários que poderão receber o extrato da filial.

    *   **IMPORTANTE**: Para inserir os e-mails, podem ser adicionados vários. Para incluir mais de um e-mail, insira o e-mail e aperte a tecla **ENTER** para inserir o próximo e-mail.

4.  **Dia de fechamento**: Poderá ser utilizado como filtro no momento de realizar o fechamento do mensalista, ou seja, no momento de gerar o extrato do mensalista o usuário poderá gerar os extratos de todos os mensalistas com a data de fechamento igual a um dia específico (ex: 5). Não será permitido inserir mais que 3 dias de fechamento.

    *   Para inserir mais um dia de fechamento, clique no botão **" + "** (sinal de adição).

5.  **Rótulos**: Através dos rótulos será possível tornar a busca das filiais mais completa. Por exemplo, pode-se criar um rótulo de "bom pagador" que poderá ser utilizado como filtro nas rotinas de filiais. O campo permite que seja criado um ou vários rótulos no cadastro da filial.

6.  **Observações**: Para inserir observações no cadastro da filial.

#### Arquivos anexos:

*   Para anexar documentos no cadastro da filial.

---

---

## M-51.0 - Funcionalidades Gerais da Tela de Protocolo
**Objetivo:** Apresentar as funcionalidades e ações principais disponíveis na tela de Protocolo, como criar, editar, salvar, consultar, e gerenciar anexos, trâmites, recibos e selos.  
**Tags:** `Protocolo`, `Notas`, `Orçamento`, `Anexos`, `Trâmites`, `Andamentos`, `Recibo`, `Selo digital`, `Caixa`

### Intenções de Busca & Dúvidas Frequentes
- gerenciar protocolo
- Pode me explicar para que servem os principais botões da tela de Protocolo?
- ações do protocolo
- Como eu consulto os protocolos que ainda estão em aberto?
- tela de protocolo
- Qual a função do botão 'Trâmites' dentro de um protocolo?
- menu do protocolo

### Procedimento / Explicação
#### Descrição:

A tela de Protocolo é a área central para a lavratura de atos notariais. Esta rotina descreve as funcionalidades e botões principais disponíveis na interface para o gerenciamento geral dos protocolos.

#### Passo a passo para acessar e utilizar as funcionalidades:

1.  Para acessar a tela de Protocolo, clique no menu **Notas > Protocolo**.

2.  A tela disponibiliza as seguintes funcionalidades no menu superior:

    * **Novo**: Para criar um novo protocolo.

    * **Editar**: Para habilitar a edição de um protocolo existente.

    * **Salvar**: Para salvar as alterações realizadas em um protocolo.

    * **Protocolos em aberto**: Para consultar os protocolos que ainda não foram lavrados. É possível configurar permissões para que o escrevente veja todos os protocolos ou apenas os seus.

    * **Cartão de assinatura**: Para buscar um cartão de assinatura e utilizar seus dados no protocolo em edição.

    * **Orçamento**: Permite criar um **Orçamento Completo** (que pode ser convertido em protocolo) ou um **Orçamento Rápido**.

    * **Anexos**: Utilizado para anexar arquivos diversos ao protocolo.

    * **Documentos apresentados**: Para marcar os documentos que foram apresentados pela parte e digitalizá-los.

    * **Trâmites**: Utilizado para cadastrar os trâmites do protocolo (andamento interno).

    * **Andamentos**: Para visualizar o histórico completo de todas as ações registradas no protocolo.

    * **Gerar recibo**: Utilizado para imprimir o recibo no momento em que o ato for lavrado.

    * **Selo digital**: Para visualizar os selos digitais gerados no protocolo.

    * **Caixa**: Para realizar movimentações financeiras de entrada ou saída no protocolo.

    * **Consumir papel**: Utilizado para consumir produtos do estoque, como papel de segurança ou traslado.

    * **Papéis consumidos**: Para visualizar os papéis que foram consumidos no protocolo.

    * **Inutilizar protocolo**: Utilizado para inutilizar um protocolo criado.

    * **Cadastro retroativo**: Para cadastrar protocolos retroativos, geralmente para consulta de índice.

---

---

## M-51.1 - Como Preencher os Dados Principais de um Protocolo
**Objetivo:** Detalhar o preenchimento do card 'Dados do Protocolo', a primeira etapa para criar um novo ato, incluindo a definição de status, escrevente, espécie, natureza e solicitante.  
**Tags:** `Protocolo`, `Dados do Protocolo`, `Cadastro`, `Recepção`, `Status`, `Situação`, `Recibo`, `Escrevente`, `Espécie`, `Natureza`, `Solicitante`

### Intenções de Busca & Dúvidas Frequentes
- Como eu inicio o cadastro de um novo protocolo de escritura?
- abrir protocolo
- Quais são os primeiros campos que preciso preencher para criar um ato em notas?
- informações iniciais do protocolo
- Como eu seleciono a espécie e a natureza de um novo protocolo?
- preencher dados da escritura
- criar novo protocolo

### Procedimento / Explicação
#### Descrição:

O preenchimento correto dos dados principais do protocolo é fundamental para a lavratura do ato. Esta rotina detalha cada campo do card "Dados do Protocolo".

#### Passo a passo:

1.  Na tela de Protocolo, clique em **Novo**. O card **Dados do protocolo** será exibido.

2.  **Data da recepção**: Informe a data em que o protocolo foi realizado.

3.  **Status**: Campo preenchido automaticamente com o status atual do protocolo.

4.  **Situação**: Informe a situação do protocolo (ex: **Cancelado**, **Em andamento**). Novas situações podem ser cadastradas.

5.  **Recibo**: Campo preenchido automaticamente ao clicar em **Gerar recibo**.

6.  **Data do recibo**: Informe a data do recibo. Se deixado em branco, será usada a data atual ao gerar.

7.  **Escrevente**: Informe o escrevente responsável.

8.  **Espécie**: Selecione a espécie do protocolo para liberar as naturezas correspondentes.

9.  **Natureza**: Selecione a natureza de acordo com a espécie.

10. No bloco **Solicitante**, preencha os dados da pessoa que solicitou o ato.

    * *Observação:* Se selecionar o tipo "Mensalista", o valor dos serviços será lançado na conta do mensalista ao gerar o recibo.

11. Preencha os blocos **Endereço** e **Contato** do solicitante, utilizando o botão **Adicionar** para incluir múltiplos registros.

12. Após preencher todos os campos, clique em **Salvar**. Os outros cards do protocolo serão liberados para preenchimento.

13. Os campos **Livro**, **Folha inicial** e **Folha final** ficarão disponíveis para preenchimento após salvar. O sistema valida para não permitir duplicidade de livro e folhas.

---

---

## M-51.2 - Como Preencher Informações Complementares em um Protocolo
**Objetivo:** Orientar sobre o preenchimento do card 'Informações Complementares', que exibe campos dinâmicos (como dados de ITCMD ou óbito) baseados na natureza do ato selecionado.  
**Tags:** `Protocolo`, `Informações Complementares`, `Natureza`, `Inventário`, `ITCMD`, `SEFAZ`, `Objeto`

### Intenções de Busca & Dúvidas Frequentes
- preencher ITCMD no protocolo
- informar objeto do protocolo
- informações específicas da natureza
- Onde eu informo o objeto do ato, como a descrição do imóvel?
- Selecionei a natureza 'Inventário', onde eu preencho o número da declaração do ITCMD?
- dados complementares da escritura
- Para que serve o card 'Informações Complementares' no protocolo?

### Procedimento / Explicação
#### Descrição:

O card de 'Informações Complementares' adapta-se à natureza do protocolo, solicitando dados específicos necessários para comunicações ou registros.

#### Passo a passo:

1.  Após salvar os dados principais do protocolo, o card **Informações complementares** será exibido.

2.  Os campos apresentados dependem da **Natureza** selecionada anteriormente.

    * *Exemplo:* Para a natureza "Inventário", podem ser exibidos campos como **Nº de declaração do ITCMD**, **data do óbito/separação** e **anexo da escritura** para a SEFAZ.

3.  As configurações que determinam quais campos aparecem são definidas no cadastro auxiliar de **Natureza**.

4.  Se a natureza não exigir nenhuma informação específica, o card exibirá apenas o campo **Objeto**.

5.  Preencha o campo **Objeto** para descrever o bem ou direito em negociação no protocolo. Esta informação pode ser utilizada como filtro em telas de pesquisa.

---

---

## M-51.3 - Como Realizar a Qualificação de Partes em um Protocolo
**Objetivo:** Detalhar o processo de preenchimento do card 'Qualificação de Partes', incluindo a adição de participantes, a definição de sua participação e a consulta de indisponibilidade de bens.  
**Tags:** `Protocolo`, `Qualificação de Partes`, `Participantes`, `Pessoa Física`, `Pessoa Jurídica`, `Cartão de Assinatura`, `Indisponibilidade`

### Intenções de Busca & Dúvidas Frequentes
- É possível importar os dados de uma pessoa a partir do cartão de assinatura dela?
- Onde eu realizo a consulta de indisponibilidade de bens das partes do ato?
- adicionar partes na escritura
- Como eu adiciono as partes (comprador, vendedor, etc.) em um protocolo?
- consultar indisponibilidade de bens
- incluir comprador e vendedor
- qualificar participantes

### Procedimento / Explicação
#### Descrição:

A qualificação de partes é o processo de identificar e detalhar todas as pessoas físicas e jurídicas envolvidas em um ato notarial.

#### Passo a passo:

1.  Acesse o card **Qualificação de partes** em um protocolo já salvo.

2.  **Participação**: Selecione o tipo de participação da pessoa no ato (ex: Vendedor, Comprador). As opções disponíveis são configuradas na **Natureza** do protocolo.

3.  **Tipo de Pessoa**: Selecione se a parte é **Pessoa Física** ou **Pessoa Jurídica** e preencha os campos obrigatórios.

4.  **Cartão**: Para agilizar o preenchimento, digite o número de um **Cartão de Assinatura** já cadastrado para importar os dados da pessoa.

5.  **Informações do COAF**: Preencha os dados que serão utilizados na comunicação ao COAF.

6.  **Botão Importar Participantes**: Utilize esta opção para importar dados de participantes de outros protocolos existentes.

7.  **Botão Adicionar Participantes**: Clique para adicionar um novo participante ao ato.

8.  **Botão Indisponibilidade de partes**: Clique para consultar via webservice a indisponibilidade de bens de todas as partes na CNIB.

9.  **Botão + Informações**: Expanda esta opção para adicionar documentos e informações de contato adicionais para cada parte.

---

---

## M-51.4 - Como Gerenciar as Custas de um Protocolo
**Objetivo:** Instruir sobre o preenchimento do card 'Custas', detalhando como adicionar itens da tabela, realizar cálculos e informar valores de ITBI e de Registro de Imóveis.  
**Tags:** `Protocolo`, `Custas`, `Tabela de Custas`, `Cálculo`, `Valor Venal`, `ITBI`, `Registro de Imóveis`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu informo o valor venal e a base de cálculo para o sistema calcular os emolumentos?
- adicionar ITBI em escritura
- Como eu adiciono e calculo os itens de custas dentro de um protocolo?
- Como eu lanço as custas do Registro de Imóveis (RI) em um protocolo?
- montar tabela de custas
- lançar custas de RI
- calcular custas de protocolo

### Procedimento / Explicação
#### Descrição:

O card de 'Custas' é utilizado para detalhar e calcular todos os valores e emolumentos relativos a um ato notarial.

#### Passo a passo:

1.  Acesse o card **Custas** em um protocolo já salvo.

2.  **Item de custas**: Insira o código do item da tabela de custas ou utilize a busca. A **Descrição** será preenchida automaticamente.

3.  **Qtd. Cálculo**: Informe a quantidade de vezes que o item será cobrado (padrão 1).

4.  **Cálculo**: Selecione o divisor a ser aplicado ao valor do item, se necessário.

5.  **Valor venal**: Informe o valor estimado do bem pelo poder público.

6.  **Valor do instrumento**: Informe o valor do bem negociado no ato.

7.  **Base de cálculo**: Informe o valor que será usado como base para o cálculo dos emolumentos.

8.  Preencha os campos **UF** e **Cidade**.

9.  **ITBI %**: Informe a alíquota do imposto. O campo **Total ITBI** será calculado automaticamente.

10. **Registro imóveis**: Informe o número de registro do imóvel.

11. **Botão de Custas de RI**: Clique para abrir um modal e cadastrar as custas específicas do Registro de Imóveis.

12. Utilize os botões de **adição (+)** e **exclusão (X)** para gerenciar múltiplos itens de custas.

13. O campo **Vigência** informa qual tabela de custas está sendo utilizada para os cálculos.

---

---

## M-52.0 - Consultar Protocolos
**Objetivo:** Realizar buscas e consultas de protocolos utilizando diversos filtros como número do protocolo, data, escrevente, natureza ou nome da parte para localizar registros específicos.  
**Tags:** `Protocolos`, `Consultas`, `Filtros`, `Busca`, `Notas`, `Recibo`, `Escrevente`, `Espécie`, `Natureza`, `Status`, `Situação`

### Intenções de Busca & Dúvidas Frequentes
- pesquisar protocolos
- buscar ato notarial
- Preciso encontrar um protocolo antigo pelo número do livro e folha, como eu busco?
- encontrar escritura
- Onde eu encontro a tela de consulta de todos os protocolos do sistema?
- Como eu faço para pesquisar um protocolo pelo nome de uma das partes?
- lista de protocolos

### Procedimento / Explicação
#### Passo a passo para acessar a tela de Protocolos:

1.  Clique no menu **Notas > Consultas > Protocolos**.

#### Descrição:

Na tela de **Protocolos**, o sistema não carrega os registros automaticamente ao abrir a tela. É necessário realizar uma pesquisa por filtro para obter os resultados.

#### Campos de filtro disponíveis:

Os campos disponíveis para filtro são:

1.  **Protocolo**: Permite efetuar uma busca pelo número do protocolo.

2.  **Data de recepção**: Quando selecionado, permite efetuar uma busca pela data de recepção do protocolo.

3.  **Mês de recepção**: Quando selecionado, permite efetuar uma busca pelo mês de recepção do protocolo.

4.  **Escrevente**: Quando selecionado, permite efetuar uma busca por pedidos vinculados ao escrevente.

5.  **Espécie**: Quando selecionado, permite efetuar uma busca pela espécie de protocolo.

6.  **Natureza**: Quando selecionado, permite efetua uma busca pela natureza.

7.  **Status**: Permite efetuar uma busca por tipo de status do protocolo.

8.  **Número Recibo**: Permite efetuar uma busca pelo número de recibo gerado no protocolo.

9.  **Data do Recibo**: Quando selecionado, permite efetuar uma busca pela data do recibo/lavratura do protocolo.

10. **Nome**: Permite efetuar uma busca pelo nome das pessoas que foram informadas nas partes do protocolo.

11. **Tipo de Documento**: Quando selecionado, habilita um campo para preenchimento de acordo com o tipo de documento selecionado.

12. **Tipo de Participação**: Quando selecionado, permite efetuar uma busca pelo tipo de participação de uma pessoa no protocolo.

13. **Situação**: Quando selecionado, permite efetuar uma busca pelo tipo de situação do protocolo.

14. **Período**: Permite efetuar uma busca de pedido mais rápida por período.

#### Ações disponíveis na tela de Protocolos:

1.  **Limpar**: Limpa a consulta realizada, retornando a tela para o estado inicial.

2.  **Filtrar**: Quando acionado, realiza o filtro com base nos campos de busca preenchidos.

3.  **Voltar**: Quando acionado, redireciona o usuário para a tela inicial do sistema.

4.  **Adicionar**: Quando acionado, redireciona o usuário para a tela de cadastro de um novo protocolo.

5.  **Visualizar**: Quando acionado, redireciona o usuário para a tela de cadastro de um novo protocolo.

---

---

## M-56.0 - Consultar Índice de Escrituras e Procurações
**Objetivo:** Realizar buscas detalhadas no índice de escrituras e procurações utilizando diversos filtros, como protocolo, nome da parte, livro, folha ou matrícula do imóvel.  
**Tags:** `Índice`, `Escrituras`, `Procurações`, `Consultas`, `Notas`, `Filtros`, `Busca`, `Protocolo`, `Recibo`, `Espécie`, `Natureza`, `Comunicação`, `Livro`, `Folha`, `Matrícula`, `Objeto`

### Intenções de Busca & Dúvidas Frequentes
- Como eu pesquiso no índice por todas as escrituras de uma determinada pessoa?
- lista de escrituras por pessoa
- Onde eu encontro o índice de atos para buscar uma procuração antiga?
- encontrar procurações antigas
- Preciso achar uma escritura pela matrícula do imóvel, qual tela eu uso?
- pesquisar escrituras no índice
- índice de atos notariais

### Procedimento / Explicação
#### Descrição:

Na tela **Índice de escrituras e procurações**, o sistema não carrega os registros automaticamente ao abrir a tela. É necessário realizar uma pesquisa por filtro para obter os resultados.

#### Passo a passo para acessar a tela de Índice de escrituras e procurações:

1.  Clique no menu **Notas > Consultas > Índice de escrituras e procurações**.

#### Campos de filtro disponíveis:

Os campos disponíveis para filtro são:

1.  **Pesquisar por protocolo**: Permite efetuar uma busca pelo número do protocolo.

2.  **Data de recepção**: Quando selecionado, permite efetuar uma busca pela data de recepção do protocolo.

3.  **Número Recibo**: Permite efetuar uma busca pelo número de recibo gerado no protocolo.

4.  **Data de recepção**: Quando selecionado, permite efetuar uma busca pela data do recibo/lavratura do protocolo.

5.  **Espécie**: Quando selecionado, permite efetuar uma busca pela espécie de protocolo.

6.  **Natureza**: Quando selecionado, permite efetuar uma busca pela natureza.

7.  **Comunicação**: Permite efetuar uma busca pelo tipo de comunicação que foi realizado.

8.  **Nome**: Permite efetuar uma busca pelo nome das pessoas que foram informadas nas partes.

9.  **Tipo de Documento**: Quando selecionado, habilita um campo para preenchimento de acordo com o tipo de documento selecionado.

10. **Livro**: Permite efetuar uma busca pelo número do livro definido para o protocolo.

11. **Folha**: Permite efetuar uma busca pelo número da folha consumida pelo protocolo.

12. **Matrícula**: Permite efetuar uma busca pelo número da matrícula do imóvel que está na escritura.

13. **Objeto**: Permite efetuar uma busca pelo tipo de imóvel que está em negociação nessa escritura.

#### Ações disponíveis na tela de Índice de escrituras e procurações:

1.  **Limpar**: Limpa a consulta realizada, retornando a tela para o estado inicial.

2.  **Filtrar**: Quando acionado, realiza o filtro com base nos campos de busca preenchidos.

3.  **Voltar**: Quando acionado, redireciona o usuário para a tela inicial do sistema.

---

---

## M-59.0 - Gerenciar Cadastro de Espécies
**Objetivo:** Acessar e gerenciar o cadastro de espécies de atos notariais (ex: 'Escritura', 'Procuração'), permitindo a visualização, edição e exclusão dos registros existentes.  
**Tags:** `Configurações`, `Geral`, `Cadastros auxiliares`, `Espécie`, `Cadastro`

### Intenções de Busca & Dúvidas Frequentes
- Como eu edito o nome de uma espécie de ato?
- gerenciar espécies de atos
- editar espécie
- cadastro de espécies
- excluir espécie
- Onde eu gerencio o cadastro de espécies, como 'Escritura Pública'?
- É possível excluir uma espécie que foi cadastrada errada?

### Procedimento / Explicação
#### Descrição:

A tela de Espécie exibe uma tabela com todas as espécies cadastradas no sistema, organizadas em ordem alfabética. É possível realizar buscas específicas e gerenciar os registros existentes.

#### Passo a passo:

1.  Para acessar a tela, clique no menu **Configurações > Geral > Cadastros auxiliares > Espécie**.

2.  Ao carregar a página Espécie, será apresentada uma tabela de dados com todas as espécies cadastradas.

3.  Caso seja necessária uma busca específica, utilize os campos de filtro disponíveis em tela.

4.  Na tabela de dados, você encontrará as seguintes funcionalidades para gerenciar as espécies:

    *   **Visualização**: Permite visualizar os detalhes das espécies criadas.

    *   **Edição**: Permite editar as informações das espécies criadas.

    *   **Exclusão**: Permite excluir as espécies criadas.

---

---

## M-60.0 - Gerenciar Cadastro de Naturezas
**Objetivo:** Acessar e gerenciar o cadastro de naturezas de atos (ex: 'Compra e Venda'), permitindo a busca, consulta, alteração, exclusão e adição de novos registros.  
**Tags:** `Configurações`, `Geral`, `Cadastros auxiliares`, `Natureza`, `Cadastro`, `Filtros`

### Intenções de Busca & Dúvidas Frequentes
- editar natureza
- Onde eu gerencio o cadastro de naturezas, como 'Compra e Venda' ou 'Doação'?
- Como eu altero as configurações de uma natureza existente?
- excluir natureza
- Preciso inativar uma natureza que não será mais utilizada, como faço?
- cadastro de naturezas
- gerenciar naturezas de atos

### Procedimento / Explicação
#### Descrição:

A tela de Natureza apresenta uma tabela com todas as naturezas cadastradas no sistema, em ordem alfabética. É possível realizar buscas específicas utilizando filtros e executar ações de gerenciamento sobre os registros.

#### Passo a passo:

1.  Para acessar a tela, clique no menu **Configurações > Geral > Cadastros auxiliares > Natureza**.

2.  Ao carregar a página Natureza, será apresentada uma tabela de dados com todas as naturezas cadastradas.

3.  Para realizar uma busca específica, utilize os campos de filtro disponíveis:

    *   **Pesquisar por descrição**: Para pesquisar por uma descrição específica.

    *   **Inativos**: Clique caso deseje filtrar os cadastros inativos do sistema.

4.  Após preencher as informações necessárias para realizar o filtro, aperte a tecla **Enter** ou clique no botão **Filtrar**.

5.  Para limpar as informações preenchidas nos filtros, clique no botão **Limpar**.

6.  Na tela de Natureza, também é possível realizar as seguintes ações:

    *   **Consultar**: Clique para visualizar os detalhes da natureza.

    *   **Alterar**: Clique para alterar as informações da natureza.

    *   **Excluir**: Clique para excluir a natureza.

    *   **Adicionar**: Clique para adicionar uma nova natureza.

7.  Para voltar para a tela anterior, clique no botão **Voltar**.

---

---

## M-61.0 - Adicionar Nova Natureza
**Objetivo:** Cadastrar uma nova natureza de ato no sistema, configurando sua descrição, a espécie à qual pertence e seus parâmetros de comunicação com centrais (CEP, CESDI, etc.).  
**Tags:** `Configurações`, `Geral`, `Cadastros auxiliares`, `Natureza`, `Cadastro`, `Adicionar`

### Intenções de Busca & Dúvidas Frequentes
- configurar comunicações da natureza
- cadastrar natureza de ato
- Como eu cadastro uma nova natureza de ato, como 'Pacto Antenupcial'?
- Como eu configuro o tipo de comunicação com a CESDI para uma nova natureza?
- Ao criar uma natureza, onde eu defino a qual espécie ela pertence?
- criar nova natureza

### Procedimento / Explicação
#### Descrição:

Este procedimento detalha como adicionar uma nova natureza ao sistema, permitindo a configuração de diversos parâmetros que definirão o comportamento e as características dessa natureza.

#### Passo a passo:

1.  Para acessar a tela, clique no menu **Configurações > Geral > Cadastros auxiliares > Natureza**.

2.  Ao carregar a página Natureza, clique no botão **Adicionar** (disponibilizado abaixo da lista de naturezas cadastradas).

3.  Para cadastrar uma nova natureza, siga os passos abaixo:

    *   Preencha o campo **Descrição** com o título da Natureza.

    *   Selecione o **Tipo de CEP**.

        *   *Observação:* No caso de selecionar a opção de **Escritura**, será apresentado o campo **Tipo escritura CEP** para ser selecionado a opção desejada.

    *   Selecione o **Tipo de CESDI**.

    *   Selecione a opção para **RCTO**.

    *   Selecione a opção para **ITCMD**.

    *   Selecione a **Espécie** que queira que a Natureza esteja vinculada.

    *   Selecione caso não queira que, ao selecionar a natureza em questão, seja exigido o **Livro e Folha**.

    *   Selecione caso queira que seja possível inserir mais de 1 **Livro e Folha** quando a natureza for selecionada.

    *   Selecione a opção para o caso da natureza se tratar de **Imóveis**.

    *   Selecione um **Perfil de partes** para que seja incluída na natureza uma parte e um documento por padrão.

---

---

## M-62.0 - Gerenciar Grupo de Itens
**Objetivo:** Acessar e gerenciar os 'Grupos de Itens' da tabela de custas, permitindo a visualização, edição, inativação e busca por grupos específicos.  
**Tags:** `Configurações`, `Geral`, `Tabela de Custas`, `Grupo de Itens`, `Cadastro`, `Filtros`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu gerencio os grupos de itens da tabela de custas?
- Preciso inativar um grupo de itens que não usamos mais, onde faço?
- Como eu edito o nome de um grupo de itens?
- inativar grupo de custas
- editar grupo de itens
- gerenciar grupos da tabela de custas

### Procedimento / Explicação
#### Descrição:

A tela de Grupo de Itens exibe automaticamente os últimos grupos de itens cadastrados. É possível filtrar, visualizar, editar e inativar os grupos de itens existentes.

#### Passo a passo:

1.  Para acessar a tela, clique no menu **Configurações > Geral > Tabela de custas > Grupo de Itens**.

2.  Ao carregar a página de Grupo de Itens, os últimos grupos de itens cadastrados serão automaticamente filtrados.

3.  Caso seja necessário filtrar algum grupo de itens específico, realize a busca preenchendo os campos de filtro disponíveis em tela e clique em **Filtrar**.

4.  A partir da listagem de grupo de item, é possível executar as seguintes ações:

    *   **Visualizar**: Para visualizar os dados cadastrados do grupo de item.

    *   **Editar**: Para editar as informações do grupo de item cadastrado.

    *   **Inativar**: Para inativar o grupo de item cadastrado.

*   **IMPORTANTE**: Caso o grupo de item esteja inativado, não será possível utilizá-lo.

---

---

## M-63.0 - Adicionar Novo Grupo de Itens
**Objetivo:** Cadastrar um novo 'Grupo de Itens' para a tabela de custas, definindo sua descrição e a especialidade (ex: Notas) à qual ele pertence.  
**Tags:** `Configurações`, `Geral`, `Tabela de Custas`, `Grupo de Itens`, `Cadastro`, `Adicionar`

### Intenções de Busca & Dúvidas Frequentes
- novo grupo para tabela de custas
- criar grupo de itens
- Como eu crio um novo grupo de itens para organizar a tabela de custas?
- adicionar grupo de custas
- Onde eu cadastro um novo grupo e o vinculo à especialidade de 'Notas'?

### Procedimento / Explicação
#### Descrição:

Este procedimento descreve como adicionar um novo grupo de itens ao sistema, associando-o a uma descrição e a uma especialidade específica.

#### Passo a passo:

1.  Para acessar a tela, clique no menu **Configurações > Geral > Tabela de custas > Grupo de Itens**.

2.  Na página de Grupo de Itens, selecione o botão **Adicionar** para cadastrar um novo Grupo de Item.

3.  Na tela de Cadastro de grupo de item, preencha os campos:

    *   **Descrição**: Informe o nome do grupo de item.

    *   **Especialidade**: Selecione a especialidade a que o grupo de item se refere.

4.  Por fim, clique no botão **Concluir** para salvar o cadastro.

---

---

## M-66.0 - Adicionar Novo Outro Serviço
**Objetivo:** Cadastrar um novo serviço avulso na seção 'Outros Serviços' da tabela de custas, definindo sua descrição e o valor padrão a ser cobrado.  
**Tags:** `Configurações`, `Negócios`, `Cadastros`, `Outros Serviços`, `Adicionar`, `Serviço`, `Valor`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu cadastro um serviço como 'Diligência' e defino o seu preço?
- novo outro serviço
- cadastrar serviço avulso
- adicionar serviço na tabela de custas
- Como eu adiciono um novo item em 'Outros Serviços' na tabela de custas?

### Procedimento / Explicação
#### Descrição:

Este procedimento detalha como adicionar um novo registro na tela de "Outros Serviços", permitindo a inclusão de novos serviços com suas respectivas descrições e valores.

#### Passo a passo:

1.  Para acessar a tela, clique no menu **Configurações > Negócios > Cadastros > Outros Serviços**.

2.  Ao carregar a página Outros Serviços, clique no botão **Adicionar** (disponibilizado abaixo da lista de serviços cadastrados).

3.  Na tela de cadastro, preencha os campos:

    *   **Descrição**: Informe o nome do serviço que será cadastrado.

    *   **Valor**: Informe o valor (R\$) que será cobrado pelo serviço.

4.  Ao preencher todos os campos, clique no botão **Concluir** para cadastrar o serviço.

5.  Para retornar à tela com a lista de serviços cadastrados, clique no botão **Voltar**.

---

---

## M-67.0 - Gerenciar Área de Atuação
**Objetivo:** Acessar e gerenciar as 'Áreas de Atuação' cadastradas no sistema, permitindo a busca por registros específicos através de filtros como descrição ou status.  
**Tags:** `Configurações`, `Negócio`, `Cadastros`, `Área de Atuação`, `Filtros`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu gerencio as Áreas de Atuação cadastradas no sistema?
- gerenciar áreas de atuação
- Como eu pesquiso por uma área de atuação específica?
- consultar áreas cadastradas
- É possível filtrar apenas as áreas de atuação inativas?
- buscar área de atuação

### Procedimento / Explicação
#### Descrição:

A tela de Área de Atuação exibe uma tabela com todas as áreas de atuação cadastradas no sistema, organizadas em ordem alfabética. É possível realizar buscas específicas utilizando os campos de filtro disponíveis.

#### Passo a passo:

1.  Para acessar a tela, clique no menu **Configurações > Negócio > Cadastros > Área de Atuação**.

2.  Ao carregar a página Área de Atuação, será apresentada uma tabela de dados em ordem alfabética com todas as áreas de atuação cadastradas no sistema.

3.  Caso seja necessária uma busca específica, você poderá realizá-la preenchendo os campos de filtro disponíveis em tela:

    *   **Pesquisar por Descrição**: Para pesquisa por uma descrição específica.

    *   **Flag Inativos**: Para pesquisa por somente áreas de atuação inativas.

4.  Após preencher as informações necessárias para realizar o filtro, aperte a tecla **Enter** ou clique no botão **Filtrar**.

5.  Para limpar as informações preenchidas nos filtros, clique no botão **Limpar**.

---

---

## M-68.0 - Cadastrar Nova Área de Atuação
**Objetivo:** Realizar o cadastro de uma nova 'Área de Atuação' no sistema, preenchendo as informações de código e descrição para sua correta identificação.  
**Tags:** `Configurações`, `Negócio`, `Cadastros`, `Área de Atuação`, `Cadastro`

### Intenções de Busca & Dúvidas Frequentes
- criar área de atuação
- adicionar área de atuação
- Onde eu informo o código e a descrição para uma nova área de atuação?
- cadastrar nova área
- Como eu faço para cadastrar uma nova Área de Atuação?

### Procedimento / Explicação
#### Passo a passo:

1.  Para acessar a tela de Área de Atuação, clique no menu **Configurações > Negócio > Cadastros > Área de Atuação**.

2.  Na tela de Área de Atuação, clique no botão **Adicionar**, que estará disponível após a lista de áreas cadastradas.

3.  Na tela de Cadastro de uma área de atuação, preencha as seguintes informações:

    *   **Código**: Número de 3 dígitos para a Área Cadastrada.

    *   **Descrição**: Nome da área de atuação que será cadastrada.

4.  Após o preenchimento das informações, clique em **"Concluir"** para cadastrar a nova área de atuação.

*   **IMPORTANTE:** Para cadastro de uma nova área de atuação, é obrigatório que todos os campos dessa etapa sejam preenchidos corretamente.

---

---

## M-69.0 - Acessar e Gerenciar Modelos de Etiqueta
**Objetivo:** Acessar a tela de Modelos de Etiqueta para visualizar a listagem de modelos cadastrados, utilizar filtros de pesquisa e realizar ações como visualização, edição e inativação.  
**Tags:** `Configurações`, `Negócios`, `Modelos`, `Etiqueta`, `Listagem`, `Filtros`, `Ações`, `Adicionar`

### Intenções de Busca & Dúvidas Frequentes
- gerenciar layouts de etiqueta
- Como eu edito um modelo de etiqueta de reconhecimento de firma que já existe?
- consultar modelos de impressão
- Preciso inativar um layout de etiqueta que não usamos mais, como faço?
- Onde eu acesso a listagem de todos os modelos de etiqueta cadastrados?
- editar modelo de etiqueta

### Procedimento / Explicação
#### Passo a passo:

1.  Para acessar a tela de Modelos de Etiqueta, clique no menu **Configurações > Negócios > Modelos > Etiqueta**.

2.  Após acessar a tela, você terá acesso à listagem de modelos de etiqueta.

3.  Nesta tela, os filtros disponíveis para pesquisa são indicados em **A** e **B**, e os modelos cadastrados são exibidos em **C**.

4.  Em **D**, estão disponíveis as ações de **visualização**, **edição** e **inativação** para os modelos.

5.  Para adicionar novos modelos, clique no botão **Adicionar**.

---

---

## M-70.0 - Criando um Novo Modelo de Etiqueta (Configuração Básica)
**Objetivo:** Realizar o cadastro básico de um novo modelo de etiqueta, definindo seu tipo, título, descrição e a qual serviço ele será associado.  
**Tags:** `Configurações`, `Modelos`, `Etiqueta`, `Cadastro`, `Tipo`, `Título`, `Serviço`

### Intenções de Busca & Dúvidas Frequentes
- Qual o primeiro passo para cadastrar um modelo de impressão?
- novo modelo de impressão
- Como eu crio um novo modelo de etiqueta no sistema?
- cadastrar etiqueta
- criar modelo de etiqueta
- Onde eu defino o nome e o serviço de uma nova etiqueta?

### Procedimento / Explicação
#### Descrição:

Esta rotina cobre a criação inicial de um modelo de etiqueta, onde são definidas suas informações de identificação e a sua vinculação a um tipo de serviço específico no sistema.

#### Passo a passo:

1.  Acesse o menu **Configurações > Negócios > Modelos > Etiqueta**.

2.  Na tela de Modelos de Etiqueta, clique no botão **Adicionar**.

3.  Na tela de criação de modelos, preencha os seguintes campos de configuração básica:

    * **Tipo modelo**: Determine qual é o tipo do modelo que será cadastrado (ex: Reconhecimento, Termo).

    * **Título**: Informe um título para este modelo, que facilitará sua identificação nas listas de seleção.

    * **Descrição**: Informe uma descrição mais detalhada para o modelo, se necessário.

    * **Serviço**: Associe a etiqueta ao serviço específico que será realizado. Isso garante que o modelo correto seja carregado ao selecionar o serviço no balcão.

    * **Modelo padrão**: Marque esta opção para definir este modelo como o padrão para o tipo e serviço selecionados.

4.  Após preencher as informações básicas, prossiga para a configuração dos parâmetros técnicos de impressão.

---

---

## M-70.1 - Configurando os Parâmetros Técnicos de um Modelo de Etiqueta
**Objetivo:** Detalhar a configuração dos parâmetros técnicos de um modelo de etiqueta, incluindo o layout de impressão, a linguagem da impressora e o uso de variáveis para inserir dados dinâmicos.  
**Tags:** `Configurações`, `Modelos`, `Etiqueta`, `Impressão`, `Linguagem`, `Fonte`, `Contraste`, `Rotação`, `Variáveis`

### Intenções de Busca & Dúvidas Frequentes
- adicionar variáveis na etiqueta
- Onde eu edito o texto que sai na impressão da etiqueta?
- Como faço para a etiqueta imprimir de lado (rotacionar)?
- editar layout de etiqueta
- configurar impressora de etiqueta
- Como eu ajusto o tamanho da fonte e o contraste da minha etiqueta?
- Quais variáveis eu posso usar no modelo de etiqueta?

### Procedimento / Explicação
#### Descrição:

Após criar um modelo de etiqueta, esta rotina detalha como configurar os aspectos técnicos da impressão, como o layout, a linguagem da impressora e o conteúdo dinâmico que será impresso.

#### Passo a passo:

1.  Durante a criação ou edição de um **Modelo de Etiqueta**, acesse as seções de configuração técnica.

2.  **Configuração**: Selecione a configuração de impressão que define o tamanho, margens e salto da etiqueta física.

3.  **Linguagem**: Determine o tipo de linguagem de impressão que o modelo utilizará. As opções são:

    * **Eltron Programming Language (EPL)** - Impressão térmica

    * **Zebra Programming Language (ZPL)** - Impressão térmica

    * **Epson Standard Code for Printers (ESC/P)** - Impressão matricial

4.  Para linguagens térmicas (EPL/ZPL), configure os seguintes parâmetros:

    * **Fonte**: Permite alterar o tamanho da fonte que será impressa.

    * **Contraste**: Permite determinar a qualidade (nitidez) da impressão.

    * **Rotacionar**: Permite alterar o sentido da impressão da etiqueta (retrato ou paisagem).

5.  **Variáveis**: Na seção de variáveis, você encontrará todos os campos de dados dinâmicos disponíveis para o tipo de modelo selecionado (ex: nome da parte, data do ato, etc.).

6.  **Conteúdo**: Na área de edição de conteúdo, monte o layout da sua etiqueta. Você pode digitar texto fixo e inserir as **Variáveis** da lista para que as informações sejam preenchidas automaticamente no momento da impressão.

7.  Após finalizar toda a configuração, clique em **Concluir** para gravar o modelo.

---

# SEÇÃO PRINCIPAL 4: Demonstração Completa do Sistema e módulos- Orion TN
***DESCRIÇÃO DA SEÇÃO:** Esta área contém as rotinas mais detalhadas e atualizadas do Orion TN e seus módulos, Orion Caixa e Orion Estoque.*

---

