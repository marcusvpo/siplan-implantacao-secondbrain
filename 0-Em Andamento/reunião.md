# 📄 Resumo Executivo da Reunião - 25/09/2026

> **Contexto Central:** Alinhamento técnico semanal sobre o progresso das frentes de **Conversão**, **Homologação** e **Virada para Produção** dos sistemas **Siplan**, definindo o balanceamento de esforço entre cronogramas de implantação e a evolução contínua da qualidade dos dados migrados.
> 
>   

## 🎯 Principais Pontos Discutidos

### 🏢 Sorocaba (**ORION TN**)

- **Contexto/Status:** A **Virada para Produção** foi executada no fim de semana com o escopo essencial, finalizando a carga de serviços realizados com mais de 3 milhões de registos.
    
      
    
- **Impedimento/Desafio:** A janela operacional durante os dias úteis foi reduzida devido à configuração de **Selos** e parametrizações pelo consultor Vieira.
    
      
    
- **Detalhes Operacionais:** As cargas complementares de **Termo de Comparecimento**, **Minuta** e documentos apresentados serão executadas na janela de sexta-feira a domingo com o servidor desimpedido.
    
      
    

### 🏢 Praia Grande (**ORION TN**)

- **Contexto/Status:** A estrutura de dados encontra-se convertida, restando apenas a vinculação das imagens com acessos já validados.
    
      
    
- **Impedimento/Desafio:** O projeto sofreu pausa pontual em virtude de testes da nova versão de documentos apresentados e priorizações emergenciais.
    
      
    
- **Detalhes Operacionais:** A conclusão da carga de imagens está planeada para hoje, visando disponibilizar o ambiente de **Homologação** na segunda-feira para Vieira.
    
      
    

### 🏢 Embu das Artes (**ORION TN** & **Control-M**)

- **Contexto/Status:** Discussão técnica sobre o relatório de inconsistências levantado na validação cruzada entre o **Control-M** e o **ORION TN**.
    
      
    
- **Impedimento/Desafio:** Divergências estruturais do legado (como cargos anexados a nomes de escreventes e omissão de utilizadores excluídos no motor) demandariam até quarta-feira para correção.
    
      
    
- **Detalhes Operacionais:** Deliberou-se por não travar o calendário atual, mantendo as regras vigentes para Embu e implementando melhorias de dados de forma gradual nas migrações futuras.
    
      
    

### 🏢 Embu das Artes (**ORION PRO** & **Control-M Prot**)

- **Contexto/Status:** A **Virada para Produção** da área de protesto foi efetuada após homologação e testes de última hora.
    
      
    
- **Impedimento/Desafio:** O ficheiro de dump fornecido pelo consultor **Brites** encontrava-se desatualizado, sem tabelas e campos obrigatórios, impedindo a subida do sistema.
    
      
    
- **Detalhes Operacionais:** O time técnico de suporte corrigiu a estrutura da base de dados; resta agora efetuar a conversão das imagens via **ORION GED** para o **ORION PRO**.
    
      
    

### 🏢 26º Tabelião de Notas da Capital (**ORION TN**)

- **Contexto/Status:** Início do projeto confirmado para 05/10/2026, com aprovação prévia das equipas internas do **Cartório**.
    
      
    
- **Pontos de Atenção:** Inviabilidade de postergar a data em razão de compromissos encadeados e do feriado de 12/10/2026.
    
      
    
- **Detalhes Operacionais:** A base requer compilação de apontamentos e nova carga, necessitando de Vieira para **Homologação** exclusivamente na quinta e sexta-feira.
    
      
    

### 🏢 Mirandópolis (**WebRI**)

- **Contexto/Status:** Prioridade absoluta do dia direcionada à conclusão da **Virada para Produção** marcada para o período da tarde.
    
      
    
- **Detalhes Operacionais:** Imagens em formato TIFF já foram catalogadas via script na pasta padrão do **WebRI**; restam apenas validações pontuais em junções de tabelas com apoio técnico de Breno.
    
      
    

### 🏢 Valinhos (**WebRI**)

- **Contexto/Status:** Processo de notificação paralisado por ausência de dados válidos.
    
      
    
- **Impedimento/Desafio:** As cópias de segurança recebidas do cartório encontram-se desprovidas de dados, sem histórico disponível em **VM** ou no **SharePoint**.
    
      
    
