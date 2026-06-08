<%*
let title = tp.file.title;
let noteDate = title;

// Se você criar a nota na mão e ela se chamar "Sem título", ele renomeia para hoje automaticamente.
if(title.includes("Sem título") || title.includes("Untitled")) {
    noteDate = tp.date.now("YYYY-MM-DD");
    await tp.file.rename(noteDate);
}
-%>
---
tipo: log-diario
data: <% noteDate %>
---
# 📅 <% noteDate %>

## ✅ Checklist do Dia (Tarefas e Lembretes)
- [ ] 
- [ ] 
- [ ] 

## 📝 Log / Anotações Rápidas
- 

## 🤝 Reuniões / Atendimentos (Atas e Detalhes)
- 
