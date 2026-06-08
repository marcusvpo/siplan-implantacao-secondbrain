
---

# DOCUMENTO 1 — Análise de Aderência

## 1. Contexto e Estado Atual (Como É Hoje)
*   **Falta de Padronização:** O processo é executado de forma individualista, com cada analista (Bruno, Brites, Vieira, Júlio) utilizando seu próprio método, checklist e nível de profundidade. Isso gera desalinhamento e dificulta a transição de informações entre a análise e a implantação.
*   **Formatos Diversos:** Os checklists existem em diferentes formatos, como documentos Word (Vieira, Brites) e formulários HTML customizados enviados por link ao cliente (Júlio), sem um repositório centralizado e atualizado.
*   **Execução Mista:** A análise é feita remotamente, presencialmente ou em um modelo híbrido, dependendo do analista e da complexidade do cliente (se já é cliente Siplan ou não).
*   **Envolvimento do Cliente:** Em alguns casos, o checklist é enviado para o cliente preencher (self-service), o que gera preocupação sobre a perda de detalhes e a qualidade da informação. Em outros, o analista conduz uma entrevista (presencial ou remota) e preenche o documento.
*   **Mapeamento de Periféricos:** A análise de compatibilidade de periféricos (scanners, impressoras de balcão) é realizada nesta etapa, pois exige testes com o sistema Siplan.

## 2. Decisões Tomadas e Novo Processo (Como Será)
*   **Padronização do Checklist:** Os checklists de cada produto (**ORION TN**, **PRO**, **REG**, etc.) serão unificados em um template mestre. A versão do Vieira, considerada a mais completa e detalhada (com sistema de cores: verde, amarelo, vermelho), será usada como ponto de partida.
*   **Centralização no Siplan HUB:** Todos os formulários de análise de aderência serão criados e gerenciados dentro da plataforma Siplan HUB. Isso garantirá que todos os analistas usem sempre a versão mais recente e os resultados fiquem vinculados ao projeto.
*   **Definição de Execução Presencial:** Ficou convencionado que toda análise de aderência para **cartórios que não são clientes Siplan** (ou seja, usam sistemas de concorrentes como Argon, Holographics, Scriba) será, idealmente, **presencial**. Para clientes Siplan, a análise pode ser remota ou presencial, a critério.
*   **Questionário Prévio para o Comercial:** Será criado um formulário genérico e simplificado (via Hub ou Forms) para a equipe comercial enviar ao cliente no ato do fechamento. Este questionário coletará informações básicas de infraestrutura, organização (andares, setores) e perfil da equipe, preparando o terreno para a análise técnica detalhada.
*   **Inclusão de Perguntas Estruturais:** Serão adicionadas aos checklists perguntas sobre a estrutura física e organizacional do cartório (quantidade de andares, distribuição dos setores, perfil dos colaboradores, resistência à mudança), que antes eram coletadas de forma separada por Henrique.
*   **Manutenção do Checklist pelo Coordenador:** Marcus (eu) ficará responsável por atualizar o template mestre no Siplan HUB sempre que um analista identificar e comunicar a necessidade de um novo item de verificação.

## 3. Responsáveis e Papéis
*   **Analistas de Implantação (Vieira, Brites, Júlio, Bruno, etc.):** Responsáveis por executar a análise de aderência (presencial ou remotamente), preencher o formulário no Siplan HUB, identificar pontos de atenção (amarelo) e impeditivos (vermelho), e comunicar a necessidade de atualizações no checklist.
*   **Marcus (eu) (Coordenação):** Ponto focal para receber os resultados das análises, alimentar o Siplan HUB, direcionar os pontos impeditivos para as áreas responsáveis (Produtos, Conversão), e manter o checklist mestre atualizado na plataforma.
*   **Equipe Comercial (Macan, Elverton):** Responsável por enviar o novo questionário genérico ao cliente após a venda e alinhar as expectativas sobre o processo.
*   **Equipe de Produtos (Luan, Cleverson, Diego):** Recebe e analisa os pontos impeditivos levantados na análise para desenvolver funcionalidades necessárias antes da implantação.

## 4. Ferramentas, Sistemas e Integrações Mencionadas
*   **Siplan HUB:** Plataforma centralizadora que passará a hospedar os formulários de análise de aderência e os resultados de cada projeto.
*   **Checklist em Word:** Ferramenta legada utilizada pela maioria dos analistas, que será descontinuada em favor do HUB.
*   **Formulário HTML:** Ferramenta customizada desenvolvida por Júlio, que envia por link ao cliente, mas que será substituída pela solução padronizada no HUB.
*   **SharePoint:** Repositório atual dos templates de checklist, que será migrado para o HUB.
*   **Microsoft Forms / Google Forms:** Sugeridos como alternativa para criar formulários padronizados de maneira simples.
*   **Sistemas Legados Citados:** Argon, Holographics, Scriba, Viscom.
*   **Produtos Siplan Mencionados:** **ORION TN**, **ORION PRO**, **ORION REG**, **WebRI**, **Siplan PRO**, **Tabnot**.

## 5. Prazos, Pendências e Próximas Ações
*   **Ação Imediata:** Marcus (eu) irá desenvolver a funcionalidade de criação e gerenciamento de formulários no Siplan HUB.
*   **Pendência da Equipe:** Consolidar os diferentes checklists existentes (Vieira, Brites, Júlio) em um único template mestre para cada produto, incorporando as perguntas estruturais.
*   **Próxima Ação:** Definir e criar o formulário genérico a ser utilizado pela equipe comercial.
*   **Fluxo Futuro:** Qualquer nova implantação deverá ter sua análise de aderência registrada e gerenciada através do Siplan HUB.

## 6. Dores, Riscos e Exceções Discutidas
*   **Informações Incorretas:** Risco de o TI do cliente fornecer informações imprecisas ou superficiais para "não se queimar", o que pode levar a problemas na implantação.
*   **Perda de Detalhes:** O envio de checklists para o cliente preencher por conta própria pode fazer com que detalhes e nuances importantes ("o calor da pergunta") se percam, pois falta a interação e o aprofundamento do analista.
*   **Checklists Desatualizados:** A falta de um processo centralizado de atualização dos checklists resulta em analistas usando versões antigas, podendo deixar de verificar pontos críticos já mapeados por outros.
*   **Desconhecimento do Cliente:** O cliente, ao preencher o formulário, pode não entender termos técnicos ou não ter a visão completa de todos os setores para responder adequadamente.

## 7. Exemplos Práticos e Cartórios Citados
*   **26º Cartório (SP):** Necessidade de cálculo do dígito verificador para formulários de segurança (NFS). Inicialmente, o substituto considerou a demanda operacional e não impeditiva, mas após conversa com o responsável do setor (Darlan), que demonstrou a inviabilidade do processo manual (200 quebras de intervalo), o item foi classificado como impeditivo.
*   **Mogi das Cruzes:** Identificada a necessidade de integração com **CNAB 240** para o banco Santander, que o **ORION PRO** não suportava. A análise levantou o ponto, mas a área de Produtos falhou na interpretação inicial.
*   **Sorocaba:** Em análise presencial, foi detectada a incompatibilidade das impressoras de balcão (8 impressoras com impressão via DOS), que não funcionavam com o sistema Siplan, gerando "comandos em japonês". A detecção prévia evitou um prejuízo maior.
*   **São Vicente:** Cliente com sistema da Holographics.
*   **Praia Grande:** Cliente com sistema da Argon.

## 8. Divergências e Pontos em Aberto
*   **Formato de Execução:** A principal divergência foi sobre o método de coleta de dados:
    *   **Abordagem 1 (Júlio):** Enviar um formulário online (HTML) para o cliente preencher, ganhando agilidade, e depois fazer uma demonstração para validar os pontos.
    *   **Abordagem 2 (Maioria):** Conduzir uma entrevista (presencial ou remota) com o cliente, preenchendo o checklist em tempo real. A maioria dos analistas defende essa abordagem para garantir a qualidade da informação e captar detalhes que seriam perdidos no preenchimento autônomo.
