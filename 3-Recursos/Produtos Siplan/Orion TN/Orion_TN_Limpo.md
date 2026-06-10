# SEÇÃO PRINCIPAL 1: ROTINAS E FUNCIONALIDADES DO SISTEMA - Orion TN
***DESCRIÇÃO DA SEÇÃO:** Esta área contém procedimentos detalhados, rotinas operacionais e soluções para casos comuns de suporte, compilados a partir da experiência do Service Desk do Orion TN. As informações são apresentadas de forma prática e passo a passo.*
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
## R-9.0 - Cancelar Selos de um Protocolo ou Inutilizar Protocolo
**Objetivo:** Realizar o cancelamento de selos de um ato específico dentro de um protocolo ou inutilizar completamente um protocolo que não terá continuidade.  
**Tags:** `Protocolos`, `Selos`, `Cancelamento`, `Inutilização`, `Estorno`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu estorno os selos de um protocolo cancelado?
- Preciso cancelar apenas os selos de um ato dentro de um protocolo, sem cancelar o protocolo todo. Como faço?
- estornar selo de escritura
- Como eu faço para cancelar um protocolo inteiro que não será mais usado?
- excluir ato
- anular protocolo
- Desisti de fazer uma escritura, como eu inutilizo o protocolo no sistema?
- dar baixa em protocolo
- inutilizar uma escritura
- cancelar ato notarial

### Procedimento / Explicação
#### Para cancelar selos de um protocolo:

1.  Acesse o protocolo em **Notas > Protocolo**.

2.  Na aba de custas, exclua os atos clicando no **"X"**.

3.  O sistema gerará um **selo digital de cancelamento** e comunicará o TJSP.

#### Para inutilizar um protocolo inteiro:

1.  Acesse o protocolo desejado.

2.  No menu superior, clique em **"Inutilizar protocolo"**.

3.  O sistema gerará um selo de cancelamento (sigla XA) e o status do protocolo será alterado para **"Inutilizado"**, não podendo mais ser usado.

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
## R-11.0 - Comunicação de Fichas com o e-Notariado
**Objetivo:** Explicar como configurar o envio automático ou realizar o envio manual das fichas de assinatura (cartões) para a plataforma e-Notariado (CCN).  
**Tags:** `Comunicação`, `e-Notariado`, `Fichas`, `Automação`, `Envio`

### Intenções de Busca & Dúvidas Frequentes
- comunicação ccn
- Preciso colocar o token do e-Notariado no sistema, onde fica?
- enviar ficha para e-notariado
- integração e-notariado
- Onde eu configuro o envio automático dos cartões de assinatura para o CCN?
- configurar envio automático ccn
- Como eu envio as fichas de assinatura para o e-Notariado manualmente?
- mandar cartão de assinatura para o ccn

### Procedimento / Explicação
Existem duas formas de envio: **automática** e **manual**.

#### Envio manual:

1.  Acesse **Administração > Comunicações > Outras comunicações**.

2.  Clique em **"GERAR"**, escolha o tipo **E-notariado** e informe o período.

3.  Selecione as fichas listadas e clique em **"Processar"** e depois em **"Finalizar"**.

#### Envio automático (configuração):

1.  Acesse **Configurações > Parametrizações > Comunicações**.

2.  Escolha o tipo **Automático**, defina a frequência (diário, semanal) e o horário.

3.  Informe o **token do cartório** (gerado na plataforma e-notariado).

4.  Verifique se o **"Status"** do serviço está "Ativo".

5.  Clique em **"Concluir"**.

---
## R-12.0 - Comunicação dos Protocolos para o COAF
**Objetivo:** Orientar sobre o procedimento de comunicação de atos notariais suspeitos ou de declaração obrigatória ao COAF através do sistema.  
**Tags:** `Comunicação`, `COAF`, `Protocolos`, `SISCOAF`

### Intenções de Busca & Dúvidas Frequentes
- comunicação siscoaf
- relatório coaf
- enviar para o coaf
- A comunicação com o COAF é feita por dentro do Orion?
- Como eu faço a comunicação de um protocolo para o COAF?
- Onde eu vejo o status de envio de um ato para o SISCOAF?
- declarar operação para o coaf

### Procedimento / Explicação
#### Como realizar a comunicação:

1.  Acesse **Orion TN > Administração > Comunicações > COAF**.

2.  Informe o período do ato ou o número do protocolo e clique em **Filtrar**.

3.  O sistema listará os protocolos. Clique em **"Comunicar"** para enviar ao SISCOAF.

4.  Uma barra de progresso indicará o status do envio (verde para sucesso, vermelha para erro). Em caso de erro, clique no ícone de interrogação para ver o motivo.

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
## R-17.0 - Comunicar Selos Digitais Pendentes
**Objetivo:** Realizar o envio manual de selos digitais que, por falha de comunicação ou configuração, não foram transmitidos automaticamente ao TJSP.  
**Tags:** `Selos Digitais`, `Comunicação`, `TJSP`, `Administração`, `Pendências`

### Intenções de Busca & Dúvidas Frequentes
- comunicação manual de selo
- forçar envio de selo
- Como eu faço para enviar os selos que estão com comunicação pendente?
- Onde eu consulto os selos que não foram comunicados ao TJ?
- enviar selo pendente
- A internet caiu e alguns selos não foram enviados, como eu os comunico agora?
- selo com erro de comunicação
- consultar selos não comunicados

### Procedimento / Explicação
#### Passo a passo:

1.  Acesse a rotina em: **Orion TN > Administração > Comunicações > Selo digital**.

2.  Informe a **"Data do ato"** e no campo **"Status"**, selecione **"Não comunicado"** ou **"Comunicação pendente"**.

