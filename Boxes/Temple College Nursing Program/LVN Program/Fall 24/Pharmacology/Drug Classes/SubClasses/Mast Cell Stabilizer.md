---
DrugClass: "[[Lower Respiratory System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Inhaled Corticosteroids]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
**[[Respiratory]] System Reactions** 
- Throat irritation and dryness 
- Unpleasant taste sensation 
- Cough or wheeze 

This drug may cause a nauseated feeling. A more complete listing of the adverse reactions associated with the mast cell stabilizer is found in the Summary Drug Table: Lower [[Respiratory]] System [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]].

### Contraindications
The mast cell stabilizer is contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and during attacks of acute asthma, because they may worsen bronchospasm during the acute asthma attack. 

A mast cell stabilizer is used cautiously during pregnancy ([[Preg Cat B]]) and lactation and in clients with impaired renal or hepatic function.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
