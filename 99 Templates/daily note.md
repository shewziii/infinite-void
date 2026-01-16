---
banner: "![[urban_architecture.jpg]]"
entry-date: <% tp.date.now("YYYY-MM-DD") %>
UID: <% tp.date.now("YYYYMMDDHHmm") %>-303101
tags:
  - DAILY-NOTE
related:
  - '[[<% tp.date.now("YYYY-[W]ww") %>]]'
banner-x: 50
banner-y: 100
banner-height: 400
banner-fade: -30
content-start: 451
---
# <% tp.date.now("dddd") %>, <% tp.date.now("MMM Do, YYYY") %>
---
<< [[<% tp.date.now("YYYY-MM-DD", -1) %>|Yesterday]] | [[<% tp.date.now("YYYY-MM-DD", 1) %>|Next Day]] >> | 

<% tp.web.daily_quote() %>

## Task Inbox

>[!todo]+ Today
>```tasks
>not done
>happens {{date}}
>sort by priority
>```
>>[!success]- Done
>>```tasks
>>done
>>happens this week
>>group by due
>>sort by priority
>>```

>[!tip]- This Month
>```tasks
>not done
>happens this month
>group by due
>sort by due
>```

# Today's Log


# Today's Notes

>[!note]- Created and Modified
>```dataview
>TABLE WITHOUT ID file.link AS "File Name", file.mtime AS "Modified On"
>WHERE file.cday = this.file.day OR file.mday = this.file.day
>SORT file.mtime desc
>LIMIT 10
>```

## On This Day
```dataview
LIST
FROM ""
WHERE dateformat(file.day, "MM-dd") = dateformat(this.file.day, "MM-dd")
```