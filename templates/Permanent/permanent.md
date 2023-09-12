<%"---"%>
aliases:
  - "Permanent note: <% tp.file.title %>"
tags:
  - <% tp.file.folder() %>
  - Permanent
  - Remember
date: <% tp.date.now("YYYY-MM-DD") %>
type: permanent
---

# 🧠 <% tp.file.title %> 

---
# 📒 Note:

**References**:
- [[]]
- [[]]



---
# ❗Important things:


---
# 📆 How to achieve the goal:



---
# 🍧 Summary:




---
# ✅ Expected effect:


<% await tp.file.move("/Permanent/"+tp.file.folder()+"/permanent/"+tp.file.title) %>
