---
DrugClass: "[[Adrenergic Blocking]]"
BrandName: 
DrugClassContra: "[[Adrenergic Blocking#Contraindications]]"
DrugClassAdverse: "[[Adrenergic Blocking#Side/Adverse Effects]]"
SubClass: "[[Antiadrenergic Drugs Peripherally Acting]]"
SecondaryDrugClass: "[[Antihypertensive Drugs]]"
SecondarySubClass: 
KindleLinkChap: "[Chapter 24](kindle://book?action=open&asin=B09FRF11YJ&location=12809)"
Chapter: "24"
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 

### Contraindications

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
