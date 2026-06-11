---
tipo: Recurso
area: Produtos Siplan
tags:
  - #orion
  - #orion_orion_pro
  - #orion_pro_-_integração_e_comunicação
status_atual: #ativo
---
# Orion PRO - Integração e Comunicação

Este recurso detalha os procedimentos, rotinas e manuais operacionais do sistema **Orion PRO** para a área de **Integração e Comunicação**.

## V-11.0 - Como Gerar a Remessa Manual para Entidades (Serasa)
**Objetivo:** Gerar manualmente o arquivo de remessa para entidades como o Serasa, contendo os protestos e cancelamentos de um período, para posterior upload na plataforma da entidade.  
**Tags:** `remessa`, `entidades`, `serasa`, `comunicação`, `gerar remessa`

### Intenções de Busca & Dúvidas Frequentes
- enviar dados para entidades
- Onde fica a rotina para criar o arquivo de comunicação com as entidades?
- remessa manual serasa
- Preciso gerar a remessa de ontem para o Serasa, qual o passo a passo?
- Como eu gero o arquivo de remessa para enviar ao Serasa?
- gerar arquivo serasa
- exportar arquivo de protestos para serasa

### Procedimento / Explicação
#### Descrição:

Esta rotina é utilizada para criar o arquivo de comunicação que deve ser enviado a entidades externas, como o Serasa. O arquivo contém as informações de protestos e cancelamentos de um período específico.

* **Observação Importante:** O sistema pode ser configurado para gerar esta remessa de forma automática. Este passo a passo descreve o procedimento manual, que deve ser usado caso a automação não esteja ativa.

#### Passo a passo:

1.  Acesse o menu **Administração > Comunicações > Entidades**.

2.  Na tela de consulta, clique em **"Gerar Nova Remessa"**.

3.  Selecione a **data** para a qual a remessa deve ser gerada (por exemplo, o dia anterior).

4.  Clique em **"Gerar"**.

5.  O sistema irá processar as informações e disponibilizar o arquivo para **download**.

6.  Salve o arquivo em seu computador e, em seguida, acesse a plataforma da entidade (Serasa) para realizar o **upload** do mesmo.

---

---

## V-12.0 - Como Consultar e Gerenciar Remessas Geradas para Entidades
**Objetivo:** Consultar o histórico de remessas já geradas para entidades, visualizar os dados enviados e realizar ações como gerar recibos de valores e verificar os selos digitais.  
**Tags:** `remessa`, `entidades`, `serasa`, `consulta`, `recibo`, `selo digital`

### Intenções de Busca & Dúvidas Frequentes
- baixar novamente arquivo de remessa
- Preciso consultar o que foi enviado em uma remessa específica, como faço?
- Onde eu vejo o histórico de remessas que já foram enviadas para o Serasa?
- histórico de envio serasa
- ver o que foi enviado para o serasa
- gerar recibo de remessa
- Como vejo os andamentos de uma remessa gerada?
- consultar remessas enviadas
- Como eu gero o recibo de uma remessa que já foi processada?

### Procedimento / Explicação
#### Descrição:

Esta tela funciona como um histórico de todas as remessas enviadas para as entidades, permitindo a conferência e o gerenciamento dos lotes já processados.

#### Passo a passo:

1.  Acesse o menu **Administração > Comunicações > Entidades**. A tela inicial já é a de consulta.

2.  Utilize o filtro de **data** para localizar a remessa que deseja consultar e clique para filtrar.

3.  O sistema listará as remessas geradas. Para cada uma, é possível ver a certidão correspondente, contendo os **protestados** e os **cancelamentos** incluídos.

4.  Na linha de cada remessa, as seguintes ações estão disponíveis:

    * **Gerar um recibo**: Cria um documento com os valores da remessa, que pode ser necessário para anexar na plataforma da entidade.

    * **Visualizar o selo digital**: Exibe o selo digital associado à certidão gerada.

    * **Andamentos**: Mostra o histórico de ações realizadas na remessa (quem gerou, quando, etc.).

    * **Download da remessa**: Permite baixar novamente o arquivo que foi gerado.

---

---

## R-13.0 - Comunicação com a CRA CENPROT (Ocorrências e Certidões)
**Objetivo:** Gerar e gerenciar os arquivos XML de comunicação com a CRA CENPROT, abrangendo o envio de ocorrências (pagamentos, cancelamentos) e de certidões.  
**Tags:** `comunicação`, `CRA`, `CENPROT`, `certidão`, `ocorrências`, `XML`, `assinatura`, `envio`

