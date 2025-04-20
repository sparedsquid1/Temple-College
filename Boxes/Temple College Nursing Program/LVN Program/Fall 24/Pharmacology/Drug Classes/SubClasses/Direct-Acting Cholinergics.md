---
DrugClass: "[[Cholinergic Drugs]]"
BrandName: 
DrugClassContra: "[[Cholinergic Drugs#Contraindications]]"
DrugClassAdverse: "[[Cholinergic Drugs#Side/Adverse Effects]]"
SubClass: "[[Direct-Acting Cholinergics]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 25](kindle://book?action=open&asin=B09FRF11YJ&location=13417)"
Chapter: "25"
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
See `= this.DrugClassAdverse`

### Contraindications
See `= this.DrugClassContra`

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
