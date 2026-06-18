---
tipo: Recurso
area: Implantação Funcional
tags:
  - #rag
  - #index
  - #organizacao
  - #mapeamento
status_atual: #ativo
---
# [Recurso] Obsidian RAG Index

Este documento constitui o **Índice RAG (Retrieval-Augmented Generation Index)** definitivo do Vault do Obsidian para o projeto *Siplan - Implantação*. Ele atua como um catálogo semântico de metadados e resumos operacionais de todos os arquivos Markdown (`.md`) do repositório, facilitando a rápida localização, contextualização e recuperação de informações estruturadas pelas IAs e pela equipe técnica.

O índice está organizado de acordo com as metodologias **P.A.R.A. (Projetos, Áreas, Recursos, Arquivo)** e **Zettelkasten (Notas Atômicas)**.

---

## 🗂️ 1. MOCs (Maps of Content) - Os Hubs de Conectividade
Os MOCs funcionam como índices temáticos ou "hubs" que conectam notas atômicas do ecossistema.

| Nome do Arquivo / Link | Caminho do Arquivo | Tipo de Conteúdo | Resumo Operacional |
| :--- | :--- | :--- | :--- |
| [[MOC - Fluxo de Implantação\|MOC - Fluxo de Implantação]] | `2-Áreas/Implantação Funcional/MOC - Fluxo de Implantação.md` | MOC / Processos | Mapeia as 10 etapas lógicas e sequenciais do processo de implantação de software da Siplan, desde o fechamento comercial até o Go-Live. |
| [[MOC - Siplan Hub\|MOC - Siplan Hub]] | `2-Áreas/Siplan Hub/MOC - Siplan Hub.md` | MOC / Hub | Centraliza a documentação operacional e técnica sobre o Siplan Hub, cobrindo o Dashboard, Módulo de Conversão, Gestão de Implantação e integrações n8n. |
| [[MOC - Mercado Cartorário\|MOC - Mercado Cartorário]] | `3-Recursos/Mercado Cartorário e CNJ/MOC - Mercado Cartorário.md` | MOC / Contexto | Consolida as notas de análise de mercado extrajudicial brasileiro, normativas regulatórias (CNJ, Provimentos) e iniciativas de IA aplicadas. |
| [[MOC - Produtos Siplan\|MOC - Produtos Siplan]] | `3-Recursos/Produtos Siplan/MOC - Produtos Siplan.md` | MOC / Portfólio | Mapa central da linha de produtos moderna (Arquitetura Orion: TN, PRO, REG, WEB RI) e das referências de migração dos sistemas legados. |
| [[MOC - Orion PRO\|MOC - Orion PRO]] | `3-Recursos/Produtos Siplan/Orion PRO/MOC - Orion PRO.md` | MOC / Produto | Detalha a arquitetura funcional, módulos (Caixa, Protocolo, Devolução) e integrações do sistema Orion PRO (Protesto). |
| [[MOC - Orion TN\|MOC - Orion TN]] | `3-Recursos/Produtos Siplan/Orion TN/MOC - Orion TN.md` | MOC / Produto | Detalha a arquitetura funcional, módulos (Firmas, Atos, Selos, Reprografia) e integrações do sistema Orion TN (Notas). |

---

## ⚙️ 2. Notas Atômicas de Processos e Workflows (`[Processo]`)
Notas que detalham etapas sequenciais, tomadas de decisão e fluxos operacionais específicos.

