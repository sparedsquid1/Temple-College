---
DrugClass: "[[Antiparkinson]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[COMT Inhibitors]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 27](kindle://book?action=open&asin=B09FRF11YJ&location=14154)"
Chapter: "27"
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
(catechol-O-methyltransferase)
### Adverse Reactions 
Adverse reactions most often associated with the administration of COMT inhibitors include the following: 
- Dizziness 
- Dyskinesias, hyperkinesias, [[akathisia]] (extreme restlessness and increased motor activity) 
- Nausea, anorexia, and diarrhea 
- Orthostatic hypotension, sleep disorders, excessive dreaming [[somnolence]] and muscle cramps

### Contraindications
These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and during pregnancy and lactation ([[Preg Cat C]]). [[tolcapone]] is contraindicated in clients with [[Liver]] dysfunction. The COMT inhibitors are used with caution in clients with hypertension, hypotension, and decreased hepatic or renal function.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
