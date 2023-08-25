---
tags: 
- index
---
# Old vault journal
```dataview
Table file.cday AS "Date"
From "Journal"
Where file.cday<date("2023-06-30")
Sort file.cday DESC 
```

---
# New vault journal
## 2023
```dataview
Table file.cday AS "Date"
From "Journal"
Where file.cday>date("2023-06-30")
Sort file.cday DESC 
```
