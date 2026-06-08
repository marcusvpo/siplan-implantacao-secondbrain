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
# 🎯 Planejamento da Semana

## 📥 Inbox / Foco da Semana (Despejo de Ideias)
- [ ] 
- [ ] 
- [ ] 

## 🗓️ Checklist dos Dias da Semana

### [[<% monday %>]] - Segunda-feira
- [ ] 
- [ ] 

### [[<% tuesday %>]] - Terça-feira
- [ ] 
- [ ] 

### [[<% wednesday %>]] - Quarta-feira
- [ ] 
- [ ] 

### [[<% thursday %>]] - Quinta-feira
- [ ] 
- [ ] 

### [[<% friday %>]] - Sexta-feira
- [ ] 
- [ ] 

## 🔄 Revisão Semanal
- [ ] Mover tarefas pendentes (undone) para a próxima semana
- [ ] Atualizar status de implantações no Siplan HUB