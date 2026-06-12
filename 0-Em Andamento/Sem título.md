# 📄 Resumo Executivo da Reunião - 12/06/2026

A reunião semanal teve como objetivo alinhar o status das frentes de **Conversão** e implantação de sistemas nos diversos **Cartórios** atendidos pela **Siplan**. Foram discutidos os progressos no processamento de bases de dados e acervos de imagens, tratamentos de inconsistências financeiras e relatórios, além da reestruturação de cronogramas e alocação de equipes técnicas devido a complexidades encontradas nos motores de migração do **ORION** e **WebRI**. O alinhamento consolidou as entregas realizadas no último período e traçou as estratégias para as próximas **Viradas para Produção** e etapas de **Homologação** junto aos clientes.

## 🎯 Principais Pontos Discutidos

- **Evolução e Ajustes na Frente de Protesto (Ademar Souza):**
    
    - **Catanduva:** A **Virada para Produção** do segundo **Cartório** foi concluída com sucesso. Houve a necessidade de aplicar um ajuste emergencial no motor de **Selos** devido a uma mudança de rotina da **CRA**, que exigiu a alteração da numeração de protocolo sequencial para reinicialização diária a partir de 01/04/2026.
        
    - **Tratamento de Acervo em Catanduva:** Foi identificada uma inconsistência onde os títulos do acervo herdado perderam a vinculação com o **Cartório** de origem. O erro foi corrigido em conjunto com Maurílio e Vambak via script diretamente no banco de dados. Adicionalmente, as observações de títulos foram migradas por meio de inserts manuais na tabela que alimenta a tela de **Anotações** em formato pop-up do **ORION**.
        
    - **Mogi das Cruzes (2º Cartório):** Identificou-se um gap estrutural nas migrações históricas vindas do **Siplan PRO**. Como as antigas ferramentas priorizavam apenas índices, os arquivos de remessa da **CRA** e da **CENPROT** não eram importados. Consequentemente, títulos cancelados manualmente ou via acervo figuravam indevidamente com o status de "protestado" no **ORION PRO**. O mapeamento dos campos necessários para a correção manual foi fornecido pelo time de desenvolvimento.
        
    - **Campinas:** O processo de **Conversão** passou por três tentativas na semana devido a travamentos. Após atualização do motor realizada por Vambak e pela equipe de desenvolvimento, uma nova execução foi iniciada em ambiente de testes. O volume estimado é de 2 a 3 milhões de registros, com tempo de processamento projetado em 24 horas.
        
    - **Franca (Protesto):** Os problemas de falta de espaço em disco na **VM** do cliente foram mitigados. O técnico local (Franco) alinhou com a Viscon a liberação de 100 GB, e o analista Alex realizou a expansão do armazenamento em disco na máquina virtual da **Siplan** na manhã de hoje para viabilizar a descompactação e o processamento do acervo de imagens.
        
- **Evolução e Ajustes na Frente de Registro de Imóveis e RTD (Eduardo Silva):**
    
    - **Olímpia:** A **Conversão** da parte de Pessoa Jurídica (PJ) atingiu 99% de conclusão no motor **ORION REG**, restando apenas a recepção de amostras de imagens de anexos coletadas por Julio.
        
    - **Inconsistência Financeira em Olímpia:** Os relatórios de custas baseados nas views da SELE não apresentaram conciliação exata. Foi reportado que o **WebRI** possui seis tabelas distintas para o controle de custas de atos, cuja validação de rotinas internas dispara triggers automáticas no momento da qualificação ou devolução de valores, tornando a parametrização altamente complexa. Ficou definido o apoio da desenvolvedora Bárbara (equipe de Larissa) para realizar a carga de dados a partir de uma tabela temporária.
        
    - **Customização de Cadastros e Notas:** Foi desenvolvido um motor de ajustes para atender às exigências do depara de Olímpia, incluindo a conversão de textos maiúsculos/minúsculos para formato padrão de nomes e a vinculação em massa de dezenas de negócios e suas respectivas participações. Também foi finalizado um conversor de arquivos RTF para HTML para assegurar a correta exibição das notas devolutivas no **WebRI**.
        
- **Evolução e Ajustes nos Projetos da Luciane Lima:**
    
    - **São Vicente:** O projeto foi totalmente encerrado durante o feriado, com a subida dos protocolos e imóveis validados por **Brites**. Foi encaminhada a listagem de imagens não convertidas e o chamado foi direcionado para fechamento.
        
    - **São Caetano:** Concluído o alinhamento com a equipe e com a doutora responsável. Foi verificado que a queixa quanto ao rodapé das certidões não configurava falha de **Conversão**, mas sim necessidade de construção de modelos de documentos internos do **ORION**, tarefa repassada a Henrique e Vieira. O ticket de migração foi encerrado.
        
    - **Santos (4TN / Balcão):** Após a entrega da **Conversão**, a auditoria realizada por Vieira apontou omissões de dados em um relatório de seis páginas. O fluxo de chamados no service desk gerou gargalo desnecessário, exigindo priorização total no ajuste destes campos.
        
    - **26 SP:** A base de dados foi baixada via OneDrive, porém o arquivo compactado apresentou corrupção crônica na descompactação nesta manhã, possivelmente devido a oscilações de energia causadas por fortes chuvas na região. O download foi reiniciado, mas constatou-se que o pacote enviado pelo cliente não continha as imagens de cartões de assinatura e balcão.
        

