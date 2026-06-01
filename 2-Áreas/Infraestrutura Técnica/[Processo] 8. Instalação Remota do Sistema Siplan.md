---
tipo: Processo
fase_implantacao: "8. Instalação Remota"
responsavel: Equipe de Infraestrutura
dependencia: "[[[Processo] 7. Agendamento da Implantação Funcional]]"
tags:
  - #infraestrutura
  - #cross_infra
status_atual: #ativo
---
# [Processo] 8. Instalação Remota do Sistema Siplan

Preparação técnica do ambiente *antes* da chegada do analista presencial.

## 📋 Cenário Atual (As-Is)

**Execução e Falso Escopo:**
A instalação remota é executada pela equipe de Infra (Alex) diretamente no **Servidor** do cartório. Envolve configurar VM, Docker, contêineres e PostgreSQL. 

**O Limite da Validação Remota (Origem das Surpresas em Campo):**
A equipe de Infraestrutura atesta que o *Servidor* está 100% pronto. No entanto, há limites claros no que é testado remotamente, o que gera as "surpresas" reportadas no [[[Processo] 9. Implantação no Cartório - Treinamento e Configuração]]:
1. **Ponto Cego das Máquinas Clientes:** O Alex acessa *somente* o servidor durante a instalação remota. As máquinas operacionais dos usuários são planilhadas com base *exclusivamente no que o cliente informou* (muitas vezes informações erradas de hardware). A validação real das máquinas de balcão fica a cargo do implantador no dia da viagem.
2. **Estresse de Banco de Dados:** O servidor pode ser validado como "OK" vazio, mas apresentar travamentos e desligamentos inesperados após a virada da conversão devido à alta carga de dados migrados, algo impossível de prever antes da conversão real ocorrer.

Apesar dessas limitações, a atuação prévia da Infra resolve 90% dos problemas bloqueantes de servidor antes do embarque do analista.

## 🚀 Visão de Futuro & Ideias (To-Be)

- **Padronização em Linux:** Servidores Windows têm apresentado muitos problemas de compatibilidade com Docker. A nova diretriz é dificultar proativamente a instalação em Windows para novos clientes e forçar a padronização no ambiente Linux.
- **Ferramenta "Wizard" de Instalação:** A ferramenta de instalação automatizada (criada por Kleverson) será oficializada, gerando ganhos significativos de tempo e estabilidade tanto para a equipe de Infra (Alex) quanto para os Implantadores em campo.
- **Parametrização Remota Pré-Viagem:** Deslocar as atividades pesadas de configurações e parametrizações (que historicamente consomem os 2 primeiros dias no cartório) para o Back Office de Implantação (Hugo e Bruno). Eles farão isso remotamente *antes* do deslocamento do analista, permitindo que o Implantador foque 100% no treinamento.
- **Script de Validação de Ponto (Endpoint):** Desenvolver um pequeno script automatizado que a TI do cartório possa rodar em todas as máquinas de balcão, devolvendo para a Siplan os dados *reais* de hardware (RAM, Disco, SO), eliminando a dependência do "achismo" do cliente e evitando surpresas para o analista.

**Ver também:** [[[Regra] Diferença entre Instalação Remota e Implantação Funcional]]
**Próxima etapa:** [[[Processo] 9. Implantação no Cartório - Treinamento e Configuração]]