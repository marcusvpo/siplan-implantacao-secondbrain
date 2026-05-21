---
tipo: Processo
fase_implantacao: "9. Implantação e Treinamento"
responsavel: Analista de Implantação
dependencia: "[[[Processo] 8. Instalação Remota do Sistema Siplan]]"
tags:
  - #implantacao
  - #treinamento
status_atual: #ativo
---
# [Processo] 9. Implantação no Cartório - Treinamento e Configuração

Fase de imersão e capacitação do cliente no uso do novo sistema Siplan (presencial ou remoto).

## 📋 Cenário Atual (As-Is)

**Base de Teste e Atividades:**
O treinamento utiliza um banco de dados provisório homologado ([[[Processo] 6. Homologação da Conversão de Dados]]), permitindo prática sem risco aos dados reais. O tempo varia de 1 a 2 semanas conforme o sistema (veja [[[Regra] Cronograma e Virada por Sistema]]).
- Configuração do Sistema (regras de negócio e modelos)
- Capacitação dos funcionários, criação de usuários e permissões.

**Impeditivos de Infraestrutura em Campo (Unhappy Path):**
Apesar da instalação remota do servidor (veja [[[Processo] 8. Instalação Remota do Sistema Siplan]]), o analista presencial comumente se depara com problemas:
- **Origem das Surpresas:** Ocorrem porque as máquinas do balcão não são acessadas pela Infra previamente (o cliente passa informações falsas de hardware) ou porque o servidor, antes validado vazio, apresenta travamentos de estresse após receber a carga total do banco de dados convertido.
- **Pequenos ajustes (Contingência):** Se for algo simples (liberar espaço em disco, aumentar um pouco a RAM de uma máquina), o implantador resolve diretamente com o cliente/TI local.
- **Bloqueios Complexos (Escalonamento):** Se envolver falência estrutural (ex: necessidade de trocar servidor ou rede corrompida), a situação é escalada. O Comercial propõe a locação de equipamentos da Siplan. Se recusado, a implantação é abortada em pleno campo e o projeto é pausado.

## 🚀 Visão de Futuro & Ideias (To-Be)

- **Manual de 'Troubleshooting' em Campo:** Criar um checklist tático no Siplan Hub acessível via celular, dando autonomia ao analista em campo para contornar problemas de infraestrutura de rede e banco de dados sem depender de telefonemas para a matriz.