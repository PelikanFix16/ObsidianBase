<%"---"%>
aliases:
  - Fleeting <% tp.file.folder() %> - index
tags:
  - <% tp.file.folder() %>
  - Index
  - Fleeting
date: <% tp.date.now("YYYY-MM-DD") %>
type: index
---

# Add new note

```button
name Add fleeting note
type command
action QuickAdd: Add fleeting note
color blue
```

# Notes list

```dataview
LIST
FROM "Fleeting/<% tp.file.folder() %>/notes" and #Fleeting 
```
