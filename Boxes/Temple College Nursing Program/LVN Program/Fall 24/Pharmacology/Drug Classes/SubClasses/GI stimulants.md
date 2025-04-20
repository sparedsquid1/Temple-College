---
DrugClass: "[[Upper Gastrointestinal System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[GI stimulants]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Adverse reactions associated with [[metoclopramide]] are usually mild. Higher doses or prolonged administration may produce [[CNS]] ([[CNS]]) symptoms, such as restlessness, drowsiness, dizziness, extrapyramidal effects (tremor, involuntary movements of the limbs, muscle rigidity), facial grimacing, and [[Depression]].

### Contraindications
The GI stimulant is contraindicated in clients with known hypersensitivity to the drug, GI obstruction, gastric perforation or hemorrhage, or [[pheochromocytoma]]. Clients with Parkinson disease or a seizure disorder who are taking [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] likely to cause extrapyramidal symptoms should not take these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. This drug is used cautiously in clients with diabetes and cardiovascular disease. [[metoclopramide]] is a [[Preg Cat B]] drug. The drug is secreted in breast milk and should be used with caution during pregnancy and lactation.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
