# Configurações Recomendadas da OpenAI Platform: Orion TN & Orion PRO

Este documento especifica a configuração técnica perfeita dos parâmetros de modelo (Model Settings) para os assistentes virtuais do **Orion TN** e **Orion PRO** rodando na plataforma de desenvolvimento da OpenAI (Responses API / Assistants API). 

---

## Tabela de Configurações Recomendadas

| Parâmetro Técnico      | Configuração Ideal | Comportamento Esperado                                                                                  |
| :--------------------- | :----------------- | :------------------------------------------------------------------------------------------------------ |
| **`text.format`**      | **`text`**         | Retorna as etapas do manual formatadas em Markdown tradicional com menus e botões em negrito.           |
| **`Reasoning effort`** | **`low`**          | Fornece poder cognitivo suficiente para interpretar restrições complexas com tempo de resposta ágil.    |
| **`verbosity`**        | **`low`**          | Limita as respostas a textos diretos e objetivos, eliminando conversações e introduções desnecessárias. |
| **`summary`**          | **`null`**         | Oculta o log de processo de raciocínio interno (*chain-of-thought*) na janela de chat do usuário final. |
| **`store logs`**       | **`true`**         | Salva o histórico de interações no painel administrativo da OpenAI para auditoria e melhoria contínua.  |

---

## Justificativas Técnicas e Operacionais (O Porquê)

### 1. Formato de Resposta (`text.format`)
*   **Decisão:** **`text`** (selecionado).
*   **Justificativa:** Os assistentes interagem diretamente com escreventes de cartório e implantadores de sistemas. Eles necessitam de respostas em linguagem natural formatadas em Markdown (listas numeradas, tópicos e marcações em **negrito** nos botões de telas). As opções `json_object` ou `json_schema` forçariam o assistente a retornar um código JSON cru estruturado, o que destruiria a legibilidade imediata no chat de atendimento ou exigiria que o time de desenvolvimento da Siplan criasse um renderizador de interface customizado no frontend.

### 2. Esforço de Raciocínio (`Reasoning effort`)
*   **Decisão:** **`low`** (baixo).
*   **Justificativa:** 
    *   Tarefas de suporte operacional consistem basicamente na leitura e transcrição fiel de manuais via *File Search* ou na busca direta de conceitos estáveis em domínios oficiais via *Web Search*. O assistente não realiza cálculos lógicos complexos nem gera códigos de programação extensos.
    *   Um esforço de raciocínio `high` (alto) causaria uma latência de resposta excessiva (o usuário esperaria vários segundos antes da primeira palavra aparecer) e consumiria muitos tokens de raciocínio, encarecendo desnecessariamente o faturamento da API da OpenAI.
    *   Por outro lado, o esforço `minimal` (mínimo) pode fazer com que o modelo ignore as restrições negativas dos prompts (como a regra estrita de não vazar os títulos das rotinas no Orion PRO ou de não exibir marcas de citação).
    *   Portanto, a configuração **`low`** fornece o equilíbrio ideal: garante que a IA siga rigorosamente as diretrizes e regras de formatação com baixa latência e custo controlado.

### 3. Verbosidade (`verbosity`)
*   **Decisão:** **`low`** (baixa).
*   **Justificativa:** Os prompts do Orion TN e do Orion PRO estabelecem a restrição absoluta de **"Sem Conversação"** (proibição de introduções educadas, cumprimentos ou conclusões amigáveis). A resposta do assistente deve ir direto à ação. Definir a verbosidade como `low` ajuda o modelo a economizar tokens de saída, reduzindo o custo da operação e entregando respostas limpas, curtas e de leitura rápida para o escrevente no balcão.

### 4. Sumário do Raciocínio (`summary`)
*   **Decisão:** **`null`** (nulo).
*   **Justificativa:** Os modelos de raciocínio da OpenAI (como o o3-mini ou GPT-5 mini) expõem seu processo de pensamento interno passo a passo. Exibir esse texto cru de pensamento conceitual na janela de chat polui visualmente a conversa e gera ruído e confusão para usuários de cartório não técnicos. Definir como **`null`** garante que apenas a resposta final tratada em Markdown chegue à tela do usuário, preservando o layout limpo do chat.

### 5. Armazenamento de Logs (`store logs`)
*   **Decisão:** **`true`** (verdadeiro).
*   **Justificativa:** Os atendimentos do Tabelionato de Notas e Tabelionato de Protesto exigem conformidade regulatória e rastreabilidade jurídica. Manter os logs ativos na nuvem da OpenAI (visíveis de forma restrita e protegida apenas para a organização administradora da Siplan) permite que a equipe de TI da Siplan audite falhas, analise respostas incorretas da IA, investigue alucinações e aprimore as instruções dos assistentes continuamente no painel administrativo.