| Nome do Arquivo / Link | Caminho do Arquivo | Escopo / Módulo | Resumo Operacional |
| :--- | :--- | :--- | :--- |
| `[Processo] 1. Início do Chamado de Implantação` | `2-Áreas/Implantação Funcional/[Processo] 1. Início do Chamado...` | Implantação | Trata da abertura física do chamado após fechamento comercial e acionamento inicial das equipes técnicas no Hub. |
| `[Processo] 2. Levantamento de Infraestrutura` | `2-Áreas/Infraestrutura Técnica/[Processo] 2. Levantamento...` | Infraestrutura | Levantamento das especificações de hardware, rede, impressoras e sistema operacional do cartório cliente. |
| `[Processo] 3. Análise de Aderência do Processo de Negócio` | `2-Áreas/Implantação Funcional/[Processo] 3. Análise de Aderência...` | Implantação | Entrevista detalhada com o cliente para mapear o enquadramento do sistema Orion e dimensionar horas/treinamento. |
| `[Processo] 4. Tratamento de Impedimentos da Análise de Aderência` | `2-Áreas/Implantação Funcional/[Processo] 4. Tratamento de Impedimentos...` | Implantação | Workflow para mitigação de incompatibilidades e blockers detectados durante a análise de aderência. |
| `[Processo] 5. Conversão do Banco de Dados` | `2-Áreas/Conversão de Dados/[Processo] 5. Conversão...` | Conversão | Execução técnica de migração da base de dados legada (Firebird, SQL Server) para o PostgreSQL do Orion. |
| `[Processo] 6. Homologação da Conversão de Dados` | `2-Áreas/Implantação Funcional/[Processo] 6. Homologação...` | Implantação | Gate condicional em que o cliente confere e atesta a integridade e correção dos dados importados. |
| `[Processo] 7. Agendamento da Implantação Funcional` | `2-Áreas/Implantação Funcional/[Processo] 7. Agendamento...` | Implantação | Formalização e definição das datas de viagem do analista com o cliente (após homologação da base). |
| `[Processo] 8. Instalação Remota do Sistema Siplan` | `2-Áreas/Infraestrutura Técnica/[Processo] 8. Instalação Remota...` | Infraestrutura | Instalação técnica dos sistemas, banco e conexões de rede de forma remota antes da viagem do implantador. |
| `[Processo] 9. Implantação no Cartório - Treinamento e Configuração` | `2-Áreas/Implantação Funcional/[Processo] 9. Implantação no Cartório...` | Implantação | Acompanhamento presencial no cartório, treinamento com funcionários de balcão e ajustes operacionais. |
| `[Processo] 10. Virada para Produção` | `2-Áreas/Implantação Funcional/[Processo] 10. Virada...` | Implantação | A "Hora Zero". Execução da conversão final e entrada oficial do sistema Orion em produção (Go-Live). |
| `[Processo] 11. Transição para o Pós-Implantação` | `2-Áreas/Implantação Funcional/[Processo] 11. Transição...` | Implantação | Handoff formal do projeto para o Suporte Técnico (Service Desk) e fechamento do chamado. |
| `[Processo] Mapeamento AS-IS e TO-BE do Siplan Hub` | `2-Áreas/Siplan Hub/[Processo] Mapeamento AS-IS e TO-BE...` | Siplan Hub | Compara o fluxo antigo de gestão (informal) com o novo workflow centralizado e estruturado dentro do Hub. |

---

## 🛡️ 3. Notas Atômicas de Regras de Negócio e Diretrizes (`[Regra]`)
Notas que detalham políticas internas, cronogramas rígidos, obrigatoriedades e governança.

| Nome do Arquivo / Link | Caminho do Arquivo | Área de Aplicação | Resumo Operacional |
| :--- | :--- | :--- | :--- |
| `[Regra] Carga Horária Mínima e Venda Comercial` | `3-Recursos/Procedimentos e Manuais/[Regra] Carga Horária Mínima e Venda Comercial.md` | Comercial / Implantação | Estipula a carga mínima de horas para implantação de cada sistema e veta o subdimensionamento de horas nas vendas. |
| `[Regra] Cronograma e Virada por Sistema` | `3-Recursos/Procedimentos e Manuais/[Regra] Cronograma...` | Implantação / Infra | Estabelece os tempos mínimos de implantação e a janela restrita de final de semana para go-live de cada sistema. |
| `[Regra] Devolução Comercial via SAC 0800` | `3-Recursos/Procedimentos e Manuais/[Regra] Devolução Comercial...` | Comercial / Suporte | Procedimento para tratamento de insatisfações e cancelamento de contratos com canal direto de ouvidoria. |
| `[Regra] Diferença entre Instalação Remota e Implantação Funcional` | `3-Recursos/Procedimentos e Manuais/[Regra] Diferença entre...` | Implantação / TI | Segrega as responsabilidades técnicas (TI) das responsabilidades pedagógicas/treinamento (Implantação). |
| `[Regra] Formulário de Formalização de Treinamento como Defesa` | `3-Recursos/Procedimentos e Manuais/[Regra] Formulário...` | Implantação | Exige assinatura do cliente formalizando que recebeu treinamento, atuando como defesa jurídica contra contestações de uso. |
| `[Regra] Gates Condicionais de Início de Projeto` | `3-Recursos/Procedimentos e Manuais/[Regra] Gates Condicionais...` | Implantação | Define as pré-condições técnicas obrigatórias (como infra de TI pronta) sem as quais a viagem do implantador é proibida. |
| `[Regra] Relatório Formal de Benefícios e Ganhos Operacionais` | `3-Recursos/Procedimentos e Manuais/[Regra] Relatório Formal...` | Implantação / Pós | Roteiro para o analista demonstrar ao cartório os ganhos reais (tempo, economia) após a instalação da linha Orion. |
| `[Regra] Uso Obrigatório do Catálogo de Conversão` | `3-Recursos/Procedimentos e Manuais/[Regra] Uso Obrigatório...` | Conversão | Exigência de recolher o aceite formal e assinado da homologação de dados antes de autorizar a virada em produção. |
| `[Regra] Abreviações de Serventias e Mapeamento de Produtos` | `3-Recursos/Produtos Siplan/[Regra] Abreviações de Serventias...` | Geral / Mercado | Define a taxonomia de abreviações dos cartórios (TN, PT, RC, RI, TDPJ) e a correspondência das soluções Orion. |

