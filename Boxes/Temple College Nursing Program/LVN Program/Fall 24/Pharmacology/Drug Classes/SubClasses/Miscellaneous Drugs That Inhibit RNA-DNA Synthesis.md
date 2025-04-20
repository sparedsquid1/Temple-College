---
DrugClass: "[[Antibacterial(Drugs That Interfere With DNA- RNA) Template]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Miscellaneous Drugs That Inhibit RNA-DNA Synthesis]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 9](kindle://book?action=open&asin=B09FRF11YJ&location=4794)"
Chapter: "09"
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
