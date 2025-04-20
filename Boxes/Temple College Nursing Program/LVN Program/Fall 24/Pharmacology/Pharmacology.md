---
tags:
  - MOCs
  - LVN
  - Pharmacology
Course: Pharmacology
SearchName: tylenol
aliases:
  - Pharm
---
https://templejc.desire2learn.com/d2l/[[Home]]/157088

 ```button
name GCalWeek
type command
action Google Calendar: Open gCal week view
color green
```
^button-gCalWk

```folder-index-content
```

#### Drug Search `= this.SearchName`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", subclass as "Sub Class", file.mtime as "Last modified"
WHERE contains(file.folder, "Fall 24") and contains(lower(file.name), lower(this.SearchName)) or contains(lower(BrandName), lower(this.SearchName)) or contains(DrugClass, this.SearchName) or contains(subclass, this.SearchName) and this.SearchName != null
sort file.mtime desc
```


![[Pharmacology Quizzes Test [[Boxes/Temple College Nursing Program/LVN Program/Summer 24/Mental Health and Illness/Assignments/Assignments|Assignments]]#Grades]]

### Jump to other classes
[[Advanced Nursing Skills]]
[[Clinical-Lvn Training]]
[[OB]]
[[MED-SURG]]
