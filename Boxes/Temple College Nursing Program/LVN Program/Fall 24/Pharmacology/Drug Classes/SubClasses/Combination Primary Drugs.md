---
DrugClass: "[[Antitubercular]]"
BrandName: 
DrugClassContra: "[[Antitubercular#Contraindications]]"
DrugClassAdverse: "[[Antitubercular#Side/Adverse Effects]]"
SubClass: "[[Combination Primary Drugs]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 10](kindle://book?action=open&asin=B09FRF11YJ&location=5128)"
Chapter: "10"
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
See `= this.DrugClassContra`

### Contraindications
See `= this.DrugClassAdverse`

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
