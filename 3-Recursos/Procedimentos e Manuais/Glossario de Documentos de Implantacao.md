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
- **O que é:** Questionário técnico e estrutural investigativo centralizado no **Siplan HUB**, gerado dinamicamente a partir de um editor de formulários com **versionamento** na Área dos Implantadores.
- **Objetivo:** Mapear a infraestrutura periférica, regras de negócio, quantidade de colaboradores/setores, espaço em disco de imagens (GED) e eventuais gaps impeditivos para garantir o enquadramento do sistema e dimensionar a implantação.
- **Evolução:** Abandonou totalmente o uso de arquivos externos `.docx`. Agora tudo é gerado, respondido, cadastrado e salvo diretamente no Hub, sincronizado em tempo real com a etapa de Análise de Aderência do cliente/projeto.
- **Referência no Vault:** [[[Processo] 3. Análise de Aderência do Processo de Negócio]] | [[[Modelo] Template - Analise de Aderencia]]

## 2. Levantamento de Infraestrutura / Análise de Ambiente (TI)
- **O que é:** Coleta técnica e automatizada de dados de hardware e rede gerada via **Link Público** exclusivo no Siplan Hub.
- **Objetivo:** Coletar dados reais de hardware (memória RAM, núcleos de processador, espaço em disco, sistema operacional, portas e rede) através de scripts executados nas máquinas/servidor do cartório. Serve como *Gate Condicional* obrigatório para impedir o avanço de projetos com infraestrutura defasada.
- **Evolução:** Substituiu as antigas planilhas manuais (`.ods`/Excel). A TI do cartório baixa o script no link público, executa no parque de máquinas, sobe os arquivos `.txt` e o Hub preenche o inventário e valida a conformidade contra os requisitos mínimos de forma 100% automática.
- **Referência no Vault:** [[[Processo] 2. Levantamento de Infraestrutura]]

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