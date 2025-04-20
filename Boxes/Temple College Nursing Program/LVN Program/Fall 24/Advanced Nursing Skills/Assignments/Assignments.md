---
tags:
  - MOCs
  - LVN
  - ANS
  - linker-exclude
---
```dataviewjs
let parentFolder = dv.current().file.folder

if (parentFolder == "")
  parentFolder = "/"
  
const lsFolder = app.vault.getFiles()
  .filter(file => file.parent.path == parentFolder )
  .map(file => dv.fileLink(file.path))

dv.list(lsFolder)
```
