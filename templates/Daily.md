---
aliases:
  - Daily note <% tp.date.now("YYYY-MM-DD") %>
tags:
  - Daily
  - <% tp.date.now("YYYY-MM-DD") %>
date: <% tp.date.now("YYYY-MM-DD") %>
---

# Daily note ==#`$= dv.pages('"Daily"').where(b => b.date).where(b => dv.date(b.date) < dv.date("<% tp.date.now("YYYY-MM-DD") %>")).length`==
<% await tp.file.move("/Daily/" + tp.file.title) %>

