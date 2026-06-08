<%*
let title = tp.file.title;
let m;
// Se o título já tiver o formato esperado (ex: 08-06--12-06), tenta usar ele.
if (title && title.includes("--")) {
    let startStr = title.split("--")[0];
    m = moment(startStr + "-" + moment().format("YYYY"), "DD-MM-YYYY");
} else {
    // Se for "Sem título" ou não tiver o formato, pergunta ao usuário!
    let promptDate = await tp.system.prompt("Qual a data da Segunda-feira desta semana? (Formato DD/MM/YYYY):", tp.date.weekday("DD/MM/YYYY", 1));
    m = moment(promptDate, ["DD/MM/YYYY", "DD-MM-YYYY", "YYYY-MM-DD"]);
}

// Calcula todos os dias clonando a data inicial para evitar erros
let monday = m.clone().format("YYYY-MM-DD");
let tuesday = m.clone().add(1, 'days').format("YYYY-MM-DD");
let wednesday = m.clone().add(2, 'days').format("YYYY-MM-DD");
let thursday = m.clone().add(3, 'days').format("YYYY-MM-DD");
let friday = m.clone().add(4, 'days').format("YYYY-MM-DD");

// Define como o título do arquivo deveria ser
let titleMon = m.clone().format("DD-MM");
let titleFri = m.clone().add(4, 'days').format("DD-MM");
let expectedTitle = `${titleMon}--${titleFri}`;

// Renomeia o arquivo automaticamente se estiver diferente (ex: "Sem título")
if(title !== expectedTitle) {
    await tp.file.rename(expectedTitle);
}
-%>
---
tipo: planejamento-semanal
inicio: <% monday %>
---
# 🎯 Planejamento da Semana: <% titleMon %> a <% titleFri %>

## 🚀 Prioridades Absolutas (Must-do)
> *As coisas mais importantes que precisam ser entregues nesta semana.*
- [ ] 
- [ ] 
- [ ] 

## 🛠️ Implantação e Cartórios
> *Atividades relacionadas a clientes, projetos e implantações ativas.*
- [ ] 
- [ ] 
- [ ] 
- [ ] 

## ⚙️ Siplan HUB & Processos Internos
> *Melhorias, automações n8n, organização do Obsidian e outros projetos internos.*
- [ ] 
- [ ] 
- [ ] 

## Inbox / Outros Assuntos
> *Coisas menores, ligações rápidas, ou tarefas que surgiram no meio do caminho.*
- [ ] 
- [ ] 

---

## 📝 Diário de Bordo (Logs longos e Atas)
> *Clique nos dias abaixo APENAS se precisar escrever uma ata de reunião longa ou documentar um problema complexo que ocorreu naquele dia. Não use para tarefas.*

- [[<% monday %>]] - Segunda-feira
- [[<% tuesday %>]] - Terça-feira
- [[<% wednesday %>]] - Quarta-feira
- [[<% thursday %>]] - Quinta-feira
- [[<% friday %>]] - Sexta-feira

---

## 🔄 Fechamento da Semana (Sexta-feira)
- [ ] Migrar tarefas que não foram feitas (undone) para a nota da próxima semana.
- [ ] Atualizar o status dos projetos no Siplan HUB.
- [ ] Esvaziar a cabeça para o final de semana.