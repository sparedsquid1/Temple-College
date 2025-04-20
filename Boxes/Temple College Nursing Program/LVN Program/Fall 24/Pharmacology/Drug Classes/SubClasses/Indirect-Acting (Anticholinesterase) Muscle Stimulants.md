---
DrugClass: "[[Cholinergic Drugs]]"
BrandName: 
DrugClassContra: "[[Cholinergic Drugs#Contraindications]]"
DrugClassAdverse: "[[Cholinergic Drugs#Side/Adverse Effects]]"
SubClass: "[[Indirect-Acting (Anticholinesterase) Muscle Stimulants]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
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
