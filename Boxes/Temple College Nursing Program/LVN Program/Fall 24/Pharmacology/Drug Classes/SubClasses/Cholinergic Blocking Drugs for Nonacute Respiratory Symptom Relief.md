---
DrugClass: "[[Cholinergic Blocking Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Cholinergic Blocking Drugs for Nonacute Respiratory Symptom Relief]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 26](kindle://book?action=open&asin=B09FRF11YJ&location=13703)"
Chapter: "26"
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
