---
tipo: Processo
fase_implantacao: "1. Início do Chamado de Implantação"
responsavel: Comercial e Implantação
dependencia: Nenhuma
tags:
  - #comercial
  - #implantacao
status_atual: #ativo
---
# [Processo] 1. Início do Chamado de Implantação

O ciclo de implantação é formalmente inaugurado com o fechamento de um novo contrato de licenciamento de software pelo departamento **Comercial**.

## 📋 Cenário Atual (As-Is)

Historicamente e atualmente, o Comercial abre o chamado no **SAC 0800** passando questões administrativas, porém com poucas informações técnicas e operacionais relevantes.

Abaixo está o modelo real de como ocorrem os trâmites atuais na abertura de um novo chamado (após fechamento de contrato):

> **Exemplo de Trâmites Atuais:**
> - **Trâmite 1:** Abertura da OP (ex: OP 9725/2023 - Implantação e Treinamento...).
> - **Trâmite 2:** Demanda do cliente descrita como "Cadastrar o contrato, sem ativar a recorrência... O contrato foi recebido via DocuSign". Observações sobre substituição de software e encaminhamento para o DADM.
> - **Trâmite 3:** Confirmação do DADM e retorno para o Comercial.
> - **Trâmite 4:** Comercial repassa o chamado para a Implantação, informando a quantidade de horas, modalidade (Presencial/Remoto) e pagamento de deslocamento/hospedagem, porém sem detalhes da operação do cliente.

**Avaliação Inicial e Cadastro:**
Após o recebimento deste chamado, o responsável pela implantação precisa realizar o **cadastro manual** do projeto na plataforma **Hub Siplan** e fazer uma avaliação inicial do perfil do cartório (novo, migração Siplan, migração concorrente) de forma investigativa, já que os dados não vêm estruturados.

## 🚀 Visão de Futuro & Ideias (To-Be)

Para corrigir a defasagem de informações vitais (deslocamento, modelos, contatos, limitações), o processo idealizado envolverá um **formulário de nova implantação** no Hub Siplan.

A rotina que deverá ser estabelecida é gerar o *output* neste formulário e colá-lo como o trâmite inicial no SAC 0800, substituindo o texto desestruturado atual.

**Template Padrão Projetado (A ser implementado):**
```text
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
PASSAGEM DE PROJETO — COMERCIAL → IMPLANTAÇÃO
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
■ DADOS ADMINISTRATIVOS
[... dados de OP, Contrato ...]
■ ESCOPO CONTRATADO
[... Sistemas e Módulos ...]
■ PERFIL DO PROJETO
[... Legado ...]
■ DATAS E AGENDA
[... Restrições e Datas ...]
■ CONTATOS DO CARTÓRIO
[... Responsáveis ...]
■ EDITOR DE MODELOS
[... Prazos ...]
■ CONDIÇÕES ESPECIAIS E OBSERVAÇÕES
[... Urgência ...]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```
(Veja o modelo completo em [[Exemplo Output - Formulário de Implantação]])

**Próxima etapa:** [[[Processo] 2. Levantamento de Infraestrutura]]