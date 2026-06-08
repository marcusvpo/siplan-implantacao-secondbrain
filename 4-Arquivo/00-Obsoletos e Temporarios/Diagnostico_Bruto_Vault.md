---
tags:
  - #auditoria
  - #diagnostico
  - #arquitetura_sistemas
  - #gargalos
---
# Diagnóstico Bruto do Vault: Raio-X Operacional

Varredura implacável e cruzamento de dados de 100% dos fluxos documentados no seu Vault. O objetivo deste relatório não é agradar, mas expor a realidade operacional nua e crua, apontando falhas estruturais severas, mentiras processuais (contradições) e pontos cegos de contingência que podem paralisar operações em campo.

---

## 🚨 Contradições e Inconsistências de Contexto

Houve um choque frontal entre o que as regras dizem que "deve ser" e o que os processos admitem que "realmente é". As seguintes notas estão mentindo uma para a outra:

1. **A Farsa do "Gate Condicional" vs. A Realidade do Agendamento**
   - **O que a regra diz:** A nota `[Regra] Gates Condicionais de Início de Projeto` afirma categoricamente que *nenhuma etapa de execução pesada ou Agendamento Final pode ser iniciada antes que Ambiente e Aderência sejam concluídas com sucesso*.
   - **O que o processo confessa:** A nota `[Processo] 7. Agendamento da Implantação Funcional` confessa que o Comercial muitas vezes *já pré-agenda uma data no ato da venda*, forçando a Implantação a correr contra o relógio mesmo com pendências ativas. A regra do Gate Condicional é, na prática, ignorada.

2. **O Paradoxo do Prazo de Conversão vs. Pressão Comercial**
   - **O Processo 5 (Conversão)** relata que se o sistema do cliente for novo/desconhecido, o desenvolvimento de um motor de conversão minucioso pode levar **de 1 a 2 meses ou mais**.
   - Como o Comercial pré-agenda a implantação na venda (Processo 7) se é humanamente impossível prever se a base de um concorrente vai demorar 3 dias ou 3 meses para ser descriptografada e convertida?

3. **A Falsa Segurança da Instalação Remota**
   - **O Processo 8 (Instalação Remota)** afirma que a equipe de Infra garante proativamente o ambiente, deixando o servidor "100% pronto" remotamente.
   - **O Processo 9 (Implantação)** desmente essa segurança, relatando que "é comum" que a infraestrutura seja precária na hora que o analista chega presencialmente e que acordos não são cumpridos. Se a Instalação Remota validou o servidor antes, como a precariedade "surge" no dia da viagem?

---

## ☣️ Pontos de Falha Crítica Sem Contingência

Processos que morrem caso haja indisponibilidade de terceiros ou indefinição externa, revelando graves falhas de resiliência:

1. **O Vácuo de Autoridade no Rollback (Sábados/Domingos)**
   - O `[Processo] 10. Virada para Produção` determina que **"Somente a Diretoria"** pode autorizar um Rollback em caso de falha crítica. A virada dos sistemas Orion TN e REG ocorre na sexta-feira à noite/fim de semana. 
   - **Ponto de Falha:** Não há contingência documentada. Se o analista presencial enfrentar um banco de dados corrompido às 02h da manhã de domingo e a Diretoria estiver inalcançável por telefone, o cartório amanhece na segunda-feira sem sistema operante?

2. **O Buraco Negro da Equipe de Produtos (Processo 3)**
   - Se a Aderência reprovar, o processo vai para "Produtos". Você já relatou que não há SLA e pode levar meses. 
   - **Ponto de Falha:** Como o projeto reage a isso? O cliente fica pagando mensalidade sem usar o sistema? O Comercial renegocia? O cartório é implantado pela metade e assume o risco de trabalhar sem a rotina essencial? O fluxo simplesmente não prevê saída caso Produtos diga "vai demorar 6 meses".

3. **Limbo Eterno de Infraestrutura (Processo 2)**
   - A implantação "pausa" quando o servidor é reprovado. O Comercial assume a cobrança. Não havendo SLA fixo para adequação, não há um "Kill Switch". O projeto pode ficar 2 anos como "Em andamento/Pausado" gerando ruído nos relatórios.

---

## 📉 Inventário de Notas Rasas/Vazias

Arquivos desnutridos que precisam de injeção urgente de conhecimento tático (menos de 3 parágrafos ou sem exemplos operacionais):

- `[Processo] 4. Tratamento de Impedimentos da Análise de Aderência.md`: Praticamente uma lista de marcadores; não explica "como" o Analista negocia, repassa e lida com o cliente quando a resposta for negativa.
- `[Processo] 8. Instalação Remota do Sistema Siplan.md`: Muito superficial na descrição técnica. O que exatamente a Infra testa? Quais portas? Como documentam esse "OK"?
- *Revisar também as notas soltas em Recursos e Regras (ex: Glossário, Diferença Remota x Funcional, Estrutura de Equipe).*

---

## 🔨 Próxima Onda de Sabatina (Perguntas Cirúrgicas)

Responda logo abaixo de cada pergunta utilizando o mesmo formato com `> **Minha Resposta:** [Digite aqui]`. Precisamos tapar os buracos da arquitetura agora.

