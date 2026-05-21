---
tipo: Processo
fase_implantacao: "5. Conversão de Dados"
responsavel: Equipe de Conversão
dependencia: "[[[Processo] 3. Análise de Aderência do Processo de Negócio]]"
tags:
  - #conversao
  - #banco_de_dados
  - #cross_conversao
status_atual: #ativo
---
# [Processo] 5. Conversão do Banco de Dados

Migração dos dados históricos do cartório para o novo sistema Siplan.

## 📋 Cenário Atual (As-Is)

**Acionamento:**
Chamado encaminhado para a Equipe de Conversão de Banco de Dados logo após superados os Gates iniciais.

**Prazos Estimados e Desafios:**
- **Sistemas Siplan/Control-M ou já convertidos:** 2 a 3 dias (uso de motores de conversão existentes).
- **Sistemas novos:** 1 a 2 meses ou mais (exige estudo minucioso para desenvolvimento de novo "motor de conversão/conversor").
- **Bases Corrompidas ou Criptografadas:** A equipe de Conversão entra em contato com a TI do cartório ou com a empresa do sistema legado. O processo é geralmente bem-sucedido, mas o desenvolvimento pode levar meses.

**Contingência de Prazo Estourado (Bases Desconhecidas):**
Quando o cartório possui um sistema cujos dados nunca foram convertidos pela Siplan e a confecção do conversor ultrapassa meses (estourando um possível acordo comercial), a contingência é **institucional**:
- A **Diretoria** entra no circuito para conversar diretamente com o cliente.
- É explicado o lado técnico e a complexidade do novo conversor.
- A própria Diretoria acalma o cliente e reagenda as expectativas de data. A implantação aguarda a finalização técnica antes de qualquer envio a campo.

## 🚀 Visão de Futuro & Ideias (To-Be)

- **Catálogo de Conversores no Hub:** Criar uma base de dados indexada no Hub com todos os sistemas do mercado e o "Nível de Maturidade" do nosso conversor para cada um. Isso permitirá que o Comercial saiba, *no ato da venda*, se aquele cartório demorará 3 dias ou 3 meses para converter.

**Próxima etapa:** [[[Processo] 6. Homologação da Conversão de Dados]]