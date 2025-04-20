---
DrugClass: "[[Upper Gastrointestinal System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Acid reducers]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Histamine H2 antagonist adverse reactions are usually mild and transient as well as rare (affecting less than 2% of users) and include: 
- Dizziness, [[somnolence]], headache 
- Confusion, hallucinations, diarrhea, and reversible impotence
\
### Contraindications
The [[Histamine H2 antagonists]] are contraindicated in clients with a known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously in clients with renal or hepatic impairment and in severely ill, older, or debilitated clients. [[cimetidine]] is used cautiously in clients with diabetes. [[Histamine H2 antagonists]] are [[Preg Cat B]] ([[cimetidine]] and [[famotidine]]) and C ([[nizatidine]]) [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and should be used with caution during pregnancy and lactation.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