- **Detalhes Operacionais:** Aguarda-se a disponibilização de acesso aos repositórios completos de backup para triagem de ficheiros preenchidos.
    
      
    

### 🏢 Franca (Dominicart para **WebRI**)

- **Contexto/Status:** Análise preliminar iniciada em base legada MariaDB/MySQL com estrutura reduzida (menos de 100 tabelas).
    
      
    
- **Pontos de Atenção:** Projeto criado no DevOps; aguardam-se esclarecimentos técnicos sobre o mapeamento e referência de imagens na **VM**.
    
      
    

### 🏢 Carapicuíba (WebTD para **ORION REG**)

- **Contexto/Status:** Análise de **Aderência** aprovada e credenciais de acesso liberadas.
    
      
    
- **Detalhes Operacionais:** Coleta da base agendada para segunda-feira, com apoio de Breno no formato WebTD para rápida liberação de **Homologação**.
    
      
    

### 🏢 São Caetano do Sul & Sertãozinho (**Inteligência Artificial (IA)** no **Registro de Imóveis**)

- **Contexto/Status:** Tratamento de inconsistências decorrentes da extração automatizada de atos via **Inteligência Artificial (IA)**.
    
      
    
- **Impedimento/Desafio:** Em São Caetano do Sul, atos foram atribuídos com a data 01/01/1900; em Sertãozinho, rasuras provocaram interpretações incorretas de nomes e divergências em dígitos de CPF.
    
      
    
- **Detalhes Operacionais:** Base de São Caetano retificada e purgada de inconsistências durante a noite; ocorrências de Sertãozinho encaminhadas para ajustes nos algoritmos de **Inteligência Artificial (IA)**.
    
      
    

### 🏢 Bragança Paulista (**ORION PRO**)

- **Contexto/Status:** Conversão de aproximadamente 400.000 imagens finalizada e validada por amostragem junto do cliente.
    
      
    
- **Pontos de Atenção:** Documentos assinados digitalmente no padrão P7S não carregam no visualizador de documentos do **ORION PRO**; criado item de backlog (PBI) com entrega prevista para a próxima semana.
    
      
    

### 🏢 Guarulhos - 1º Protesto (**ORION PRO**)

- **Contexto/Status:** Termo de responsabilidade assinado pelo responsável interino e dados coletados.
    
      
    
- **Detalhes Operacionais:** Ficheiros CSV em geração para disponibilizar o ambiente de **Homologação** na segunda-feira para o consultor **Mizuno**.
    
      
    

### 🏢 Mogi Mirim (**ORION PRO**)

- **Contexto/Status:** Identificado caso pontual no qual um título suspenso foi indevidamente migrado com o estado de protestado.
    
      
    
- **Detalhes Operacionais:** Ajuste manual agendado para retificar a base no **ORION PRO** e validação preventiva de demais títulos na mesma condição.
    
      
    

### 🏢 Taubaté - 3º Cartório (**ORION PRO**)

- **Contexto/Status:** Processo de **Homologação** finalizado pelo consultor **Mizuno** sem inconsistências relatadas.
    
      
    
- **Detalhes Operacionais:** Início de implantação confirmado para segunda-feira, com execução da **Virada para Produção** na terça-feira à noite.
    
      
    

### 🏢 Demandas em Fila: Araraquara, Itu, Olímpia e Araras

- **Araraquara:** Servidor liberado pela equipa de **Infraestrutura**; projeto pronto para inclusão na fila de **Conversão**.
    
      
    
- **Itu:** Processo estagnado aguardando contratação de servidores em nuvem por parte do cliente, sem resposta aos contactos.
    
      
    
- **Olímpia e Araras:** Demandas suspensas dependendo de alinhamento comercial e contato telefónico direto com os responsáveis.
    
      
    

## ✅ Decisões Tomadas & Conclusões

- **Diretriz de Dados Siplan vs. Terceiros:** Adotou-se o compromisso de aprimorar progressivamente os motores para máxima qualidade de dados em migrações internas (**Control-M** ou **Siplan PRO** para família **ORION**), mantendo a régua de alterações mínimas necessárias para sistemas de outros fornecedores.
    
      
    
- **Alocação em Sorocaba:** O consultor Vieira permanecerá no suporte presencial em Sorocaba de segunda a quarta-feira, retornando quinta e sexta-feira para os trabalhos do 26º Tabelião de Notas. O acompanhamento posterior será absorvido pela área de **Pós-Implantação**.
    
      
    
