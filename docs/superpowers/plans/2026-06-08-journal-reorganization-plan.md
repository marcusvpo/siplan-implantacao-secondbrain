# Vault Reorganization Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Implement the approved vault architecture by creating isolated zones for drafts and obsolete files to keep the RAG context clean.

**Architecture:** Moving files to strict designated folders (`0-Em Andamento` for active work, `4-Arquivo/00-Obsoletos e Temporarios` for discarded files, and keeping `2-Áreas`/`3-Recursos` for permanent atomic notes). Updating `.geminiignore` to hide obsolete files from AI tools.

**Tech Stack:** Obsidian, Gemini CLI (.geminiignore)

---

### Task 1: Create New Directory Structure

**Files:**
- Create: `0-Em Andamento/` (In Vault)
- Create: `D:\Projetos Obsidian\Siplan - Arquivo Obsoleto\` (Outside Vault)

- [ ] **Step 1: Create the new root folder for drafts**

```bash
mkdir -Force "0-Em Andamento"
```

- [ ] **Step 2: Create the external folder for obsolete files**

```bash
mkdir -Force "D:\Projetos Obsidian\Siplan - Arquivo Obsoleto"
```

- [ ] **Step 3: Commit structural changes**

```bash
git add .
git commit -m "chore: create vault reorganization directories"
```

### Task 2: Configure RAG Isolation (Geminiignore)

**Files:**
- Modify/Create: `.geminiignore`

- [ ] **Step 1: Write/Update the `.geminiignore` file**

```bash
echo "0-Em Andamento/" >> .geminiignore
```

- [ ] **Step 2: Verify the file content**

```bash
cat .geminiignore
```
Expected: output includes `0-Em Andamento/`

- [ ] **Step 3: Commit the ignore configuration**

```bash
git add .geminiignore
git commit -m "build: ignore drafts directory in gemini context"
```

### Task 3: Migrate Rascunhos from Inbox

**Files:**
- Modify (Move): All AI-generated questionnaires and active drafts from `3-Recursos/00 - Inbox/` to `0-Em Andamento/` or `D:\Projetos Obsidian\Siplan - Arquivo Obsoleto\`

- [ ] **Step 1: Move active questionnaires to the draft zone**

```bash
mv "3-Recursos\00 - Inbox\Questionario_Aprofundamento_Implantacao.md" "0-Em Andamento\"
mv "3-Recursos\00 - Inbox\Questionário Investigação.md" "0-Em Andamento\"
mv "3-Recursos\00 - Inbox\Questionario_ASIS_TOBE_Siplan_Hub.md" "0-Em Andamento\"
mv "3-Recursos\00 - Inbox\Ideias Automações Disparo E-mail - Siplan HUB.md" "0-Em Andamento\"
```

- [ ] **Step 2: Move old/processed raw data to the external obsolete zone**

```bash
mv "3-Recursos\00 - Inbox\Diagnostico_Bruto_Vault.md" "D:\Projetos Obsidian\Siplan - Arquivo Obsoleto\"
mv "3-Recursos\00 - Inbox\Sabotagem_do_Conhecimento.md" "D:\Projetos Obsidian\Siplan - Arquivo Obsoleto\"
mv "3-Recursos\00 - Inbox\Análise Transição e Aderência.md" "D:\Projetos Obsidian\Siplan - Arquivo Obsoleto\"
mv "3-Recursos\00 - Inbox\Relatorio_Transformacao_Implantacao_2026.md" "D:\Projetos Obsidian\Siplan - Arquivo Obsoleto\"
```

- [ ] **Step 3: Verify the remaining files in Inbox**
*Note: Any remaining files should be legitimate permanent resources or raw content still awaiting processing.*

```bash
ls "3-Recursos\00 - Inbox\"
```

- [ ] **Step 4: Commit Inbox migration**

```bash
git add "3-Recursos\00 - Inbox\" "0-Em Andamento\" "4-Arquivo\00-Obsoletos e Temporarios\"
git commit -m "refactor: migrate drafts and obsolete files out of Inbox"
```

### Task 4: Migrate Anotações Diárias

**Files:**
- Modify (Move): Files from `Anotações Diárias/Notas/`

- [ ] **Step 1: Move active templates/notes to the draft zone**

```bash
mv "Anotações Diárias\Notas\Templates de Email - Siplan Skills.md" "0-Em Andamento\"
```

- [ ] **Step 2: Remove the empty Notas folder (if applicable)**

```bash
rmdir "Anotações Diárias\Notas"
```

- [ ] **Step 3: Commit Anotações migration**

```bash
git add "Anotações Diárias\" "0-Em Andamento\"
git commit -m "refactor: move daily notes artifacts to draft zone"
```

### Task 5: Final RAG Reindex

- [ ] **Step 1: Execute the RAG reindex to reflect the deleted/ignored context**
*This ensures the vector database no longer points to the files moved to the obsolete folder.*

Run the tool: `obsidian_rag_index` with `force_reindex: true`