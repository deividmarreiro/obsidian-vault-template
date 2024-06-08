---
date: <%tp.date.now("YYYY-MM-DD")%>T<%tp.date.now("HH:mm")%>
tags:
  - Daily
cssclasses:
  - daily
  <% "- " + tp.date.now("dddd", 0, tp.file.title, "YYYYMMDD").toLowerCase() %>
---
# DAILY NOTE
## <% tp.date.now("dddd, MMMM Do, YYYY", 0, tp.file.title, "YYYYMMDD") %>
***
### Log
#### TIME
Customize this template to your liking!
...
***
### Daily Deeds & Rituals
- [ ] Task 1
- [ ] Task 2
- [ ] Task 3