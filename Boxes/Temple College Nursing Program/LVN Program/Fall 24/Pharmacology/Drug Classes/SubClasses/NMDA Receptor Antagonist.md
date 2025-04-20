---
DrugClass: "[[Antidementia]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[NMDA Receptor Antagonist]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 8](kindle://book?action=open&asin=B09FRF11YJ&location=4155)"
Chapter: "8"
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
