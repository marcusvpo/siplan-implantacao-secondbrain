---
tipo: Regra
area: Implantação Funcional
tags:
  - #implantacao
  - #documentacao
---
# Glossário de Documentos de Implantação

Durante o ciclo de vida de uma implantação, a equipe técnica da Siplan produz e assina diversos documentos que garantem a rastreabilidade, segurança jurídica do projeto e a correta passagem de bastão entre os setores.

Abaixo estão descritos os principais documentos operacionais (modelos encontrados no repositório de implantação) e suas finalidades:

## 1. Análise de Aderência
- **O que é:** Questionário técnico e estrutural respondido pelo cliente junto ao analista.
- **Objetivo:** Mapear a infraestrutura periférica, regras de negócio, quantidade de funcionários e particularidades operacionais para garantir que o sistema da Siplan atenda à serventia e para dimensionar o esforço de implantação.
- **Evolução:** Foi unificado do antigo modelo de checklist simples (PRO/TN) para o modelo robusto investigativo (inspirado no REG).
- **Referência no Vault:** [[[Modelo] Template - Analise de Aderencia]]

## 2. Análise de Ambiente (TI)
- **O que é:** Planilha (geralmente `.ods` ou Excel) preenchida pela equipe de Infraestrutura/TI (ex: Alex) no Início do Projeto.
- **Objetivo:** Coletar dados de hardware (memória RAM, processador, espaço em disco, versão do banco de dados, antivírus e rede). Serve como *Gate Condicional* para não enviar o analista de implantação a um cartório com infraestrutura incapaz de rodar o sistema.

## 3. Checklist de Implantação
- **O que é:** Um roteiro passo-a-passo no formato de "to-do list".
- **Objetivo:** Guiar o analista *durante* a semana de implantação. Contém os passos lógicos de instalação (Instalação do Banco, do Sistema, Liberação de Licença, Configuração de Divisores, Parametrização de Selos). Garante que nenhuma etapa técnica da instalação seja esquecida na pressa do dia a dia.

## 4. Catálogo de Conversão
- **O que é:** Documento formal em PDF assinado pelo cliente e pelo líder do projeto/analista.
- **Objetivo:** Detalhar exatamente quais dados lógicos foram migrados do sistema antigo para o novo (ex: Protocolos, Recibos, Sinal Público, Cartões de Assinatura, Mensalistas). Funciona como o "Termo de Aceite" de que a equipe de Conversão da Siplan cumpriu sua parte e que o cliente validou os dados migrados na Fase 6 de Homologação.

## 5. Documento de Transição de Conhecimento (Handoff)
- **O que é:** Formulário utilizado no término do projeto ou na transição de fases.
- **Objetivo:** Formalizar a passagem de bastão (Handoff) da equipe de Implantação para a equipe de Suporte (Service Desk).
- **Conteúdo:** 
  - Dados dos Analistas e do Cartório (Key Users, Telefones).
  - Versão exata instalada (Sistema e Banco de Dados PostgreSQL).
  - Dados de Acesso (Senhas do Postgres, IDs de TeamViewer/AnyDesk).
  - Resumo narrativo de como foi o processo de implantação (Ex: "Organizei os treinamentos com o pessoal do balcão, migração de dados OK, deixado sistema legado para consulta...").

## 6. Relatório de Atendimento Técnico (RAT)
- **O que é:** Relatório oficial de horas trabalhadas e serviços prestados.
- **Objetivo:** Registrar as horas consumidas (viagem, treinamento, configuração) contra as horas vendidas no contrato. É assinado pelo cliente ao final da viagem, servindo como base administrativa para possível faturamento de horas excedentes (caso o projeto exija e o Comercial tenha negociado).