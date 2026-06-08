---
tipo: Questionário
foco: Processos do Siplan Hub (AS-IS vs TO-BE)
status: Aguardando Preenchimento
---
# Questionário de Mapeamento: Fluxos do Siplan Hub (AS-IS vs TO-BE)

Este documento foi criado para extrair de forma crítica e cirúrgica como cada equipe interage (ou não) com o Siplan Hub hoje (**AS-IS**) e como deveria ser o processo ideal e descentralizado no futuro (**TO-BE**). 

Preencha os campos abaixo de cada pergunta. Seja o mais detalhista possível nas dores atuais e na visão ideal.

---

## 1. Equipe Comercial (Passagem de Bastão e Gestão de Crise)

**Contexto:** O Comercial é a ponta da lança. Eles vendem e precisam passar o projeto redondo para Implantação, além de atuar quando o cliente trava o projeto (Bloqueios).

### Pergunta 1.1: O "Handoff" do Projeto
*Atualmente, a tela "Form. Nova Implantação" não está liberada. Como a equipe comercial avisa a Implantação que um novo cliente foi fechado e quais são os requisitos técnicos/comerciais acordados? Como deveria ser esse ritual usando a nova tela do Hub?*
* **[AS-IS] (Quando o contrato é fechado, é aberto um chamado no 0800 e depois dos primeiros trâmites administrativos eles me passam esse chamado, aí entra na fila de implantações. Os requisitos são sempre variados de cliente para cliente, o Comercial sempre é responsável por negociar isso e pode acionar a Diretoria em casos específicos. ):** 
* **[TO-BE] (A ideia é o Comercial utilizar esse formulário de nova implantação para nos fazer a passagem de informações de maneira formal e centralizada, com tudo ja dentro do HUB. Ao invés de ficar no boca a boca e dependendo de chegar o chamado no 0800 com informações incompletas.):** 

### Pergunta 1.2: Gestão de Bloqueios e Saúde da Carteira
*Quando uma implantação trava por culpa do cliente (ex: não entregou infraestrutura ou banco de dados), como o Comercial é acionado para cobrar o cartório? Eles chegam a abrir as telas "Painel de Clientes" ou "Bloqueios"?*
* **[AS-IS] (Nós avisamos via Teams ou E-mail diretamente o responsável do comercial por negociar com o cliente. Eles não tem nenhum contato com o HUB.):** 
* **[TO-BE] (A ideia é manter o aviso via e-mail padronizado com a automação de disparo de e-mail de infra inadequada que já está funcionando. O Comercial sempre está em deslocamento, então quanto menos coisas eles tiverem que fazer pelo HUB, melhor.):** 

---

## 2. Equipe de Conversão (Fila de Trabalho e Homologação)

**Contexto:** A conversão é o gargalo técnico. Eles precisam receber o banco, converter e devolver para homologação da Implantação. O Hub possui as telas "Gestão de Atividades", "Motores" e "Homologação" com uso praticamente nulo por eles.

### Pergunta 2.1: Triagem e Fila de Atividades
*Como um analista de conversão sabe em qual cartório ele deve trabalhar hoje? Como a liderança da conversão distribui a carga de trabalho sem usar a "Gestão de Atividades" do Hub?*
* **[AS-IS] (É passado por mim "informalmente" via Teams, por mensagem ou chamada. A distribuição é feita de acordo com a especialidade de cada membro da equipe de conversão.):** 
* **[TO-BE] (Dentro de cada projeto em "Gerenciar Projetos" na etapa 3. Conversão de Dados há um botão "Enviar para Conversão" que ao clicar cai na fila da Conversão em "Gestão de Atividades" como pendente até um membro da conversão assumir aquela conversão. Após assumir, há um sistema de "posts" com uma timeline para cada conversão onde o membro que assumiu a conversão deve ir postando atualizações rápidas e objetivas de acordo conforme for seguindo a conversão.)

### Pergunta 2.2: O Fim da Conversão e a Homologação
*Quando a conversão de um banco finaliza, como o implantador é avisado de que já pode validar (Homologação)? Onde ficam os arquivos de log ou inconsistências? Como a tela "Homologação" deveria costurar esse vai-e-vem entre Conversão e Implantação?*
* **[AS-IS] (É enviado um e-mail pelo responsável pela Conversão direto ao Implantador, fornecendo os dados de acesso do servidor e os caminhos dos arquivos e pastas específicas. As inconsistências são reportadas pelo Implantador como resposta a esse mesmo e-mail, geralmente enviando um arquivo em Word ou Docs com prints e um detalhamento das inconsistências):** 
* **[TO-BE] (Acredito que esse processo não deverá ser muito alterado. Do jeito que está com essa dinâmica de e-mails está funcionando. Não quero que o implantador tenha que entrar no hub para verificar homologação ou não. Temos uma opção no HUB na fila da conversão de "Enviar para Homologação", porém é somente para acompanhamento e queremos manter assim. O que deve ser feito dentro do HUB é somente para os membros da equipe de Conversão.):** 

