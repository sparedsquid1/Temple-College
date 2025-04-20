---
DrugClass: "[[Upper Gastrointestinal System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Proton pump inhibitors]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
The most common adverse reactions seen with the proton pump inhibitors include headache, nausea, diarrhea, and abdominal pain.

### Contraindications
PPIs are contraindicated in clients who are hypersensitive to any of the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. PPIs are used cautiously in older adults and in clients with hepatic impairment. Prolonged treatment may decrease the body’s ability to absorb vitamin [[B12]], resulting in anemia. [[omeprazole]] ([[Preg Cat C]]) and [[lansoprazole]], [[rabeprazole]], and [[pantoprazole]] ([[Preg Cat B]]) are contraindicated during pregnancy and lactation.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
