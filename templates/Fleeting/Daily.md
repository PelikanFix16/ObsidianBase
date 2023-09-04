---
aliases: 
  - "Daily note: <% tp.date.now("YYYY-MM-DD") %>"
<% tp.file.include('[[base template metadata fleeting]]') %>
---

# 🌅 Daily note ==#`$= dv.pages('"<% tp.file.folder() %>"').where(b => b.date).where(b => dv.date(b.date) < dv.date("<% tp.date.now("YYYY-MM-DD") %>")).length`==
<% await tp.file.move("/Daily/" + tp.file.title) %>

