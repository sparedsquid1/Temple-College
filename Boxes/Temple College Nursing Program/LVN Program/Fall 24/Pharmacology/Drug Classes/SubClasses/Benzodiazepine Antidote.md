---
DrugClass: "[[Antianxiety]]"
SubClass: 
DrugClassContra: "[[Antianxiety#Contraindications]]"
DrugClassAdverse: "[[Antianxiety#Side/Adverse Effects]]"
SecondaryDrugClass: 
SecondarySubClass: 
BrandName: 
Chapter: "19"
KindleLinkChap: "[Chapter 19](kindle://book?action=open&asin=B09FRF11YJ&location=10180)"
KindleLink: 
tags:
  - Drug
Course: Pharmacology
---

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage

### Contraindications
See `= this.drugclasscontra`

### Interactions

### Side/Adverse Effects
See `= this.drugclassadverse`

### Interactions

### Drugs with subclass Benzodiazepine Antidote
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = [[Benzodiazepine Antidote]] or SecondarySubClass = [[Benzodiazepine Antidote]]
sort file.name asc
```