*   **Ponto de Consenso Parcial:** A ideia de um questionário self-service foi considerada válida, mas apenas para perguntas genéricas e de fácil compreensão, a serem enviadas pelo comercial. A análise técnica aprofundada permaneceria como uma entrevista conduzida pelo analista de implantação.

---

# DOCUMENTO 2 — Análise de Infraestrutura

## 1. Contexto e Estado Atual (Como É Hoje)
*   **Execução Remota:** O processo é majoritariamente executado de forma remota pela equipe de infraestrutura (Alex Silva) ou pela equipe técnica de implantação (Bruno Fernandes, Hugo).
*   **Coleta de Dados:** A coleta é feita máquina a máquina, geralmente via TeamViewer, que fornece um resumo das configurações (CPU, memória, S.O., rede). Outras ferramentas como AnyDesk são usadas, mas consideradas menos detalhadas.
*   **Dependência do TI do Cliente:** Frequentemente, o analista depende do TI do cartório. Em alguns casos, o TI se recusa a conceder acesso e prefere ele mesmo preencher uma planilha com as informações, o que gera um risco de dados incorretos ou superficiais ("Ah, as máquinas são novas", "Core i5" sem especificar a geração).
*   **Escopo de Verificação:** O foco atual é em servidores e estações (processador, memória, disco, S.O.). A verificação de periféricos (impressoras, scanners) fica a cargo da Análise de Aderência. A verificação de rede (domínio, velocidade, antivírus, firewall) é feita, mas pode ser superficial se depender apenas da informação do TI.
*   **Falta de Confirmação:** Promessas de adequação feitas pelo cliente ("vou aumentar a memória", "vou comprar um servidor novo") não são sistematicamente verificadas antes do início da implantação presencial.

## 2. Decisões Tomadas e Novo Processo (Como Será)
*   **Exigência de Informações Detalhadas:** Quando o TI do cliente optar por fazer o levantamento, será exigido o preenchimento completo da planilha padrão da Siplan, com todas as especificações técnicas, não sendo mais aceitas respostas genéricas como "está tudo OK".
*   **Inclusão de Novos Itens no Checklist:** A planilha de análise de infraestrutura deverá incluir explicitamente:
    *   Verificação de **domínio** para sistemas com essa dependência (**WebRI**).
    *   Verificação se o ambiente será **local ou em nuvem**.
    *   Se em nuvem, verificar a existência de **link de internet redundante**.
*   **Confirmação Pré-Implantação:** Será instituída uma etapa **obrigatória** na semana anterior à implantação para validar com o cliente se todas as adequações de infraestrutura recomendadas foram de fato realizadas. Caso não tenham sido, a implantação pode ser adiada para evitar problemas.
*   **Comunicação dos Sistemas:** A equipe de análise de infraestrutura deve receber a lista completa de todos os produtos Siplan a serem implantados no projeto para dimensionar corretamente os recursos do servidor (Ex: **ORION TN** + **ORION PRO** + SGA). Isso será formalizado no trâmite do chamado no sistema de chamados.
*   **Dimensionamento de Disco:** A responsabilidade de avaliar o espaço em disco necessário para a **conversão** das imagens (que pode exigir o dobro do espaço atual) será articulada entre a equipe de infraestrutura e a equipe de conversão, com base no levantamento de imagens feito na Análise de Aderência.

## 3. Responsáveis e Papéis
*   **Equipe de Infra/Técnica de Implantação (Alex Silva, Bruno Fernandes, Hugo):** Executam a análise, preenchem o relatório, apontam inconformidades e, futuramente, farão a checagem pré-implantação.
*   **Analistas de Implantação (Mizuno, Vieira, etc.):** Sofrem o impacto direto de uma análise falha. Devem comunicar ao comercial e à coordenação quando identificam problemas em campo decorrentes de falhas de infraestrutura não resolvidas.
*   **TI do Cliente:** Frequentemente o interlocutor, responsável por fornecer acesso ou as informações das máquinas. Sua colaboração (ou a falta dela) é um fator crítico.
*   **Equipe Comercial:** Deve alinhar com o cliente a necessidade de liberar o acesso para a equipe da Siplan ou, alternativamente, o compromisso de preencher a planilha detalhada.
*   **Marcus (eu) (Coordenação):** Garante que o chamado para a análise contenha todos os sistemas a serem implantados.

## 4. Ferramentas, Sistemas e Integrações Mencionadas
*   **TeamViewer:** Ferramenta preferencial para a coleta remota de dados por fornecer um relatório detalhado das configurações.
*   **AnyDesk:** Ferramenta alternativa, porém considerada menos completa que o TeamViewer.
*   **Planilha de Análise de Infraestrutura:** Documento padrão (online) onde as configurações de cada máquina e servidor são registradas.
*   **Script de Coleta (sugestão da IA):** Foi mencionada a possibilidade de criar um script que o TI do cliente executaria para coletar e enviar as informações de hardware automaticamente, padronizando a coleta.

## 5. Prazos, Pendências e Próximas Ações
*   **Ação Contínua:** Adicionar ao checklist de infra os novos pontos definidos (domínio, nuvem, link redundante).
*   **Ação de Processo:** Implementar o gate de verificação na semana anterior a cada implantação para confirmar as adequações de infra.
*   **Ação de Comunicação:** Garantir que o trâmite dos chamados para a equipe de infra sempre liste todos os sistemas do projeto.

## 6. Dores, Riscos e Exceções Discutidas
*   **Promessas não Cumpridas:** O maior risco é o cliente prometer adequar a infraestrutura (e.g., aumentar memória) e não o fazer, resultando em lentidão, travamentos e instabilidade durante a implantação, com a culpa sendo erroneamente atribuída ao sistema Siplan.
*   **Servidor Inadequado:** Casos em que o cliente compra um servidor novo sem consultar a Siplan e o equipamento não atende aos requisitos, ou chega "na caixa" no dia da implantação.
*   **Ambiente em Nuvem Mal Configurado:** Risco de o cliente usar um servidor em nuvem com link de internet instável e sem redundância, causando quedas e lentidão no sistema.
*   **Falta de Retorno:** Dificuldade em obter retorno do TI do cartório, atrasando a análise.
*   **Dimensionamento Incorreto:** Não saber todos os sistemas a serem implantados (ex: esquecer o SGA) leva a um dimensionamento incorreto dos recursos do servidor.

## 7. Exemplos Práticos e Cartórios Citados
*   **Mogi das Cruzes e São Vicente:** Em ambos os casos, foi orientado que o cliente precisava fazer adequações de infra (aumentar memória/recursos do servidor). A orientação não foi seguida a tempo, e as implantações ocorreram com o sistema lento e travando. Em Mogi, o TI (Filipe) só fez o upgrade na sexta-feira, após a implantação já ter começado.
*   **Olímpia:** Análise de infraestrutura inicial falhou em detectar que o cartório não tinha domínio na rede, o que é um requisito para o **WebRI**. O problema foi identificado posteriormente, evitando um caos na data original da implantação.
*   **Guarulhos (3º):** Havia a expectativa de um servidor local, mas o TI do cliente provisionou um servidor em nuvem com link instável e sem redundância, causando intermitências e lentidão. O espaço em disco também era insuficiente para a conversão.
*   **Matão:** Caso antigo onde a falta de domínio na rede causou enormes dores de cabeça, exigindo uma solução de última hora do TI para criar um domínio para uma única máquina.
*   **Catanduva:** Exemplo positivo de cliente que já está rodando o sistema em nuvem com uma infraestrutura bem preparada pelo seu próprio TI, facilitando o trabalho da Siplan.

## 8. Divergências e Pontos em Aberto
*   Não houve divergências significativas nesta etapa. O consenso é que a análise precisa ser rigorosa e que as recomendações devem ser seguidas pelo cliente antes da implantação. O principal ponto em aberto é como garantir efetivamente que as adequações sejam feitas, sendo a proposta de "verificação na semana anterior" a solução definida.

---

# DOCUMENTO 3 — Conversão

