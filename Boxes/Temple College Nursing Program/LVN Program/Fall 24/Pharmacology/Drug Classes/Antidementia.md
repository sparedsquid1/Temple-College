---
DrugClass: "[[Antidementia]]"
SubClass: 
Chapter: "18"
KindleLinkChap: "[Chapter 18](kindle://book?action=open&asin=B09FRF11YJ&location=9834)"
KindleLink: 
tags:
  - Drug
BrandName: 
Course: Pharmacology
---
### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`
	
### Contraindications

### Side/Adverse Effects

### Subclasses
#### Cholinesterase Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "Secondary Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and SubClass = [[Cholinesterase Inhibitors]]
```

#### NMDA Receptor Antagonist
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "Secondary Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and SubClass = [[NMDA Receptor Antagonist]]
```

#### Combination Drugs
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "Secondary Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Combination Drugs]]
```



