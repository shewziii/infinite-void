---
banner: "![[urban_architecture.jpg]]"
entry-date: <% tp.date.now("YYYY-MM-DD") %>
UID: <% tp.date.now("YYYYMMDDHHmm") %>-303101
tags:
  - daily
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
````col
```col-md
flexGrow=1
===
> [!PREVIOUS] [[<% tp.date.now("YYYY-MM-DD", -1) %>|Yesterday]]
```
```col-md
flexGrow=1
===
>[!NEXT] [[<% tp.date.now("YYYY-MM-DD", 1) %>|Next Day]]
```
````

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

# Today's Notes


>[!note]- Created and Modified
>```dataview
>TABLE WITHOUT ID file.link AS "File Name", file.mtime AS "Modified On"
>WHERE file.cday = this.file.day OR file.mday = this.file.day
>SORT file.mtime desc
>LIMIT 10
>```

---
````col
```col-md
flexGrow=1
===
> [!BUTTON] [[Projects]]
```
```col-md
flexGrow=1
===
>[!BUTTON] [[Library]]
```
````