## 1. Contexto e Estado Atual (Como É Hoje)
*   **Processo Remoto:** A coleta do banco de dados e imagens é feita remotamente pelos analistas de conversão (Luciane, Ademar, Du).
*   **Falta de Padronização no Ponto de Partida:** O processo para iniciar a conversão varia entre os produtos.
    *   **ORION PRO (Protesto):** A base que a conversão utiliza é "zerada", sem parametrizações essenciais como as tabelas de custas. Isso obriga o analista de implantação a gastar cerca de 2 horas em configurações manuais antes de poder homologar.
    *   **ORION TN (Notas):** A base zerada utilizada já vem com mais parâmetros e tabelas pré-configuradas, agilizando o processo.
*   **Mapeamento (De-Para):** A equipe de conversão é responsável por fazer o mapeamento do banco de dados de sistemas de terceiros (Scriba, Argon, Viscom, etc.). Isso funciona bem pois cada analista é especialista em uma área (Du em R.I., Ademar em Protesto, Luciane em Notas).
*   **Imagens:** A conversão de imagens, especialmente do **GED** de sistemas legados (**Control-M PRO**), é um grande ponto de dor. Muitas implantações de protesto foram concluídas sem a conversão das imagens, gerando um "rabo" (backlog) técnico significativo. Em R.I. e Notas, o processo parece mais maduro, embora também sujeito a problemas de falta de espaço em disco.
*   **Catálogo de Conversão:** Existe um documento formal ("Formalização da Migração de Dados") que detalha o que será e o que não será convertido. No entanto, seu uso não é padronizado. O Vieira o utiliza para alinhar expectativas com o cliente antecipadamente, mas outros analistas não o fazem ou o utilizam de forma diferente.

## 2. Decisões Tomadas e Novo Processo (Como Será)
*   **Padronização do Catálogo de Conversão:** O uso do documento "Formalização da Migração de Dados" se tornará **obrigatório** em todas as implantações, para todos os produtos. Ele deve ser enviado ao cliente antes da implantação para alinhar expectativas sobre o que será ou não migrado (ex: livro caixa, logs, contas de mensalistas).
*   **Geração de Relatório de Quantidades:** A equipe de conversão deverá gerar um relatório/resumo com as quantidades de registros na origem e no destino (ex: "convertidos 200 mil de 210 mil nomes"). Isso dará mais transparência e segurança tanto para a equipe de implantação (na homologação) quanto para o cliente.
*   **Levantamento de Imagens na Aderência:** Ficou definido que na etapa de **Análise de Aderência**, o analista de implantação deverá mapear todas as pastas de imagens que o cliente utiliza (inclusive as do **GED**) e estimar o volume total (em GB).
*   **Resolução do Backlog de Imagens:** É preciso criar ou finalizar os motores de conversão para as imagens do **GED** do **Control-M PRO** (Protesto) e outros legados, para eliminar o backlog de implantações sem imagens convertidas.
*   **Base Parametrizada para Protesto:** Será ajustado o processo para que a base de dados utilizada na conversão do **ORION PRO** já venha pré-parametrizada (pelo menos com as tabelas de custas), assim como já ocorre com o **ORION TN**, economizando tempo do analista na homologação.

## 3. Responsáveis e Papéis
*   **Equipe de Conversão (Luciane, Ademar, Du):** Responsáveis por executar a extração, conversão, mapeamento de-para, e, futuramente, gerar o relatório de quantidades e realizar uma pré-homologação interna.
*   **Analistas de Implantação (Brites, Vieira, etc.):** Responsáveis por, na Análise de Aderência, levantar o volume de imagens. Devem utilizar o Catálogo de Conversão para alinhar com o cliente e, no caso do **ORION PRO**, preparar uma base pré-configurada para a conversão.
*   **Marcus (eu) (Coordenação):** Solicitará à equipe de conversão a criação do template de relatório de quantidades e padronizará o uso do Catálogo de Conversão.

## 4. Ferramentas, Sistemas e Integrações Mencionadas
*   **Motores de Conversão:** Scripts e programas utilizados para transformar os dados do sistema legado para o padrão **ORION**.
*   **PostgreSQL:** Banco de dados de destino dos sistemas **ORION**.
*   **Catálogo de Conversão ("Formalização da Migração de Dados"):** Documento Word para alinhar escopo da migração.
*   **Siplan ORION GED:** Sistema de gerenciamento eletrônico de documentos, para onde as imagens são migradas.
*   **Sistemas Legados:** **Control-M PRO** (Protesto), **Tabnot**, **Scriba**, **Viscom**.

## 5. Prazos, Pendências e Próximas Ações
*   **Pendência Crítica:** Criar/finalizar o motor de conversão para imagens do **GED** de protesto.
*   **Ação Imediata (Conversão):** Ademar irá refazer os motores de protesto em uma nova linguagem, com a intenção de incluir a conversão de imagens.
*   **Ação Imediata (Implantação):** Criar e padronizar o template do Catálogo de Conversão para todos os produtos e iniciar seu uso obrigatório.
*   **Próxima Ação:** Equipe de conversão deve desenvolver um método para gerar o relatório de batimento de quantidades (origem vs. destino).

## 6. Dores, Riscos e Exceções Discutidas
*   **Espaço em Disco para Imagens:** A principal dor técnica. O processo de conversão de imagens (TIF para PDF) e importação para o **Docker** (em Linux) exige temporariamente o **dobro** do espaço de armazenamento das imagens originais. Isso frequentemente causa problemas e atrasos.
*   **Backlog Técnico:** Existe um grande volume de implantações passadas (principalmente de protesto) que estão sem as imagens do **GED** convertidas, criando um passivo para a empresa.
*   **Desalinhamento de Expectativas:** A falta do uso padronizado do Catálogo de Conversão gera atrito com o cliente, que descobre tardiamente que certos dados (livro caixa, logs) não serão migrados.
*   **Perda de Dados Silenciosa:** O fato de um motor de conversão rodar sem erros não garante que 100% dos dados foram trazidos. Registros "órfãos" ou com inconsistências na base de origem podem ser perdidos sem que ninguém perceba, gerando riscos legais futuros para o cliente.

## 7. Exemplos Práticos e Cartórios Citados
*   **Olímpia:** Cliente extremamente intransigente que exigiu a conversão de itens que normalmente não são migrados, como **log do sistema e livro caixa**, ameaçando abortar o projeto. A situação forçou uma reavaliação e esforço extra da Siplan.
*   **São Vicente:** Durante a conversão, Luciane identificou que de 7 mil nomes, 2 mil não estavam sendo convertidos por serem "órfãos" (sem vínculo a protocolos). Ela precisou criar um protocolo fictício para conseguir migrá-los, demonstrando a importância da análise detalhada.
*   **Americana:** Exemplo de como o mapeamento de imagens pode falhar. As imagens foram inicialmente vinculadas pelo número de registro, quando o correto seria pelo número do protocolo, exigindo um retrabalho na importação.
*   **Franca (Protesto):** A conversão da Viscom (concorrente) foi a primeira, feita do zero. Durante a implantação, a falta de algumas informações no banco convertido impediu a geração de selos e listagens, exigindo ajustes emergenciais.

## 8. Divergências e Pontos em Aberto
*   **Quem deve estimar o espaço de disco?** A equipe de infra faz uma análise preliminar, mas a equipe de conversão tem a visão real após analisar o banco. A solução foi delegar o levantamento do volume de imagens para a Análise de Aderência, para que a necessidade de espaço possa ser calculada e comunicada ao cliente com antecedência.
*   **Duração da Conversão:** O tempo varia drasticamente. Conversões do **ORION REG** podem levar de 6 a mais de 48 horas, dependendo do volume. A do indicador pessoal de Olímpia levou 12-13 horas. Isso impacta o cronograma da "virada" no fim de semana.

---

# DOCUMENTO 4 — Homologação