### Intenções de Busca & Dúvidas Frequentes
- enviar certidão para CRA
- O que eu preciso fazer antes de gerar o arquivo de ocorrências da CRA?
- Como eu gero o arquivo XML de ocorrências para enviar para a CRA?
- Gerei um arquivo para a CRA com erro, como posso gerar novamente?
- arquivo de comunicação
- Qual o procedimento para enviar as certidões para a CENPROT?
- gerar XML CENPROT
- lote CRA
- enviar arquivo CRA
- comunicação de ocorrências

### Procedimento / Explicação
#### Descrição:

Este módulo centraliza a comunicação com a CRA CENPROT, garantindo a geração, assinatura e o envio correto dos arquivos de ocorrências e certidões.

#### Pré-requisitos:

* **Para Ocorrências:** O termo de protesto dos títulos envolvidos já deve ter sido exportado e assinado digitalmente.

* **Para Certidões:** As certidões devem ser previamente exportadas na tela de **Administração > Certidões**, utilizando a opção **somente CENPROT**.

#### Geração de XML de Ocorrências:

1.  Na tela de comunicação com a CRA, clique em **Gerar XML**.

2.  Defina o **Período** e escolha o tipo de ocorrência que deseja comunicar (ex: pagamentos, cancelamentos).

3.  Clique em **Gerar**. O sistema preparará os arquivos para assinatura digital e posterior download.

* **Observação Importante:** Em caso de erro, você deve **excluir** o arquivo gerado antes de tentar gerar um novo. Isso garante que a contagem de itens para o novo arquivo seja refeita corretamente.

#### Geração de Arquivo de Certidões:

1.  Após cumprir o pré-requisito (exportar as certidões na tela de administração), acesse a tela de comunicação CRA CENPROT.

2.  Gere o arquivo de certidões, que também exigirá assinatura digital antes do envio.

---

---

## V-13.0 - Como Gerar o Arquivo de Ocorrências para a CRA/CENPROT
**Objetivo:** Gerar e assinar o arquivo XML de ocorrências (pagamentos, cancelamentos) para envio à CRA/CENPROT, e orientar sobre como consultar e corrigir arquivos gerados com erro.  
**Tags:** `ocorrências`, `CRA`, `CENPROT`, `comunicação`, `XML`, `pagamentos`, `cancelamentos`

### Intenções de Busca & Dúvidas Frequentes
- enviar pagamentos para CRA
- gerar XML de cancelamentos
- comunicação CENPROT
- Gerei o arquivo para a CRA com erro, como eu refaço?
- arquivo de ocorrências
- assinar arquivo CRA
- Onde eu consulto os arquivos de ocorrências que já foram enviados?
- Como eu gero o arquivo XML de ocorrências (pagamentos e cancelamentos) para a CRA?
- Onde eu envio as informações de títulos pagos para a CENPROT?

### Procedimento / Explicação
#### Descrição:

Esta rotina é responsável por criar o arquivo de comunicação (XML) que informa a CRA/CENPROT sobre as ocorrências de pagamentos, cancelamentos e outros eventos. A tela principal serve tanto para gerar novos arquivos quanto para consultar os que já foram enviados.

* **Observação Importante:** A exportação e assinatura dos termos de protesto individuais devem ser realizadas previamente em suas respectivas telas. Esta rotina apenas gera o arquivo de **comunicação** desses eventos.

#### Passo a passo:

1.  Acesse o menu **Administração > Comunicações > CRA/CENPROT**.

2.  Para criar um novo arquivo, clique em **"Gerar XML"**.

3.  Informe o **período** desejado e, se necessário, filtre pelo **Tipo de ocorrência** ("Protestados", "Outras Ocorrências" ou "Todos").

4.  Clique em **Gerar**.

5.  Aguarde a notificação do sistema (no ícone de sino) e realize a **assinatura digital** do arquivo.

6.  Após a assinatura, o arquivo ficará disponível para **download**. Baixe-o e faça o upload na plataforma da CRA/CENPROT.

* **Atenção à Sequência:** As sequências de arquivos devem ser geradas em ordem (ex: 2, 3, 4). Não é possível pular uma numeração.

