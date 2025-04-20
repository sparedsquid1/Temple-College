---
DrugClass: "[[Upper Gastrointestinal System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Antiemetics]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
The most common adverse reactions resulting from these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are varying degrees of drowsiness. Additional adverse reactions for each drug are listed in the Summary Drug Table: Upper Gastrointestinal System [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]].

### Contraindications
Antiemetic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with known hypersensitivity to these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] or with severe [[CNS]] [[Depression]]. The 5-HT3 receptor antagonists should not be used by clients with [[Heart]] block or prolonged QT intervals. In general, these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are not recommended during pregnancy and lactation or for uncomplicated vomiting in young children. [[prochlorperazine]] is contraindicated in clients with bone marrow [[Depression]], [[Blood]] dyscrasia, Parkinson disease, or severe [[Liver]] or cardiovascular disease.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