## 1. Contexto e Estado Atual (Como É Hoje)
*   **Processos Variados:** A metodologia de homologação não é padronizada e varia significativamente entre os analistas.
    *   **Vieira:** Utiliza uma abordagem mais detalhada e demorada, especialmente para sistemas de concorrentes. Ele se baseia nos **layouts de conversão** (documentos que especificam cada campo a ser migrado) e usa scripts SQL para buscar registros com variações específicas na base de origem, garantindo a cobertura de casos de borda.
    *   **Brites, Mizuno, Júlio:** Utilizam uma abordagem mais ágil e focada no fluxo do sistema. Eles fazem a validação por amostragem, muitas vezes envolvendo o cliente para apontar onde as informações estão no sistema antigo ("tela a tela"). Focam em validar se os principais processos (recepção, contraditório, registro) funcionam com os dados convertidos.
*   **Falta de Checklist:** Não existe um checklist ou roteiro formal para a homologação. O processo é guiado pelo "feeling", pela experiência do analista ou, no caso do Vieira, pelos layouts de conversão.
*   **Prazos Apertados:** Frequentemente, a base para homologação é liberada muito perto da data de implantação (ex: na quinta-feira para uma implantação na segunda), forçando o analista a fazer a homologação no final de semana ou de forma corrida. Em alguns casos, a homologação ocorre durante a primeira semana de implantação, junto com outras atividades.
*   **Comunicação de Ajustes:** A comunicação dos ajustes necessários para a equipe de conversão é informal, feita via Word, TXT, e-mail ou Teams. Júlio desenvolveu uma pequena aplicação para formalizar seus próprios apontamentos.

## 2. Decisões Tomadas e Novo Processo (Como Será)
*   **Criação de Checklist Padrão:** Será criado um **checklist de homologação** padronizado para cada produto, a ser hospedado no **Siplan HUB**. O objetivo é garantir que todos os analistas verifiquem um conjunto mínimo de itens e variações, nivelando a qualidade do processo.
*   **Pré-Homologação pela Equipe de Conversão:** A equipe de conversão passará a realizar uma **pré-homologação** mais aprofundada. Eles deverão validar campo a campo, com base nos layouts, e verificar a integridade da migração (usando o relatório de quantidades a ser criado), entregando uma base com maior garantia de qualidade.
*   **Envolvimento de Especialistas Internos:** Será avaliada a possibilidade de alocar um recurso interno (como o Eric Marques para **ORION TN**) para apoiar ou executar as homologações, liberando os analistas de campo. No entanto, isso é uma solução de médio/longo prazo.
*   **Foco da Homologação do Analista:** Com a pré-homologação da conversão, o analista de implantação poderá focar em validar os **fluxos de trabalho** com os dados convertidos, simulando a operação do dia a dia, em vez de uma verificação exaustiva campo a campo.

## 3. Responsáveis e Papéis
*   **Analistas de Implantação (Vieira, Brites, Júlio, etc.):** Atualmente executam a homologação. Com o novo processo, focarão na validação dos fluxos. Serão responsáveis por criar o primeiro rascunho do checklist de homologação.
*   **Equipe de Conversão (Du, Luciane, Ademar):** Responsáveis por executar a conversão e, futuramente, por realizar a pré-homologação detalhada (campo a campo e quantitativa).
*   **Marcus (eu) (Coordenação):** Responsável por alinhar com a equipe de conversão a nova responsabilidade de pré-homologação e implementar os checklists no Siplan HUB.
*   **Eric Marques (a ser avaliado):** Potencial recurso para assumir as homologações do **ORION TN** no futuro.

## 4. Ferramentas, Sistemas e Integrações Mencionadas
*   **SQL (Scripts):** Usado por Vieira para fazer buscas detalhadas e encontrar variações de dados na base de origem.
*   **Layouts de Conversão:** Documentos técnicos que servem como guia para o que deve ser migrado, usados por Vieira como um checklist implícito.
*   **Siplan HUB:** Plataforma onde o futuro checklist de homologação será hospedado.
*   **Aplicação do Júlio:** Ferramenta interna simples para comunicar os ajustes necessários à equipe de conversão.

## 5. Prazos, Pendências e Próximas Ações
*   **Pendência:** Criar os checklists de homologação para cada produto, a partir da experiência dos analistas.
*   **Próxima Ação:** Marcus (eu) irá alinhar com a equipe de Conversão a viabilidade e o processo da nova etapa de pré-homologação.
*   **Ação de Melhoria:** Avaliar a contratação ou alocação de pessoal (Eric Marques) para se especializar na homologação.

## 6. Dores, Riscos e Exceções Discutidas
*   **Qualidade vs. Agilidade:** O principal dilema. Uma homologação detalhada (estilo Vieira) é demorada, mas segura. Uma homologação ágil (focada no fluxo) é rápida, mas corre o risco de deixar passar problemas de dados em casos de borda.
*   **Problemas em Produção:** Mesmo com a homologação, problemas ainda são encontrados em produção, especialmente em rotinas que dependem de comunicação externa (ex: com a **CRA/CENPROT** ou bancos), pois não podem ser totalmente testadas em ambiente de homologação.
*   **Perda de Ajustes no Motor de Conversão:** Ajustes feitos em uma conversão específica (via script de update) podem não ser incorporados ao motor de conversão principal. Com isso, o mesmo erro pode reaparecer em implantações futuras do mesmo sistema legado, como ocorreu com o cadastro de ficha em Guarulhos.
*   **Homologação em Campo:** Fazer a homologação durante a semana de implantação consome tempo precioso que deveria ser usado para treinamento e preparação do ambiente, gerando uma percepção negativa para o cliente.

## 7. Exemplos Práticos e Cartórios Citados
*   **Franca (Protesto):** Problemas na conversão que não foram pegos na homologação (ou a homologação foi corrida) impediram o envio de arquivos de retorno para a Serasa, exigindo a criação de um script de correção pós-implantação.
*   **Guarulhos (Notas):** Um ajuste no cadastro de ficha (para lidar com fichas sem tipo de documento) que havia sido corrigido em conversões antigas se perdeu no motor atual. O problema só foi descoberto em produção porque a homologação foi muito rápida devido ao cronograma apertado.
*   **Bragança Paulista:** Após a virada, foi identificado que o excedente de protocolo não foi convertido, embora estivesse presente na base de homologação. Exigiu um ajuste rápido da equipe de conversão.
*   **Sumaré:** Exemplo de onde a conversão dos termos de comparecimento veio com campos "sujos" ou com padronização incorreta, embora já fosse um problema conhecido e discutido anteriormente.

## 8. Divergências e Pontos em Aberto
*   **Metodologia de Homologação:** A principal divergência é entre a abordagem **bottom-up** (verificação detalhada de dados campo a campo, baseada nos layouts) e a abordagem **top-down** (validação dos principais fluxos de trabalho, baseada no uso prático do sistema).
*   **Solução em Aberto:** Como equilibrar a necessidade de uma homologação de qualidade com a agilidade exigida pelos cronogramas de implantação? A proposta de dividir a responsabilidade (pré-homologação detalhada pela conversão e homologação de fluxo pelo analista) é a principal aposta, mas sua implementação ainda precisa ser detalhada.

---

# DOCUMENTO 5 — Instalação do Sistema e Configuração de Ambiente

## 1. Contexto e Estado Atual (Como É Hoje)
*   **Execução Remota por Equipe Especializada:** A instalação do ambiente do servidor (**VM** Linux, **Docker**, banco de dados) é feita remotamente pela equipe de infraestrutura (Alex Silva) ou pela equipe técnica de implantação (Bruno Fernandes, Hugo).
*   **Instalação nas Estações pelo Analista:** A instalação nas estações de trabalho (atalhos, integrador, drivers de periféricos) é, na maioria dos casos, feita pelo analista de implantação quando ele chega no cartório.
*   **Processo Rápido, mas Volumoso:** A instalação em cada estação é rápida (cerca de 2 minutos por máquina), mas o tempo total depende do número de máquinas e de restrições de TI (ex: necessidade de um técnico local digitar senhas de administrador em cada máquina).
*   **Dependência da Análise de Infra:** O sucesso da instalação depende diretamente da qualidade da análise de infraestrutura. Dimensionamento incorreto de recursos (memória, CPU, disco) causa problemas nesta etapa.
*   **Comunicação de Acessos:** Após a instalação no servidor, os dados de acesso (IP, usuários, senhas) são formalmente enviados por e-mail ao analista responsável pela implantação.

