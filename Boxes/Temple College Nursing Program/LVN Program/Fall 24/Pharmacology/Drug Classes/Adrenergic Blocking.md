---
DrugClass: "[[Adrenergic Blocking]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 24](kindle://book?action=open&asin=B09FRF11YJ&location=12809)"
Course: Pharmacology
Chapter: "24"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications

### Side/Adverse Effects 

### Subclasses
#### Beta (β)-adrenergic blocking
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass and DrugClass = [[Adrenergic Blocking]] and subclass = [[Beta (β)-adrenergic blocking]] or SecondarySubClass = [[Beta (β)-adrenergic blocking]]
sort file.name asc
```

#### Antiadrenergic Drugs Peripherally Acting
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass and DrugClass = [[Adrenergic Blocking]] and subclass = [[Antiadrenergic Drugs Peripherally Acting]]
sort file.name asc
```

#### Antiadrenergic Drugs Centrally Acting
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass and DrugClass = [[Adrenergic Blocking]] and subclass = [[Antiadrenergic Drugs Centrally Acting]]
sort file.name asc
```

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass and DrugClass = [[Adrenergic Blocking]]
sort file.name asc
```
