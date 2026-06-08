# Reestruturação do Journal no Obsidian - Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Reestruturar a pasta de Anotações Diárias para adotar um fluxo focado na semana usando templates automatizados com o Templater.

**Architecture:** O sistema terá uma pasta raiz `Anotações Diárias` contendo `0-Templates`, `Semanas`, e `Dias`. A lógica central é baseada em Notas Semanais dinâmicas.

**Tech Stack:** Obsidian Core Plugins (Daily Notes), Templater.

---

### Task 1: Criar Estrutura de Pastas e Mover Notas Existentes

**Files:**
- Create Dir: `Anotações Diárias/0-Templates`
- Create Dir: `Anotações Diárias/Semanas`
- Create Dir: `Anotações Diárias/Dias`
- Move: `Anotações Diárias/Ideias Automações Disparo E-mail - Siplan HUB.md` para a pasta inbox (vamos usar `3-Recursos/00 - Inbox` já existente)

- [ ] **Step 1: Criar as pastas**

```bash
mkdir -p "Anotações Diárias/0-Templates"
mkdir -p "Anotações Diárias/Semanas"
mkdir -p "Anotações Diárias/Dias"
```

- [ ] **Step 2: Mover a nota existente**

```bash
mv "Anotações Diárias/Ideias Automações Disparo E-mail - Siplan HUB.md" "3-Recursos/00 - Inbox/Ideias Automações Disparo E-mail - Siplan HUB.md"
```

- [ ] **Step 3: Commit**

```bash
git add "Anotações Diárias/" "3-Recursos/00 - Inbox/"
git commit -m "chore: create folder structure for new journal system and move inbox note"
```

---

### Task 2: Criar Templates

**Files:**
- Create: `Anotações Diárias/0-Templates/Template - Semana.md`
- Create: `Anotações Diárias/0-Templates/Template - Dia.md`

- [ ] **Step 1: Criar o Template da Semana**

Crie o arquivo `Anotações Diárias/0-Templates/Template - Semana.md` com o seguinte conteúdo:
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

- [ ] **Step 2: Criar o Template do Dia**

Crie o arquivo `Anotações Diárias/0-Templates/Template - Dia.md` com o seguinte conteúdo:
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

- [ ] **Step 3: Commit**

```bash
git add "Anotações Diárias/0-Templates/"
git commit -m "feat: add templater templates for weekly and daily notes"
```

---

### Task 3: Configurar Plugins do Obsidian

**Files:**
- Modify: `.obsidian/daily-notes.json`
- Modify: `.obsidian/plugins/templater-obsidian/data.json` (ou criar se não existir)

- [ ] **Step 1: Atualizar configuração do Daily Notes**

O arquivo `.obsidian/daily-notes.json` deve ficar assim:
```json
{
  "format": "YYYY-MM-DD",
  "folder": "Anotações Diárias/Dias",
  "template": "Anotações Diárias/0-Templates/Template - Dia.md"
}
```

- [ ] **Step 2: Atualizar configuração do Templater**

O arquivo `.obsidian/plugins/templater-obsidian/data.json` deve ser criado/modificado para:
```json
{
  "templates_folder": "Anotações Diárias/0-Templates",
  "templates_pairs": [],
  "trigger_on_file_creation": true,
  "auto_jump_to_cursor": false,
  "enable_system_commands": false,
  "shell_path": "",
  "user_scripts_folder": "",
  "enable_folder_templates": false,
  "folder_templates": [],
  "syntax_highlighting": true,
  "syntax_highlighting_mobile": false,
  "enabled_templates_hotkeys": []
}
```

- [ ] **Step 3: Commit**

```bash
git add .obsidian/daily-notes.json .obsidian/plugins/templater-obsidian/data.json
git commit -m "chore: configure daily notes and templater for new folder structure"
```