---

## 3. Equipe Modelos Editor OrionTN (Customização)

**Contexto:** Parametrizar modelos de documentos (OrionTN) é crítico. As telas "Dashboard", "Gerenciar Projetos (OrionTN)" e "Editor de Modelos" têm uso baixo.

### Pergunta 3.1: Recepção e Progresso dos Modelos
*Como a equipe de Modelos recebe os arquivos do cartório e como eles reportam quantos % dos modelos já foram configurados? A Implantação fica "no escuro" esperando?*
* **[AS-IS] (Eles recebem os arquivos dos modelos atuais por e-mail diretamente vindo do cliente à pedido do Comercial. Depois, caso necessário, a equipe de modelos fica em contato direto com o cliente para entender e validar as mudanças e adaptações. Normalmente fica a critério do cliente definir se está tudo pronto ou não. Para a implantação normalmente recomendamos iniciar com cerca de 3 a 5 modelos mais utilizados pelo cartório e os outro modelos, caso o cliente solicite, serão adaptados ao longo do tempo após a implantação. Há casos que o cliente nos envia mais de 40 modelos e fica um pouco "impossível" de atender tudo isso por conta da complexidade, por isso indicamos pegar os top 5 mais utilizados para nossa equipe adaptar e iniciar a implantação com esses prontos.):** 
* **[TO-BE] (O formato de envio deve seguir o mesmo, onde o cliente envia por e-mail. Porém com o preenchimento do formulário de nova implantação pelo Comercial, teremos uma visão melhor e mais transparente do que foi combinado sobre Modelos e prazo de envio com o cliente. As etapas dos Modelos para cada projeto servem mais para um acompanhamento de progresso e status de cada Modelo onde a equipe anexa os arquivos e define os que já estão prontos e os que estão pendentes.):** 

### Pergunta 3.2: O Uso do Editor de Modelos
*A tela "Editor de Modelos" deveria ser a ferramenta de trabalho diária deles. Por que eles não usam? Falta alguma feature técnica ou é apenas resistência cultural? Como obrigar/incentivar esse uso?*
* **[AS-IS] (Hoje não há uma transparência clara dos Modelos para a equipe de Implantação, justamente por essa tela não estar sendo utilizada mas já está funcional. Acredito que seja apenas uma falta de incentivo.):** 
* **[TO-BE] (Incentivar o uso da equipe de Modelos nessa tela dentro do HUB para termos uma melhor visualização e acompanhamento. O formato de recebimento por e-mail deverá ser mantido e o contato com o cliente para ajustes também. Apenas queremos usar essa seção dentro do HUB como uma forma de acompanhamento e centralização de informações, mas isso requer o preenchimento e uso da equipe de Modelos.):** 

---

## 4. Equipe de Implantação (Seu Time e Você)

**Contexto:** Você é o "Heavy User" da tela "Gerenciar Projetos". Mas e os analistas/implantadores que viajam ou fazem acesso remoto? 

### Pergunta 4.1: Atualização de Etapas e Status
*Hoje você centraliza a atualização do projeto. No cenário ideal, o implantador que está lá no cartório (ou remoto) deveria abrir o Hub no fim do dia e atualizar a etapa em que ele está? Se sim, em qual tela exatamente e o que ele deve preencher?*
* **[AS-IS] (Não a gente não quer trazer esse trabalho a mais para o implantador porque vai ser mais uma coisa para ele cadastrar e preencher. E além disso enquanto ele tá. Na implantação presencialmente não tem nenhuma etapa específica do Rubi que ele precisa preencher. As etapas que são preenchidas são as etapas que vem antes do período da implantação. Hoje em dia para ter um detalhamento diário das atividades que eles realizaram no dia a dia eles mesmos. Vão salvando e preenchendo e colocando no 0800. Então se a gente pedir para eles fazerem. esse cadastro também no Hub já que o 0800 não tem nenhuma integração que pode ser feita via API vai ser meio que um retrabalho que eles vão ter que fazer e vai acabar tomando mais tempo e também para a gente ter essas informações específicas de detalhamento diário da implantação nas faz muito sentido. Será apenas mais trabalho para o Implantador):** 
* **[TO-BE] (Como eu disse então no HUB não deve ter nenhuma tela que o implantador vai preencher enquanto ele estiver na implantação porque esse detalhamento diário ele já faz e já joga no 0800 e para a gente. O que importa são os processos que vem antes da implantação? E de ele tá lá presencialmente. a gente quer o mínimo de interação dos implantadores no HUB para cadastro de informações, porém eles Devem utilizar o Hub para fazer algum acompanhamento para olhar indicadores métricas ou ver que pé que tá alguma implantação, mas em relação a eles serem os responsáveis por cadastrar informações em alguma etapa ou em alguma tela, aí a gente já não pretende fazer isso.):** 