---

## 🚨 4. Notas Atômicas de Gargalos Operacionais (`[Gargalo]`)
Notas que documentam os gargalos reais enfrentados durante a instalação, migração e suporte.

| Nome do Arquivo / Link | Caminho do Arquivo | Fase Impactada | Resumo Operacional |
| :--- | :--- | :--- | :--- |
| `[Gargalo] Dependência da TI do Cliente na Análise` | `2-Áreas/Implantação Funcional/[Gargalo] Dependência da TI...` | Levantamento / TI | Atrasos causados pela indisponibilidade ou lentidão da equipe ou parceiro de TI local do cartório em prover acessos. |
| `[Gargalo] Desafios da Operação Real` | `2-Áreas/Implantação Funcional/[Gargalo] Desafios da Operação...` | Implantação | Desafios diários e imprevistos na viagem, incluindo resistência à mudança de sistemas legados. |
| `[Gargalo] Espaço em Disco para Imagens GED` | `2-Áreas/Conversão de Dados/[Gargalo] Espaço em Disco...` | Conversão / Infra | Servidores de cartório estourando espaço físico de armazenamento devido ao grande volume de PDFs do legado migrado. |
| `[Gargalo] Dúvidas Operacionais no Service Desk` | `2-Áreas/Service Desk e Suporte/[Gargalo] Dúvidas Operacionais...` | Pós-Implantação | Sobrecarga de chamados de suporte simples causados por falta de autonomia e treinamento de escreventes. |

---

## 💡 5. Notas Atômicas de Oportunidades (`[Oportunidade]`)
Notas que apontam soluções tecnológicas para otimizar tempo, reduzir custos e automatizar tarefas.

| Nome do Arquivo / Link | Caminho do Arquivo | Módulo Focado | Resumo Operacional |
| :--- | :--- | :--- | :--- |
| `[Oportunidade] Automação da Parametrização e Instalação de Estações` | `2-Áreas/Implantação Funcional/[Oportunidade] Automação...` | Infra / Instalação | Proposta de scripts e instaladores automatizados para reduzir as horas de configuração manual em computadores. |
| `[Oportunidade] Evolução e Rollout do Hub` | `2-Áreas/Implantação Funcional/[Oportunidade] Evolução e Rollout...` | Siplan Hub | Melhorias de fluxo no Hub para controle gerencial de SLAs, prazos e gates. |
| `[Oportunidade] Evolução do Suporte para Autoatendimento e IA` | `2-Áreas/Service Desk e Suporte/[Oportunidade] Evolução...` | Service Desk | Criação de base de conhecimento conversacional (RAG) integrada para desafogar o atendimento humano. |

---

## 🏢 6. Notas Atômicas do Siplan Hub (`[Hub]`)
Documentos de design e mapeamento técnico sobre a plataforma interna de gestão de projetos.

