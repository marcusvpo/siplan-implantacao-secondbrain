---
tipo: Recurso
area: Siplan Hub
tags:
  - #recurso
  - #contatos
  - #emails
  - #fallback
  - #implantacao
status_atual: #ativo
---
# 📇 Tabela Geral de Mapeamento de E-mails de Colaboradores (Fallback)

Esta tabela serve como a fonte de verdade para buscas estáticas e fallbacks nas automações de e-mail no n8n. Ela mapeia o nome do colaborador (registrado nos campos de texto livre legados no banco de dados) para o seu e-mail institucional oficial do domínio `@siplan.com.br`.

---

## 👥 Lista de Colaboradores e Contatos

| Nome do Colaborador | Área / Cargo | E-mail Oficial |
| :--- | :--- | :--- |
| **Marcus** | Gestão / Coordenação | `marcus.vinicius@siplan.com.br` |
| **Bruno Fernandes** | Conversão de Dados | `bruno.fernandes@siplan.com.br` |
| **Marcos Ortiz** | Conversão de Dados | `marcos.ortiz@siplan.com.br` |
| **Ademar** | Conversão de Dados | `ademar.souza@siplan.com.br` |
| **Luciane** | Conversão de Dados | `luciane.lima@siplan.com.br` |
| **Eduardo Silva** | Conversão de Dados | `eduardo.silva@siplan.com.br` |
| **Luan Caldeira** | Conversão de Dados | `luan.caldeira@siplan.com.br` |
| **Amanda Flor** | Administrativo / Vendas | `amanda.flor@siplan.com.br` |
| **Maurilio Camargo** | Administrativo / Vendas | `maurilio.camargo@siplan.com.br` |
| **Maria** | Implantação / Coordenação | `maria.santos@siplan.com.br` |
| **Alex Silva** | Infraestrutura / Suporte | `alex.silva@siplan.com.br` |
| **Hugo Januário** | Infraestrutura / Suporte | `hugo.santariosi@siplan.com.br` |
| **Rodrigo Brites (Brites)** | Implantador de Campo (TN/PRO) | `rodrigo.brites@siplan.com.br` |
| **Ricardo Vieira** | Implantador de Campo (TN) | `ricardo.vieira@siplan.com.br` |
| **Bruno Santos (Bruno Matos)** | Implantador de Campo (TN/PRO) | `bruno.santos@siplan.com.br` |
| **Rodrigo Mizuno (Mizuno)** | Implantador de Campo (PRO) | `rodrigo.mizuno@siplan.com.br` |
| **Julio Araujo** | Implantador de Campo (REG) | `julio.araujo@siplan.com.br` |
| **Fernando Cruz** | Especialista WEB RI (RI) | `fernando.lopes@siplan.com.br` |

---

## 🛠️ Como Utilizar no n8n (Nó de Busca de Fallback)

Quando uma automação precisar enviar um e-mail para o responsável pelo projeto e a consulta ao `public.profiles` retornar nula ou sem e-mail, utilize um nó **Switch** ou um nó **Code (JavaScript)** para obter a correspondência a partir deste mapeamento estático.

### Exemplo de implementação no nó Code do n8n:
```javascript
const emailMap = {
  "marcus": "marcus.vinicius@siplan.com.br",
  "bruno fernandes": "bruno.fernandes@siplan.com.br",
  "marcos ortiz": "marcos.ortiz@siplan.com.br",
  "ademar": "ademar.souza@siplan.com.br",
  "luciane": "luciane.lima@siplan.com.br",
  "eduardo silva": "eduardo.silva@siplan.com.br",
  "luan caldeira": "luan.caldeira@siplan.com.br",
  "amanda flor": "amanda.flor@siplan.com.br",
  "maurilio camargo": "maurilio.camargo@siplan.com.br",
  "maria": "maria.santos@siplan.com.br",
  "alex silva": "alex.silva@siplan.com.br",
  "hugo januário": "hugo.santariosi@siplan.com.br",
  "rodrigo brites": "rodrigo.brites@siplan.com.br",
  "brites": "rodrigo.brites@siplan.com.br",
  "ricardo vieira": "ricardo.vieira@siplan.com.br",
  "bruno santos": "bruno.santos@siplan.com.br",
  "bruno matos": "bruno.santos@siplan.com.br",
  "rodrigo mizuno": "rodrigo.mizuno@siplan.com.br",
  "mizuno": "rodrigo.mizuno@siplan.com.br",
  "julio araujo": "julio.araujo@siplan.com.br",
  "julio": "julio.araujo@siplan.com.br",
  "fernando cruz": "fernando.lopes@siplan.com.br"
};

// Normalização do nome para busca
const responsibleName = item.json.responsible_name ? item.json.responsible_name.toLowerCase().trim() : "";
item.json.resolved_email = emailMap[responsibleName] || "marcus.vinicius@siplan.com.br"; // Marcus como fallback global
return item;
```
