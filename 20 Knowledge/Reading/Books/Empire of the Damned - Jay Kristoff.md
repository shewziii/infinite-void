---
entry-date: 2026-01-16
UID: 20260116141316
tags:
  - book/reading
aliases:
  - Empire of the Damned
series: Empire of the Vampire
author: Jay Kristoff
pages: "725"
published: 2024-03-12
isbn: "9781250245342"
genre:
  - DARK FANTASY
  - HORROR
  - VAMPIRES
status: reading
date-read:
rating:
goodreads: https://www.goodreads.com/book/show/126918599-empire-of-the-damned?from_search=true&from_srp=true&qid=0JzNkYoWpA&rank=1
banner: https://m.media-amazon.com/images/S/compressed.photo.goodreads.com/books/1687870963i/126918599.jpg
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

# Empire of the Damned

## About
From the New York Times bestselling author of the Nevernight Chronicle, Jay Kristoff, comes the much-anticipated sequel to the #1 international bestselling sensation EMPIRE OF THE VAMPIRE.  
  
From holy cup comes holy light;  
The faithful hands sets world aright.  
And in the Seven Martyrs’ sight,  
Mere man shall end this endless night.  
  
Gabriel de León has saved the Holy Grail from death, but his chance to end the endless night is lost. Drawn into an uneasy alliance with the mysterious vampire Liathe, Gabriel must now deliver the Grail to ancients of the Blood Esani, and learn the truth of how Daysdeath might be finally undone.  
  
But the Last Silversaint faces peril, within and without. Pursued by terrors of the Blood Voss, drawn into warfare between the Blood Dyvok and duskdancers of the frozen Highlands, and ravaged by his own rising bloodlust, Gabriel may not survive to see the Grail learn her truth.  
  
And that truth may be too awful for any to imagine.
## Quotes

## Review

## Notes

[[Library|Books]]