## 2. Decisões Tomadas e Novo Processo (Como Será)
*   **Antecipação das Atividades:** A principal decisão é buscar formas de **antecipar** as atividades que hoje são feitas em campo, transferindo-as para a equipe de backoffice (Bruno Fernandes, Hugo) ou para uma futura equipe "júnior".
    *   **Proposta:** Que a instalação do **integrador** e configuração dos atalhos em todas as estações seja feita **antes** da chegada do analista de implantação ao cartório.
*   **Ferramenta de Automação:** A equipe aguarda a apresentação da nova ferramenta de Kleverson e Diego, que promete automatizar parte do processo de instalação e configuração do ambiente, potencialmente reduzindo o trabalho manual.

## 3. Responsáveis e Papéis
*   **Equipe de Infra/Técnica (Alex Silva, Bruno Fernandes, Hugo):** Responsáveis pela instalação e configuração do ambiente no servidor (criação de **VM**, instalação do Linux, **Docker**, etc.).
*   **Analistas de Implantação (em campo):** Atualmente responsáveis pela instalação do sistema (integrador, atalhos) nas estações de trabalho, uma tarefa que se busca transferir para a equipe de backoffice.
*   **Kleverson e Diego (Desenvolvimento):** Estão desenvolvendo uma ferramenta para automatizar a criação de instalações e bases de dados.

## 4. Ferramentas, Sistemas e Integrações Mencionadas
*   **Linux:** Sistema operacional padrão para as **VMs** nos servidores.
*   **Docker:** Tecnologia de containerização utilizada para rodar os sistemas Siplan no servidor.
*   **VM (Máquina Virtual):** Utilizada para isolar o ambiente do sistema Siplan no servidor do cliente.
*   **Integrador Siplan:** Componente essencial que precisa ser instalado nas estações para comunicação com periféricos (scanners, impressoras) e execução de certas funcionalidades.
*   **Siplan On-Field:** Ferramenta mencionada em associação ao SGA e painéis.

## 5. Prazos, Pendências e Próximas Ações
*   **Ação:** Aguardar a apresentação da nova ferramenta de automação de ambientes por Kleverson e Diego para avaliar como ela impactará e otimizará o processo de instalação.
*   **Pendência Estratégica:** Definir e estruturar o processo para que a instalação nas estações de trabalho seja feita remotamente pela equipe de backoffice antes da implantação presencial.

## 6. Dores, Riscos e Exceções Discutidas
*   **Tempo Consumido em Campo:** A principal dor é o tempo que o analista de implantação gasta em campo com tarefas de instalação que não agregam valor direto ao treinamento do cliente. Em um cartório grande, isso pode consumir quase um dia inteiro.
*   **Políticas de Segurança do Cliente:** Políticas de TI restritivas que exigem a presença de um técnico local para digitar senhas de administrador em cada máquina atrasam o processo de instalação nas estações.
*   **Dependência de Componentes não Instalados:** Em alguns casos, componentes essenciais como o serviço do **CRA/CENPROT** não são instalados por padrão, e essa falha só é descoberta no **Pós-Implantação**, gerando retrabalho e insatisfação.
*   **Falta de Manuais:** Foi relatado que a falta de manuais de instalação e migração de componentes (como **Selo** Digital para Linux) pode dificultar a resolução de problemas, forçando o acionamento de especialistas.

## 7. Exemplos Práticos e Cartórios Citados
*   **Olímpia:** Um único arquivo `composer` do **Docker** foi trocado para resolver um problema específico de instalação do **ORION REG**.
*   **São Vicente:** Um exemplo complexo onde a integração do **Brites** com o **ORION** exigiu que ambos rodassem na mesma máquina (**Docker** Desktop no Windows), devido a uma limitação do navegador em chamadas entre IPs diferentes, forçando uma configuração de ambiente não-padrão.

## 8. Divergências e Pontos em Aberto
*   Não foram discutidas divergências diretas sobre o processo de instalação em si. O ponto principal é o consenso de que essa atividade, especialmente nas estações, deve ser deslocada do cronograma presencial para otimizar o tempo do analista em campo. O "como" fazer isso de forma eficiente ainda está em aberto, aguardando a apresentação da nova ferramenta e a estruturação da equipe de backoffice.

---

# DOCUMENTO 6 — Parametrização/Configurações dos Sistemas

## 1. Contexto e Estado Atual (Como É Hoje)
*   **Atividade Manual e Repetitiva:** Grande parte da parametrização dos sistemas (**ORION PRO**, **ORION TN**, etc.) é feita manualmente pelo analista de implantação em cada novo projeto.
*   **Repetição de Parâmetros:** Muitos parâmetros são idênticos entre os cartórios (ex: otimização de telas, configurações de segurança). O analista acaba fazendo um "Ctrl C + Ctrl V" de relatórios de um cartório para o outro, pois as configurações são as mesmas.
*   **Dependência do CNS:** A principal barreira para reutilizar uma base já parametrizada é que muitas configurações estão amarradas ao CNS (Cadastro Nacional de Serventias), que funciona como chave primária em diversas tabelas. Mudar o CNS exige reconfigurar tudo.
*   **Tempo Consumido em Campo:** Essa etapa consome um tempo significativo do analista em campo (estimado em 4 a 5 horas, ou até um dia inteiro), tempo que poderia ser dedicado ao treinamento e acompanhamento.
*   **Esforço Desperdiçado:** O analista precisa popular uma base zerada para testar configurações (como layouts de impressão) e depois descartar essa base, tendo que refazer as parametrizações na base final convertida.

## 2. Decisões Tomadas e Novo Processo (Como Será)
*   **Discussão Adiada:** A equipe decidiu **adiar a discussão aprofundada** sobre o novo processo de parametrização para após a apresentação da nova ferramenta de automação de ambientes de Kleverson e Diego.
*   **Expectativa sobre a Ferramenta:** A expectativa é que a nova ferramenta possa resolver grande parte dessas dores, permitindo criar bases de dados já com parâmetros pré-configurados, desvinculados do CNS ou permitindo sua fácil alteração.
*   **Levantamento de Parâmetros Padrão:** Já existe um levantamento (feito em reuniões anteriores) de parâmetros que poderiam vir prontos na base padrão do **ORION TN**, mas nem tudo foi implementado. Esse levantamento será revisitado.
*   **Exportação/Importação de Configurações:** Foi levantada a necessidade crítica de poder exportar e importar configurações, como layouts de etiqueta e tipos de documentos internos, para evitar o retrabalho de copiar e colar via TXT.

## 3. Responsáveis e Papéis
*   **Analistas de Implantação:** Atualmente executam a parametrização manual em campo. São a principal fonte de informação sobre quais parâmetros podem ser padronizados.
*   **Kleverson e Diego (Desenvolvimento):** Responsáveis pela nova ferramenta que pode automatizar e padronizar a parametrização.
*   **Equipe de Produtos:** Responsável por incorporar os parâmetros padrão nas bases "zeradas" dos sistemas.

## 4. Ferramentas, Sistemas e Integrações Mencionadas
*   **Nova Ferramenta de Automação (sem nome):** A ser apresentada por Kleverson e Diego, com a promessa de facilitar a criação de ambientes e bases já configuradas.
*   **JSON / TXT:** Formatos mencionados como possíveis para exportação de configurações (proposta de Vieira para o Luan).

## 5. Prazos, Pendências e Próximas Ações
*   **Próxima Ação:** Participar da apresentação de Kleverson e Diego para entender as capacidades da nova ferramenta e como ela se encaixa no processo de parametrização.
*   **Pendência (Produtos):** Implementar a funcionalidade de exportar/importar layouts e outras configurações para facilitar a migração entre bases (de homologação para produção).
*   **Pendência (Implantação/Produtos):** Revisar e completar a implementação dos parâmetros padrão na base zerada do **ORION TN** e estender o conceito para o **ORION PRO** e outros sistemas.

