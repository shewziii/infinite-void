---
entry-date: 2026-01-16
UID: 20260116010735
tags:
  - BOOK
  - READING_AS_A_HOBBY
aliases:
  - "Empire of the Vampire"
series:
author: "Jay Kristoff"
pages: "747"
published: "2021-09-14"
isbn: "9781250245298"
genre:
status:
date-read:
rating:
goodreads:
banner:
banner-y:
banner-x:
---

```dataviewjs
const page = dv.current();

// cover
let coverImageHTML = page.banner
  ? `<img src="${page.banner}" alt="Cover Image" style="width:100%; height:auto; display:block;">`
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

# Empire of the Vampire

## About

## Series

## Annotations

## Review

## Notes

[[books]]