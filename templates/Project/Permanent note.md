<%"---"%>
aliases:
  - "permanent note project: <% tp.file.title %>"
tags:
  - <% tp.file.folder() %>
  - Permanent
  - Project
date: <% tp.date.now("YYYY-MM-DD") %>
type: permanent
---


# Permanent note topic: <% tp.file.title %>

## 📝 Description

## 🔗 References

---
# ❗ Important things:


---
# 🤔 What we want to: 


---
# 🤝 What do we need:


---
# ✅ Expected effect:


---
# 🕐 Estimated time:



<% await tp.file.move("/Projects/"+tp.file.folder()+"/notes/permanent/"+tp.file.title) %>