## 6. Dores, Riscos e Exceções Discutidas
*   **Gasto de Tempo Precioso:** A principal dor é o consumo de horas valiosas do analista em campo com uma tarefa repetitiva e de baixo valor percebido pelo cliente.
*   **Retrabalho:** A necessidade de configurar uma base para testes e depois reconfigurar a base de produção é um grande ponto de retrabalho e ineficiência.
*   **Perda de Produtividade:** Um analista dedicado por um dia a parametrizar o sistema não está treinando ou acompanhando usuários, o que atrasa a implantação e impacta a percepção de valor do cliente.
*   **Risco de Esquecimento (se pré-configurado):** Uma preocupação levantada foi que, se os parâmetros vierem pré-configurados, o analista pode se acostumar e esquecer de validar ou ajustar uma configuração específica para um cartório que é uma exceção, causando problemas em produção.

## 7. Exemplos Práticos e Cartórios Citados
*   **Guarulhos e São Vicente:** Citados como exemplos onde as mesmas configurações de parâmetros foram repetidas, mudando apenas o CNS.
*   **Padrão entre Cartórios:** Foi citado que configurações como "otimizar telas" são aplicadas em 80% dos cartórios e poderiam vir como padrão.
*   **Parâmetros Genéricos Inúteis:** Foram mencionadas configurações genéricas que foram adicionadas à base padrão (como "centímetros genéricas") que não são utilizadas na prática e poderiam ser limpas para simplificar o processo.

## 8. Divergências e Pontos em Aberto
*   **Configuração Padrão vs. Risco de Esquecimento**: Houve um breve debate sobre o risco de ter parâmetros pré-configurados.
    *   **Visão 1 (Pró-Padrão):** É melhor ter 80% do trabalho feito e o analista ajustar os 20% restantes, ganhando muito tempo.
    *   **Visão 2 (Cautela):** O analista pode se acostumar com o padrão e esquecer de ajustar uma exceção, o que poderia causar problemas. deixar o campo zerado força o analista a configurar e pensar sobre ele.
*   **Ponto em Aberto:** A solução definitiva para a otimização da parametrização está dependente do que a nova ferramenta de Kleverson e Diego irá oferecer.

---

# DOCUMENTO 7 — Treinamento

## 1. Contexto e Estado Atual (Como É Hoje)
*   **Metodologia não Padronizada:** Cada analista tem seu próprio método e roteiro de treinamento. Alguns fazem sessões em grupo ("enfia todo mundo na sala"), outros preferem abordagens individuais ou por setor, dependendo da dinâmica do cartório.
*   **Falta de Checklist/Roteiro:** Não há um roteiro de treinamento formal e padronizado, o que leva a variações no conteúdo e na sequência do que é ensinado. O processo é guiado pelo fluxo do sistema e pela experiência do analista.
*   **Baixa Adesão aos Vídeos:** Embora existam vídeos de treinamento na plataforma **Siplan Skills**, a adesão dos usuários é baixa. A maioria relata que "começou, mas não terminou" e não há um processo de cobrança ou acompanhamento para incentivar o uso. A disponibilização dos vídeos é feita de forma "solta", sem um compromisso formal do cliente.
*   **Documento de Formalização:** Existe um "Formulário de Formalização de Treinamento", que serve tanto como comprovante de que o treinamento foi ministrado quanto como um checklist de tópicos. No entanto, seu uso não é 100% consistente (ex: foi esquecido em Franca).
*   **Treinamento vs. Acompanhamento:** O processo de treinamento se mistura com o acompanhamento pós-virada. Muitas vezes, o aprendizado real do usuário ocorre apenas quando ele precisa usar o sistema "para valer" em produção.
*   **Gestão de Pessoas e Resistência:** O sucesso do treinamento é altamente impactado pelo fator humano. Usuários resistentes, com má vontade, ou com dificuldades de aprendizado representam um grande desafio. O envolvimento do titular do cartório em "chamar na chincha" os funcionários resistentes é um fator decisivo para o sucesso.

## 2. Decisões Tomadas e Novo Processo (Como Será)
*   **Criação de Roteiro de Treinamento Padrão:** Será criado um roteiro de treinamento padronizado para cada produto, detalhando os tópicos por setor e fluxo. Este roteiro servirá como base para o "Formulário de Formalização" e para guiar novos analistas.
*   **Obrigatoriedade do Formulário de Formalização:** O preenchimento e a coleta de assinaturas no "Formulário de Formalização de Treinamento" serão **mandatórios** em todas as implantações. Este documento será a evidência para contra-argumentar futuras alegações de que algo não foi treinado.
*   **Alinhamento com o Comercial:** O comercial passará a incluir na proposta e no contrato a **responsabilidade do cliente** em garantir que sua equipe assista aos vídeos de treinamento (quando disponíveis) e colabore com o processo de mudança, sob pena de impactar o cronograma e os custos da implantação.
*   **Foco em Ganhos Operacionais:** Durante o treinamento, os analistas devem focar em demonstrar os diferenciais e ganhos operacionais do sistema Siplan em relação ao sistema anterior, para ajudar o cliente a perceber o valor do investimento.
*   **Produção de Mais Vídeos:** Há um compromisso de expandir a biblioteca de vídeos na plataforma **Siplan Skills**, com foco em tutoriais curtos e por rotina, especialmente para o **ORION REG** e a parte de balcão do **ORION TN**.

## 3. Responsáveis e Papéis
*   **Analistas de Implantação:** Responsáveis por ministrar o treinamento, adaptar a abordagem ao perfil do cartório, preencher o formulário de formalização, coletar assinaturas e produzir conteúdo para os novos vídeos de treinamento. Serão responsáveis por criar a primeira versão dos roteiros de treinamento.
*   **Equipe Comercial:** Responsável por alinhar com o cliente suas responsabilidades no processo de treinamento (incentivar o uso de vídeos, gerenciar a resistência da equipe).
*   **Marcus (eu) (Coordenação):** Responsável por verificar a entrega dos documentos de formalização e mediar a produção e edição dos vídeos de treinamento.
*   **Titular/Oficial do Cartório:** Papel crucial em apoiar a implantação, gerenciando a resistência interna e motivando a equipe.

## 4. Ferramentas, Sistemas e Integrações Mencionadas
*   **Siplan Skills:** Plataforma de treinamento com vídeos da Siplan.
*   **Formulário de Formalização de Treinamento:** Documento usado para registrar os tópicos abordados e coletar a assinatura dos usuários treinados.
*   **Vídeos de Demonstração e Treinamento:** Material de apoio essencial para o processo.

## 5. Prazos, Pendências e Próximas Ações
*   **Pendência:** Criar roteiros de treinamento padronizados para cada produto, destrinchando os tópicos por setor.
*   **Ação Contínua:** Produzir novos vídeos de treinamento para o **Siplan Skills**, com foco no **ORION REG** e **ORION TN** (balcão).
*   **Ação de Processo:** Instituir a verificação obrigatória da entrega do formulário de formalização assinado ao final de cada implantação.

## 6. Dores, Riscos e Exceções Discutidas
*   **Resistência à Mudança:** A principal dor é lidar com funcionários resistentes, que fazem "caras e bocas", influenciam negativamente os colegas e se recusam a aprender, culpando o sistema ou o analista por qualquer dificuldade.
*   **Falta de Absorção:** Mesmo com o treinamento, muitos usuários só aprendem de fato quando começam a usar o sistema em produção, o que gera um grande volume de dúvidas e chamados no acompanhamento e no pós-implantação.
*   **Alegações de Falta de Treinamento:** Risco de o cliente ou funcionário alegar que uma rotina não foi treinada para justificar um erro ou a não execução de uma tarefa, especialmente se não houver um documento assinado comprovando o treinamento.
*   **Cronograma Apertado:** O tempo limitado em campo muitas vezes não permite um acompanhamento extenso da prática do usuário em todas as rotinas, especialmente aquelas de baixa frequência (ex: comunicações mensais).

