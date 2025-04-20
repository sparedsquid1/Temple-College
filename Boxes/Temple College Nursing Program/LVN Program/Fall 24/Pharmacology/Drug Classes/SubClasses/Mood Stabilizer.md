---
DrugClass: "[[Antidepressent]]"
DrugClassContra: 
DrugClassAdverse: 
SubClass: 
SecondaryDrugClass: 
SecondarySubClass: 
BrandName: 
Chapter: "21"
KindleLinkChap: "[Chapter 21](kindle://book?action=open&asin=B09FRF11YJ&location=10945)"
KindleLink: 
tags:
  - Drug
Course: Pharmacology
---
```smiles

```

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage

### Contraindications

### Interactions

### Side/Adverse Effects

### Interactions


### Drugs with SubClass Mood Stabilizer
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = [[Mood Stabilizer]] or SecondarySubClass = [[Mood Stabilizer]]
sort file.name asc
```
