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
