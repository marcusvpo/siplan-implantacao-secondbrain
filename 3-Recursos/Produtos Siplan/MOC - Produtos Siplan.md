---
tipo: MOC
area: Produtos Siplan
tags:
  - #orion
  - #produtos
  - #sistemas
status_atual: #ativo
---
# MOC - Produtos Siplan

Este é o Mapa de Conteúdo (MOC) central do portfólio de produtos e sistemas da Siplan, voltado à automação e gestão operacional de serventias extrajudiciais (cartórios). A Siplan desenvolve soluções robustas focadas na modernização tecnológica, facilidade de uso, aderência normativa e observabilidade gerencial.

O epicentro tecnológico da linha moderna da Siplan é a **Arquitetura Orion**, caracterizada por operações 100% web, suporte a hospedagem em nuvem (ou servidores locais sobre Windows/Linux), banco de dados open source (reduzindo custos de licenciamento) e interfaces modernas e responsivas.

## 🖥️ Portfólio de Sistemas

O ecossistema Siplan divide-se em especialidades cartorárias para atender de forma granular cada tipo de serventia:

### 1. Orion PRO (Tabelionato de Protesto de Títulos)
O **Orion PRO** é a solução web e em nuvem voltada para a gestão e execução das rotinas de protesto de títulos. É responsável por automatizar todo o ciclo de vida do protesto, desde a recepção de arquivos de remessa até a efetivação do ato ou cancelamento.
- **MOC de Direcionamento:** [[MOC - Orion PRO]]
- **Módulos Principais:**
  - [[Orion PRO - Consulta e Protocolo|Consulta e Protocolo]] — Filtros de títulos, andamentos, logs de auditoria e controle de apresentantes.
  - [[Orion PRO - Caixa e Financeiro|Caixa e Financeiro]] — Operações de caixa, cancelamentos, orçamentos (pré-cota), boleto online/manual, mensalistas, faturamento, e integrações de pagamentos (Parcela Express).
  - [[Orion PRO - Devolução e Irregularidades|Devolução e Irregularidades]] — Baixa de irregularidade, pré-irregularidade, sustações judiciais, suspensões e editais.
  - [[Orion PRO - Livros e Selagem|Livros e Selagem]] — Geração e assinatura digital de Livros de Protocolo, controle/auditoria de Selos Digitais do TJ/SP, termo e instrumento.
  - [[Orion PRO - Integração e Comunicação|Integração e Comunicação]] — Integração nativa com CRA/CENPROT, Serasa, Boa Vista, JUCESP e Receita Federal.

### 2. Orion TN (Tabelionato de Notas)
O **Orion TN** é a plataforma web para automação de Tabelionatos de Notas. Combina automação no balcão (firmas, DUT e autenticações), escrituração ágil de atos no editor integrado, controle financeiro rigoroso e conformidade com provimentos regulatórios.
- **MOC de Direcionamento:** [[MOC - Orion TN]]
- **Módulos Principais:**
  - [[Orion TN - Balcão de Firmas|Balcão de Firmas]] — Reconhecimento de firmas, captura de fotos, biometria, DUT com IA e cartões de assinatura.
  - [[Orion TN - Escrituração de Atos|Escrituração de Atos]] — Elaboração de escrituras e procurações usando LibreOffice integrado, minutas dinâmicas, qualificação de partes/imóveis e IA para minutas.
  - [[Orion TN - Caixa e Financeiro|Caixa e Financeiro]] — Movimentação de caixa, controle de depósitos prévios, mensalistas, faturas, comissões de escreventes e conciliação bancária.
  - [[Orion TN - Certidões e GED|Certidões e GED]] — Emissão e histórico de certidões, reprografia, e o Orion GED integrado com OCR e indexação.
  - [[Orion TN - Selos e Integrações|Selos e Integrações]] — Controle de selos digitais, comunicação automática com o TJ/SP, indisponibilidades (CENIB/CNIB), e-Notariado, COAF, SEFAZ, DOIWeb e SGA (totem/filas).

---

## 🔗 Integração Operacional (O "Segundo Cérebro" Siplan)

Os produtos da Siplan não operam isolados; eles estão integrados às rotinas internas da empresa, aos gargalos operacionais e à governança estratégica descrita em nossa base de conhecimento:

1. **Gargalos de Implantação:**
   - O dimensionamento e estimativa de horas variam com o sistema: no mínimo **40h para o Orion PRO** e **80h para o Orion TN/REG** (veja [[[Gargalo] Desafios da Operação Real]]).
   - Problemas frequentes de infraestrutura técnica (como compatibilidade com impressoras antigas como Zebra GC420T) afetam o Go-Live (detalhado em [[[Processo] 8. Instalação Remota do Sistema Siplan]]).
   
2. **Siplan Hub (O Orquestrador Invisível):**
   - O Siplan Hub gerencia e monitora os projetos ativos de implantação de cada sistema. Por exemplo, possui o módulo de *Modelos Editor do OrionTN* para formatar os arquivos JSON dos modelos de escrituras do Orion TN diretamente no Hub (veja [[MOC - Siplan Hub]] e [[[Hub] Gestão do OrionTN (Modelos Editor)]]).
   
3. **Conversão de Dados:**
   - A migração de bases legadas para os novos bancos Open Source dos sistemas Orion PRO e Orion TN é uma das etapas mais críticas (gates) para garantir o go-live sem retrabalho (consulte [[[Processo] 5. Conversão do Banco de Dados]] e [[[Processo] 6. Homologação da Conversão de Dados]]).

4. **Mercado e CNJ:**
   - O desenvolvimento e a manutenção desses produtos são guiados por pressões regulatórias intensas do CNJ (Provimentos 74/2018 e 134/2023) e pela necessidade de integração com centrais eletrônicas nacionais (veja [[MOC - Mercado Cartorário]]).
