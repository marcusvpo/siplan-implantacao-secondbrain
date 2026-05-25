---
tipo: Hub
modulo: Conversão de Projetos
tags:
  - #hub
  - #conversao
---
# [Hub] Conversão de Projetos

Módulo crítico do Siplan Hub para a equipe de banco de dados migrar sistemas legados.

## Funcionalidades
- **Fila de Conversão e Minha Fila:** Tabela de projetos em conversão com filtros. "Minha Fila" foca nas tarefas do usuário logado.
- **Motores de Conversão (Engines):** Painel de controle e monitoramento de scripts e rotinas de migração em tempo real.
- **Homologação:** Etapa de governança para projetos que aguardam validação de dados e aceite do cartório.

## Processos: AS-IS vs TO-BE

### 1. Triagem e Distribuição de Fila
- **AS-IS:** Distribuição de tarefas é informal, feita via Teams, mensagem ou ligação, com base na especialidade técnica de cada analista.
- **TO-BE:** Ao clicar em **"Enviar para Conversão"** na gestão do projeto, o card cai na "Fila de Conversão". O analista técnico assume a tarefa (movendo para "Minha Fila") e passa a utilizar um sistema de **"Posts" (Timeline)** para registrar atualizações rápidas e objetivas ao longo do desenvolvimento do motor.

### 2. Processo de Homologação (Conversão -> Implantação)
- **AS-IS:** Após converter, o analista envia um e-mail ao Implantador com acessos e caminhos. O Implantador valida e reporta inconsistências em um documento Word/Docs respondendo ao mesmo e-mail.
- **TO-BE:** **A dinâmica por e-mail será mantida.** O objetivo é *não* forçar o Implantador a entrar no Hub apenas para reportar homologação. O botão "Enviar para Homologação" no Hub servirá exclusivamente para a equipe de Conversão marcar o status interno de acompanhamento. A comunicação com a Implantação segue via canais tradicionais.
