<%"---"%>
aliases:
  - <% tp.file.title %> - subtask
tags:
  - Subtask
  - Kanban
  - <% tp.file.folder(true).split("/")[tp.file.folder(true).split("/").length - 3] %>
date: <% tp.date.now("YYYY-MM-DD") %>
type: subtask
---

# 👷‍♂️ ToDo: <% tp.file.title %>



## 👅 Description



## 📝 References





<% await tp.file.move("/Projects/"+tp.file.folder(true).split("/")[tp.file.folder(true).split("/").length - 3]+"/Tasks/"+tp.date.now("YYYY-MM-DD")+"/Subtasks/"+tp.file.title) %>


