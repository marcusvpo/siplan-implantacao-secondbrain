# Design Spec: Reestruturação Global do Vault (P.A.R.A + Zettelkasten)

## 1. Visão Geral e Objetivos
A solicitação exige um ajuste e melhoria completa da estrutura de pastas, arquivos e links de todo o projeto (Vault).
O Vault utiliza o método P.A.R.A e Zettelkasten. Atualmente, existem inconsistências estruturais, arquivos soltos, links quebrados e pastas mal nomeadas.

O objetivo desta reestruturação é:
1.  **Limpar o Arquivo Morto:** Remover pastas vazias/quebradas (ex: `[Gargalo`), organizar arquivos soltos na raiz de `4-Arquivo`.
2.  **Consolidar a Organização Diária:** Aplicar a reestruturação previamente desenhada em `docs/superpowers/specs/2026-06-08-journal-reorganization-design.md` para o Diário/Semanal.
3.  **Corrigir Links Quebrados:** Identificar e corrigir os links quebrados apontados pela auditoria.
4.  **Padronizar MOCs:** Garantir que todos os arquivos cruciais estejam mapeados em seus respectivos MOCs.
5.  **Revisão do Inbox:** Preparar o terreno em `3-Recursos/00 - Inbox` para que seja facilmente processável (transformando textos longos em notas atômicas no futuro).

## 2. Ações Estruturais (Pastas e Arquivos)

### 2.1. Limpeza em `4-Arquivo`
-   **Remover:** Pasta vazia `4-Arquivo/[Gargalo`.
-   **Remover Arquivos Inúteis:** `Sem título.md`, `Sem título.base` (vazios ou corrompidos).
-   **Organizar Arquivos Soltos:** 
    -   Mover `Detalhes do Chamado.md` e `Exemplo Output - Formulário de Implantação.md` para uma subpasta `4-Arquivo/Exemplos e Chamados Antigos/`.
    -   Mover `Reunião com Implantadores - 25-05 - 26-05 - 27-05.md` para `4-Arquivo/transcricoes-reunioes-semana25/`.
    -   Mover `Siplan_Implantacao_Transformacao_Operacional_v2.pdf` para `4-Arquivo/Documentos de Base/`.
-   **Consertar Diários no Arquivo:** O arquivo `08-06--12-06.md` está em `4-Arquivo` mas contém links quebrados para dias da semana. Moveremos para a nova estrutura de `Anotações Diárias`.

### 2.2. Implementação da Estrutura de Anotações Diárias
Conforme o design anterior:
-   Criar `Anotações Diárias/0-Templates/Template - Semana.md`
-   Criar `Anotações Diárias/0-Templates/Template - Dia.md`
-   Criar `Anotações Diárias/Semanas/`
-   Criar `Anotações Diárias/Dias/`
-   Mover `4-Arquivo/08-06--12-06.md` para `Anotações Diárias/Semanas/08-06--12-06.md` e consertar seus links (eles devem apontar para a pasta `Dias/YYYY-MM-DD.md`).
-   Remover o arquivo `4-Arquivo/2026-06-08.md` (vazio) e a pasta `Anotações Diárias/Semanas` atual (substituindo de forma correta).

### 2.3. Consertar Links Quebrados
-   Os links dinâmicos `<% tp.date.now... %>` quebrados nos arquivos de specs serão tratados ou ignorados pelo Obsidian nativamente, mas vamos consertar as anotações semanais para que criem links válidos.
-   Garantir que as notas em `2-Áreas/` estão todas apontando corretamente para os MOCs.

## 3. Workflow de Execução
1.  **Fase 1: Limpeza (Arquivos Inúteis)** - Remoção de lixo e pastas mal formatadas.
2.  **Fase 2: Estruturação Diária (Journal)** - Implementação dos templates e pastas.
3.  **Fase 3: Movimentação (Refactoring de Pastas)** - Movimentação de arquivos soltos em Arquivo e Inbox para estruturas coerentes.
4.  **Fase 4: Conserto de Links e Mapeamento** - Atualização de MOCs e links internos.

## 4. Aprovação do Usuário
Aguardando confirmação do usuário para iniciar as fases descritas.