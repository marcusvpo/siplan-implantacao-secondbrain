---
tipo: trap
project: general
tags:
  - #conversao
  - #infraestrutura
  - #imagens
created: 2026-06-08
provenance: 1.0
---
# [Gargalo] Espaço em Disco para Imagens GED

A conversão e migração de imagens, especialmente do GED de sistemas legados (como o Control-M PRO), representa um ponto crítico e fonte comum de problemas nas implantações.

## Contexto Técnico
O processo de conversão de imagens (geralmente de TIF para PDF) e a subsequente importação para a infraestrutura Docker em Linux exigem temporariamente o **dobro do espaço** de armazenamento original do cartório.

## Impacto
A falta de espaço em disco no momento da conversão paralisa o processo, atrasando o cronograma do final de semana de virada e, em muitos casos históricos, resultou em implantações liberadas sem as imagens antigas, gerando um "rabo técnico" (backlog) significativo para a Siplan.

## Mitigação (Decisão)
Foi definido que, durante a fase de **Análise de Aderência**, o Analista de Implantação deverá mapear todas as pastas de imagens que o cliente utiliza e **estimar o volume total (em GB)**. Essa informação será cruzada antecipadamente com a Equipe de Infraestrutura e Conversão para dimensionamento do servidor.

## Fontes
- [[Resumo das Reuniões com Implantadores por Tópicos]]

## Links
- [[[Processo] 5. Conversão do Banco de Dados]]
- [[[Processo] 2. Levantamento de Infraestrutura]]
