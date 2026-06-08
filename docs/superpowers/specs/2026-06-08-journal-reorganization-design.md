# Design Spec: Reestruturação do Obsidian para Gestão Diária e Semanal

## 1. Objetivo
Migrar o fluxo de gestão de tarefas diárias e planejamento semanal do Google Keep para o Obsidian, mantendo o paradigma de "Nota Semanal como painel de controle principal", mas aproveitando as capacidades de interligação do Obsidian.

## 2. Estrutura de Pastas
A pasta atual `Anotações Diárias/` será reestruturada para suportar o novo fluxo de forma limpa:

```text
Anotações Diárias/
├── 0-Templates/               (Armazena os templates do sistema)
│   ├── Template - Semana.md
│   └── Template - Dia.md
├── Semanas/                   (Onde os painéis semanais viverão)
└── Dias/                      (Apenas para logs longos, atas de reunião e aprofundamento)
```

## 3. Padrão de Nomenclatura (File Naming)
Conforme solicitado pelo usuário, a nomenclatura das Notas Semanais refletirá o intervalo de dias úteis (Segunda a Sexta). 
*Nota: Como o Windows/Obsidian não permite o caractere `/` em nomes de arquivos, utilizaremos hífen.*

*   **Semanas:** `DD-MM--DD-MM` (Exemplo: `08-06--12-06.md`)
*   **Dias:** `YYYY-MM-DD` (Exemplo: `2026-06-08.md`) - Padrão nativo, facilita ordenação cronológica.

## 4. Templates

### 4.1. Template Semanal (Template - Semana.md)
O arquivo concentrará as anotações rápidas e as tarefas divididas por dias, imitando o comportamento do Google Keep.

```markdown
---
tipo: planejamento-semanal
inicio: <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "DD-MM--DD-MM") %>
---
# 🎯 Planejamento: <% tp.file.title %>

## 📥 Inbox / Foco da Semana
- [ ] 

## 🗓️ Dias da Semana

### [[<% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "DD-MM--DD-MM") %>]] - Segunda-feira
- [ ] 

### [[<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "DD-MM--DD-MM") %>]] - Terça-feira
- [ ] 

### [[<% tp.date.now("YYYY-MM-DD", 2, tp.file.title, "DD-MM--DD-MM") %>]] - Quarta-feira
- [ ] 

### [[<% tp.date.now("YYYY-MM-DD", 3, tp.file.title, "DD-MM--DD-MM") %>]] - Quinta-feira
- [ ] 

### [[<% tp.date.now("YYYY-MM-DD", 4, tp.file.title, "DD-MM--DD-MM") %>]] - Sexta-feira
- [ ] 

## 🔄 Revisão Semanal
- [ ] Mover tarefas pendentes para a próxima semana
- [ ] Atualizar status de implantações no Siplan HUB
```

### 4.2. Template Diário (Template - Dia.md)
Criado sob demanda apenas quando houver necessidade de expandir um tópico do dia (atas, logs de erros).

```markdown
---
tipo: log-diario
data: <% tp.file.title %>
---
# 📅 <% tp.file.title %>

## 📝 Log / Anotações
- 

## 🤝 Reuniões / Atendimentos
- 
```

## 5. Configurações Necessárias
1.  **Plugin "Daily Notes" (Nativo):**
    *   Folder: `Anotações Diárias/Dias/`
    *   Template: `Anotações Diárias/0-Templates/Template - Dia.md`
2.  **Plugin "Templater" (Comunidade):**
    *   Template folder location: `Anotações Diárias/0-Templates`
    *   Habilitar disparo ao criar novos arquivos (para gerar as datas dinâmicas da semana).
