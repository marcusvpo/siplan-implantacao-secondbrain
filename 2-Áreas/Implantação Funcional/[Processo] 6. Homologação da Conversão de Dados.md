---
tipo: Processo
fase_implantacao: "6. Homologação"
responsavel: Analista de Implantação
dependencia: "[[[Processo] 5. Conversão do Banco de Dados]]"
tags:
  - #implantacao
  - #conversao
status_atual: #ativo
---
# [Processo] 6. Homologação da Conversão de Dados

Garantia da integridade das informações migradas. É crucial notar que **a equipe de Conversão NÃO realiza a homologação**; o papel deles termina na disponibilização da base. A validação é responsabilidade exclusiva do Analista de Implantação (linha de frente).

## Execução (O "De-Para")
Após a primeira conversão (base provisória), o Analista de Implantação conecta-se remotamente ao servidor do cartório e realiza um teste de "De-Para":
1. Abre o sistema legado (antigo) diretamente no ambiente do cliente.
2. Abre o novo sistema Siplan (convertido) no nosso ambiente.
3. Compara visualmente e estruturalmente se os dados migraram para os lugares corretos e se as lógicas foram mantidas. Este processo muitas vezes é feito em conjunto com um funcionário do cartório.

## Feedback e Retrabalho
- **Sucesso:** Base pronta para testes e treinamento. Avança para [[[Processo] 7. Agendamento da Implantação Funcional]].
- **Inconsistências Encontradas:** O Analista de Implantação documenta os erros e **envia um e-mail** para a Equipe de Conversão solicitando os ajustes.
  - *Prioridade Absoluta:* Como a homologação ocorre na semana anterior à implantação e a Equipe de Conversão fica de prontidão aguardando esse retorno, esses ajustes **entram em primeiro lugar na fila** da Conversão para não causar nenhum atraso na viagem. O projeto retorna temporariamente ao status de conversão até que a base seja liberada.

## ⏱️ Regras de SLA e Capacidade de Homologação
- **Complexidade da Validação:** 
  - **Sistemas Legados Complexos/Desconhecidos (Concorrentes):** A homologação exige extrema cautela, reservando-se obrigatoriamente de **2 a 3 dias** do analista para a tarefa.
  - **Sistemas Legados Siplan (Control-M):** Validação simplificada e rápida, já que as tabelas de equivalência e conversores estão consolidados.
- **Contingência de Indisponibilidade de Analistas:**
  - Se todos os implantadores estiverem em campo e não houver ninguém livre para homologar, a liderança aciona a equipe de Conversão para verificar se o próprio conversor consegue fazer a homologação.
  - Como plano B, solicita-se ao implantador para homologar a base no final de semana imediatamente anterior à viagem, ou nos primeiros dias presenciais em campo junto com a parametrização inicial.

## 🚀 Visão de Futuro & Ideias (To-Be)

- **Prazo Estendido:** A homologação deverá ter um tempo maior de execução antes da semana da implantação presencial, garantindo mais tempo hábil para testes.
- **Formulário/Checklist de Homologação no HUB:** Os implantadores deverão criar um checklist de homologação padronizado para todos os sistemas. Essa função será alocada na nova tela "Implantadores > Checklist Homologação" no HUB, funcionando como um criador/editor de formulários semelhante ao de Aderência.
- **Relatório de Inconsistências:** O envio do arquivo Word com inconsistências via e-mail para a equipe de Conversão está fluindo bem e será mantido como padrão.
- **Pré-homologação por Conversão:** Verificar a viabilidade da equipe de Conversão (ou uma equipe dedicada) realizar uma pré-homologação "campo a campo" validando os dados contra os layouts do SharePoint antes de liberar para o Implantador.
- **Checklist Padrão:** Criação do checklist padrão de homologação guiado por fluxos (top-down) no Siplan HUB, em contraposição a análises infinitas focadas apenas nos dados brutos.
- **Pré-Homologação pela Conversão (Bottom-up):** A equipe de Conversão passará a realizar uma pré-homologação exaustiva, validando dados contra o layout e usando relatórios de batimento quantitativo de origem/destino antes de liberar a base para o Implantador.
