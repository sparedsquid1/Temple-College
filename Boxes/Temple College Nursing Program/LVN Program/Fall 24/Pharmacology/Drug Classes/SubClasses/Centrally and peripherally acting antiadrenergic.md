---
DrugClass: "[[Adrenergic Blocking]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Centrally and peripherally acting antiadrenergic]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 8](kindle://book?action=open&asin=B09FRF11YJ&location=4155)"
Chapter: "8"
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
- Peripherally acting antiadrenergic: hypotension, weakness, lightheadedness, and bradycardia 
- Centrally acting antiadrenergic: dry [[Mouth]], drowsiness, sedation, anorexia, rash, malaise, and weakness
\
### Contraindications
The peripherally acting antiadrenergic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with a hypersensitivity to any of the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. Reserpine is contraindicated in clients who have an active peptic ulcer or ulcerative colitis and in clients who are mentally depressed. Reserpine is used cautiously in clients with a history of [[Depression]], in those with renal impairment or cardiovascular disease, and during pregnancy and lactation. 
Centrally acting antiadrenergic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in active hepatic disease, in antidepressant therapy using MAOIs, and in clients with a history of hypersensitivity to these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. The centrally acting antiadrenergic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously in clients with a history of [[Liver]] disease or renal impairment and during pregnancy and lactation.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