3.  Clique em **Filtrar**.

4.  O sistema listará os selos pendentes. Após confirmar, clique em **Comunicar** para enviá-los ao TJSP.

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
## R-32.0 - Imprimir Relatório de Atos Comunicados ao COAF
**Objetivo:** Gerar e imprimir um relatório de atos notariais que foram comunicados ou estão pendentes de comunicação ao COAF.  
**Tags:** `coaf`, `relatório`, `comunicação`, `impressão`

### Intenções de Busca & Dúvidas Frequentes
- Como imprimo um relatório dos atos que foram enviados ao COAF?
- listar atos enviados ao coaf
- Como gerar um comprovante dos atos comunicados ao COAF?
- relatório coaf
- consulta de envio coaf
- Onde tiro uma lista dos protocolos pendentes de comunicação com o COAF?
- imprimir comunicação coaf

### Procedimento / Explicação
#### Descrição:

Este procedimento permite gerar um relatório dos atos que foram comunicados ou que estão indicados para comunicação (pendentes de envio) ao COAF.

#### Passo a passo:

1.  Acesse o caminho: **OrionTN > Administração > Comunicações > COAF**.

2.  Defina o filtro **“Situação do protocolo”** como:

    * **Comunicados**: Para listar apenas os atos que já foram comunicados ao COAF.

    * **Não comunicado**: Para listar apenas os atos indicados, que estão pendentes de envio.

3.  Clique no botão **Imprimir** e selecione o modelo disponível.

4.  Confirme para que o sistema gere o relatório.

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
## M-12.0 - Gerenciamento de Serviços Lançados (Visualizar, Reutilizar/Inutilizar Selo)
**Objetivo:** Gerenciar os serviços já lançados em um pedido de balcão, permitindo visualizar a etiqueta impressa, reutilizar um selo não danificado ou inutilizar um selo estragado.  
**Tags:** `Firmas`, `Balcão`, `Gerenciamento`, `Selo`, `Reutilizar`, `Inutilizar`, `Visualizar`, `Etiqueta`, `Termo`

### Intenções de Busca & Dúvidas Frequentes
- visualizar etiqueta impressa
- Imprimi uma etiqueta de reconhecimento por engano, mas não colei o selo. Como eu faço para reutilizar esse selo?
- gerenciar selos do balcão
- A etiqueta atolou na impressora e estragou o selo. Como eu faço para inutilizá-lo no sistema?
- cancelar reconhecimento de firma
- inutilizar selo de etiqueta
- estornar selo de reconhecimento
- Onde eu posso visualizar a imagem de uma etiqueta que já foi impressa?

### Procedimento / Explicação
#### Descrição:

Após a impressão de uma etiqueta ou o lançamento de um serviço, é possível realizar diversas ações de gerenciamento, como visualizar os documentos gerados, estornar selos para o estoque ou inutilizá-los permanentemente.

#### Passo a passo:

1.  Na tela do **Balcão de Firmas**, na seção **Últimos serviços realizados**, ou clicando no ícone para expandir a janela de detalhes, localize o serviço que deseja gerenciar.

2.  Para cada serviço lançado, as seguintes ações estão disponíveis:

    * **Visualizar etiqueta**: Clique para abrir uma pré-visualização da etiqueta que foi impressa.

    * **Visualizar termo**: Se um Termo de Comparecimento foi gerado para o serviço, clique para visualizá-lo.

    * **Reutilizar selo**: Clique nesta opção para estornar o selo (físico ou digital) de volta para o estoque. Esta ação deve ser usada caso a etiqueta tenha sido impressa por engano e o selo não tenha sido danificado.

    * **Inutilizar selo**: Clique nesta opção para inutilizar o selo permanentemente (ex: em caso de danos). O selo será baixado do estoque e não poderá ser mais utilizado.

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
## M-15.0 - Central Selo Digital TJ-SP
**Objetivo:** Gerenciar a comunicação de selos digitais e híbridos com o TJSP, permitindo consultar, filtrar por status, comunicar pendências manualmente e visualizar detalhes de cada selo.  
**Tags:** `Selo Digital`, `TJSP`, `Administração`, `Comunicação`, `Filtro`, `Status`, `Produto`, `Série`, `Sequência`, `Serviço`, `Detalhes`, `QRCode`, `Andamentos`, `Notificações`

### Intenções de Busca & Dúvidas Frequentes
- Onde fica a central para gerenciar a comunicação de todos os selos digitais com o TJSP?
- ver qr code de selo
- Como eu vejo o motivo da falha de um selo que não foi comunicado?
- Como eu filtro e envio todos os selos que estão com 'Comunicação pendente'?
- comunicar selo digital tjsp
- consultar status de selo no tj
- enviar selos pendentes
- Preciso ver os detalhes de um selo específico que foi comunicado ao TJ, onde consulto?
- central de selos

### Procedimento / Explicação
#### Descrição:

A tela Central Selo Digital TJ-SP é o ambiente para gerenciar a comunicação de selos digitais e híbridos com o Tribunal de Justiça de São Paulo. Ela permite filtrar selos por status, período, produto, série, sequência, número do selo digital e serviço, além de processar a comunicação de selos pendentes e visualizar informações detalhadas.

#### Passo a passo:

1.  Para acessar a tela de **Central selo digital**, clique no menu **Administração > Selo Digital**.

2.  Ao acessar a tela, automaticamente é realizado um filtro apresentando todos os selos digitais e híbridos que estejam **pendentes de comunicação**. A consulta inicial é feita utilizando os filtros **status (A)** e **período data do ato (B)**, para que assim apresente os selos pendentes do dia atual (C).

