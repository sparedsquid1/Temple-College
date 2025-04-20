---
DrugClass: "[[Anticoagulant and Thrombolytic Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Antiplatelet Agents]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Some of the more common adverse reactions include the following: 
- [[Heart]] palpitations
- Bleeding 
- Dizziness and headache
- Nausea, diarrhea, constipation, [[Dyspepsia]] 

### Contraindications
Contraindications and Precautions Antiplatelet [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in pregnant or lactating clients and those with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], congestive [[Heart]] failure, active bleeding, or thrombotic thrombocytopenic purpura (TTP). These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are to be used cautiously in older adult clients, pancytopenic clients, or those with renal or hepatic impairment. If TTP is diagnosed, the antiplatelet treatment should be stopped immediately. [[clopidogrel]] is a [[Preg Cat B]] and the others are [[Preg Cat C]]; none of these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] have been well studied in humans. Antiplatelet [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] should be discontinued 1 week before any surgical procedure.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
