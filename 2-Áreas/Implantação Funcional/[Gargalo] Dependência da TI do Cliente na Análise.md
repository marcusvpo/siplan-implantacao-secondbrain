---
tipo: trap
project: general
tags:
  - #infraestrutura
  - #aderencia
  - #riscos
created: 2026-06-08
provenance: 1.0
---
# [Gargalo] Dependência da TI do Cliente na Análise

Um dos maiores riscos para o cronograma e sucesso da implantação é a dependência de informações e acessos fornecidos pela TI (interna ou terceirizada) do próprio cartório.

## Contexto e Impacto
- **Falta de Acesso:** Em alguns casos, a TI do cartório recusa acesso (via TeamViewer) e prefere preencher planilhas por conta própria.
- **Informações Superficiais:** Há o risco constante de o TI do cliente fornecer respostas vagas ou "maquiadas" (ex: "As máquinas são novas", sem especificar; ou afirmar que "está tudo OK" quando não está) para não expor fragilidades de sua gestão.
- **Promessas Não Cumpridas:** O cliente promete adequar o servidor (memória, recursos) mas não cumpre até o dia da virada, causando lentidão, travamentos e instabilidade. A culpa recai erroneamente sobre o sistema Siplan.

## Mitigação

1. **Automação via Link Público e Scripts:** Substituição do preenchimento manual de planilhas por **scripts automatizados de auditoria de hardware**. O TI do cartório baixa o script via link público do Siplan Hub, executa nas máquinas/servidores e faz upload do `.txt` gerado. O Hub processa os dados reais e valida automaticamente contra os requisitos mínimos, eliminando respostas subjetivas ou maquiadas.
2. **Gate de Validação Pré-Viagem:** Realizar obrigatoriamente uma checagem (check-up técnico) na semana anterior à implantação presencial para confirmar se as adequações e upgrades sinalizados pelo Hub foram efetivamente cumpridos.
3. **Análise Presencial Estratégica:** Quando o cliente migra de sistemas de terceiros (externos), manter análises investigativas presenciais focadas nas rotinas operacionais e particularidades do negócio.

## Fontes
- [[Resumo das Reuniões com Implantadores por Tópicos]]

## Links
- [[[Processo] 2. Levantamento de Infraestrutura]]
- [[[Processo] 3. Análise de Aderência do Processo de Negócio]]
