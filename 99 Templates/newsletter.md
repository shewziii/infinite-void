---
<%*
const fileName = await tp.system.prompt("Newsletter title");
await tp.file.move("10 Projects/Act One Creative/Newsletter/" + fileName);
-%>
title: <% fileName %>
type: newsletter
content-series: 
episode: 
writing-status: idea
topic: 
publish_date:
created: <% tp.date.now("YYYY-MM-DD") %>
tags:
  - content/newsletter
related:
  - 
---

<%*
await new Promise(resolve => setTimeout(resolve, 300));
-%>
<% tp.file.cursor() %>

## 📖 More Reading for You
