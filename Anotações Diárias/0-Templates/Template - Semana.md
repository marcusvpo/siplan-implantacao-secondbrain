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

// Calcula a data inicial para o frontmatter
let monday = m.clone().format("YYYY-MM-DD");

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

## 🚀 Atualizar Projetos (Siplan HUB)
> *Atualizar os projetos ativos diariamente no HUB.*
- [ ] Segunda
- [ ] Terça
- [ ] Quarta
- [ ] Quinta
- [ ] Sexta

## 🛠️ Implantação e Cartórios
> *Atividades relacionadas a clientes, projetos e implantações ativas.*
- [ ] 
- [ ] 
- [ ] 

## ⚙️ Desenvolvimento & Processos Internos
> *Melhorias Siplan HUB e Siplan Skills, automações , organização e projetos internos.*
- [ ] 
- [ ] 
- [ ] 

## Inbox / Outros Assuntos
> *Coisas menores, ligações rápidas, ou tarefas que surgiram no meio do caminho.*
- [ ] 
- [ ] 

---

## 📝 Atas e Reuniões da Semana
> *Documente aqui os detalhes de reuniões, alinhamentos ou problemas complexos que ocorreram ao longo da semana.*
- 

---

## 🔄 Fechamento da Semana (Sexta-feira)
- [ ] Migrar tarefas que não foram feitas (undone) para a nota da próxima semana.
- [ ] Atualizar o status dos projetos no Siplan HUB.
- [ ] Esvaziar a cabeça para o final de semana.