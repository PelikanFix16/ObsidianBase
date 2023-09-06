---
aliases: 
  - "<% tp.file.folder() %> note: <% tp.file.title %>"
<% tp.file.include('[[base template metadata fleeting]]') %>
---

# 🕵️‍♂️ <% tp.file.folder() %> note topic: <% tp.file.title %>


<% tp.file.include('[[base template]]') %>


<% await tp.file.move("/Fleeting/"+tp.file.folder()+"/notes/"+tp.date.now("YYYY-MM-DD")+"/"+tp.file.title) %>