3.  A tela apresenta as seguintes informações para filtro:

    1.  **Status**: Permite selecionar um dos status possíveis para os selos digitais:

        *   **Comunicado**: Selo enviado ao TJSP sem nenhuma crítica.

        *   **Comunicação pendente**: Selo não enviado ao TJSP, seja pela parametrização da rotina de geração dos selos ser Offline ou problemas de infraestrutura no momento da comunicação.

        *   **Retificado**: Selos enviados e que foram retificados posteriormente.

        *   **Falha**: Selos não comunicados e que não podem mais ser enviados, pois possuem falha estrutural.

        *   **Aguardando retificação**: Selos comunicados ao TJSP, mas que possuem críticas e aguardam as correções.

        *   **Não comunicado**: Todos os selos que estão pendentes de comunicação (não gerados ou gerados offline) e aguardando retificação.

    2.  **Data do ato**: Permite informar um período para busca referente à data em que o ato foi praticado.

    3.  **Produto**: Lista todos os produtos do estoque (selos híbridos) que possuem vínculo a um item da tabela de custas e que, por sua vez, possuam parametrização de sigla do TJSP.

    4.  **Série**: Permite informar a série de um produto do estoque (selo híbrido) para busca.

    5.  **Sequência**: Permite informar a sequência/número de um produto do estoque (selo híbrido) para busca, sendo necessário informar uma série para a busca.

    6.  **Selo Digital**: Permite informar o número de um selo digital, composto por 25 dígitos, para busca, permitindo verificar seu status e informações comunicadas ao TJSP.

    7.  **Período de geração**: Permite informar um período para busca referente à data em que o selo digital foi gerado.

    8.  **Período de comunicação**: Permite informar um período para busca referente à data em que o selo digital foi comunicado.

        *   *Disponível apenas quando o filtro "Status" for "Comunicado".*

    9.  **Serviço**: Permite selecionar um dos serviços (itens da tabela) que possuem sigla para comunicação ao TJSP.

4.  Ações de filtro:

    *   **Limpar**: Limpa os filtros preenchidos.

    *   **Filtrar**: Efetua o filtro com base nas informações preenchidas.

5.  O botão **Comunicar** faz o processamento dos selos digitais que estão com status **"Comunicação pendente"** e **"Aguardando retificação"** com base no filtro em tela.

    *   No momento da comunicação, caso sejam detectados outros tipos de selos digitais (ex: "Fotocópia" ou "Autenticação digital") para envio, será exibido um alerta.

        *   Se clicar em **"Sim"**, o sistema fará o processamento e envio deste selo.

        *   Se clicar em **"Não"**, somente os selos digitais localizados no filtro inicial serão enviados.

    *   *Obs.: Para os serviços que geram selo digital único, como exemplo a Fotocópia, o sistema identifica se para o dia já existe um selo e caso seja gerado novamente, será enviado como uma retificação.*

6.  Ao iniciar o processamento, é apresentada uma tela com o progresso da geração. Ao término, será informado que todos os selos foram gerados.

7.  Caso hajam inconsistências, será exibida uma mensagem e, ao clicar em **"Sim"**, serão exibidos os selos que apresentaram problemas.

8.  Para cada selo digital, temos as seguintes opções:

    1.  **Detalhes**: Apresenta uma tela com todos os dados utilizados e comunicados ao TJSP, incluindo informações do Ato e valores utilizados.

    2.  **QrCode**: Apresenta uma tela com o QrCode do Selo Digital, permitindo sua leitura, cópia ou cópia de sua URL.

    3.  **Andamentos**: Apresenta uma tela com os andamentos do selo digital, mostrando informações sobre quando foi gerado, comunicado, cancelado, retificado, entre outras.

9.  Ao término do processamento dos selos pendentes, é enviado um e-mail ao(s) responsável(eis), conforme parametrização de envio das notificações, apresentando as informações do processamento.

    *   Este e-mail é enviado caso o processamento dos selos digitais seja feito de forma manual ou automática.

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
## M-16.5 - Configurar Comunicações Externas (Selo Digital, E-notariado, COAF)
**Objetivo:** Configurar os parâmetros de comunicação do Orion TN com serviços externos, como o modo de envio do Selo Digital, os dados do e-Notariado, COAF e a integração com o Livro Caixa Web.  
**Tags:** `Configurações`, `Comunicações`, `Selo Digital`, `e-Notariado`, `COAF`, `Central de Indisponibilidade`, `SEFAZ`, `Livro Caixa Web`, `LCW`

### Intenções de Busca & Dúvidas Frequentes
- parametrizar envio de selo
- integração livro caixa web
- configurar e-notariado
- Onde eu configuro o token do e-Notariado para a comunicação de fichas?
- parâmetros do COAF
- Preciso alterar o modo de comunicação do selo digital para 'Off-line', onde fica essa opção?
- Como eu configuro a integração do Orion com o Livro Caixa Web, informando usuário e senha?
- Onde eu ajusto os parâmetros de comunicação com a Central de Indisponibilidade?
- configurações de comunicação

### Procedimento / Explicação
#### Descrição:

Esta seção centraliza as configurações de integração e comunicação do sistema com diversas plataformas e serviços externos.

#### Passo a passo:

1.  Acesse o menu **Configurações > Parametrizações**.

2.  Selecione a aba **5 - Comunicações**.

3.  Configure o **Selo digital**:

    * **Modo de comunicação**: Defina como **Online** (envio imediato ao TJSP) ou **Off-line** (envio posterior manual ou agendado).

    * **Notificação por e-mail**: Configure as opções de notificação.

4.  Configure o **e-Notariado**:

    * Defina o **Tipo de comunicação**, **Token do cartório**, **Subscription** e o **Diretório de instalação do Java**.

