
```dataview
table without id file.link as "Note", dateformat(file.ctime, "DD") as "Added"
WHERE file.mtime >= date(today) - dur(1 week)
sort file.mtime desc limit 7
```