## ✅ Decisões Tomadas & Conclusões

- **Postergação da Virada de Olímpia:** Devido à complexidade no mapeamento das tabelas de custas e à estimativa de uma semana solicitada pela equipe do **WebRI** (Michelle/Larissa), a **Virada para Produção** programada para este final de semana foi cancelada para evitar ruídos operacionais graves no cliente. Foguinho demonstrará a base de dados atualizada ao oficial para negociar a extensão do prazo.
    
- **Definição da Homologação de Salto:** O cenário de teste de Salto, que havia sido desmontado para poupar espaço em disco na **Infraestrutura**, será remontado próximo à data disponível na agenda de Vieira. A etapa de **Homologação** foi agendada formalmente para a sexta-feira, 26/06/2026.
    
- **Estratégia de Implantação em Campinas:** A equipe decidiu que, caso a **Conversão** iniciada ontem seja concluída sem erros de encerramento do JBoss, a base de testes será migrada para o ambiente definitivo na semana de trabalho paralelo (15/06 a 19/06) conduzida por Vambak. A meta é realizar o go-live em produção no dia 22/06/2026.
    
- **Integração do Primeiro RI de Franca:** A data para início da implantação do primeiro RI de Franca foi fixada para a semana do dia 29/06/2026, após o encerramento dos testes da **API** desenvolvida em parceria com o sistema Luiz Fernando.
    
- **Rotina de Extração para o 26 SP:** Como o extrator da Escriba exige dependências de DLLs locais e não roda fora do servidor do cliente, Luciane Lima acionará o técnico do **Cartório** (Cristiano) para que ele execute a extração das imagens internamente e realize um novo upload estruturado no OneDrive.
    

## 🚀 Próximos Passos & Pendências (Action Items)

- [ ] **Ação:** Encaminhar a evidência fotográfica e o log do arquivo compactado corrompido do 26 SP para reenvio dos dados | **Responsável:** Luciane Lima | **Prazo:** Imediato
    
- [ ] **Ação:** Formalizar a abertura do chamado de Salto na agenda técnica para reservar o dia de validação do implantador | **Responsável:** Luciane Lima | **Prazo:** Breve
    
- [ ] **Ação:** Entrar em contato com Cristiano (**Cartório** 26 SP) para alinhar as senhas e procedimentos de extração de imagens de balcão | **Responsável:** Marcos Ortiz / Luciane Lima | **Prazo:** Hoje
    
- [ ] **Ação:** Concluir a correção manual dos seis relatórios de inconsistências de Santos para estancar chamados no suporte | **Responsável:** Luciane Lima | **Prazo:** 15/06/2026
    
- [ ] **Ação:** Realizar o levantamento e cruzamento dos títulos autorizados para cancelamento manual em Mogi das Cruzes sem vínculo com a **CRA** | **Responsável:** Ademar Souza | **Prazo:** 16/06/2026
    
- [ ] **Ação:** Finalizar o processamento em lotes e a importação das imagens de títulos e intimações no servidor Linux de Franca | **Responsável:** Ademar Souza | **Prazo:** Hoje
    
- [ ] **Ação:** Direcionar formalmente o chamado de **Conversão** do primeiro RI de Franca para o fluxo de trabalho do desenvolvedor | **Responsável:** Marcus Vinicius Ortiz | **Prazo:** 15/06/2026
    
- [ ] **Ação:** Acompanhar o processamento do motor de Campinas e monitorar o encerramento da fase de ocorrências | **Responsável:** Ademar Souza / Daniel | **Prazo:** Hoje (até às 17h)
    
- [ ] **Ação:** Ajustar a regra de depara no script de Limeira para corrigir a falha de atribuição do status "entregue" em registros de edital | **Responsável:** Ademar Souza | **Prazo:** Concluído (Aguardando feedback de **Mizuno**)
    
- [ ] **Ação:** Validar o recebimento dos arquivos de ofícios e imagens de anexos junto a Julio para complementar o motor de PJ | **Responsável:** Eduardo Silva | **Prazo:** Hoje
    

## 📌 Destaques / Riscos