### Pergunta 4.2: Agenda e Calendário
*Temos o "Calendário de Projetos" e a "Agenda dos Analistas" (puxando do SAP/0800). Qual a visão definitiva para o analista de implantação saber para onde ele vai na próxima semana? Ele deveria consultar o Hub ou ele só olha o SAP/Email?*
* **[AS-IS] (Hoje em dia a gente tem o calendário de projetos que ele pega as informações de dentro do HUB quando a gente cadastra na etapa de implantação de acordo com a data de início e a data de término. Então isso é mais uma informação para estar presente dentro do HUB e a gente ter o controle de quais são as próximas implantações e o que ficou agendado de data somente do período de implantação presencial. Já essa agenda dos analistas que puxa do SAP/0800. Essa é a agenda principal que os Implantadores utilizam porque é cadastrado as atividades diretamente com o número do chamado, exatamente a solicitação, e outras informações administrativas. Então a gente tem esses dois tipos de calendários, mas um é mais para a gente ter essa visão futura e o outro é realmente onde são cadastradas as atividades semanais e diárias do implantador. E aí quando a gente tem a confirmação de alguma implantação agendada. Essa informação também sai do indicador de calendário e projetos de dentro do HUB e também passa para essa agenda dos analistas onde a Maria mesmo cadastro na agenda deles.):** 
* **[TO-BE] (Como esse processo de ter duas agendas já é um pouco confuso e o fato da gente não conseguir fazer uma integração entre o Hub e o SAP e o 0800. então, a gente não quer mexer nessa questão das agendas e a gente vai deixar essa de calendário de projetos de dentro do Rubi, apenas como uma agenda de visualização e prévia de futuras implantações. E vamos manter os cadastros administrativos na Agenda dos Analistas conforme funciona atualmente.):** 

---

## 5. Gestão e Diretoria (Visibilidade e Métricas)

**Contexto:** A diretoria consome o Hub pontualmente. O Hub tem telas de "Dashboard", "Kanban" e "Relatórios".

### Pergunta 5.1: Consumo de Indicadores
*Quando a diretoria quer saber "Como estão os projetos desse mês?", eles olham o Dashboard sozinhos ou te pedem um resumo no WhatsApp/Teams? Como deveria ser o consumo de relatórios no cenário ideal?*
* **[AS-IS] (Eles olham diretamente no projeto individual em específico, os dashboards e relatórios também são pouco utilizados por eles. Eles acessam o hub de maneira mais pontual quando querem saber de alguma etapa específica de algum projeto.):** 
* **[TO-BE] (Esse processo fica a critério da Diretoria. Os relatórios e indicadores quem acompanha mais sou eu, porém vou incentiva-los a fazer esse acompanhamento também. No geral acredito que não deva ter nenhuma mudança de processo ou no HUB):** 

---

## 6. O Hub como "Orquestrador" (Automações)

### Pergunta 6.1: Notificações e Gatilhos Ativos
*Pensando em não forçar o usuário a abrir o Hub o tempo todo: quais processos/telas deveriam obrigatoriamente disparar e-mails/mensagens no Outlook ou WhatsApp (via n8n) para acionar as pessoas no momento exato em que elas precisam agir?*
* **[AS-IS] (Atualmente só existe o disparo de e-mail para o Comercial referente a Infraestrutura inadequada.):** 
* **[TO-BE] (Quero criar diversos tipo de notificações para disparar no e-mail (integração com Outlook) para os membros que eu selecionar. Por Exemplo:
* - Disparo de e-mail para equipe de Conversão ao ser enviado uma Conversão para a fila (Acionamento junto ao ser clicado o botão "Enviar para Conversão")
* - Ainda não tenho ideias de outros disparos porém quero ter ainda mais essa integração do HUB com Outlook, me ajude com isso.):** 
