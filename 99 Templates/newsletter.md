---
<%*
const fileName = await tp.system.prompt("Newsletter title");
await tp.file.move("10 Work/Newsletter/" + fileName);
-%>
title: <% fileName %>
type: newsletter
topic: 
content-series: 
episode: 
writing-status: idea
publish_date:
related:
  - 
tags:
  - content/newsletter
---

<%*
await new Promise(resolve => setTimeout(resolve, 300));
-%>
<% tp.file.cursor() %>

## 📖 More Reading for You