- **Escopo e Prazos de Embu das Artes:** Manutenção das regras de conversão atuais para viabilizar o cronograma geral e garantir a entrega tempestiva do 26º Tabelião de Notas.
    
      
    
- **Diretriz Técnica de Restauração de Bases:** Vetado terminantemente o uso de clientes gráficos genéricos (DBeaver) em rotinas de backup e restore, oficializando o uso de scripts em lote (.bat) ou linha de comando direta em **PostgreSQL** e **Docker**.
    
      
    
- **Processo de Comunicação de Implantação:** A equipa de **Conversão** será incluída formalmente nas notificações oficiais de agendamento de implantação e hospedagem para evitar descompassos de calendário.
    
      
    

## 🚀 Próximos Passos & Pendências (Action Items)

|**Status**|**Ação / Pendência Técnica**|**Responsável**|**Prazo**|
|---|---|---|---|
|[ ]|Executar cargas de **Termo de Comparecimento**, **Minuta** e documentos em Sorocaba|Luciane Lima|27/09/2026|
|[ ]|Concluir vinculação de imagens e liberar base de Praia Grande para **Homologação**|Luciane Lima|25/09/2026|
|[ ]|Consolidar pendências, processar nova base do 26º Tabelião de Notas e liberar para Vieira|Luciane Lima|01/10/2026|
|[ ]|Reorganizar recursos de memória/CPU nas máquinas virtuais de **Homologação** do **ORION TN**|Hugo Santariosi|25/09/2026|
|[ ]|Validar relações de tabelas com Breno e acompanhar **Virada para Produção** em Mirandópolis|Hugo Santariosi|25/09/2026|
|[ ]|Conectar na infraestrutura de Carapicuíba e recolher base para início dos trabalhos|Hugo Santariosi|28/09/2026|
|[ ]|Converter e transferir repositório de imagens de Embu das Artes via **ORION GED** para **ORION PRO**|Ademar Souza|25/09/2026|
|[ ]|Gerar ficheiros CSV e disponibilizar base de **Homologação** de Guarulhos para **Mizuno**|Ademar Souza|28/09/2026|
|[ ]|Realizar correção do título suspenso diretamente na base de dados de Mogi Mirim|Ademar Souza|25/09/2026|
|[ ]|Executar a **Virada para Produção** noturna do 3º Cartório de Taubaté|Ademar Souza|29/09/2026|
|[ ]|Elaborar comunicado e roteiro de boas práticas para restauração via linha de comando|Ademar Souza|02/10/2026|
|[ ]|Formalizar entrada de Araraquara na fila de **Conversão** para coleta de termo e dados|Marcus Ortiz|25/09/2026|
|[ ]|Alinhar com Maria a inclusão da equipa de conversão nos comunicados formais de agendamento|Marcus Ortiz|25/09/2026|
|[ ]|Cobrar posicionamento comercial junto de **Macan** referente aos cartórios de Itu e Olímpia|Marcus Ortiz|25/09/2026|
|[ ]|Alinhar com o consultor **Brites** as precauções para envio de dumps em versões atualizadas|Marcos Ortiz|28/09/2026|

## 📌 Destaques & Riscos Críticos

- ⚠️ **Estouro de Cronograma no 26º Tabelião de Notas:** Qualquer retrabalho excessivo em bases paralelas comprometerá a janela de homologação prévia de Vieira, colocando em risco o go-live fixado para 05/10/2026.
    
      
    
- ⚠️ **Inconsistência Relacional por Ferramentas de BD Inadequadas:** A execução de restaurações de base através do DBeaver gera omissão silenciosa de triggers e índices, causando falhas graves na subida dos sistemas em clientes finais.
    
      
    
- ⚠️ **Falhas Críticas em Modelos de OCR e Inteligência Artificial:** Extrações automatizadas com datas distorcidas (01/01/1900) e geração errónea de CPFs em matrículas de **Registro de Imóveis** apresentam alto risco de passivo jurídico.
    
      
    

## 👥 Resumo de Ações por Participante

### 👤 Luciane Lima

- **Relato & Validações:**
    
      
    - Concluiu o processamento massivo de mais de 3 milhões de registos de serviços realizados em Sorocaba.
        
          
        
    - Fomentou o alinhamento sobre critérios de saneamento de dados com base na análise de Embu das Artes.
        
          
        
    - Estruturou a agenda necessária para disponibilizar a base do 26º Tabelião de Notas para homologação.
        
          
        
