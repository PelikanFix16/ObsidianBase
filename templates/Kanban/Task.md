---
aliases:
  - <% tp.file.title %> - task
tags:
  - Task
  - Kanban
  - <% tp.file.folder() %>
date: <% tp.date.now("YYYY-MM-DD") %>
type: task
---


# 👷‍♂️ ToDo: <% tp.file.title %>


## 👅 Description


## ✅ Subtask

- [ ] Subtasks
	- [ ] test task
		- [ ] test 
	- [ ] test



## 📝 References



<% await tp.file.move("/Projects/"+tp.file.folder()+"/Tasks/"+tp.date.now("YYYY-MM-DD")+"/"+tp.file.title) %>

