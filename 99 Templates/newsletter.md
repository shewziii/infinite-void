---
<%*
const fileName = await tp.system.prompt("Newsletter title");
await tp.file.move("10 Projects/Act One Creative/Newsletter/" + fileName);
-%>
title: <% fileName %>
series: 
episode: 
type: newsletter
status: idea
topic: 
published: false
publish_date:
created: <% tp.date.now("YYYY-MM-DD") %>
tags:
  - newsletter
  - act-one-creative
related:
  - 
---

<% tp.file.cursor() %>