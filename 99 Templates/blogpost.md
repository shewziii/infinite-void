---
<%*
const fileName = await tp.system.prompt("Blog post title");
await tp.file.move("10 Projects/Act One Creative/Blog/" + fileName);
-%>
title: <% fileName %>
type: blog
status: idea
topic: 
published: false
publish_date:
created: <% tp.date.now("YYYY-MM-DD") %>
tags:
  - blog
  - act-one-creative
related:
  - 
---