---
DrugClass: "[[Antidiabetic Drugs]]"
BrandName: 
DrugClassContra: "[[Antidiabetic Drugs#Contraindications]]"
DrugClassAdverse: "[[Antidiabetic Drugs#Side/Adverse Effects]]"
SubClass: "[[Dipeptidyl Peptidase-4 Inhibitors]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
aliases:
  - Gliptins
---
### Adverse Reactions 
See `= this.DrugClassAdverse`

Headache and upper [[Respiratory]] tract symptoms such as nasopharyngitis are the most frequent adverse reactions when taking this medication.


### Contraindications
See `= this.DrugClassContra`

These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] should not be used for DKA or if the client has type 1 diabetes. A gliptin should be used cautiously in clients with chronic kidney disease or in older adults. This drug has not been studied in pregnant women but is believed to be a category B drug from animal studies, and it should be used cautiously in lactating women.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