> ⚠️ **Risco de Atraso Comercial:** A parametrização financeira de Olímpia revelou-se um gargalo crítico. A dependência de desenvolvimento customizado no core business do **WebRI** inviabiliza estimativas automáticas e pode estender o cronograma do cliente por semanas caso o depara de custas falhe nos testes de triggers.
> 
> ⚠️ **Gargalo de Escopo (Novos Motores):** O mapeamento de **Aderência** realizado em Praia Grande apontou o uso do sistema Argon para notas. A **Siplan** não possui motor de **Conversão** homologado para este fornecedor, exigindo o desenvolvimento de um motor do zero na sequência dos projetos prioritários.

## 👥 Resumo de Ações por Participante

**Marcos Ortiz**

- **Status/Relato:** Coordenou a distribuição das demandas, avaliou os impactos técnicos do cancelamento da virada de Olímpia e definiu o remanejamento das datas de Salto e Franca com base na disponibilidade de agenda de atendimento presencial.
    
- **A Fazer (Próximos Passos):** Realizar contato com a gerência de TI do 26 SP para intermediar a liberação de dados e alinhar prazos de infraestrutura.
    

**Luciane Lima**

- **Status/Relato:** Entregou as bases de São Vicente e São Caetano, promovendo o encerramento dos seus respectivos tickets de migração. Reportou falhas de corrupção nos dados compactados recebidos do 26 SP e o travamento físico por falta de espaço no fluxo de Salto, além de catalogar os erros de mapeamento apontados pela auditoria de Santos.
    
- **A Fazer (Próximos Passos):** Dedicar o cronograma entre hoje e segunda-feira para sanar as inconsistências de Santos, remontar o ambiente de Salto para o dia 26/06 e iniciar o estudo de mapeamento de tabelas para o projeto de Praia Grande.
    

**Ademar Souza**

- **Status/Relato:** Validou a entrada em produção de Catanduva aplicando correções em tempo de execução para rotinas de numeração diária de guias, vínculos de acervos e reincorporação de notas e observações em pop-ups. Concluiu as alterações de scripts de Limeira enviadas a **Mizuno** e coordenou a expansão de armazenamento para processar as mídias de Franca.
    
- **A Fazer (Próximos Passos):** Monitorar a conclusão do motor de 24 horas de Campinas, realizar a reimportação manual de dados de cancelamento em Mogi das Cruzes e retomar o desenvolvimento do motor de notas da Visconde.
    

**Eduardo Silva**

- **Status/Relato:** Concluiu a estrutura lógica de PJ de Olímpia, desenvolveu rotinas de depara para tratamento de strings de cadastros, vinculação de tabelas de participação e o parser RTF para HTML para resoluções de exibição de notas devolutivas no **WebRI**. Evidenciou a inviabilidade da virada do RI devido aos severos desvios de conciliação de custas.
    
- **A Fazer (Próximos Passos):** Entregar a base de dados de conferência para Foguinho, processar os arquivos de imagem de ofícios coletados com Julio e aguardar a codificação das tabelas de custas pela equipe de suporte à infraestrutura do produto.
    

**Marcus Vinicius Ortiz**

- **Status/Relato:** Validou o planejamento de datas operacionais, confirmou a disponibilidade de Bruno Matos na agenda para atuações de suporte e **Homologação**, e revisou os prazos de congelamento de escopo para novos chamados de protesto.
    
- **A Fazer (Próximos Passos):** Transferir o chamado técnico do primeiro RI de Franca para Ademar Souza e travar a data do projeto de Salto no cronograma de Vieira.
    

**Alex Silva (Não presente)**

- **Status/Relato:** Atuou diretamente na gerência de **Infraestrutura**, executando a criação de snapshots de segurança e expandindo em 100 GB o volume de armazenamento mapeado para os ambientes de conversão de imagem.
    

**Bárbara (Não presente)**

- **Status/Relato:** Teve a tarefa de desenvolvimento delegada por Larissa para atuar de forma emergencial na sustentação do projeto de Olímpia, mapeando a distribuição de dados financeiros entre as seis tabelas nativas de custas do sistema.
    

**Daniel / Vambak / Maurílio (Não presentes)**

- **Status/Relato:** Atuaram em conjunto no suporte de desenvolvimento para fornecer atualizações de compilação de motores (Campinas), liberação estrutural de scripts de banco de dados para correção de acervos históricos (Catanduva) e mapeamento de campos manuais de cancelamento (Mogi das Cruzes).
    

**Vieira / Henrique / Bruno Matos / Mizuno (Não presentes)**

- **Status/Relato:** Profissionais citados para ações de campo e validação. Mizuno e Bruno Matos atuarão nas homologações e conferências de scripts de Limeira e Catanduva. Vieira realizará visitas técnicas presenciais em São Caetano na próxima semana e em Jundiaí na semana subsequente, ficando responsável pelas demonstrações de rotinas aos usuários finais.