---
entry-date: 2026-01-16
UID: 20260116131621
tags:
  - book/read
aliases:
  - Buyology
series:
author: Martin Lindstrom
pages: "274"
published: 2010-02-02
isbn: "9780385523899"
genre:
  - business
  - psychology
  - science
date-read: 2026-02-01
rating:
status: read
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

> Because emotions are the way in which our brains encode things of value, and a brand that engages us emotionally—think Apple, Harley-Davidson, and L'Oréal, just for starters—will win every single time.

### Chapter II
> Unless the brand in question plays a fundamental party of the storyline, we won’t remember it, period.

### Chapter III
> *Yawn*. Are you yawning now, or feeling the initial stirrings of yawning? I am, and not because I’m bored, or tired of writing about the brain, but simply because I just typed the word *yawn*. You see, mirror neurons become activated not only when we’re *observing* other people’s behavior, they even fire when we’re *reading* about someone performing it.

> The results found that the subject’ orbitofrontal cortices—the region of the brain associated with rest processing—were more active when the subject were learning and recalling the names of smiling individuals.

### Chapter IV
> The researchers termed this effect "unconscious emotion," meaning that a minute emotional change had taken place without the subjects being aware of either the stimulus that caused it or any shift in their emotional states. In other words, smiling faces can subconsciously get us to buy more stuff, suggesting that store managers who instruct their employees to smile are on the right track.

### Chapter V
> Whether you know it or not, you don't want to tamper with the region of your brain made up of your "implicit" memory, which encompasses everything you know how to do without thinking about it, from riding a bike to parallel-parking to tying your shoelaces to buying a book effortlessly on Amazon.

> And in many ways, brand obsession has a lot in common with rituals and superstitious behavior—both involve habitual, repeated actions that have little or no logical basis, and both stem from the need for a sense of control in an overwhelming and complex world.

### Chapter VI

---
## Notes
### Chapter I
Chapter 1 touches on who Martin Lindstrom is, information about the study, what the parameters were, his subjects, the reach of the study, and gave some foreshadowing conclusions, including:
- warning labels are a waste of money
- fMRI and SST used together can paint a clear picture of what’s going on in consumers brains
- Traditional research methods such as focus groups, surveys, and quantitative and qualitative research are not as effective as we think because while we believe we are telling the truth, our brains tell another story
- Appealing to emotions will win out over logical reasoning and value every single time

Based on a study done in Princeton University, students were asked to choose between a $15 Amazon gift card now, or a $20 gift card a week from now. Most of the students chose immediate gratification because of that emotional response to getting something they deem valuable *now*.

### Chapter II
This chapter explored the concept of product placement in media, such as Coke’s strategic product placement on American Idol, Ford’s not so effective use of ad spots on the network of the same show, or Reese’s Pieces incredibly culture changing placement in Stephen Spielberg’s E.T., which caused theaters around the nation to carry the peanut butter chocolate candy. 

Based on a study he did, Lindstrom concludes that product placement is only effective if the product or brand plays a critical role in the media it’s placed in. 

### Chapter III
This chapter explores the role of mirror neurons and dopamine in our buying decisions. Lindstrom voices the idea that a lot of what we do and why we buy is to increase our status in society. This is because we—humans, who at the base level are just animals—attribute status to higher levels of attraction, and the more status we have, the more likely it is for us to find a mate. Where mirror neurons and dopamine come into play is in the consumer journey. Martin Lindstrom talked about Abercrombie and Fitch, which makes use of young, attractive clerks, pictures of models, and even positions groups of models sporting their apparel outside of stores. Consumers who walked into or around the stores felt their status improved just by observing and being around those models. It made them feel good. They walk into the store, and they see clothes on mannequins and on the models and think “that could be me if I wore these clothes”, so they move to buy. Dopamine is released when we make buying decisions. 

### Chapter IV
Subliminal messaging has been a controversial topic in advertising for a long time, with many consumers believing it to be a malicious and manipulative practice. Subliminal messaging is the use of imagery, audio cues, and visual cues that lie just below the threshold of conscious awareness to influence decision-making. Though it isn’t as concrete as people used to believe, there is evidence that points to effective use of subliminal messaging in marketing—just in different ways. When showed images of people smiling vs people frowning for a fraction of a second, subjects of an experiment seemed to be more willing to buy and spend more from the messaging that showed the smiling faces. Lindstrom also explains—in regard to cigarette smokers—that when smokers see the logos of cigarette companies explicitly, they put their guards up because they know it’s bad for them. However, when put through an experiment where only imagery, colors, and visual cues that were used by the companies (and not logos), the parts of the subjects’ brains that are associated with craving became more active than when they were explicitly shown the logos. Lindstrom explains that this happens because the smokers had their guards down. With no explicit signals to tell them that what they were seeing was related to the cigarette brands, their brains were free to take in the subliminal messaging even more.

### Chapter V
This chapter explores superstitions and rituals. Although we know that many of the superstitions we perform regularly—knocking on wood so you don’t jinx yourself, walking around a ladder rather than underneath—don’t have any rational roots or logical reasoning behind them, we still perform them. Why? Lindstrom believes this comes from the innate need to feel in control. Animals, including humans, exhibit elevated levels of stress when put in any situation where they feel they aren’t in control. Your implicit memory is in charge of doing things automatically. You don’t think about riding a bike, tying your shoelaces, or washing your hands. You just do it. There’s a certain degree of comfort in ritualistic behavior. Regarding companies, things like dipping Oreos in milk, waiting for a glass of Guinness to be poured perfectly, or even just buying the same brand of toothpaste are all examples of rituals we do.

### Chapter VI

---
## Review


---
[[Library|Books]]