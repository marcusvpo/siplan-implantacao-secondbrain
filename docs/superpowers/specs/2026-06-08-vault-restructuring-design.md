# Spec: Reorganização do Vault e Isolamento RAG

## Objetivo
Reorganizar a arquitetura de pastas do Obsidian Vault "Siplan - Implantação" para criar uma separação rígida entre rascunhos em andamento, conhecimento permanente (Second Brain) e lixo/arquivos obsoletos, garantindo que o contexto da IA (RAG) se mantenha limpo e altamente relevante.

## Estrutura de Pastas Proposta

### 1. Zona de Rascunho e Andamento (`0-Em Andamento`)
- **Novo Diretório:** Criar a pasta `0-Em Andamento` na raiz do Vault.
- **Função:** Atuará como a "mesa de trabalho". Receberá questionários em elaboração, esboços gerados pela IA, notas diárias em preenchimento e rascunhos não consolidados.
- **Ciclo de Vida:** Arquivos aqui são temporários. Eles existem apenas para serem posteriormente processados (ex: via skill `wiki-ingest`) e transformados em conhecimento consolidado.

### 2. Zona de Lixo Inteligente (Fora do Vault)
- **Novo Diretório:** `D:\Projetos Obsidian\Siplan - Arquivo Obsoleto`.
- **Função:** "Cemitério" de arquivos que cumpriram sua função e não devem mais poluir pesquisas semânticas. Ex: questionários já respondidos e absorvidos, rascunhos velhos, rascunhos de reuniões já degravadas.
- **Isolamento RAG:** Ao mover os arquivos para fora da raiz do Vault, garantimos 100% de isolamento, já que a ferramenta de indexação não terá acesso físico a esses arquivos. Isso resolve a limitação técnica onde o `.geminiignore` não era respeitado pelo indexador RAG.

### 3. Zona de Conhecimento Permanente
- Mantém-se as atuais pastas `2-Áreas` e `3-Recursos`.
- **Função:** Acomodar estritamente notas atômicas estruturadas (com tags e frontmatter) extraídas dos rascunhos.
- **Limpeza do Inbox Atual:** O diretório `3-Recursos/00 - Inbox` e a pasta de `Anotações Diárias/Notas` serão analisados. Os arquivos úteis em andamento irão para `0-Em Andamento`, o que for lixo irá para `4-Arquivo/00-Obsoletos e Temporarios`, e o que for conhecimento maduro será categorizado corretamente.

## Ações de Implementação
1. Criar os novos diretórios propostos.
2. Criar/atualizar o arquivo `.geminiignore` para incluir a regra de exclusão da pasta de obsoletos.
3. Migrar os arquivos atuais das pastas de Inbox e Anotações para a nova estrutura.
4. Forçar uma reindexação completa do RAG ao final do processo para expurgar referências aos arquivos movidos para o lixo.