5.  Configure o **Coaf**:

    * Defina os parâmetros de **Envio comunicação**, **Solicitação de recibo** e **Notificar por e-mail**.

6.  Preencha os dados para outras comunicações, como **Central de indisponibilidade**, **SEFAZ Veículos - SP**, **SEFAZ - ITCMD** e **DOITU**.

7.  Configure a **Integração com o Livro Caixa Web** informando **Usuário**, **Senha**, **Horário** e **E-mail**.

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
## M-27.0 - Como Cadastrar e Gerenciar Impedimentos
**Objetivo:** Cadastrar e gerenciar impedimentos para pessoas, fazendo com que o sistema emita um alerta (aviso) sempre que houver uma tentativa de realizar um serviço para elas.  
**Tags:** `Administração`, `Impedimento`, `Cadastro`, `Bloqueio`, `Pessoa`, `Documento`, `Motivo`, `Alerta`, `Anexos`, `Busca`

### Intenções de Busca & Dúvidas Frequentes
- Onde eu consulto os impedimentos que já foram cadastrados no sistema?
- bloquear pessoa
- criar restrição para cliente
- O alerta de impedimento impede a realização do ato ou apenas avisa o usuário?
- cadastrar alerta para CPF
- consultar impedimentos
- alerta de impedimento
- Como eu faço para cadastrar um impedimento para uma pessoa, para que o sistema me avise sempre que ela aparecer?
- Como eu removo um impedimento de uma pessoa?

### Procedimento / Explicação
A rotina de Impedimentos permite registrar alertas para pessoas, de modo que o sistema avise o usuário sempre que o nome ou documento for utilizado em um serviço de notas ou firmas.

    #### Parte 1: Cadastrar um Novo Impedimento

    1.  Acesse o menu **Administração > Impedimento**.

    2.  Na tela de consulta, clique no botão **Adicionar**.

    3.  **Preencha os dados da pessoa:**

        * **Nº Cartão**: Se a pessoa tiver cartão de assinatura, informe o número para preencher automaticamente o nome e documento.

        * **Nome**: Informe o nome da pessoa que será impedida. O campo possui auto sugestão com base nos cartões cadastrados.

        * **Documento**: Selecione o tipo de documento (**RG** ou **CPF**) e informe o **Número**.

    4.  **Descreva o Impedimento:**

        * **Motivo**: Campo obrigatório. Descreva de forma curta e clara o motivo do impedimento (ex: "Ordem Judicial", "Documento Falso"). Este texto será exibido no alerta.

        * Utilize o campo de texto longo para detalhar o impedimento, se necessário.

    5.  **Anexe Documentos (Opcional):**

        * **Selecionar**: Anexe um arquivo existente do computador.

        * **Capturar**: Utilize a webcam para capturar uma imagem.

        * **Digitalizar**: Utilize um scanner para digitalizar um documento.

    6.  Clique em **Concluir** para salvar o impedimento.

    **IMPORTANTE:** Quando o nome ou documento impedido for utilizado nas rotinas de reconhecimento de firmas ou lavratura de notas, o sistema irá emitir um alerta. Este alerta **não bloqueia** a prática do ato, servindo apenas como um aviso ao usuário.

    #### Parte 2: Consultar e Gerenciar Impedimentos

    1.  Acesse o menu **Administração > Impedimento**.

    2.  A tela listará os últimos impedimentos cadastrados. Utilize os campos de filtro para buscar por **Nome**, **Documento** ou **Data de digitação**.

    3.  Para cada impedimento na lista, as seguintes ações estão disponíveis:

        * **Visualizar**: Para consultar as informações e os anexos do impedimento.

        * **Editar**: Para alterar as informações do cadastro.

        * **Excluir**: Remove o registro de impedimento do sistema.

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
## M-32.0 - Como Consultar e Gerenciar Lotes de Comunicação (SEFAZ / E-notariado)
**Objetivo:** Consultar e gerenciar lotes de comunicação já processados para a SEFAZ e E-notariado, permitindo filtrar por diversos critérios e executar ações como visualizar logs e estornar lotes.  
**Tags:** `Administração`, `Comunicações`, `SEFAZ`, `E-notariado`, `Lotes`, `Consulta`, `Filtros`, `Gerenciamento`, `Estorno`, `Log`

### Intenções de Busca & Dúvidas Frequentes
- encontrar lote processado
- estornar um lote de comunicação
- Preciso estornar um lote de comunicação que foi com informações erradas, como eu faço?
- Como eu consulto um lote de comunicação que já foi enviado para a SEFAZ?
- Onde eu vejo o histórico de lotes que já foram enviados para o e-Notariado?
- verificar status comunicação e-notariado
- histórico de envios para SEFAZ
- consultar lote SEFAZ
- Como eu visualizo os itens que foram enviados dentro de um lote específico?

### Procedimento / Explicação
Esta rotina descreve como utilizar a tela de Comunicações para consultar, filtrar e gerenciar lotes de dados que já foram processados e enviados para órgãos externos.

    #### Passo a passo:

    1.  Acesse a tela de Comunicações pelo menu **Administração > Comunicações**.

    2.  Ao abrir, a tela já realiza um filtro padrão, geralmente exibindo os lotes processados no dia atual.

    3.  Para localizar lotes específicos, utilize os seguintes campos de filtro:

        * **Tipo**: Selecione o tipo de comunicação, como **Sefaz** (veículos) ou **E-notariado** (cartões de assinatura).

        * **Data de processamento**: Filtre pela data em que os lotes foram gerados no sistema.

        * **Período**: Busque pelos lotes com base no período em que os serviços foram praticados.

        * **Mês de referência**: Alternativa ao filtro de período para buscar por um mês completo.

        * **Status**: Filtre pelo status do lote, como **Processado** ou **Estornado**.

        * **Lote**: Busque por um número de lote específico.

    4.  Após preencher os filtros, clique em **Filtrar**.

    5.  Para cada lote listado nos resultados, as seguintes ações estão disponíveis:

        * **Visualizar logs**: Abre uma janela com a lista de todos os itens (termos ou cartões) comunicados naquele lote.

        * **Anexos do lote**: Permite anexar documentos ao lote, como um comprovante de envio ou protocolo de recebimento.

        * **Estornar lote**: Realiza o estorno do lote, desvinculando os itens para que possam ser processados novamente em um novo lote, se necessário. O lote estornado permanece no sistema para consulta.

        * **Visualizar andamentos**: Exibe o histórico de todas as ações realizadas no lote (criação, estorno, etc.).

