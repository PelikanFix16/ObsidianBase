<%"---"%>
aliases:
  - <% tp.file.folder() %> - index
tags:
  - <% tp.file.folder() %>
  - Index
date: <% tp.date.now("YYYY-MM-DD") %>
type: index
---

# ⚡ Fleeting notes:

```button
name Add fleeting note
type command
action QuickAdd: Add project fleeting note
color blue
```


```dataview
LIST
FROM "Projects/<% tp.file.folder() %>/notes/fleeting" and #Fleeting 
```



# 🚩 Permanent notes:

```button
name Add Permanent note
type command
action QuickAdd: Add project permanent note
color blue
```


```dataview
LIST
FROM "Projects/<% tp.file.folder() %>/notes/permanent" and #Permanent 
```

