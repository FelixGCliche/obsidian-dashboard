---
creation_date: <% tp.file.creation_date("YYYY-MM-DD") %>
---
# Daily Notes <% tp.file.creation_date("YYYY-MM-DD") %>

````ad-card
title: Due Today
icon: lucide-calendar-days
collapse: none

```tasks
due <% tp.file.creation_date("YYYY-MM-DD") %>
short mode
```

```button
name New Task
type command
action Quickadd: task-create
```
````


## Notes