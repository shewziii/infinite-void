---
title: Scientific Advertising
author: Claude Hopkins
type: book
series:
series-number:
genre:
  - business
status: reading
date-read:
rating:
published: 2019-03-22
pages: "106"
isbn: "9781090890191"
goodreads: https://www.goodreads.com/ro/book/show/2621927-scientific-advertising
cover: https://m.media-amazon.com/images/I/71fMDLTeggL._AC_UF1000,1000_QL80_.jpg
tags:
  - book/business
---

```dataviewjs
const page = dv.current();

// cover
let coverImageHTML = page.cover
  ? `<img src="${page.cover}" alt="Cover Image" style="width:100%; height:auto; display:block;">`
  : "No cover";

// date-read format to YYYY-MM-DD
let formattedDate = page["date-read"]
  ? window.moment(page["date-read"]).format("YYYY-MM-DD")
  : "N/A";

// goodreads: view
let goodreadsLink = page.goodreads
  ? `<div><strong>Goodreads:</strong> <a href="${page.goodreads}" target="_blank">View</a></div>`
  : "";

// book details in stack
let detailsHTML = [
  `<div><strong>Author:</strong> ${page.author ?? "N/A"}</div>`,
  `<div><strong>Series:</strong> ${page.series ?? "N/A"}</div>`,
  `<div><strong>Genre:</strong> ${page.genre ?? "N/A"}</div>`,
  `<div><strong>Status:</strong> ${page.status ?? "N/A"}</div>`,
  `<div><strong>Date Read:</strong> ${formattedDate}</div>`,
  `<div><strong>Rating:</strong> ${page.rating ?? "N/A"}</div>`,
  goodreadsLink
].join("");

// html table
dv.container.innerHTML = `
  <table style="width:100%; border-collapse: collapse;">
    <thead>
      <tr>
        <th style="text-align:left; padding: 4px; width: 30%;">Cover</th>
        <th style="text-align:left; padding: 4px;">Details</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="vertical-align: top; padding: 4px;">${coverImageHTML}</td>
        <td style="vertical-align: top; padding: 4px;">${detailsHTML}</td>
      </tr>
    </tbody>
  </table>
`;
```

# Scientific Advertising

## About
Scientific Advertising is an important work on advertising from the early 20th century and is still used today by those learning the basics and more advanced parts of the advertising field. The author of Scientific Advertising, Claude C. Hopkins, is well known as the father of modern advertising techniques, and this book has been widely used by students of advertising and marketing. This book covers many important aspects of advertising including how advertising laws are established, mail order advertising, headlines, psychology, strategy, budgeting, and more advanced subjects like negative advertising and how to test an advertising campaign.

---
## Quotes


---
## Notes


---
## Review


---
[[Library|Books]]