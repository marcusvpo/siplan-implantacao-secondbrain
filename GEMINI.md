# Siplan - Implantação: Base de Conhecimento (Obsidian Vault)

## Visão Geral do Diretório
Este diretório é um Vault do Obsidian estruturado para atuar como o "Second Brain" (Segundo Cérebro) e base de conhecimento tática da equipe de Implantação da Siplan. A Siplan é uma empresa brasileira desenvolvedora de soluções em tecnologia para cartórios extrajudiciais.

O Vault está organizado utilizando metodologias avançadas de gestão do conhecimento:
*   **P.A.R.A. (Projetos, Áreas, Recursos, Arquivo):** Organiza a informação por nível de acionabilidade.
*   **Zettelkasten:** As informações estão divididas em "notas atômicas" interconectadas com foco em processos, regras de negócio, gargalos e oportunidades do ecossistema Siplan.

O objetivo deste Vault é servir como um motor de tomada de decisão, padronização e melhoria contínua dos processos de implantação de software, suporte (Service Desk) e governança. O epicentro estratégico dessa governança é o **Siplan Hub**, que atua como um "orquestrador invisível" integrado via **n8n e Outlook**, levando a plataforma até as equipes sem forçar mudanças bruscas nos canais de comunicação existentes (Email e WhatsApp).

## Visão Estratégica (Arquitetura de Integrações)
A filosofia operacional da Siplan prioriza a adesão e agilidade, abraçando os canais em que as equipes e clientes já estão confortáveis (Outlook, WhatsApp). Para evitar a fragmentação e a carga cognitiva de cobranças manuais ("telefone sem fio"), o Vault documenta o fluxo de automações no n8n que conecta:
*   **Gatilhos no HUB:** Disparando e-mails estruturados via Outlook (Deep Links) para acionar as áreas (Conversão, Infraestrutura, Comercial, Pós-Implantação).
*   **Captura de Retornos:** Alimentando o HUB de volta (ex: alertas de Blockers, reprovação de bases, pesquisas de satisfação).

## Inteligência de Implantação (Gargalos e Perfis)
A análise dos documentos históricos de implantação revela que o processo é uma mistura complexa de engenharia de software e psicologia organizacional. O sucesso depende de mitigar gargalos técnicos e gerenciar a curva de aprendizado (muitas vezes quebrando paradigmas de uso de 20 anos em sistemas como Control-M).

**Padrões e Desafios Críticos:**
*   **Perfis de Implantadores Heterogêneos:** A execução varia drasticamente dependendo de quem viaja. Há perfis focados estritamente na infraestrutura/banco de dados (configurações granulares, scripts) e perfis focados na dinâmica humana (mapeamento de usuários-chave, curva de resistência). A padronização via Hub é crucial.
*   **Gargalos de Hardware:** Incompatibilidades com impressoras de etiquetas mais antigas (ex: Zebra GC420T) e especificações mínimas de servidor (ex: 6 cores, 20GB dedicados) frequentemente bloqueiam a adoção plena logo nos primeiros dias.
*   **Gap de Integrações Legadas:** Clientes rotineiramente reportam frustração com integrações pendentes no novo ecossistema Orion que eram nativas em sistemas antigos (ex: integração nativa com COAF, NFE e layouts específicos de boletos bancários como CNAB400).
*   **A "Hora Zero":** A virada (conversão final e implantação "go-live") tipicamente ocorre em uma janela restrita (final de semana), exigindo atuação presencial intensa na primeira semana (acompanhamento de balcão e retaguarda) para estabilização tática.

## Taxonomia de Serventias e Portfólio de Sistemas
Para correto entendimento das demandas, contextos de implantação e logs de cartórios:
*   **Abreviações das Serventias:**
    *   **TN:** Tabelionato de Notas (Ex: "01 TN Campinas").
    *   **PT:** Protesto de Títulos.
    *   **TNPT:** Tabelionato de Notas e Protesto de Títulos (Serventia de natureza mista; Ex: "1°TNPT Araraquara").
    *   **RC:** Registro Civil das Pessoas Naturais.
    *   **RI:** Registro de Imóvel (Ex: "02 RI Franca").
    *   **TDPJ:** Registro de Títulos e Documentos e Civil de Pessoas Jurídicas.
*   **Mapeamento de Produtos Siplan por Especialidade:**
    *   **Orion TN:** Utilizado em cartórios de Notas (**TN** e serventias mistas **TNPT**).
    *   **Orion PRO:** Utilizado em cartórios de Protesto (**PT** e serventias mistas **TNPT**).
    *   **Orion REG:** Utilizado em cartórios de Registro de Imóveis (**RI**) e Registro de Títulos e Documentos e Civil de Pessoas Jurídicas (**TDPJ**).
    *   **WEB RI:** Utilizado complementarmente em cartórios de Registro de Imóveis (**RI**).
