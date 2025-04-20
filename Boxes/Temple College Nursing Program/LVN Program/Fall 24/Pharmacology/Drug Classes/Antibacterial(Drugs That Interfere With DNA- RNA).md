---
DrugClass: "[[Antibacterial(Drugs That Interfere With DNA- RNA) Template]]"
DrugClassContra: 
DrugClassAdverse: 
SubClass: 
SecondaryDrugClass: 
SecondarySubClass: 
BrandName: 
Chapter: "09"
KindleLinkChap: "[Chapter 9](kindle://book?action=open&asin=B09FRF11YJ&location=4794)"
KindleLink: 
tags:
  - Drug
Course: Pharmacology
---
### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
See `= this.DrugClassContra`

### Side/Adverse Effects
See `= this.DrugClassAdverse`

### SubClasses

#### fluoroquinolones
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "Secondary Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and SubClass = [[Fluoroquinolones]]
sort file.name asc
```


#### Miscellaneous Drugs That Inhibit RNA-DNA Synthesis
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "Secondary Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and SubClass = [[Miscellaneous Drugs That Inhibit RNA-DNA Synthesis]]
sort file.name asc
```