* **Correção de Erros:** Se um arquivo foi gerado com erro e precisa ser refeito, é fundamental **excluí-lo** da lista de consulta nesta tela antes de gerar um novo. Isso garante que os títulos e valores sejam reprocessados e incluídos corretamente no novo arquivo.

---

---

## R-14.0 - Gerar Remessa de Comunicação para Entidades (Serasa)
**Objetivo:** Gerar arquivos de remessa para comunicação com entidades externas (ex: Serasa), incluindo a criação de documentos de suporte como certidões e recibos.  
**Tags:** `comunicações`, `entidades`, `remessas`, `serasa`, `geração`, `exportação`, `arquivo`

### Intenções de Busca & Dúvidas Frequentes
- enviar protesto para Serasa
- gerar remessa Serasa
- arquivo de protesto Serasa
- Como eu envio os cancelamentos de protesto para o Serasa?
- Onde fica a tela para comunicação com entidades como o Serasa?
- Como eu gero o arquivo de remessa para enviar os protestos para o Serasa?
- Após gerar a remessa, quais outros documentos o sistema cria?
- negativar no Serasa
- comunicação com entidades

### Procedimento / Explicação
#### Descrição:

Este módulo permite a geração de arquivos de remessa para comunicação de protestos e cancelamentos com entidades externas, como o Serasa.

#### Passo a passo:

1.  Acesse o menu **Administração > Comunicações > Entidades**.

2.  Clique em **Gerar Nova Remessa**.

3.  Selecione a **Data** para a qual deseja gerar a remessa (geralmente o dia anterior para consolidar todos os atos) e clique em **Gerar**.

4.  O sistema criará um arquivo para download, que deve ser salvo e posteriormente enviado no portal da entidade correspondente (ex: Serasa).

5.  Após a geração da remessa, o sistema também disponibiliza ações complementares:

    * **Gerar Certidão**: Cria uma certidão correspondente com o total de protestos e cancelamentos enviados na remessa.

    * **Gerar Recibo**: Gera um recibo com os valores, que pode ser necessário anexar no portal da entidade.

    * **Visualizar Selo Digital** e **Andamentos**.

---

---

## V-14.0 - Como Gerar o Arquivo de Certidões para a CRA/CENPROT
**Objetivo:** Realizar o processo de duas etapas para enviar certidões à CRA/CENPROT: primeiro exportando e assinando as certidões individualmente, e depois gerando e assinando o arquivo de comunicação final.  
**Tags:** `certidões`, `CRA`, `CENPROT`, `comunicação`, `exportação`, `assinatura digital`

### Intenções de Busca & Dúvidas Frequentes
- Como eu envio as certidões solicitadas pela CENPROT?
- enviar certidões para a CENPROT
- assinar arquivo de certidões
- Qual o processo para gerar o arquivo de certidões para a CRA?
- exportar certidões para CRA
- Por que o sistema pede para assinar as certidões duas vezes no envio para a CENPROT?
- comunicação de certidões

### Procedimento / Explicação
#### Descrição:

O envio de certidões para a CRA/CENPROT é um processo que exige duas assinaturas digitais: uma para as certidões em si e outra para o arquivo de lote que as agrupa.

#### Passo a passo:

1.  **Etapa 1: Exportar e Assinar as Certidões**

    * Acesse o menu **Administração > Certidões**.

    * Filtre pelo **período** desejado, selecionando apenas as certidões que têm como destino a **CENPROT**.

    * Clique no botão de **exportação**.

    * Realize a **primeira assinatura digital**, que se refere às certidões individuais.

2.  **Etapa 2: Gerar o Arquivo de Comunicação**

    * Acesse o menu **Administração > Comunicações > CRA/CENPROT**.

    * Vá para a seção ou aba de **Certidões**.

    * Clique para gerar o arquivo, informando o mesmo período da exportação anterior.

    * O sistema solicitará uma **segunda assinatura digital**. Desta vez, você estará assinando o arquivo de lote (XML) que agrupa todas as certidões.

3.  Após a segunda assinatura, faça o **download** do arquivo final e realize o upload na plataforma da CRA/CENPROT.

---

---

## D-27.0 - Autenticar Consulta Boa Vista (Informações Complementares)
**Objetivo:** Registrar e autenticar consultas realizadas na plataforma Boa Vista disponibilizada pela CRA.  
**Tags:** `boa vista`, `informações complementares`, `cra`, `autenticação`, `consulta`