---
## M-32.1 - Gerando Lote SEFAZ - Filtrando e Validando Termos Pendentes
**Objetivo:** Detalhar a primeira parte do processo de comunicação com a SEFAZ: como filtrar, localizar e validar os termos de comparecimento (CRV) que estão pendentes de envio.  
**Tags:** `Administração`, `Comunicações`, `SEFAZ`, `Lotes`, `Filtros`, `Validação`, `Termo de Comparecimento`, `CRV`

### Intenções de Busca & Dúvidas Frequentes
- validar pendências de comunicação SEFAZ
- Onde eu começo o processo para gerar o lote da SEFAZ?
- consultar termos para enviar à SEFAZ
- Como eu vejo quais termos de venda de veículo ainda não foram comunicados para a SEFAZ?
- filtrar CRVs para lote
- O sistema valida se o termo está preenchido corretamente antes de enviar?

### Procedimento / Explicação
#### Descrição:

Antes de gerar um novo lote para a SEFAZ, é crucial identificar e validar todos os termos de comparecimento de venda de veículos (CRV) que estão pendentes de comunicação. Esta rotina cobre a fase de filtragem e verificação inicial.

#### Passo a passo:

1.  Acesse a tela de Comunicações pelo menu **Administração > Comunicações**.

2.  Para iniciar a geração de um novo lote, clique no botão **Comunicar**.

3.  Na tela seguinte, selecione o tipo de comunicação **Sefaz** e informe o **período** para buscar os termos pendentes.

4.  Clique no botão **Filtrar**.

5.  O sistema listará todos os termos de comparecimento que foram configurados com a opção **CRV - SEFAZ SP** e que ainda não pertencem a nenhum lote.

6.  Para cada termo listado, é possível expandir a linha para visualizar os dados do comprador e as informações de transferência do veículo.

7.  Neste momento, o sistema realiza uma validação preliminar para garantir que as informações obrigatórias foram preenchidas e que a digitalização do DUT foi anexada.

    * *Observação Importante:* O processo de geração do lote só pode ser iniciado se ao menos um dos termos filtrados tiver a imagem do DUT digitalizada.

8.  Após confirmar que os termos corretos estão na lista, o próximo passo é o processamento e a assinatura digital.

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
## M-51.5 - Como Preencher as Informações do COAF em um Protocolo
**Objetivo:** Orientar sobre o preenchimento do card 'COAF', detalhando como selecionar os participantes, escolher os enquadramentos e preparar a comunicação para envio.  
**Tags:** `Protocolo`, `COAF`, `Comunicação`, `Enquadramento`, `Prevenção à Lavagem de Dinheiro`

### Intenções de Busca & Dúvidas Frequentes
- preparar comunicação ao COAF
- selecionar participantes para COAF
- Onde eu seleciono o enquadramento do COAF para um ato específico?
- preencher dados do COAF
- Como eu adiciono uma pessoa na comunicação do COAF que não é parte do ato?
- Dentro de um protocolo, como eu preparo a comunicação para o COAF?
- enquadramento COAF

### Procedimento / Explicação
#### Descrição:

O card 'COAF' é a ferramenta para preparar e enviar comunicações de operações suspeitas ou de comunicação obrigatória ao Conselho de Controle de Atividades Financeiras (COAF).

#### Passo a passo:

1.  Acesse o card **COAF** em um protocolo já salvo.

2.  **Participantes do Ato**: A lista é preenchida automaticamente com as pessoas da **Qualificação de Partes**. Selecione as que farão parte da comunicação.

3.  **Indicação que não fazem parte do ato**: Adicione aqui outras pessoas relevantes para a comunicação que não estão na qualificação de partes.

4.  **Bloco Enquadramento**: Pesquise pelo código ou descrição do enquadramento do COAF em que a operação se encaixa. É possível selecionar mais de um.

5.  **Enquadramentos**: A lista exibirá todos os enquadramentos selecionados.

6.  **Bloco Detalhes do Ato**: Selecione o modelo a ser usado na indicação e adicione observações, se necessário.

7.  **Botão Cancelar Indicação**: Utilize para cancelar uma indicação já preparada.

8.  **Botão Enviar Indicação**: Utilize para enviar a comunicação ao COAF.

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
## D-1.13 - Ativar Integração com SGA (Sistema de Senhas)
**Objetivo:** Habilitar integração com o SGA para encerramento automático de senhas ao concluir pagamentos.  
**Tags:** `sga`, `integração`, `senha`, `atendimento`

### Intenções de Busca & Dúvidas Frequentes
- Como integrar o SGA ao Orion Caixa?
- integrar sistema de senhas
- Como encerrar senhas automaticamente?
- Onde configuro a integração com o sistema de atendimento?
- ativar sga
- configurar encerramento de senhas

### Procedimento / Explicação
#### Descrição:

A integração com SGA permite encerramento automático de senhas de atendimento quando um pagamento é concluído.