- **Pendências Assumidas (A Fazer):**
    
      
    - [ ] Subir as cargas de **Termo de Comparecimento**, **Minuta** e documentos de Sorocaba no fim de semana.
        
          
        
    - [ ] Finalizar o tratamento de imagens e disponibilizar Praia Grande para homologação de Vieira.
        
          
        
    - [ ] Consolidar alterações e processar base do 26º Tabelião de Notas até quarta-feira.
        
          
        

### 👤 Hugo Santariosi

- **Relato & Validações:**
    
      
    - Concluiu a estruturação dos scripts de TIFF e importação para a virada de Mirandópolis.
        
          
        
    - Realizou purge noturno e script corretivo para retificar atos com data de 1900 em São Caetano do Sul.
        
          
        
    - Reportou ausência de dados em Valinhos e iniciou análise da base Dominicart de Franca no DevOps.
        
          
        
- **Pendências Assumidas (A Fazer):**
    
      
    - [ ] Remanejar alocação de hardware e contentores nas máquinas de **Homologação** do **ORION TN**.
        
          
        
    - [ ] Finalizar a **Virada para Produção** do **WebRI** em Mirandópolis.
        
          
        
    - [ ] Iniciar a recolha e avaliação da base de Carapicuíba na segunda-feira com Breno.
        
          
        

### 👤 Ademar Souza

- **Relato & Validações:**
    
      
    - Conduziu a virada técnica de protesto em Embu das Artes contornando falhas causadas por dump desatualizado.
        
          
        
    - Concluiu a migração de 400.000 imagens de Bragança Paulista e abriu PBI para suporte a ficheiros P7S.
        
          
        
    - Obteve termo assinado e iniciou extração de CSVs do 1º Protesto de Guarulhos.
        
          
        
    - Formalizou aviso de ausência programada e inadiável para o dia 23/10/2026.
        
          
        
- **Pendências Assumidas (A Fazer):**
    
      
    - [ ] Efetuar a conversão e transporte das imagens de Embu das Artes para o **ORION PRO**.
        
          
        
    - [ ] Liberar base de **Homologação** de Guarulhos para o consultor **Mizuno**.
        
          
        
    - [ ] Corrigir o estado do protocolo indevidamente protestado na base de Mogi Mirim.
        
          
        
    - [ ] Realizar a **Virada para Produção** noturna do 3º Cartório de Taubaté na terça-feira.
        
          
        
    - [ ] Redigir manual técnico orientando procedimentos de backup/restore por linha de comando.
        
          
        

### 👤 Marcus Vinicius Ortiz

- **Relato & Validações:**
    
      
    - Confirmou o destravamento e a homologação sem ressalvas do 3º Cartório de Taubaté para início em campo.
        
          
        
    - Detalhou o status de infraestrutura dos projetos de Araraquara, Itu, Olímpia e Araras.
        
          
        
    - Comunicou entrada em período de férias a partir de 28/09/2026.
        
          
        
- **Pendências Assumidas (A Fazer):**
    
      
    - [ ] Abrir chamado técnico no sistema e incluir Araraquara na fila de **Conversão**.
        
          
        
    - [ ] Solicitar à coordenação a inclusão formal do time de conversão nos avisos de hospedagem e datas.
        
          
        
    - [ ] Solicitar a **Macan** atualização das negociações sobre Itu, Olímpia e Araras.
        
          
        

### 👤 Erik Marques (Participação Pontual)

- **Relato & Validações:**
    
      
    - Conduziu auditoria aprofundada comparando bases migradas e layouts oficiais de produto.
        
          
        
    - Evidenciou gargalos e inconsistências nos motores vigentes para subsidiar a melhoria de diretrizes.
        
          
        
- **Pendências Atribuídas (A Fazer):**
    
      
    - [ ] Dar continuidade à homologação técnica das bases respeitando os acordos de escopo definidos.
        
          
        

### 👤 Marcos Ortiz

- **Relato & Validações:**
    
      
    - Arbitrou o equilíbrio entre esforço de saneamento de dados e cumprimento de prazos de implantação.
        
          
        
    - Alinhou o remanejamento parcial da escala do consultor Vieira entre Sorocaba e o 26º Tabelião de Notas.
        
          
        
- **Pendências Assumidas (A Fazer):**
    
      
    - [ ] Tratar com o consultor **Brites** a obrigatoriedade de conferência prévia da integridade de bases.