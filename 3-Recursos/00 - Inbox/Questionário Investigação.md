# Questionário: Investigação Profunda Operação Siplan

**Instruções:** Responda as perguntas abaixo logo após cada "R: ". Quando terminar, avise no chat que o arquivo foi atualizado.

---

### A. Sobre a Orquestração e o seu Papel (O "Cérebro")

**1. O Gatilho de Pressão:** 
Quando a Maria avisa que "o cartório quer implantar dia 15" e a equipe de Conversão diz "não conseguimos entregar a base antes do dia 12", quem arbitra esse conflito? Você, a Maria, ou a Diretoria?
**R:** Eu entro em contato com a equipe de Conversão para entender melhor, passo para a Diretoria e com o aval da diretoria eu peço para a Maria contactar o cliente e informar sobre essa impossibilidade.

**2. Priorização:** 
Como você decide qual projeto é mais importante? Existe uma regra clara (ex: "quem pagou mais", "quem está esperando há mais tempo", "cartório maior") ou é no feeling?
**R:** Normalmente quem nos passa essa prioridade é o Comercial, acredito que de acordo com a relevância do cartório, urgência do prazo contratado e o valor da mensalidade contratada.

---

### B. Sobre a Preparação de Ambiente (TI)

**3. Dependência do Cliente:** 
O Alex faz a Análise de Ambiente. Mas quando a TI do cartório precisa comprar um servidor novo, o projeto entra em "Espera". Quem cobra a TI do cartório semanalmente para saber se o servidor já chegou? O Alex, você, ou o Comercial?
**R:** Quem faz essa cobrança e nos deixa informado é o Comercial, pois estão em contato direto com o cliente, porém muitas das vezes eu mesmo que cobro o Comercial para eles cobrarem o cliente pois as vezes eles não fazem esse acompanhamento. Mas a comunicação e negociação é sempre do Comercial com o cliente.

**4. Instalação Remota (Configuração):** 
O processo diz que a instalação remota (configuração de Docker/VM) ocorre antes do analista viajar. Isso costuma dar problema de firewall ou bloqueio de rede no cartório na última hora? Como o Alex contorna isso?
**R:** Não, o próprio Alex já garante que não dê esses problemas. Ele conecta direto no servidor do cartório e em alguma máquina para deixar tudo isso já pré configurado. O Analista nos primeiros dias são responsáveis por instalar o sistema no restante das máquinas e fazer as configurações/parametrizações iniciais, por isso o servidor já deve estar 100% pronto e configurado para as maquinas receberem o sistema.

---

### C. Sobre a Homologação e Conversão

**5. O Retrabalho:** 
Quando o Implantador (ex: Ricardo) faz o "De-Para" da homologação e acha erros, ele manda email para a Conversão (ex: Luciane). A Luciane costuma resolver isso em 1 dia, ou o projeto volta pro final da fila da conversão e demora uma semana?
**R:** Nesse caso essas inconsistências sempre entram em primeiro lugar na fila de prioridade da Conversão, pois a homologação sempre é feita na semana anterior e a própria equipe de conversão fica aguardando o retorno do Implantador sobre a homologação justamente para corrigir as inconsistências apontadas logo em seguida para não haver nenhum atraso.

**6. Bases Corrompidas:** 
Já aconteceu de a base do sistema legado vir corrompida ou bloqueada por senha do concorrente? O que a equipe de Conversão faz nesse caso?
**R:** Sim, normalmente eles entram em contato com o cartório e o TI do cartório para identificar onde está o problema. Na maioria das vezes da certo, porém quando são sistemas que nós nunca trabalhamos, a equipe de conversão ainda nao tem o Motor de Conversão (ou Conversor) pronto, então eles tem que estudar minuciosamente a base para entender como fazer o relacionamento com a base do nosso sistema. Algumas vezes há criptografias e aí eles entram em contato com a empresa do outro sistema e pede suporte, normalmente sempre da certo, porém essa questão de criação do Conversor demora meses.

---

### D. Sobre o Pós-Implantação

**7. O Grupo de WhatsApp:** 
Você mencionou que o CS/CX (Henrique e Bruna) cuida do Pós-Implantação pelo WhatsApp. Quando o cartório relata um "bug" crítico no WhatsApp no dia seguinte à virada, o Henrique abre um chamado no 0800 para a equipe de Produtos, ou ele liga direto para o Implantador que acabou de sair de lá?
**R:** No dia seguinte da virada ainda temos o implantador em campo justamente para esses casos. Ele estando lá presencialmente alguns dias após a virada é vital para o processo de implantação. Normalmente as agendas dos Implantadores funciona assim:

Para o Orion PRO - 40h mínimo (1 semana)
Segunda e Terça - Configurações e Treinamento
Noite de Terça para Quarta - Conversão roda a virada do sistema fora do horário comercial
Quarta até Sexta - Acompanhamento do implantador com o sistema já rodando em produção, para dar todo o suporte, tirar dúvidas e corrigir possíveis erros.

Para o Orion TN e Orion REG - 80h mínimo (2 semanas)
Segunda a Sexta (semana 1) - Configurações e parametrizações nos primeiros dois dias (Segunda e Terça) e Treinamento no restante da semana (Quarta até Sexta)
Sexta após o expediente (e também durante o final de semana se necessário) - Roda a conversão para a virada do sistema
Segunda a Sexta (semana 2) - Já inicia a semana com o sistema em produção e o acompanhamento contínuo do Implantador, para dar suporte, tirar dúvidas e corrigir possíveis erros.

Após o fim da implantação e a saída do Implantador do cartório, inicia-se o Pós Implantação com duração média de mais 2 semanas, com um contato bem próximo via grupos de Whatsapp com o cliente e nossa equipe de Pós e SD.

---

Atualizar Informações Equipe Pós Implantação

(As próprias equipes se organizam internamente para definir quem vai ficar com qual cliente no Pós, eu não participo dessa atividade/processo)

Pós Implantação Orion TN:
Erik Marques
Henrique Troiano
Quando há agenda, os implantadores também participam do pós mas não é comum.

Pós Implantação Orion PRO:
Klerison
Alana
Quando há agenda, os implantadores também participam do pós mas não é comum.

Pós Implantação Orion REG:
Romário
Luiz
Quando há agenda, os implantadores também participam do pós mas não é comum.