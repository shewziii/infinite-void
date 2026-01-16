---
entry-date: 2026-01-16
UID: 20260116143532
tags:
  - BOOK
  - READING_AS_A_HOBBY
aliases:
  - Empire of the Dawn
series: Empire of the Vampire
author: Jay Kristoff
pages: "826"
published: 2025-11-04
isbn: "9781250245380"
genre:
  - DARK FANTASY
  - HORROR
  - VAMPIRES
status: TBR
date-read:
rating:
goodreads: https://www.goodreads.com/book/show/222376766-empire-of-the-dawn?from_search=true&from_srp=true&qid=IEBO7HKeJR&rank=1
banner: https://m.media-amazon.com/images/S/compressed.photo.goodreads.com/books/1743484777i/222376766.jpg
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

# Empire of the Dawn

## About
**From New York Times bestselling author of the _Empire of the Vampire_ and _Empire of the Damned_, Jay Kristoff, comes the epic conclusion to the #1 internationally bestselling series.  

*From holy cup comes holy light;*  
*The faithful hands sets world aright.*  
*And in the Seven Martyrs’ sight,*  
*Mere man shall end this endless night.*

Gabriel de León has lost his family, his faith, and the last hope of ending the endless night—his surrogate daughter, Dior. With no thought left but vengeance, he and a band of loyal brothers journey into the war-torn heart of Elidaen to claim the life of the Forever King.  

Unbeknownst to the Last Silversaint, the Grail still lives—speeding towards the besieged capital of Augustin in the frail hope of ending Daysdeath. But deadly treachery awaits within the halls of power, and the Forever King’s legions march ever closer. Gabriel and Dior will be drawn into a final battle that will shape the very fate of the Empire, but as the sun sets for what may the last time, there will be no one left for them to trust.  

Not even each other.
## Annotations

## Review

## Notes

[[10 Books|Books]]