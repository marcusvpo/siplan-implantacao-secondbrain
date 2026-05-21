---
tipo: Processo
fase_implantacao: "10. Virada para Produção"
responsavel: Analista de Implantação e Equipe de Conversão
dependencia: "[[[Processo] 9. Implantação no Cartório - Treinamento e Configuração]]"
tags:
  - #implantacao
  - #conversao
  - #virada
status_atual: #ativo
---
# [Processo] 10. Virada para Produção

Transição definitiva do cartório para o novo sistema Siplan. 

## 📋 Cenário Atual (As-Is)

**Execução da Virada:**
A Equipe de Conversão realiza a **conversão final** a partir do banco de dados legado atualizado. O cartório inicia a operação exclusivamente no Siplan na manhã seguinte, e o implantador dedica o resto da sua agenda semanal presencial ao acompanhamento em produção. (Detalhes de datas em [[[Regra] Cronograma e Virada por Sistema]]).

**Rollback e Contingência (Unhappy Path):**
Em cenários de falhas extremas durante a implantação (bugs bloqueantes inoperáveis), existe o procedimento de **Rollback Oficial**.
- **Segurança dos Dados:** Como os dados sempre são armazenados no servidor físico de propriedade do cartório (junto ao banco de dados), não há grande risco de perda de dados caso ocorra um retorno ao sistema legado. O legado é sempre mantido instalado localmente.
- **Autoridade de Rollback:** Somente a **Diretoria** possui a autoridade final para decretar o Rollback, baseada na análise técnica em tempo real.
- **Protocolo de Madrugada (Falha fora do horário comercial):** Se o banco corromper de madrugada num fim de semana (comum nas viradas do Orion TN/REG) e a Diretoria estiver inalcançável:
  - O analista **não** tem autonomia para decretar o Rollback e apertar o botão vermelho por conta própria.
  - A orientação primária é aguardar a manhã do dia seguinte e comunicar imediatamente a Diretoria logo no primeiro horário.
  - A partir do alinhamento matinal, aciona-se as equipes (Produtos, Conversão ou TI) para estudar a viabilidade de correção rápida em conjunto com o cliente e a Diretoria, antes de recorrer ao Rollback.

## 🚀 Visão de Futuro & Ideias (To-Be)

- **Métricas de Contingência:** Desenhar critérios técnicos mais objetivos para classificar o que constitui uma "falha crítica", agilizando a comunicação entre os implantadores em campo e a Diretoria.
- **Aperfeiçoamento do Protocolo de Retorno:** Estruturar um checklist de ações imediatas e protocolos de emergência de fim de semana, garantindo autonomia guiada (via Playbook) caso a Diretoria esteja inalcançável às vésperas do cartório abrir o balcão.