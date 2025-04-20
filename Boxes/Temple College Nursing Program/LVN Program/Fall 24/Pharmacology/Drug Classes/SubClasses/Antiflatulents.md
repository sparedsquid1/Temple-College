---
DrugClass: "[[Lower Gastrointestinal System Drugs]]"
BrandName: 
DrugClassContra: "[[Antiflatulents#Contraindications]]"
DrugClassAdverse: "[[Antiflatulents#Adverse Reactions]]"
SubClass: "[[Antiflatulents]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
No adverse reactions have been reported with the use of antiflatulents.

### Contraindications
Antiflatulents are contraindicated in clients with known hypersensitivity to any components of the drug. The pregnancy category of [[simethicone]] has not been determined; because it is not absorbed, it may be safe for use during pregnancy, although the primary health care provider should be consulted whenever any drug is to be taken. [[Charcoal]] is a [[Preg Cat C]] drug.
           
### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