## 7. Exemplos Práticos e Cartórios Citados
*   **Franca:** Um problema com a comunicação da DOI ocorreu porque, segundo o cartório, a rotina não foi treinada. O analista esqueceu de coletar o formulário de formalização assinado, ficando sem evidências para contra-argumentar.
*   **São Bernardo:** Exemplo de cliente com alta resistência inicial, onde pedidos de customização eram constantes. A postura firme do analista e da gestão Siplan foi necessária. O envolvimento do tabelião também foi citado como crucial para "baixar a bola" da equipe.
*   **18º Cartório (SP):** Exemplo onde o tabelião reuniu todos os 110 funcionários e foi taxativo: "o cartório é meu, eu mandei mudar. Quem não quiser se adequar, pode ir embora". A postura mudou o comportamento da equipe drasticamente.
*   **Americana:** Caso de um funcionário extremamente resistente, que dizia "pago para voltar" para o sistema antigo. O sucesso da implantação dependeu do apoio de outros colegas que gostaram do sistema.
*   **Batatais:** Foi citado como um exemplo onde formulários de formalização foram cruciais para comprovar que o treinamento havia sido feito.

## 8. Divergências e Pontos em Aberto
*   **Eficácia do Treinamento vs. Prática:** Foi discutido se mais tempo de treinamento resolveria o problema de absorção. A conclusão foi que não necessariamente. O aprendizado efetivo acontece na prática, durante o acompanhamento em produção. Portanto, otimizar tarefas pré-implantação para ganhar mais tempo de **acompanhamento pós-virada** é mais valioso do que apenas estender o tempo de treinamento teórico.
*   **Abordagem do Treinamento:** Há uma divergência implícita na metodologia. Vieira foca em alinhar o novo processo ao que o usuário já faz para facilitar a absorção, deixando as novidades para o final. Outros focam em treinar todo o setor de uma vez para ganhar tempo. A necessidade de padronizar um roteiro busca mitigar essa variação.

---

# DOCUMENTO 8 — Entrada em Produção

## 1. Contexto e Estado Atual (Como É Hoje)
*   **Processo Crítico de Fim de Semana:** A "virada" para o novo sistema geralmente ocorre durante um fim de semana. O analista de conversão executa a migração final dos dados, e o analista de implantação realiza as configurações "pós-conversão".
*   **Jornada de Trabalho Extensa:** É comum que o analista de implantação trabalhe até tarde da noite no sábado ou madrugada de domingo para deixar o ambiente pronto para a segunda-feira.
*   **Dependência da Liberação da Conversão:** O início do trabalho do analista de implantação depende da finalização do processo de conversão. Atrasos na liberação da base convertida comprimem ainda mais o tempo disponível para as configurações finais.
*   **Acompanhamento Imediato:** Na segunda-feira, o analista de implantação já precisa estar no cartório para acompanhar os primeiros usos do sistema em ambiente real, muitas vezes com poucas horas de sono.

## 2. Decisões Tomadas e Novo Processo (Como Será)
*   **Otimização das Etapas Prévias:** A principal estratégia para melhorar a fase de entrada em produção é otimizar todas as etapas que a antecedem:
    *   **Pré-configuração da base:** Fazer com que a base de dados já venha com o máximo de parâmetros prontos para reduzir o trabalho de "pós-conversão".
    *   **Antecipação da Instalação/Parametrização:** Realizar a instalação nas estações e parametrizações complexas antes da semana da virada, através da equipe de backoffice ou de uma equipe júnior.
*   **Redução do Tempo de Acompanhamento:** Foi discutida a necessidade de otimizar o tempo de acompanhamento em produção. A ideia é ganhar eficiência nas fases anteriores (instalação, parametrização) para que o tempo do analista em campo seja mais focado em acompanhar o uso real e tirar dúvidas, e não em configurar o ambiente.

## 3. Responsáveis e Papéis
*   **Analista de Conversão (Luciane, Ademar, Du):** Responsável por executar a conversão final dos dados no fim de semana da virada.
*   **Analista de Implantação:** Responsável pelas configurações "pós-conversão" e por estar presente no cartório na segunda-feira para o acompanhamento inicial (o "day one").

## 4. Ferramentas, Sistemas e Integrações Mencionadas
*   Nenhuma ferramenta nova ou específica para esta etapa foi mencionada, pois ela é o culminar do uso das ferramentas das etapas anteriores (motores de conversão, scripts de parametrização, etc.).

## 5. Prazos, Pendências e Próximas Ações
*   As ações relacionadas a esta etapa são as mesmas das etapas de **Conversão**, **Instalação** e **Parametrização**: melhorar e antecipar esses processos para que a entrada em produção seja mais suave e menos dependente de um trabalho heroico no fim de semana.

## 6. Dores, Riscos e Exceções Discutidas
*   **Cansaço do Analista:** A jornada de trabalho no fim de semana da virada é exaustiva, comprometendo a disposição e a energia do analista para o acompanhamento na segunda-feira.
*   **Imprevistos na Conversão:** Qualquer problema na conversão final (falta de espaço em disco, erro no motor, dados corrompidos) impacta diretamente o cronograma, podendo atrasar ou comprometer a entrada em produção.
*   **Pressão do Cliente:** A segunda-feira é um dia de alta tensão. Os usuários estão inseguros, o sistema é novo e qualquer pequeno problema (uma impressão que não sai, um campo que não encontram) gera pânico e pressão sobre o analista.
*   **Descoberta de Problemas Críticos:** É na entrada em produção que problemas de infraestrutura não resolvidos (servidor lento, rede instável) se manifestam de forma mais dolorosa, gerando a percepção de que "o sistema novo é ruim".

## 7. Exemplos Práticos e Cartórios Citados
*   **Francana (falado por Júlio):** Para dar conta, o analista acorda às 4h da manhã no dia seguinte à liberação da conversão para fazer as configurações "pós" e conseguir viajar a tempo de estar no cliente na segunda-feira cedo.
*   **Mogi das Cruzes / Guarulhos:** Exemplos de onde problemas de infraestrutura não resolvidos antes da entrada em produção causaram lentidão e travamentos, gerando frustração nos usuários e estresse para o analista.

## 8. Divergências e Pontos em Aberto
*   Não houve divergências nesta etapa. Há um consenso de que o processo de entrada em produção é o momento mais crítico e estressante da implantação e que as melhorias devem focar em tornar as etapas anteriores mais robustas para que a "virada" seja o mais tranquila possível.

---

# DOCUMENTO 9 — Transição para o Pós Implantação

## 1. Contexto e Estado Atual (Como É Hoje)
*   **Período de "UTI":** Após a saída do analista de campo, o cliente entra em um período de acompanhamento pela equipe de Pós-Implantação (atualmente focada em **ORION TN** e **ORION REG**).
*   **Comunicação Fragmentada:** A transição de conhecimento do analista de campo para a equipe de pós é feita principalmente através de um "Documento de Transição", mas a comunicação não é totalmente fluida.
*   **Geração de Ruído:** A equipe de Pós-Implantação relata receber muitas dúvidas "simples" dos clientes, que teoricamente deveriam ter sido sanadas durante o treinamento e acompanhamento em campo. Isso gera um sentimento de que o treinamento pode não estar sendo 100% eficaz ou que os usuários não absorveram o conteúdo.
*   **Reclamações de Falta de Treinamento:** É comum que a equipe de pós ouça do cliente "o analista que esteve aqui não me ensinou isso", colocando em xeque o trabalho feito em campo.
*   **Ativação de Rotinas:** O pós-implantação frequentemente precisa ativar ou finalizar a configuração de rotinas que não foram deixadas 100% funcionais em campo, como o serviço do **CRA/CENPROT**.

