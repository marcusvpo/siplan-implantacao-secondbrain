---
tipo: Recurso
area: Produtos Siplan
tags:
  - #orion
  - #orion_orion_tn
  - #orion_tn_-_selos_e_integrações
status_atual: #ativo
---
# Orion TN - Selos e Integrações

Este recurso detalha os procedimentos, rotinas e manuais operacionais do sistema **Orion TN** para a área de **Selos e Integrações**.

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

---

