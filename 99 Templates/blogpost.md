---
<%*
const fileName = await tp.system.prompt("Blog post title");
await tp.file.move("10 Work/Blog/" + fileName);
-%>
title: <% fileName %>
type: blogpost
writing-status: idea
topic: 
publish_date:
tags:
  - content/blog
related:
  - 
created: <% tp.date.now("YYYY-MM-DD") %>
---

<%*
await new Promise(resolve => setTimeout(resolve, 300));
-%>
<% tp.file.cursor() %>