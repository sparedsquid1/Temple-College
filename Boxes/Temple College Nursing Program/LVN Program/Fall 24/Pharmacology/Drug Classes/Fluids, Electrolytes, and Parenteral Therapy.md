---
DrugClass: "[[Fluids, Electrolytes, and Parenteral Therapy]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 54](kindle://book?action=open&asin=B09FRF11YJ&location=32655)"
Course: Pharmacology
Chapter: "54"
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

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass
sort file.name asc
```