#### Passo a passo:

1. Acesse **Configurações > Parametrizações > Produtos Orion**.

2. Localize a opção **Ativar Integração com SGA**.

3. Marque a opção para ativar.

4. Salve as configurações.

* **Observação Importante:** Com esta integração ativa, toda conclusão de pagamento no caixa encerrará automaticamente a senha relacionada no SGA.

---
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
## D-3.28 - Consultar Indisponibilidade de Pessoa (CENIB)
**Objetivo:** Consultar Central de Indisponibilidade para verificar se pessoa tem bloqueio ou restrição.  
**Tags:** `cenib`, `indisponibilidade`, `consulta`, `integração`

### Intenções de Busca & Dúvidas Frequentes
- buscar restrição
- Como saber se pessoa tem indisponibilidade?
- consultar cenib
- O que significa ordem de indisponibilidade?
- Como consultar CENIB?
- verificar indisponibilidade

### Procedimento / Explicação
#### Descrição:

Integração automática com CENIB verifica indisponibilidade de contratantes durante qualificação.

#### Passo a passo:

1. Na **qualificação de parte**, sistema **consulta automaticamente** CENIB.

2. Se há **consulta já realizada**:

   * Sistema mostra mensagem: "Consulta realizada, não há ordem de indisponibilidade" ou "Há ordem de indisponibilidade"

3. Para **nova consulta**, clique em **botão de reconsulta**.

4. Sistema faz **nova requisição ao CENIB**.

5. Resultado aparece com **código e documento consultado**.

6. Clique em **?** para ver detalhes da consulta anterior.

#### Também Consulta Cônjuge:

- Se pessoa é casada, sistema **consulta cônjuge automaticamente**

- Resultado aparece com **informações de ambos**

7. Você pode **incluir resultado** no livro se desejar (função avançada).

* **Observação Importante:** Consulta automática integrada. Importante para proteção do cartório contra fraudes. Cônjuge é consultado automaticamente.

---
## D-3.29 - Consultar Central de Indisponibilidade no Livro (CENIB)
**Objetivo:** Realizar consulta CENIB de todos os contratantes e adicionar resultado ao livro/traslado.  
**Tags:** `livro`, `cenib`, `indisponibilidade`, `editor`

### Intenções de Busca & Dúvidas Frequentes
- adicionar cenib ao livro
- Como registrar que fez consulta?
- Como adicionar consulta CENIB ao livro?
- registrar consulta
- fazer consulta cenib

### Procedimento / Explicação
#### Descrição:

Dentro do editor de livro, você pode fazer consulta CENIB formalizada e adicionar resultado ao documento.

#### Passo a passo:

1. Na **tela de Editor de  texto**, clique em **Central de Indisponibilidade**.

2. Sistema **faz nova consulta** de todos os documentos no protocolo.

3. Enquanto carrega, sistema está **consultando CENIB**.

4. Resultado aparece com **código de consulta e resultado** (ordem ou não).

5. Sistema mostra **mescla realizada com sucesso**.

6. Na **lupinha de modelo**, procure por **Modelo de Consulta CENIB**.

7. Clique no modelo para **adicionar resultado ao livro**.

8. Sistema insere ** texto de consulta** no local onde você clicou.

9. Texto mostra:

   * Que foi realizada consulta

   * Nomes dos consultados

   * Códigos hash

   * Resultado (sem indisponibilidade)

10. Clique em **Salvar**.

* **Observação Importante:** Consulta CENIB é importante para fraude prevention. Deve estar documentada no livro. Modelo é configurável.

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
## D-3.37 - Gerar Selo de Cancelamento
**Objetivo:** Cancelar protocolo formalmente gerando selo de cancelamento e comunicando ao TJ.  
**Tags:** `protocolo`, `cancelamento`, `selo`, `comunicação`

### Intenções de Busca & Dúvidas Frequentes
- comunicar cancelamento
- cancelar protocolo
- Como cancelar um protocolo?
- gerar cancelamento
- Como comunicar cancelamento?

### Procedimento / Explicação
#### Descrição:

Cancelamento formal gera selo específico e comunica ao TJ a anulação.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Não Utilizar Protocolo** ou **Cancelar**.

2. Sistema gera **selo de cancelamento**.

3. Sistema **comunica ao TJ** (se configurado).

4. Protocolo muda status para **cancelado**.

* **Observação Importante:** Cancelamento é formal e rastreável. Melhor que deletar (que deixa rastro).

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
## D-3.39 - Visualizar Selos Digitais do Protocolo
**Objetivo:** Visualizar todos os selos digitais gerados para o protocolo.  
**Tags:** `protocolo`, `selo digital`, `consulta`

### Intenções de Busca & Dúvidas Frequentes
- Como ver os selos que foram gerados?
- verificar comunicação
- ver selos
- Como consultar no TJ?
- consultar selos digital

### Procedimento / Explicação
#### Descrição:

Visualização de selos digitais gerados e comunicados.

#### Passo a passo:

1. Na **tela do Protocolo**, clique em **Selo Digital**.

2. Sistema exibe:

   * **Selos gerados**

   * **Datas de geração**

   * **Status de comunicação**

   * **QR Codes** para consultar no TJ

3. Clique em **QR Code** para **abrir portal TJ** e verificar.

* **Observação Importante:** Integração com TJ para conferência instantânea.

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
## D-3.55 - Fazer Consulta de Selos Digitais
**Objetivo:** Fazer auditoria de selos digitais comparando sistema com TJ para identificar divergências.  
**Tags:** `auditoria`, `selo`, `consulta`, `tj`