## 2. Decisões Tomadas e Novo Processo (Como Será)
*   **Uso de Evidências:** A equipe de pós-implantação deve ser orientada a usar o **Formulário de Formalização de Treinamento** como primeira linha de defesa contra alegações de falta de treinamento. Ao invés de assumir a falha, devem verificar o documento assinado e contra-argumentar: "Esta rotina foi apresentada e o documento foi assinado. Qual é a sua dúvida específica sobre ela?".
*   **Melhoria no Documento de Transição:** O documento de transição deve ser mais detalhado, registrando não apenas pendências, mas também contextos importantes, como "Rotina X não foi ativada porque o cliente não tinha o certificado digital" ou "Funcionário Y não assinou o formulário de treinamento pois estava ausente".
*   **Alinhamento entre Equipes:** Haverá uma reunião específica com a equipe de Pós-Implantação para alinhar esses novos procedimentos e criar um canal de feedback mais estruturado, para que as dores do pós sejam usadas para aprimorar o processo de implantação.

## 3. Responsáveis e Papéis
*   **Analistas de Implantação:** Responsáveis por preencher o Documento de Transição de forma detalhada e garantir a coleta do Formulário de Formalização de Treinamento assinado.
*   **Equipe de Pós-Implantação (Bruno, Hugo, etc.):** Responsáveis por dar o suporte inicial após a saída do analista de campo. Devem usar as documentações (transição, formalização de treinamento) para gerenciar as expectativas e dúvidas dos clientes.
*   **Marcus (eu) (Coordenação):** Facilitará a reunião de alinhamento entre as equipes de Implantação e Pós-Implantação.

## 4. Ferramentas, Sistemas e Integrações Mencionadas
*   **Documento de Transição:** Principal ferramenta para a passagem de conhecimento entre a implantação em campo e o pós-implantação.
*   **Formulário de Formalização de Treinamento:** Ferramenta chave para evidenciar que o treinamento foi ministrado.
*   **Microsoft Teams:** Usado para comunicação informal sobre pendências específicas (ex: Vieira comunicando Eric sobre o certificado pendente).

## 5. Prazos, Pendências e Próximas Ações
*   **Ação Imediata:** Agendar e realizar a reunião de alinhamento com a equipe de Pós-Implantação.
*   **Pendência:** Estruturar um processo de feedback formal do Pós-Implantação para a equipe de Implantação, para que as falhas recorrentes sejam identificadas e corrigidas no processo raiz.

## 6. Dores, Riscos e Exceções Discutidas
*   **Desgaste da Imagem do Analista:** A principal dor é o sentimento de "levar chicotada nas costas", onde o trabalho feito em campo é questionado pela equipe interna com base em reclamações do cliente, sem uma análise completa do contexto.
*   **Retrabalho para o Pós-Implantação:** A equipe de pós acaba tendo que fazer "retrabalho" de treinamento ou configuração, o que sobrecarrega a equipe e gera frustração.
*   **Percepção de Falha no Processo:** A recorrência de dúvidas simples no pós pode criar uma percepção interna de que o processo de implantação e treinamento está falhando, mesmo que o problema seja a falta de absorção ou má-fé do usuário.

## 7. Exemplos Práticos e Cartórios Citados
*   **Caso do CRA/CENPROT:** Citado múltiplas vezes como um exemplo de rotina que frequentemente chega ao Pós-Implantação sem estar totalmente configurada, seja por falta de certificado no cliente, seja por esquecimento na instalação do serviço.
*   **Discussão sobre o Formulário:** Vieira explicou a importância de registrar exceções no formulário: se um funcionário foi treinado mas estava ausente na hora da assinatura, ele anota isso à mão. Se uma rotina como **CENSEC** não pôde ser testada por falta de certificado, isso é registrado no documento de transição.

## 8. Divergências e Pontos em Aberto
*   **Origem do Problema:** Há uma divergência de perspectiva. A equipe de implantação acredita que faz um trabalho completo e que os problemas no pós são devidos à curva de aprendizado do cliente e ao fator humano. A equipe de pós (pelo relato) tende a ver como uma possível falha no treinamento ou no processo.
*   **Solução:** O ponto de consenso para resolver a divergência é o uso rigoroso da documentação como evidência para mediar essas situações, estabelecendo uma base factual para a análise de cada caso.

---

# DOCUMENTO 10 — Relatório de Benefícios do Sistema

## 1. Contexto e Estado Atual (Como É Hoje)
*   **Etapa Recente e Inconsistente:** A elaboração de um relatório formal de benefícios para apresentar ao titular do cartório é uma etapa recente no processo de implantação e não está sendo cumprida em todos os projetos.
*   **Foco no Operacional:** Durante a implantação, os ganhos e benefícios são demonstrados diretamente aos usuários operacionais (escreventes, recepcionistas), mas essa percepção de valor nem sempre chega ao tomador de decisão (tabelião, oficial).
*   **Visão do Tabelião:** Muitos tabeliães não participam do dia a dia da operação e, portanto, dependem do feedback de sua equipe. Se a equipe, por estar na curva de aprendizado ou por resistência, só reportar dificuldades, o tabelião pode ter uma visão distorcida e negativa do valor do novo sistema.

## 2. Decisões Tomadas e Novo Processo (Como Será)
*   **Obrigatoriedade da Apresentação:** A elaboração e apresentação de um relatório consolidado de "Ganhos Operacionais" para o titular do cartório ao final da implantação se tornará uma **etapa obrigatória** do processo.
*   **Conteúdo do Relatório:** O relatório deve condensar todos os diferenciais positivos e melhorias de processo identificados durante a implantação em todos os setores. O objetivo é tornar tangível o retorno sobre o investimento feito pelo cartório.
*   **Uso Estratégico da Linguagem:** Foi sugerido o uso do termo **"ganhos operacionais"**, pois foi observado que "o olho do cara brilha" ao ouvir essa expressão, associando-a diretamente a uma boa decisão de investimento.

## 3. Responsáveis e Papéis
*   **Analistas de Implantação:** Responsáveis por identificar e registrar os ganhos operacionais ao longo da implantação e, ao final, consolidar e apresentar essas informações de forma clara e objetiva para o titular do cartório.

## 4. Ferramentas, Sistemas e Integrações Mencionadas
*   Nenhuma ferramenta específica foi discutida, apenas a necessidade de se criar um "relatório" ou documento para essa finalidade.

## 5. Prazos, Pendências e Próximas Ações
*   **Pendência:** Criar um template padrão para o "Relatório de Ganhos Operacionais".
*   **Ação de Processo:** Incorporar formalmente a etapa de apresentação deste relatório no checklist e cronograma de todas as implantações.

## 6. Dores, Riscos e Exceções Discutidas
*   **Percepção de Valor Negativa:** O maior risco de não executar esta etapa é o titular do cartório ficar com uma percepção negativa da implantação e do sistema, baseada apenas nas reclamações e dificuldades iniciais de sua equipe, sem ter visibilidade dos benefícios reais conquistados.
*   **Tabelião Ausente:** A dificuldade aumenta em cartórios onde o tabelião é ausente e não se envolve no processo, tornando ainda mais crucial a entrega de um documento formal que resuma os resultados.

## 7. Exemplos Práticos e Cartórios Citados
*   **Franca (Protesto):** Exemplo de ganho operacional claro. O cartório usava cinco funcionários no setor, cada um com funções segmentadas devido a limitações do sistema antigo (**Tabnot**). Com o **ORION PRO**, o processo foi tão otimizado que o analista estimou que apenas três pessoas seriam suficientes, liberando mão de obra para outros setores.
*   **São Bernardo:** O próprio analista, ao conversar com o substituto (Ricardo) no pós-implantação, teve que "puxar" dele o reconhecimento dos benefícios. Ricardo admitiu que as rotinas de comunicação (com **Selo Digital**, **TJ**, etc.) e consulta de indisponibilidade eram muito superiores e mais automatizadas no sistema Siplan em comparação com o da Scriba.
*   **IA e Contraditório:** Foi citado o exemplo geral da IA no contraditório, que reduz um processo manual de 30 minutos para 1 minuto, mas que enfrenta resistência inicial dos usuários que não querem aprender a nova rotina. O benefício só é percebido após a adoção.

## 8. Divergências e Pontos em Aberto
*   Não houve divergências sobre a importância desta etapa. O consenso foi unânime de que ela é essencial para "fechar com chave de ouro" a implantação e garantir que o valor do sistema seja percebido por quem paga a conta. O único ponto em aberto é a criação de um template padrão para o relatório.