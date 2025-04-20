---
DrugClass: "[[Urinary Tract Anti-Infectives and Other Urinary Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 46](kindle://book?action=open&asin=B09FRF11YJ&location=26990)"
Course: Pharmacology
Chapter: "46"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications


### Side/Adverse Effects 


### SubClasses
#### Urinary anti-infectives
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondaryDrugClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Urinary anti-infectives]] or SecondSubClass = [[Urinary anti-infectives]] and SubCat = Null or SubCat = "Aminopenicillins"
sort file.name asc
```

#### Urinary Anti-Infective Combinations
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondDrugClass as "2nd Class", SecondSubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Urinary anti-infectives]] or SecondSubClass = [[Urinary anti-infectives]] and SubCat = "Urinary Anti-Infective Combinations"
sort file.name asc
```

#### Other Urinary Drug (Analgesic)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondDrugClass as "2nd Class", SecondSubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Urinary anti-infectives]] or SecondSubClass = [[Urinary anti-infectives]] and SubCat = "Other Urinary Drug (Analgesic)"
sort file.name asc
```