### Intenções de Busca & Dúvidas Frequentes
- Como fazer auditoria de selos?
- Como corrigir selo divergente?
- conferir divergência
- auditar selos
- Como saber se há divergência?
- comparar sistema tj

### Procedimento / Explicação
#### Descrição:

Auditoria de selos é rotina rigorosa que compara cada selo gerado no sistema com registro no TJ.

#### Passo a passo:

1. Acesse **Administração > Auditoria de Selos** (ou Comunicações).

2. Clique em **Auditar** para iniciar auditoria.

3. Sistema **faz comparação** entre:

   * **Sistema:** O que foi gerado aqui

   * **TJ:** O que TJ recebeu

4. Sistema traz **relatório** com estatuto:

   * **Conformidade:** Tudo ok (verde)

   * **Não Encontrado:** Não foi gerado ou não enviou

   * **Divergência:** Algo diferente entre sistema e TJ

#### Ações em Caso de Divergência:

1. Clique em **divergência** para ver detalhes.

2. Sistema exibe:

   * **O que está no sistema**

   * **O que está no TJ**

   * **Diferença específica** (ex: custo zerado no sistema, com valor no TJ)

3. Clique em **ícone de olho** para abrir o ato divergente.

4. **Corrija** a informação conforme necessário.

5. Sistema permite **retificação** ou **alteração** no solicitante.

#### Relatório:

- Após auditoria, gere **relatório** mostrando todos os tipos de serviço.

- **Verde:** Conformidade

- **Vermelho:** Divergência

- Mostra **valores** do sistema e TJ lado a lado.

* **Observação Importante:** Auditoria deve ser feita antes do recolhimento. Divergências devem ser corrigidas. Essencial para compliance.

---
## D-3.56 - Comunicar Selos ao TJ
**Objetivo:** Enviar selos gerados para o TJ (web service) ou gerar arquivo para envio (CEPHAS/DOI).  
**Tags:** `comunicação`, `selo`, `tj`, `envio`

### Intenções de Busca & Dúvidas Frequentes
- enviar selo
- Como comunicar ao CEPHAS?
- Como enviar selos?
- Como enviar para DOI?
- comunicar tj
- processar envio

### Procedimento / Explicação
#### Descrição:

Comunicação dispara envio automático (web service) ou gera arquivo para central específica.

#### Passo a passo:

1. Acesse **Administração > Comunicações > Selos Digitais** (ou similar).

2. Selecione **período** desejado.

3. Sistema traz **selos prontos para comunicação**.

4. Clique em **Processar**.

#### Tipos de Comunicação:

**Web Service (Automático):**

- SGA, Notariado, e Selo Digital

- Clique em **Processar**

- Sistema **valida campos**

- Se ok, **envia automaticamente**

- Se divergência, sistema lista o que **precisa corrigir**

**Gerar Arquivo (Manual):**

- CEPHAS e DOI

- Clique em **Processar**

- Sistema **gera arquivo** (.xml ou similar)

- Você **baixa arquivo**

- Você **envia manualmente** no portal da central

5. Sistema mostra **validação**:

   * **Ok:** Pronto para enviar

   * **Pendente:** Falta preencher algo

6. Corrija **pendências** conforme necessário.

7. Ressubmeta após correções.

#### Comunicação Automática:

- Se configurada, sistema **envia sozinho** em horário predefinido (ex: 21h para Selo Digital).

- Você apenas **valida** no dia seguinte.

* **Observação Importante:** Web service = envio automático. Arquivo manual = você envia na central. Horários automáticos são configuráveis.

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
## D-3.70 - Cadastrar Impedimento de Pessoa/Documento
**Objetivo:** Registrar pessoas ou documentos com impedimento (fraude, restrição, etc.) para alerta ao processar.  
**Tags:** `impedimento`, `bloqueio`, `fraude`, `proteção`

### Intenções de Busca & Dúvidas Frequentes
- Como registrar fraude?
- Como impedir operação?
- bloquear pessoa
- adicionar restrição
- registrar fraude
- Como bloquear uma pessoa?

### Procedimento / Explicação
#### Descrição:

Impedimento previne operação com pessoas/documentos suspeitos ou fraudulentos.

#### Passo a passo:

1. Acesse **Administração > Impedimentos**.

2. Clique em **Adicionar** impedimento.

3. Configure:

   * **Pessoa/Documento:** Quem está bloqueado

   * **Motivo:** Fraude, documento vencido, etc.

   * **Observações:** Detalhes

4. Clique em **Salvar**.

#### Resultado:

- Quando **tentar fazer operação** com pessoa/documento impedido:

  * Sistema **mostra alerta**

  * Descreve **motivo do impedimento**

  * Você pode **prosseguir com confirmação** ou **cancelar**

5. Para **remover impedimento**, acesse novamente e **delete**.

* **Observação Importante:** Proteção contra fraude. Alerta impede operações sem perceber risco. Essencial para segurança.

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
## D-3.73 - Visualizar Central de Notificações
**Objetivo:** Visualizar todos os alertas e notificações recebidas no sistema.  
**Tags:** `notificação`, `alerta`, `comunicação`, `sistema`

### Intenções de Busca & Dúvidas Frequentes
- ver alertas
- ler mensagens
- consultar notificações
- Como ver minhas notificações?
- Onde vejo os alertas?

### Procedimento / Explicação
#### Descrição:

Central de notificações consolida todos os alertas do sistema.

#### Passo a passo:

1. Na **barra superior**, clique em **ícone de notificações** (sino).

2. Visualize **lista de alertas**:

   * **Trâmites:** Mensagens de protocolo

   * **Comunicações Pendentes:** Pendências de envio

   * **Alertas do Sistema:** Falhas, updates, etc.

3. Clique em **notificação** para acessar rapidamente.

