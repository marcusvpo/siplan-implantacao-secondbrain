# Questionário de Aprofundamento: Processos de Implantação

Este documento foi gerado pelo Process Architect AI após análise dos MOCs, Gargalos e Processos de Implantação atuais da Siplan. O objetivo é extrair o conhecimento tácito sobre as "zonas cinzentas", exceções e detalhes operacionais para refinar a base de conhecimento.

Por favor, responda abaixo de cada pergunta. Se uma pergunta não fizer sentido ou não tiver resposta ainda, sinta-se livre para indicar.

---

## 1. Gestão de Capacidade e Conflitos de Agenda

**Contexto:** Identificamos que os 6 analistas técnicos realizam tanto o campo (viagens de 2 semanas) quanto o back-office (Aderência e Homologação), gerando um "apagão" de homologações.

**Q1.1:** Como ocorre a priorização quando um analista está em campo e existem homologações críticas paradas na sua fila? Outro analista assume a demanda, o coordenador intervém, ou o projeto simplesmente sofre atraso no cronograma?
**[Na maioria desses casos tentamos passar a homologação para outro analista que não esteja em implantação, porém pode coincidir de todos os analistas estarem em implantação e não há ninguém disponível para a homologação (ou também análise de aderência). Quando isso acontece, para a homologação,  conversamos com o responsável pela conversão para entender se ele mesmo consegue realizar essa homologação. 
Caso não for possível tentamos correr e pedir para o analista homologar no final de semana ou então nos primeiros dias junto com a configuração/parametrização e treinamento. No caso da Aderência aí realmente ficamos dependendo da agenda do analista para uma semana quando ele não estiver em implantação e agendamos de acordo com as aderências que estão há mais tempo aguardando.]**



**Q1.2:** Existe um SLA formal (em dias ou horas) estipulado para a entrega da "Análise de Aderência" e da "Homologação de Conversão"? Se sim, qual é e com que frequência ele é descumprido na realidade atual?
**[Não há nada formalizado pois cada homologação e cada análise de aderência tem suas particularidades. Se for um cartório muito grande e um sistema desconhecido, a homologação levará mais tempo e deverá ser feita com cautela, sendo reservado cerca de dois dias do analista para homologação. 
Se for um cliente que o sistema legado é nosso, os nossos motores de conversão já estão praticamente prontos e validados, então a homologação é mais tranquila e mais rápida.
Para análise de Aderência, também depende muito do cartório e o sistema atual. Quando são sistemas que não são Siplan, priorizamos a análise de aderência presencial onde enviamos o analista por 2 até 3 dias para a análise de aderência presencial e identificando todas as solicitações do cliente. Quando a aderência está pronta, aí avaliamos se está adequada para seguir ou se está inadequada e temos que passar os pontos para o time de produtos avaliar.
Para análise de Aderência onde o sistema legado é Siplan, fazemos remotamente e de maneira mais rápida/tranquila pois já conhecemos nossos próprios sistemas. As vezes acontece do cliente utilizar sistemas de terceiros para rotinas específicas e isso é importante de ser identificado na Aderência.]**



---

## 2. Comercial vs. Entrega e o "Sprint da Última Semana"

**Contexto:** O documento de gargalos cita a "Janela de Ação Frenética" na semana anterior à viagem e fechamento de horas insuficientes (ex: 40h para sistemas de 80h).

**Q2.1:** Quando o Comercial vende um projeto subdimensionado (ex: 40h em vez de 80h), como isso é resolvido na prática? O analista faz horas extras absorvidas pela Siplan, há um aditivo de contrato cobrado do cliente, ou a qualidade da entrega/treinamento é reduzida?
**[Então nesse caso a gente já teve algumas ocasiões parecidas com isso. Onde o comercial vem de 40 horas para um projeto do Orion. Mas a gente sabe que são no mínimo 80 horas. E aí? A resposta do comercial é que durante a negociação com o cliente. É definido que o que exceder de horas o cliente vai pagar a mais depois da conclusão da implantação.
Mas a gente sabe que isso não é o recomendado a gente tem casos que o cliente simplesmente não se importa. E aí ele realmente paga porque ele já sabe que teria um custo a mais e também tem casos que o cliente fica indignado falando que foram vendidas 40 horas e a gente quer cobrar a mais e acaba gerando uma frustração, mas aí quem resolve isso é diretamente o comercial, então já foi passado até situações parecidas como essa para a diretoria. e agora a instrução do comercial é sempre vender com as horas de acordo com que a gente sabe que vai ser a quantidade mínima então Órion pro o mínimo é de 40 horas que é uma semana e para Orion TN. E Orion REG. A quantidade mínima são de 80 horas.]**



