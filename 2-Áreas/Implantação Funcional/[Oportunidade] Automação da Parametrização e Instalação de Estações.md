---
tipo: pattern
project: general
tags:
  - #implantacao
  - #automacao
  - #eficiencia
created: 2026-06-08
provenance: 1.0
---
# [Oportunidade] Automação da Parametrização e Instalação de Estações

Existe uma grande oportunidade de otimizar o tempo do analista em campo deslocando atividades puramente técnicas e repetitivas para o backoffice (equipe interna/júnior), antes da implantação presencial.

## Contexto e Dores
- **Repetição:** A parametrização de bases no cartório exige repetição manual ("Ctrl C + Ctrl V" de perfis, layouts) e configurações padronizadas de segurança que tomam de 4 a 5 horas ou mais da agenda em campo.
- **Falta de Exportação:** Não há hoje uma forma simples de exportar configurações padrão (via JSON ou TXT) entre bases devido ao atrelamento dos parâmetros ao Cadastro Nacional de Serventias (CNS).
- **Tempo nas Estações:** Instalar o integrador e criar atalhos em dezenas de máquinas consome tempo que deveria ser destinado ao treinamento dos usuários.

## Iniciativas (To-Be)
1. **Transferência de Responsabilidade:** Que a equipe de infra/backoffice assuma remotamente a instalação do integrador nas estações antes da chegada do implantador.
2. **Ferramenta de Automação:** Há expectativa em torno de uma nova ferramenta desenvolvida internamente (Kleverson/Diego) que automatizará a criação das VMs, Docker e bancos de dados pré-parametrizados, reduzindo drasticamente o trabalho em campo.

## Fontes
- [[Resumo das Reuniões com Implantadores por Tópicos]]

## Links
- [[[Processo] 8. Instalação Remota do Sistema Siplan]]
- [[[Processo] 9. Implantação no Cartório - Treinamento e Configuração]]