| Nome do Arquivo / Link | Caminho do Arquivo | Módulo do Hub | Resumo Operacional |
| :--- | :--- | :--- | :--- |
| `[Hub] Conversão de Projetos` | `2-Áreas/Siplan Hub/[Hub] Conversão de Projetos.md` | Conversão | Gerenciamento de testes, fila e logs do banco de dados migrado de cada cartório. |
| `[Hub] Dashboard e Visão Estratégica` | `2-Áreas/Siplan Hub/[Hub] Dashboard...` | Geral / Gerência | Indicadores macros de projetos ativos, atrasos, SLAs e volumetria geral. |
| `[Hub] Estrutura de Telas e Diagnóstico de Uso` | `2-Áreas/Siplan Hub/[Hub] Estrutura de Telas...` | Frontend | Mapeamento de interface de usuário do Hub para melhoria da navegação. |
| `[Hub] Gestão de Implantação` | `2-Áreas/Siplan Hub/[Hub] Gestão de Implantação.md` | Implantação | Acompanhamento em tempo real da agenda e status das 11 fases de viagem do analista. |
| `[Hub] Gestão do OrionTN (Modelos Editor)` | `2-Áreas/Siplan Hub/[Hub] Gestão do OrionTN...` | Editor | Mapeamento de minutas JSON de escrituras e procurações editáveis no Hub para o Orion TN. |
| `[Hub] Integrações e Automações n8n` | `2-Áreas/Siplan Hub/Automações/[Hub] Integrações e Automações n8n.md` | Backend / n8n | Detalha as conexões automatizadas via webhooks do Hub disparando emails Outlook (Deep Links). |
| `[Manual] Guia Passo a Passo - Automações de E-mail Siplan HUB` | `2-Áreas/Siplan Hub/Automações/[Manual] Guia Passo a Passo - Automações de E-mail Siplan HUB.md` | Backend / n8n | Guia passo a passo definitivo para a configuração e implantação das automações de disparo de e-mail no n8n. |
| `[Conceito] Ideias Automações Disparo E-mail - Siplan HUB` | `2-Áreas/Siplan Hub/Automações/[Conceito] Ideias Automações Disparo E-mail - Siplan HUB.md` | Backend / n8n | Detalhamento de requisitos, escopo de campos e mapeamento de destinatários das automações propostas. |
| `[Hub] Relacionamento Comercial (CRM Interno)` | `2-Áreas/Siplan Hub/[Hub] Relacionamento Comercial...` | CRM | Registro de leads, fechamento de contratos e passagem do comercial para a implantação. |
| `[Hub] Mapeamento Prático e Funcional do Sistema` | `2-Áreas/Siplan Hub/[Hub] Mapeamento Prático...` | Geral | Detalhamento dos bancos de dados, conexões de redes e microsserviços integrados ao Hub. |

---

## 📦 7. Recursos Gerais (`[Recurso]`) e Contexto do Mercado
Materiais de apoio técnico e mercadológico da base de conhecimento.

| Nome do Arquivo / Link | Caminho do Arquivo | Categoria | Resumo Operacional |
| :--- | :--- | :--- | :--- |
| `[Recurso] Sistemas Legados Siplan e Control-M` | `3-Recursos/Produtos Siplan/[Recurso] Sistemas Legados...` | Produtos | Análise exaustiva dos 11 sistemas legados (linhas Siplan e Control-M) e tabelas de equivalência de migração. |
| `[Recurso] Glossário Mestre de Correção de Transcrições` | `3-Recursos/Procedimentos e Manuais/[Recurso] Glossário Mestre...` | Padronização | Dicionário de normalização de termos foneticamente truncados de reuniões transcritas (ex: ciplan -> Siplan). |
| `[Mercado] Perfil Heterogêneo e Baixa Maturidade Tecnológica` | `3-Recursos/Mercado Cartorário e CNJ/[Mercado] Perfil...` | Mercado | Análise do perfil técnico dos cartórios de pequeno porte em contraste com serventias altamente informatizadas. |
| `[Mercado] Transformação Digital e Pressão Regulatória (CNJ, LGPD)` | `3-Recursos/Mercado Cartorário e CNJ/[Mercado] Transformação...` | Regulatório | Impacto dos Provimentos 74/2018 e 134/2023 do CNJ na digitalização e conformidade dos cartórios. |
| `[Mercado] Uso de IA e Automação (Iniciativas como IARI)` | `3-Recursos/Mercado Cartorário e CNJ/[Mercado] Uso de IA...` | Mercado / IA | O uso de inteligência artificial no ambiente registral, como o registro eletrônico e assistentes inteligentes. |
| [[Modelo] Template - Analise de Aderencia] | `3-Recursos/Procedimentos e Manuais/[Modelo] Template...` | Template | Documento modelo investigativo utilizado pelo analista para mapear as rotinas do cartório cliente. |
| `Estrutura da Equipe e Especialidades` | `3-Recursos/Procedimentos e Manuais/Estrutura da Equipe...` | Organização | Detalha a estrutura organizacional da equipe de implantação, infraestrutura, conversão e service desk. |
| `Glossario de Documentos de Implantacao` | `3-Recursos/Procedimentos e Manuais/Glossario de Documentos...` | Organização | Explica a finalidade do RAT, CAT, Checklist, Handoff e Análise de Ambiente. |