**Q2.2:** O que deveria compor um "Checklist Mínimo de Viabilidade Técnica e Operacional" ideal que o Comercial seria obrigado a preencher antes de poder prometer e agendar qualquer data com o cliente?
**[Eu não sei falar exatamente, o que deveria compor esse check list. Mas o que eu posso falar é que o comercial é o centro das informações e o primeiro contato direto com o cliente então a gente aqui da implantação trabalha com base nas informações que o comercial passa para a gente e aí pode ser via chamado do 0800. Ou então comunicações aí pelo Teams. ou reuniões.
Hoje em dia sobre data eles ainda me procuram. Na etapa da negociação com o cliente. Ou seja ainda não foi fechado o contrato. E aí algumas vezes eles vem me chamam a gente conversa no teams. E aí eles me questionam. Como que tá a agenda do implantador X para o mês Y? Porque o cliente tá querendo essa tal data e aí dependendo da agenda eu dou a resposta eu falo se a gente pode seguir porque a agenda dele vai estar livre nessa data que o cliente está solicitando. Ou então se não tá disponível aí ele. Comercial tem que retornar o contato com o cliente para ver uma melhor data, só que quando eles vem me procurar eles já meio que definiram essa data com o cliente e querem saber se vai dar certo porque o cliente quer nessa data então ele já sabem que se não der nessa data eles vão ter que entrar em contato novamente com o cliente para reagendar renegociar essas datas e aí a Palavra Final vem do comercial para gente.]**



---

## 3. Análise de Aderência e Padronização

**Contexto:** A Análise de Aderência carece de padronização. O modelo do Orion REG (que pergunta sobre a estrutura física do cartório, como nº de andares) evitou problemas que sistemas como PRO e TN não evitam.