* **Observação Importante:** Atalho para ficar atualizado de tudo que você foi mencionado ou que precisa atenção.

---
## D-3.74 - Acessar Integração SGA (Sistema de Senhas)
**Objetivo:** Integração com SGA para chamar senhas de atendimento e encerrar ao finalizar serviço.  
**Tags:** `sga`, `senha`, `atendimento`, `integração`

### Intenções de Busca & Dúvidas Frequentes
- finalizar senha
- Como integrar SGA?
- Como chamar senha?
- chamar senha
- gerenciar atendimento

### Procedimento / Explicação
#### Descrição:

SGA integrado permite gerenciamento de senhas de atendimento direto do ORION.

#### Passo a passo:

1. Na **barra superior/inferior**, procure **botão de Atendimento** (SGA).

2. Clique para acessar.

3. Sistema exibe **painel de senhas**:

   * Senhas em espera

   * Senhas em atendimento

4. Para **chamar senha**, selecione em fila.

5. Ao **finalizar operação** no ORION (ex: reconhecimento), sistema **encerra senha** automaticamente (se configurado).

* **Observação Importante:** Integração automática economiza passo. Sensível ao conceito de consumo automático no ORION.

---
## D-3.75 - Consultar Selos Digitais Gerados
**Objetivo:** Consultar status de selos digitais gerados, comunicados e verificar no TJ via QR Code.  
**Tags:** `selo`, `consulta`, `qr code`, `tj`

### Intenções de Busca & Dúvidas Frequentes
- verificar tj
- ver selos
- Como saber se selo foi comunicado?
- Como consultar no TJ?
- consultar estado

### Procedimento / Explicação
#### Descrição:

Consulta de selos mostra status de cada selo com acesso direto ao TJ.

#### Passo a passo:

1. Acesse **Administração > Selos Digitais** (ou integrado em protocolo).

2. Visualize **selos gerados**:

   * **Comunicado:** Enviado ao TJ

   * **Não Comunicado:** Pendente envio

   * **Aguardando Retificação:** Com problema

3. Para **verificar no TJ**, clique em **QR Code**.

4. Sistema **abre portal TJ** com comunicação.

* **Observação Importante:** QR Code leva direto ao TJ. Ótimo para conferência rápida.

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
## D-3.77 - Ativar Consumo Automático de Papel e Selos
**Objetivo:** Configurar sistema para consumir automaticamente papel de segurança e selos ao registrar cartões e protocolos.  
**Tags:** `configuração`, `consumo automático`, `papel`, `selo`

### Intenções de Busca & Dúvidas Frequentes
- Qual é a vantagem?
- configurar sistema
- ativar consumo automático
- habilitar consumo
- Como o sistema consome papel?
- Como ativar consumo automático?

### Procedimento / Explicação
#### Descrição:

Consumo automático elimina necessidade de lançamento manual, otimizando fluxo de trabalho.

#### Passo a passo:

1. Acesse **Configurações > Parametrizações** (conforme seu módulo).

2. Procure opção **Consumo Automático**.

3. Para **Cartão de Assinatura**:

   * Habilite **consumo automático de papel**

   * Habilite **geração de selo**

4. Para **Protocolo/Notas**:

   * Habilite **consumo automático de livro/folha**

   * Habilite **geração de selo digital**

5. Clique em **Salvar**.

#### Resultado:

- **Cartão criado:** Papel consumido automaticamente

- **Protocolo criado:** Livro/Folha consumido automaticamente

- **Recibo gerado:** Selo gerado automaticamente

- **Tempo economizado:** Eliminam-se lançamentos manuais

* **Observação Importante:** Recomenda-se ativar. Otimiza muito o tempo. Requisito para digitalização por código de barras.

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
## D-5.0 - Consultar Indisponibilidade de Bens (CNIB) no Protocolo
**Objetivo:** Realizar a consulta de indisponibilidade de bens (CNIB) para as partes envolvidas em um protocolo, de forma individual ou em lote, gerando o código HASH e status.  
**Tags:** `Protocolo`, `Notas`, `CNIB`, `Indisponibilidade`, `Consulta`, `CPF`, `Partes`, `API`

### Intenções de Busca & Dúvidas Frequentes
- Onde fica o botão para consultar a CNIB dentro do protocolo?
- verificar cnib
- O sistema gera o hash da consulta da CNIB automaticamente?
- consultar cpf na cnib
- Como eu consulto se uma pessoa tem indisponibilidade de bens pelo sistema?
- consulta hash cnib
- checar indisponibilidade de bens
- Consigo consultar a indisponibilidade de todas as partes e cônjuges de uma vez só?
- validar partes cnib
- consultar bonequinho

### Procedimento / Explicação
#### Descrição:

Esta rotina permite verificar a indisponibilidade de bens das partes cadastradas em um protocolo através da integração via API com o portal da CNIB. A consulta retorna o código HASH, documento, nome e a mensagem de status (se há ou não indisponibilidade).

#### Passo a passo:

1.  Acesse o **Protocolo** desejado.

2.  Certifique-se de preencher a **Qualificação das partes** corretamente.

3.  Para realizar a consulta, existem duas formas disponíveis no card de preenchimento das partes:

    * **Consulta Individual:** Localize o campo **CPF** da parte específica e clique no **ícone de um "bonequinho"** ao lado do campo.

    * **Consulta em Lote (Todas as partes):** Localize o mesmo **ícone de "bonequinho"** situado no início do card de preenchimento das partes. Ao clicar nele, o sistema consultará todos os CPFs preenchidos na qualificação, incluindo os cônjuges.

4.  Após o clique, o sistema processará a consulta via API e retornará as informações (Código HASH, documento, nome e status de indisponibilidade).

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