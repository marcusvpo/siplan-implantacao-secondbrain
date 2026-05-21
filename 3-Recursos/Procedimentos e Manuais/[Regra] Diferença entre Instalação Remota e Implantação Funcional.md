---
tipo: Regra
tags:
  - #regra_negocio
  - #infraestrutura
  - #implantacao
status_atual: #ativo
---
# [Regra] Diferença entre Instalação Remota e Implantação Funcional

É vital diferenciar as duas fases de "instalação":

## 1. Instalação Remota do Sistema (Preparação Técnica)
- **Quem:** Equipe de Infraestrutura.
- **Quando:** Antes do analista de implantação iniciar.
- **O que:** Configurar VM, Docker, PostgreSQL.
- **Objetivo:** Ambiente tecnicamente pronto.

## 2. Implantação Funcional
- **Quem:** Analista de Implantação.
- **Quando:** Após a instalação remota.
- **O que:** Configuração das regras de negócio, parametrizações, treinamento e virada.
- **Objetivo:** Software alinhado aos processos e usuários capacitados.