**Q3.1:** Além do número de andares/tamanho do cartório, quais são as outras "bombas-relógio" mais comuns que não são mapeadas na aderência atual e acabam estourando apenas quando o analista chega presencialmente no cartório?
**[Análise de aderência hoje em dia ela busca fazer uma análise técnica de viabilidade do nosso sistema em comparação com o sistema atual do cartório. Então o analista ele entra em contato com alguém do cartório e faz uma série de perguntas sobre o sistema atual e compara com o que o novo sistema entrega ou não.
Sobre essa questão de tamanho do cartório andares quantidade de funcionários e etc foi uma iniciativa do nosso implantador Júlio e que a gente achou viável colocar dentro da análise de aderência porque são informações relevantes e uma vez que o implantador já tá fazendo análise aderência em contato direto com o funcionário do cartório. Para ver essas questões técnicas não custa nada, ele também já perguntar e sanar essas outras dúvidas estruturais.
um tipo de bomba relógio que a gente já enfrentou recentemente algumas vezes. É a questão do editor que é basicamente um editor de minutos dentro do Orion TN. Que é contratado a parte durante a negociação com o comercial? Esse editor é basicamente um editor de texto para o cartório utilizar as minutas do modelo atual que eles usam mais de adaptado para o nosso sistema Orion TN. E aí a gente tem uma equipe de modelos que fica responsável por adaptar. Os modelos atuais no cartório para o padrão do Orion TN. E aí o que que acontece? Recentemente a gente teve casos que o implantador chegou lá. para implantar e não tinha sido enviado por parte do cartório nenhum modelo para a equipe de modelos, mas aí a gente descobriu que isso foi uma falha do comercial que não tinha sido. Informado para o cliente que ele deveria fazer esse envio para nossa equipe de modelos, mas também já teve casos da gente chegar lá para implantar e quem esqueceu de fazer o envio dos modelos foi o próprio cliente. Mesmo ele estando ciente então essa parte dos modelos é uma parte bem complexa e bem trabalhosa e que não é fácil e rápido de se resolver e adaptar aos modelos do editor do TN então por isso a gente tem uma equipe especializada nisso. E aí agora a gente já tá padronizando uma um novo processo para o comercial. Assim que fechar a negociação. E se tiver modelos incluso. Eles já direcionam os e-mails da equipe de modelos que é o e-mail do Hugo e do Bruno Fernandes o cartório fazer o envio dos modelos o quanto antes. Essa questão dos modelos estamos adaptando para também estar incluso no "[[Exemplo Output - Formulário de Implantação|Exemplo Output - Formulário de Implantação]]" em "3-Recursos/00 - Inbox/Questionario_Aprofundamento_Implantacao"**



**Q3.2:** Qual é o nível de colaboração/resistência dos clientes na etapa de aderência? Eles fornecem os dados solicitados rapidamente ou há muita dificuldade em fazer o cliente "parar" para analisar seus próprios processos antes da viagem do implantador?
**[Eu vejo que por parte dos clientes. A resistência é bem baixo, o que a gente mais tem de dificuldade para fazer análise de aderência é na verdade agenda interna dos nossos implantadores uma vez que a gente consegue agendar a Maria, ela é responsável por ligar e contactar o cliente. Para fazer o agendamento e já deixar ele ciente de que no dia x. O nosso implantador vai entrar em contato para fazer análise de aderência. Então ele já deixam preparado alguém para estar à disposição de responder essas perguntas. Então por parte do cliente a gente não enfrenta muita resistência mais essa dificuldade de agendamento quando as agendas dos implantadores está lotada e eles estão em implantação porque aí essa é uma atividade que eles fazem remotamente. Mas só quando eles não estão em implantação.]**



---

## 4. Transição Tecnológica: O Rollout do Hub Siplan

**Contexto:** A equipe usa o sistema legado 0800 e há uma janela de treinamento de 25 a 29 de Maio para a migração para o Hub.

**Q4.1:** Qual é a principal resistência comportamental esperada dos analistas para abandonar os trâmites longos do 0800 e migrar para a estrutura do Hub? 
**[Olha na verdade, eu acho que você entendeu errado, a gente não vai abandonar o 0800, ele sempre vai existir. Porque lá é onde está Centralizado é todos os chamados do service desk e é o ponto de contato dos clientes que solicitam suporte para gente então lá também é conectado com o SAP. que é utilizado pelo comercial e pelo administrativo para administração e gestão dos contratos. O Hub nada mais é do que uma plataforma facilitadora e centralizadora de informações em momento nenhum a gente vai parar de usar o 0800 para usar somente o Hub, a ideia na verdade é usar os dois em conjunto e fazer com que o que normalmente é preenchido só no HUB ou às vezes nem é preenchido no ramo e fica no Boca a Boca e acaba sendo perdido essas informações sejam centralizadas no Hub.]**



**Q4.2:** O Hub terá algum tipo de bloqueio sistêmico ("hard stop")? Por exemplo: o analista não pode iniciar a fase 9 (Treinamento em Campo) se o Hub não estiver com o check verde de "Homologação" e "Aderência" concluídos?
**[Na verdade a gente não tem nenhum hard Stop, mas a gente tem os faróis de sinalização de cada etapa de cada projeto, então a gente mesmo sabe é que se a aderência não tá concluída ou com sua impedimento ou então a homologação não foi feita ou apontou inconsistências que ainda não foi corrigida. A gente sabe que o analista não deve iniciar o treinamento em campo e a implantação em si por conta dessas pendências, então a gente não tem nenhum tipo de bloqueio dentro da plataforma, mas a gente tem noção e a gente sabe que não dá para começar a implantação. Sem essas coisas estarem 100% concluídas. Isso é um senso comum.]**



---

## 5. Exceções, Falhas e Contingências (Unhappy Path)

**Contexto:** Documentos de processo muitas vezes assumem que tudo dará certo, mas os sistemas de cartórios lidam com cenários de alta sensibilidade e segurança jurídica.

**Q5.1:** O que acontece quando o processo de "Virada para Produção" (Fase 10) falha de maneira crítica? (ex: o sistema apresenta bugs bloqueantes no primeiro dia de atendimento ao público). Existe um procedimento formal de "Rollback" para o sistema antigo ou a equipe apaga incêndios até resolver?
**[Em casos de ocorrer alguma falha extrema durante a implantação e que a gente não vai realmente conseguir fazer a virada para o sistema ou a virada para o sistema foi feita e tá com muitos problemas. A gente sempre tem. O sistema legado rodando e até por questão de backup e de informações para consulta então quando a gente enquanto o sistema a gente pelo menos por alguns meses. Também deixa no próprio servidor no cartório. O sistema anterior para caso seja necessário consulta de informações de outros períodos. Ou como um backup mesmo.
Então, a gente já tem esse processo de que se tudo der errado, a gente tem como voltar atrás para o sistema antigo até a gente conseguir resolver o que foi encontrado de problema, mas isso é bastante Difícil de acontecer e a maioria das vezes. São problemas mais pontuais em que o próprio Implantador consegue resolver ou então ele aciona a equipe de produtos e eles trabalham em conjunto para conseguir solucionar ainda naquela semana da implantação.]**



**Q5.2:** Como são tratados os impeditivos de infraestrutura de última hora? Exemplo: o analista chega na segunda-feira para iniciar a implantação presencial e os computadores novos do cartório não chegaram ou a rede não funciona. O analista volta? Ele atua como técnico de TI do cartório?
**[Normalmente a gente sempre me diga esse risco de ter impedimentos de infraestrutura de última hora Justamente por isso a gente faz a análise de ambiente que é um dos primeiros passos. Assim que o chamado chega para a equipe de implantação então. O nosso ti o Alex ele entra em contato com o cliente e ele tem uma planilha onde ele faz toda coleta de informações de hardware das máquinas e também do Servidor também da rede antivírus. Faz igual e etc. Então a gente já sabe a partir da finalização dessa análise de ambiente se a gente pode seguir ou não, o que pode acontecer são casos que o cliente já sabe que a infraestrutura dele não tá adequada. Ou então foi descoberta que não está adequada pela análise de ambiente. E aí o comercial ela tem contato para discutir e negociar com o cliente então, às vezes eles mesmo por conta própria resolvem adequar o ambiente e aí a gente espera a data deles. Para depois conseguir reagendar ou então o próprio comercial pode fornecer o nosso serviço de aluguel de máquinas ou servidores Para esse cliente.
Essa questão da infraestrutura é muito importante e também muito delicada, a gente tem até contratos que são cancelados por conta da quantidade de adequações e de dinheiro a ser gastado que o cliente teria que investir. Para conseguir suportar o nosso sistema. E aí eu não falo que o nosso sistema exige muita infraestrutura, mas na verdade é muitos cartórios têm uma infraestrutura muito precária mesmo hoje em dia. Com máquinas muito antigas e que não suportam quase nenhum outro programa.
Mas se acontece alguma questão é onde não é constatada um impedimento de uma inadequação na análise prévia da implantação e aí o analista chega lá na hora e se depara com alguma coisa do tipo. Aí fica a critério dele resolver direto com o cliente. E aí também envolve comercial para ver o que eles conseguem fazer. E aí depende se for por exemplo aumentar um pouco da memória RAM de algumas máquinas ou então liberar mais espaço em disco do Servidor são coisas simples que conseguem ser. Adequadas durante a semana mas se envolve compras de novos equipamentos de máquinas de servidor uma coisa mais complexa aí é tratado é com o comercial e com a diretoria e normalmente. o plantador aborta implantação e o cliente fica disposto a adequar o que precisar.]**



**Q5.3:** Sobre os grupos de WhatsApp no pós-implantação que mascaram o esforço do suporte: como o cliente deveria oficialmente solicitar ajuda? Há algum plano de mitigação para "cortar o cordão umbilical" do WhatsApp do analista e direcionar o cliente aos canais oficiais?
**[Sim hoje em dia a gente tem o 0800 para isso. o WhatsApp ele só é utilizado no pós implantação por conta de ser um contato mais direto e mais rápido e também mais próximo do cliente e a gente entende que clientes que acabaram de ser implantados vão requisitar um suporte maior porque envolve uma mudança de sistema mudança de operação e mudança da rotina dos funcionários do cartório, então é normal que as dúvidas venham no começo. Depois que passa o pós implantação normalmente tem uma duração de duas semanas até tudo se estabelecer a gente tem casos também que pode durar um mês ou até mais depende da dificuldade que o cliente está enfrentando, mas quando é encerrado possa implantação. O canal de contato do cliente passa a ser o 0800. E aí lá eles abrem chamado. E aí entra para fila de espera do SD (Service Desk)
Então qualquer contato depois do pós implantação. É feito pelo 0800. E aí Independente se for erro bug dúvida operacional solicitação de algum serviço migração treinamento normalmente é tudo dentro do 0800 e alguns casos os clientes também ligam no telefone aqui da Siplan. E a gente orienta eles abre o chamado no 0800.]**
