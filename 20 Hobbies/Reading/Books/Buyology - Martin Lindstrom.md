---
entry-date: 2026-01-16
UID: 20260116131621
tags:
  - BOOK
  - READING_AS_A_HOBBY
aliases:
  - Buyology
series:
author: Martin Lindstrom
pages: "274"
published: 2010-02-02
isbn: "9780385523899"
genre:
  - BUSINESS
  - PSYCHOLOGY
  - SCIENCE
status: READING
date-read:
rating:
goodreads: https://www.goodreads.com/book/show/2848658-buyology
banner: https://m.media-amazon.com/images/S/compressed.photo.goodreads.com/books/1631079519i/2848658.jpg
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

# Buyology

## About
How much do we know about why we buy? What truly influences our decisions in today’s message-cluttered world? An eye-grabbing advertisement, a catchy slogan, an infectious jingle? Or do our buying decisions take place below the surface, so deep within our subconscious minds, we’re barely aware of them?  
  
In BUYOLOGY, Lindstrom presents the astonishing findings from his groundbreaking, three-year, seven-million-dollar neuromarketing study, a cutting-edge experiment that peered inside the brains of 2,000 volunteers from all around the world as they encountered various ads, logos, commercials, brands, and products. His startling results shatter much of what we have long believed about what seduces our interest and drives us to buy. Among his  
  
Gruesome health warnings on cigarette packages not only fail to discourage smoking, they actually make smokers want to light up.  
  
Despite government bans, subliminal advertising still surrounds us – from bars to highway billboards to supermarket shelves.  
  
"Cool” brands, like iPods trigger our mating instincts.  
  
Other senses – smell, touch, and sound - are so powerful, they physically arouse us when we see a product.  
  
Sex doesn't sell. In many cases, people in skimpy clothing and suggestive poses not only fail to persuade us to buy products - they often turn us away .  
  
Companies routinetly copy from the world of religion and create rituals – like drinking a Corona with a lime – to capture our hard-earned dollars.  
  
Filled with entertaining inside stories about how we respond to such well-known brands as Marlboro, Nokia, Calvin Klein, Ford, and American Idol, BUYOLOGY is a fascinating and shocking journey into the mind of today’s consumer that will captivate anyone who’s been seduced – or turned off – by marketers’ relentless attempts to win our loyalty, our money, and our minds. Includes a foreword by Paco Underhill.

---
## Quotes
### Chapter I
> warning labels on the sides, fronts, and backs of cigarette packs had no effect on suppressing the smokers' cravings at all. Zero. In other words, all those gruesome photographs, government regulations, billions of dollars some 123 countries had invested in nonsmoking campaigns, all amounted, at the end of a day, to, well, a big waste of money.

> In short, the fMRI results showed that cigarette warning labels not only failed to deter smoking, but by activating the nucleus accumbens, it appeared they actually encouraged smokers to light up. We couldn't help but conclude that those same cigarette warning labels intended to curb smoking, reduce cancer, and save lives had instead become a killer marketing tool for the tobacco industry.

> We may think we know why we do the things we do—but a much closer look into the brain tells us otherwise.

> Because emotions are the way in which our brains encode things of value, and a brand that engages us emotionally—think Apple,Harley Davidson, and L’Oreal, just for starters—will win every single time.

### Chapter II

---
## Notes
### Chapter I
Chapter 1 touches on who Martin Lindstrom is, information about the study, what the parameters were, his subjects, the reach of the study, and gave some foreshadowing conclusions, including:
- warning labels are a waste of money
- fMRI and SST used together can paint a clear picture of what’s going on in consumers brains
- Traditional research methods such as focus groups, surveys, and quantitative and qualitative research are not as effective as we think because while we believe we are telling the truth, our brains tell another story
- Appealing to emotions will win out over logical reasoning and value every single time

Based on a study done in Princeton university, students were asked to choose between a $15 Amazon gift card now, or a $20 gift card a week from now. Most of the students chose immediate gratification because of that emotional response to getting something they deem valuable *now*.
### Chapter II


---
## Review


---
[[Library|Books]]