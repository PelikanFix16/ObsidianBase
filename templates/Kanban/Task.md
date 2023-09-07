<%"---"%>
aliases:
  - <% tp.file.title %> - task
tags:
  - Task
  - <% tp.file.folder() %>
date: <% tp.date.now("YYYY-MM-DD") %>
type: task
---


# 👷‍♂️ ToDo: <% tp.file.title %>


## 👅 Description


## ✅ Subtask

```button
name Add subtask
type command
action QuickAdd: Add subtask
color blue
```



## 📝 References



<% await tp.file.move("/Projects/"+tp.file.folder()+"/Tasks/"+tp.date.now("YYYY-MM-DD")+"/"+tp.file.title) %>