### Intenções de Busca & Dúvidas Frequentes
- Como faço para autenticar consulta boa vista (informações complementares)?
- autenticação
- Onde consigo autenticar consulta boa vista (informações complementares)?
- cra

### Procedimento / Explicação
#### Passo a passo:

1. Em **Operações de Caixa**, adicionar novo serviço

2. Selecionar **Outros Serviços**

3. Escolher **Informações Complementares**

4. Informar a quantidade conforme indicado pela CRA

5. Selecionar **Boa Vista**

6. Realizar a autenticação

7. O sistema inclui automaticamente o valor no caixa

8. O sistema realiza consumo e envio de selos para o TJ

---

---

## D-38.0 - Processar E-formulário Digitalizado no Site da CRA
**Objetivo:** Importar dados de título digitado no site da CRA através da leitura do código de barras da ficha impressa.  
**Tags:** `e-formulário`, `cra`, `código de barras`, `importação`

### Intenções de Busca & Dúvidas Frequentes
- Qual o procedimento para processar e-formulário digitalizado no site da cra?
- código de barras
- Como processar e-formulário digitalizado no site da cra?
- importação

### Procedimento / Explicação
#### Passo a passo:

1. Acessar **Operações Internas > Protocolo**

2. Receber do apresentante a ficha impressa da CRA

3. Verificar documentação anexa

4. Usar leitor de código de barras

5. Ler o código de barras do e-formulário OU

6. Digitar manualmente a numeração do formulário

7. O sistema baixa automaticamente todas as informações digitadas

8. Conferir os dados importados

9. Fazer ajustes se necessário

10. Finalizar a inclusão do protocolo

---

---

## D-43.0 - Protocolizar Arquivo Diretamente do Site da CRA
**Objetivo:** Buscar e processar arquivos de protocolização diretamente da API da CRA sem distribuidor.  
**Tags:** `protocolização`, `cra`, `api`, `busca automática`, `remessa`

### Intenções de Busca & Dúvidas Frequentes
- remessa
- busca automática
- api
- Qual o caminho para protocolizar arquivo diretamente do site da cra?
- Como faço para protocolizar arquivo diretamente do site da cra?
- protocolização

### Procedimento / Explicação
#### Passo a passo:

1. Acessar **Remessas > Protocolização**

2. Clicar em **Buscar Diretamente da CRA**

3. Informar a **Data da Remessa**

4. Clicar em **Confirmar**

5. O sistema busca automaticamente na API da CRA

6. O sistema baixa todos os arquivos em aberto

7. Aguardar processamento

8. Verificar protocolos gerados

9. Conferir mensagens e críticas

---

---

## D-60.0 - Exportar Arquivo XML de Manifestação para CRA
**Objetivo:** Gerar arquivo XML assinado digitalmente de manifestação (certidões) para envio ao portal CRA.  
**Tags:** `xml`, `manifestação`, `certidão`, `cra`, `exportação`

### Intenções de Busca & Dúvidas Frequentes
- Como faço para exportar arquivo xml de manifestação para cra?
- Qual o caminho para exportar arquivo xml de manifestação para cra?
- certidão
- exportação

### Procedimento / Explicação
#### Passo a passo:

1. Acessar **Comunicações > CRA**

2. Clicar em **Gerar XML** (aba manifestação)

3. Informar a **Data do Pedido**

4. Informar a **Sequência**

5. Clicar em **Gerar XML**

6. O sistema gera arquivo assinado digitalmente

7. Salvar o arquivo

8. Fazer upload no portal da CRA

---

---

## D-92.0 - Criar Arquivo de Comunicação para Serasa
**Objetivo:** Gerar arquivo para envio de informações de protestos ao Serasa.  
**Tags:** `serasa`, `comunicação`, `arquivo`, `protesto`

### Intenções de Busca & Dúvidas Frequentes
- Como criar arquivo de comunicação para serasa?
- protesto
- Onde faço para criar arquivo de comunicação para serasa?
- Como protestar títulos?

### Procedimento / Explicação
#### Passo a passo:

1. Acessar **Comunicações > Entidades > Serasa**

2. Clicar em **Gerar Remessa**

3. Informar a **Data** desejada

4. O sistema gera arquivo automaticamente

5. Salvar arquivo

6. Fazer upload na plataforma do Serasa

---

---

