---
entry-date: 2026-01-15
UID: 20260115152143
aliases:
  - The Name of the Wind
series: Kingkiller Chronicles
author: Patrick Rothfuss
pages: "661"
published: 2007-03-27
isbn: "9781101147160"
genre:
  - FANTASY
  - FICTION
date-read: Dec 29, 2025
rating: ⭐⭐⭐⭐
goodreads: https://www.goodreads.com/book/show/186074.The_Name_of_the_Wind
banner: https://m.media-amazon.com/images/S/compressed.photo.goodreads.com/books/1704917687i/186074.jpg
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

# The Name of the Wind

## About
Told in Kvothe's own voice, this is the tale of the magically gifted young man who grows to be the most notorious wizard his world has ever seen.  
  
The intimate narrative of his childhood in a troupe of traveling players, his years spent as a near-feral orphan in a crime-ridden city, his daringly brazen yet successful bid to enter a legendary school of magic, and his life as a fugitive after the murder of a king form a gripping coming-of-age story unrivaled in recent literature.  
  
A high-action story written with a poet's hand, _The Name of the Wind_ is a masterpiece that will transport readers into the body and mind of a wizard.
## Quotes

## Review

## Notes

[[Library|books]]