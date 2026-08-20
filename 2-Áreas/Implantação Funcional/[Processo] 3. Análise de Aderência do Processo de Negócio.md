---
tipo: Processo
fase_implantacao: "3. Análise de Aderência"
responsavel: Analista de Implantação
dependencia: "[[[Processo] 2. Levantamento de Infraestrutura]]"
tags:
  - #implantacao
  - #produtos
status_atual: #ativo
---
# [Processo] 3. Análise de Aderência do Processo de Negócio

Com a infraestrutura validada, o foco passa para a compatibilidade dos processos de negócio do cliente com o software Siplan. Atua como um "Gate Condicional" antes da Conversão.

## 📋 Centralização no Siplan HUB & Arquitetura Operacional

A **Análise de Aderência do Processo de Negócio** foi totalmente integrada e centralizada dentro do **Siplan HUB**, eliminando a geração e manipulação descentralizada de arquivos externos no formato `.docx`. Todo o ciclo de vida da aderência ocorre diretamente na plataforma:

### 1. Editor de Formulários com Versionamento (Área dos Implantadores)
- **Localização:** Módulo `Implantadores > Editar Form. Aderência`.
- **Governança e Evolução Contínua:** Os próprios analistas e implantadores possuem autonomia para ajustar, refinar e incluir novas perguntas e seções conforme novos requisitos e particularidades de cada sistema (Orion TN, Orion PRO, Orion REG) são mapeados em campo.
- **Controle de Versionamento:** O editor conta com suporte a **versionamento dinâmico**. Cada alteração estrutural no questionário cria uma nova versão do template, garantindo que projetos históricos mantenham os dados fiéis à versão sob a qual foram avaliados, enquanto novos projetos utilizam sempre a versão mais atualizada e padronizada.

### 2. Geração, Preenchimento e Sincronização por Projeto
- **Geração Automática:** Na tela do projeto/cliente (`/projects/:id`), ao acessar a **Etapa de Análise de Aderência**, o sistema identifica o software contratado e instancia a versão vigente do formulário correspondente via botão de geração.
- **Preenchimento e Auto-Save:** O analista preenche as informações operacionais, técnicas e periféricas diretamente no formulário web no Hub, com persistência e salvamento automático dos dados.
- **Sincronização em Tempo Real:** As respostas, observações e apontamentos de gaps ficam gravados e vinculados à etapa do projeto no banco de dados do Hub, alimentando os faróis de status e indicadores de saúde do cliente.

---

## 🔍 Execução e Mapeamento de Campo

**Diferenciação de Execução por Origem do Sistema:**
- **Sistemas de Terceiros (Externos):** A análise de aderência é conduzida preferencialmente de forma **presencial** (durante 2 a 3 dias de visita técnica do analista), garantindo o levantamento exaustivo de fluxos de trabalho e particularidades locais.
- **Sistemas Legados Siplan/Control-M:** A análise é conduzida de forma **remota** e ágil, apoiada no conhecimento consolidado da equipe sobre as estruturas de dados e regras do legado.

**Itens Críticos Investigados no Formulário:**
1. **Estrutura Física e Dimensionamento:** Quantidade de andares, distribuição de setores por piso e contagem de colaboradores (mitigando subdimensionamento de equipes).
2. **Periféricos e Hardware:** Compatibilidade de impressoras de etiquetas, scanners, biometrias e webcams homologadas.
3. **Verificação de Espaço em Disco (Imagens GED):** Levantamento do volume total ocupado por imagens e documentos no servidor do cartório para dimensionamento prévio junto à equipe de Conversão e Infraestrutura Docker.
4. **Minutas e Modelos Orion TN:** Verificação de envio imediato dos top 5 modelos mais utilizados para a equipe de Modelos (Hugo Januário / Bruno Fernandes).

---

## ⛔ Tratamento de Impedimentos (Gate Condicional)

A conclusão da Análise de Aderência atua como um gate rigoroso para a continuidade do projeto:
- **Aderente (Sem Gaps Críticos):** O gate é liberado, avançando o projeto no fluxo para a fila de [[[Processo] 5. Conversão do Banco de Dados]].
- **Não Aderente / Gap de Produto:** Se for identificada a ausência de uma rotina vital para a serventia (ex: integração obrigatória com órgão municipal ou formato específico de cobrança):
  - O implantador sinaliza o gap no formulário nativo do Hub (`has_product_gap = true`).
  - O projeto é mantido pausado na etapa de Aderência.
  - A demanda é escalada para o time de **Produtos/P&D** para avaliação de esforço, enquanto a Diretoria/Comercial negocia prazos e viabilidade com o cartório. **Regra rígida:** O sistema nunca é implantado "pela metade" ou sem rotinas operacionais indispensáveis.

---

**Próxima etapa:** [[[Processo] 4. Tratamento de Impedimentos da Análise de Aderência]]
