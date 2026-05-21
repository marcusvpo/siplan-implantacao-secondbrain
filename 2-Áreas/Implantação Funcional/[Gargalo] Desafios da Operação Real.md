---
tipo: Gargalo
area: Implantação Funcional
tags:
  - #gargalo
  - #estrategico
  - #capacidade
---
# [Gargalo] Desafios da Operação Real de Implantação

Esta nota consolida as dores e limitações identificadas no cotidiano da equipe de implantação da Siplan, servindo como base para propostas de melhoria.

## 1. Conflito de Capacidade (Campo vs. Back-office)
O principal gargalo é a **dualidade de funções** dos analistas de implantação.
- **O Problema:** Os 6 analistas técnicos são os mesmos que viajam para implantação presencial (2 semanas por projeto) e os que realizam Análise de Aderência e Homologação de Conversão.
- **Consequência:** Quando os analistas estão em campo, as etapas remotas de outros 28 projetos em andamento ficam travadas ou atrasadas.
- **Mitigação Atual (Apagão de Homologações):** Não existe SLA formalizado. Quando o analista responsável está em campo, tenta-se repassar a demanda para outro analista livre. Se todos estiverem ocupados, a equipe de Conversão é acionada para tentar homologar o próprio trabalho. Em último caso, o analista faz a homologação aos finais de semana ou nos primeiros dias da implantação presencial, comprimindo o cronograma.

## 2. Abismo de Comunicação e a "Sombra do 0800"
Existe uma ferramenta robusta (Hub Siplan), mas seu uso não é democratizado.
- **O Problema:** Apenas um responsável centraliza as atualizações no Hub. Os analistas de implantação estão acostumados a registrar suas atividades diárias exclusivamente através de "trâmites" longos e não-estruturados no sistema legado de chamados (SAC 0800).
- **Consequência:** O Hub não reflete a realidade em tempo real. O Comercial fica "cego" sobre o status das implantações.
- **Esclarecimento de Arquitetura:** O objetivo do Hub **não é substituir o 0800**. O 0800 continua sendo a central oficial e ponto de contato integrado ao SAP. O Hub entra como um orquestrador paralelo para centralizar as informações soltas (boca a boca) e consolidar os dados do projeto, sem forçar o abandono do 0800.
- **Janela de Oportunidade:** Existe uma janela de **Rollout do Hub programada para a reunião presencial de 25 a 29 de Maio**, onde os analistas receberão treinamento para transicionar os registros gerenciais e paralelos para a nova plataforma.

## 3. Desalinhamento Vendas vs. Entrega e o "Sprint da Última Semana"
O setor Comercial foca no fechamento da venda, muitas vezes ignorando a capacidade técnica e repassando informações incompletas.
- **Venda de Horas Insuficientes:** Fechamento de 40h para sistemas que exigem 80h (como TN e REG). 
  - *Resolução Prática:* O Comercial define em negociação que horas excedentes serão cobradas do cliente posteriormente. Isso frequentemente gera atrito e indignação no cliente ("mas vocês venderam 40h").
  - *Mitigação Recente:* Diretoria instruiu o Comercial a não flexibilizar. Mínimo de 40h para Orion PRO e 80h para Orion TN/REG.
- **Agendamento "Pelo Lado" (Bypass de Viabilidade):** O Comercial frequentemente aborda o Coordenador de Implantação diretamente via Teams durante a negociação para checar a disponibilidade de um analista específico (ex: "como tá a agenda do fulano no mês X?"), já pré-agendando com o cliente antes do contrato fechado. A palavra final do agendamento, na prática, tem vindo do Comercial.
- **Janela de Ação Frenética:** A preparação técnica é comprimida na **semana anterior à implantação presencial**.

## 4. Inconstância na Conversão de Dados
- **Sistemas Desconhecidos:** Quando o cartório usa um sistema que a Siplan nunca converteu, o prazo é imprevisível.
- **Priorização Reativa:** A fila de conversão sofre interrupções constantes para atender correções de clientes que já viraram, atrasando as novas implantações.

## 5. Pós-Implantação e Transição de Suporte (WhatsApp vs. 0800)
A dependência de grupos de WhatsApp no pós-implantação gera um suporte "paralelo" que mascara o esforço da equipe, mas existe uma regra de transição estabelecida:
- **Período de Transição:** O suporte pelo WhatsApp é tolerado e encorajado nas primeiras **2 a 4 semanas** após a virada. Isso se justifica pela curva de aprendizado (mudança drástica de operação para o cartório) e necessidade de contato direto e rápido com o implantador.
- **Encerramento e Hard Cut:** Assim que o pós-implantação é finalizado, encerra-se o uso do WhatsApp. O canal oficial para qualquer erro, bug, dúvida ou nova solicitação passa a ser **exclusivamente o 0800**, entrando para a fila do Service Desk (SD). Quando clientes tentam "furar fila" ligando direto na Siplan, são orientados a abrir chamado no 0800.

---
**Próximos Passos Sugeridos:**
- [ ] Implementar um "Score de Risco" no Hub para projetos com datas agendadas vs. etapas pendentes.
- [ ] Criar incentivos ou obrigatoriedade de atualização do Hub pelas equipes técnicas.
- [ ] Alinhar com o Comercial um checklist mínimo de viabilidade técnica antes da promessa de data.
