<%"---"%>
aliases:
  - "fleeting note project: <% tp.file.title %>"
tags:
  - <% tp.file.folder() %>
  - Fleeting
  - Project
date: <% tp.date.now("YYYY-MM-DD") %>
type: fleeting
---

# ℹ️ Fleeting note topic: <% tp.file.title %>

<% tp.file.include('[[base template]]') %>




<% await tp.file.move("/Projects/"+tp.file.folder()+"/notes/fleeting/"+tp.file.title) %>
