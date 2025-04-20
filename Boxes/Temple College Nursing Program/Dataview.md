https://obsidian.rocks/dataview-in-obsidian-a-beginners-[[Guide]]/

```dataview
table file.path, file.size, file.mtime from "Boxes/Temple College Nursing Program" 
WHERE file.mtime >= date(today) - dur(1 week)
```