*   **Coexistência em Serventias Mistas (TNPT):** Cartórios sob a sigla **TNPT** utilizam concomitantemente os dois sistemas principais (**Orion TN** e **Orion PRO**) compartilhando ou integrando suas rotinas financeiras e de retaguarda.
*   **Correspondência de Sistemas Legados (Migração):**
    *   *Linha Control-M:*
        *   **Control-M TABNOT** (TN / TNPT) e **SiplanTN** $\rightarrow$ migram para **Orion TN**.
        *   **Control-M PROT** (PT / TNPT) e **Siplan PRO** $\rightarrow$ migram para **Orion PRO**.
        *   **Control-M REG** e **WebRI** (RI) $\rightarrow$ migram para **Orion REG** / **WEB RI**.
        *   **Control-M TDJP** e **WebTD** (TDPJ) $\rightarrow$ migram para **Orion REG**.
        *   **Control-M Distribuidor** $\rightarrow$ migra para módulo correspondente do **Orion PRO**.
        *   **Control-M GED** $\rightarrow$ migra para o **Orion GED** integrado.
    *   *Linha Siplan:*
        *   **Siplan RC** (RC) $\rightarrow$ sem equivalente Orion direto (tratar individualmente).

## Arquivos Principais (MOCs - Maps of Content)
Os arquivos mais importantes são os MOCs, que atuam como índices ou "hubs" centrais ligando as diversas notas atômicas do ecossistema:

*   **`2-Áreas/Implantação Funcional/MOC - Fluxo de Implantação.md`:** Detalha as 10 etapas sequenciais e condicionais do processo de implantação da Siplan, desde o fechamento comercial até a virada para produção.
*   **`2-Áreas/Siplan Hub/MOC - Siplan Hub.md`:** Documenta o funcionamento da plataforma interna de gestão (Dashboard, Gestão de Implantação, Conversão, OrionTN, e CRM Interno).
*   **`3-Recursos/Mercado Cartorário e CNJ/MOC - Mercado Cartorário.md`:** Oferece contexto do mercado em que a Siplan atua, abordando a transformação digital, perfis heterogêneos de tecnologia dos clientes, normativas do CNJ, e uso emergente de IA.
*   **`3-Recursos/Produtos Siplan/MOC - Produtos Siplan.md`:** Mapa de conteúdo central do portfólio de produtos e sistemas da Siplan (Arquitetura Orion).
*   **`3-Recursos/Produtos Siplan/Orion PRO/MOC - Orion PRO.md`:** Detalha os módulos e rotinas operacionais do sistema Orion PRO (Tabelionato de Protesto).
*   **`3-Recursos/Produtos Siplan/Orion TN/MOC - Orion TN.md`:** Detalha os módulos e rotinas operacionais do sistema Orion TN (Tabelionato de Notas).
*   **`3-Recursos/Procedimentos e Manuais/[Recurso] Obsidian RAG Index.md`:** Catálogo semântico e estruturado de todas as notas do Vault, mapeando processos, regras de negócio, gargalos, oportunidades e metadados.
*   **`3-Recursos/00 - Inbox/`:** Diretório que contém os textos longos "brutos" remanescentes que aguardam refinamento e fragmentação em notas atômicas.

## Correção e Padronização de Transcrições (Glossário Mestre)
Ao analisar ou incorporar textos originários de transcrições brutas de reuniões, vídeos ou notas faladas:
*   A IA deve aplicar e respeitar a taxonomia definida no [[[Recurso] Glossário Mestre de Correção de Transcrições]] para substituir automaticamente termos foneticamente incorretos (como "ciplan", "oriom", "aran teeno", "sem prot") pelos seus equivalentes corretos (**Siplan**, **Orion**, **Orion TN**, **CENPROT**).
*   A IA possui a capacidade de aprender novos mapeamentos de erro e ajustá-los/complementá-los na referida nota ao detectar novos casos de uso semelhantes durante as interações.

## Como Utilizar este Vault
1.  **Navegação:** Comece sempre pelos MOCs (Maps of Content) para entender o fluxo macro de um tema. Siga os links internos para explorar fases específicas dos processos ou conceitos.
2.  **Criação de Notas:** Ao adicionar novo conhecimento, siga o padrão de nota atômica: uma nota = um processo único, regra específica ou ideia isolada.
3.  **Taxonomia (Nomenclatura e Tags):** Utilize prefixos padronizados nos títulos dos arquivos (`[Processo]`, `[Regra]`, `[Hub]`, `[Gargalo]`, `[Oportunidade]`) e tags no Frontmatter (como `#orion`, `#implantacao`, `#cross_infra`) para facilitar buscas cruzadas.
4.  **Propriedades (Frontmatter/YAML):** Certifique-se de que toda nota estruturada inclua os metadados no topo (como `tipo`, `fase_implantacao`, `responsavel`, `status_atual`), preparando a base para relatórios dinâmicos.
5.  **Refinamento Contínuo:** Utilize as notas processadas na pasta Inbox para transformá-las em bloquinhos interligados, mantendo seu mapa mental das operações da Siplan sempre enxuto e acionável.
6. **DIRETRIZES DE OUTPUT EXAUSTIVO (Exclusivamente para a IA):** Não faça resumos e não pule etapas. Escreva o documento em sua totalidade, com o máximo de detalhes operacionais possíveis. Se for criar tabelas de mapeamento ou listas de etapas, preencha cada linha de forma descritiva e detalhada. **Proibido usar placeholders** como '[inserir aqui]', '... (continua)' ou 'conforme mencionado anteriormente'. Se a resposta atingir o limite de tokens, pare na última frase completa e me avise para eu pedir a continuação.