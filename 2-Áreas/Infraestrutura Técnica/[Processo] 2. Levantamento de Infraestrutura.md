---
tipo: Processo
fase_implantacao: "2. Levantamento de Infraestrutura"
responsavel: Equipe de Infraestrutura
dependencia: "[[[Processo] 1. Início do Chamado de Implantação]]"
tags:
  - #infraestrutura
  - #cross_infra
status_atual: #ativo
---
# [Processo] 2. Levantamento de Infraestrutura

Após a avaliação inicial, a primeira verificação técnica é determinar se o ambiente tecnológico do cartório cliente possui os requisitos mínimos para a correta operação do software Siplan.

## 📋 Fluxo Automatizado de Coleta e Validação (Siplan HUB)

O processo de **Levantamento de Infraestrutura** foi totalmente modernizado e automatizado através do **Siplan HUB**, eliminando planilhas manuais (`.ods`/Excel) e reduzindo a dependência de acessos remotos manuais via AnyDesk/TeamViewer:

### 1. Geração e Envio de Link Público
- **Geração no HUB:** Na etapa de Infraestrutura do projeto (`/projects/:id`), o sistema gera um **link público exclusivo** para o cliente.
- **Envio ao TI do Cartório:** O link é compartilhado diretamente com o responsável de TI (interno ou parceiro terceirizado) da serventia.

### 2. Execução dos Scripts de Coleta Automática
- **Download dos Scripts:** Na página pública acessada, o responsável de TI faz o download de scripts de coleta desenvolvidos pela Siplan.
- **Execução nas Máquinas e Servidores:** O TI executa o script no(s) servidor(es) e nas estações de trabalho de balcão e retaguarda.
- **Geração de Arquivo `.txt`:** O script realiza uma varredura completa do ambiente tecnológico (processador, quantidade de núcleos, memória RAM, discos/partições, versão do Sistema Operacional, rede, portas e antivírus) e compila os dados em arquivos estruturados no formato `.txt`.

### 3. Ingestão e Preenchimento Automático
- **Upload Simplificado (Drag & Drop):** O profissional de TI apenas arrasta/faz o upload dos arquivos `.txt` gerados diretamente na página do link público.
- **Leitura e Cadastro Automático:** O Siplan HUB realiza o *parsing* imediato dos arquivos, cadastrando e preenchendo automaticamente o inventário completo de hardware e estações na etapa de infraestrutura do projeto.

### 4. Validação Automática de Conformidade (Adequado vs. Inadequado)
- **Cruzamento com Recomendações Mínimas:** O sistema cruza instantaneamente os dados ingeridos com os parâmetros técnicos e recomendações mínimas homologadas para a linha de produtos Siplan (Orion TN, Orion PRO, Orion REG):
  - Ex: Servidor com mínimo de 6 cores, 20GB de RAM dedicada, modelo de nuvem/local, link de internet redundante e compatibilidade de SO.
- **Status Instantâneo:** O HUB indica automaticamente se o ambiente está **Adequado** (liberando o projeto) ou **Inadequado** (apontando exatamente quais máquinas ou componentes estão fora da conformidade).

---

## ⛔ Tratamento de Impedimentos (Gate Condicional)

- **Ambiente Adequado:** O gate de infraestrutura é aprovado automaticamente, permitindo o avanço sincronizado para a [[[Processo] 3. Análise de Aderência do Processo de Negócio]] e fila de conversão.
- **Ambiente Inadequado:** 
  - O HUB destaca as inconsistências e itens reprovados.
  - A equipe técnica aciona o botão de **Notificar Comercial** ou dispara o relatório técnico formal diretamente ao cartório.
  - O projeto é pausado até que o cartório providencie os upgrades de hardware ou correções de rede necessárias.
  - **Check-up Pré-Viagem:** Uma semana antes do deslocamento para implantação presencial, é feita a revalidação para garantir que as melhorias foram de fato aplicadas.

---

**Próxima etapa:** [[[Processo] 3. Análise de Aderência do Processo de Negócio]]