1. **Sobre o Paradoxo dos Gates:** Se o Comercial pré-agenda a data e atropela os Gates de Aderência e Infraestrutura, qual é a autoridade real do Gestor de Implantação para barrar a viagem? Ele viaja mesmo com o servidor reprovado?
> **Minha Resposta:** [O Implantador nunca irá viajar sabendo que o Servidor está inadequado ou com pendências na análise de aderência, a não ser que for pré acordado com o cliente. No caso do Orion TN as vezes dividimos a implantação em duas etapas, primeiro a parte de Firmas (Balcão) e depois a parte de notas em uma nova implantação conforme as necessidades individuais e pré acordadas do cartório.
> Sobre o agendamento do Comercial, depende muito do cliente e de como foi negociado. Se o cliente for rígido e quer a implantação para o mês X, eles entram em contato comigo para verificar a agenda dos implantadores, e de acordo com a minha resposta eles renegociam com o cliente. Porém há casos que não fica pré agendado nenhuma data entre o cliente e Comercial e apenas entra na nossa fila de implantação para "quando der para implantar". Essa questão de agendamento sempre é um pouco bagunçada pois é muito imprevisivel as agendas dos implantadores e as implantações. Tem implantações que conseguimos implantar apenas 2 semanas após chegar o chamado (rápido) e tem implantações que demoram mais de 6 Mêses (demorado) para implantar. Tudo depende dos resultados de todas as etapas anteriores da implantação.]

2. **Sobre Bases Novas e Desconhecidas:** Quando o cartório usa um sistema cujos dados nós nunca convertemos, quem segura a bronca do cliente quando o prazo do contrato não é cumprido porque o conversor demorou 3 meses?
> **Minha Resposta:** [Normalmente a Diretoria entra no circuito para conversar com o cliente e explicar o lado técnico da complexidade da criação do conversor. Então a própria diretoria conversa e reagenda com o cliente caso haja uma data pré acordada pelo Comercial e que não será possível ser cumprida por conta da complexidade do conversor. ]

3. **Sobre a Falsa Segurança do Processo 8:** Se o Alex da Infra instalou o Docker, VM e banco de dados remotamente, por que ocorrem surpresas de hardware quando o analista chega lá presencialmente no Processo 9? A validação remota é incompleta?
> **Minha Resposta:** [Na prática não deveria ocorrer essas surpresas, porém há casos que a culpa/responsabilidade é do cartório por não ter nos informado anteriormente sobre alguma particularidade ou nos passou a informação errada de Hardware. O Alex acessa somente o servidor (Na etapa da Configuração do Ambiente), as máquinas ele preenche na Análise de Ambiente de acordo com o que o cliente passa para ele. Quando se trata de problemas ou inadequações no servidor, o Alex sempre identifica antes de o implantador ir para lá presencialmente. Porém podem ocorrer surpresas no servidor que ocorrem após a virada da conversão, as vezes travamentos do servidor, desligamentos, etc.  Isso é raro mas é devido a quantidade de dados movidos pela conversão e é impossível prever problemas como esse antes da conversão.]

4. **Sobre o Rollback de Madrugada:** É domingo de madrugada, o banco corrompeu, a migração falhou. O cartório abre daqui a poucas horas. A Diretoria não atende o celular. O que o analista tem autonomia/permissão para fazer? Ele aperta o botão vermelho por conta própria?
> **Minha Resposta:** [Não sei responder ao certo. Acredito que o essencial é aguardar o outro dia e comunicar a Diretoria primeira coisa pela manhã para entendermos melhor o problema, acionar a equipe de Produtos, ou Conversão ou TI de acordo com o problema e estudar qual seria a solução a se tomar, em conjunto com o cliente e a Diretoria.]

5. **Sobre o Buraco Negro de Produtos:** O cartório precisa de uma funcionalidade crítica que a Siplan não tem (ex: integração com prefeitura local). O time de Produtos diz que demora 4 meses. Qual o protocolo comercial para esse caso? A implantação é cancelada, adiada ou feita pela metade?
> **Minha Resposta:** [Nesse caso a implantação fica em pausa, sem passar para as próximas etapas até a finalização do desenvolvimento da rotina solicitada. Tudo isso é acordado com o cliente pelo Comercial ou pela Diretoria. Mas nunca fazemos a implantação pela metade, nós simplesmente pausamos até estar finalizado, por isso a aderência é uma das primeiras etapas ao chegar o chamado para implantação, para identificar essas necessidades o quanto antes e poupar tempo. A não ser que seja uma coisa que requer muito esforço de desenvolvimento ou poderia quebrar/corromper outras rotinas, Então tudo é passado para o cliente para definir como seguir, entender se essa necessidade é primordial e imprescindível para o cliente ou não, e de acordo com a definição nós seguimos da melhor maneira para ambos os lados.]

6. **Sobre o "Kill Switch" de Projetos:** Após quantos dias de silêncio/inércia do cliente em resolver sua infraestrutura precária a Siplan cancela ou arquiva o contrato formalmente? Existe uma multa ou o projeto fica adormecido eternamente?
> **Minha Resposta:** [Basicamente o projeto fica adormecido/pausado. Atualmente temos clientes que o contrato e implantação não foram canceladas mas estamos há quase 1 ano aguardando as adequações. Nesse caso o Comercial faz o follow up mas não podemos fazer nada a não ser esperar e acompanhar.]

---
**Quando terminar de responder a todas as perguntas cirúrgicas, me avise no chat para eu consolidar essas verdades nas notas oficiais.**