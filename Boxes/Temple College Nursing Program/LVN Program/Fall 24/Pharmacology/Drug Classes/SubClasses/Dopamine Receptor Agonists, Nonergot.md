---
DrugClass: "[[Antiparkinson]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Dopamine Receptor Agonists, Nonergot]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 27](kindle://book?action=open&asin=B09FRF11YJ&location=14154)"
Chapter: "27"
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
The most common adverse reactions include the following: 
- Nausea, dizziness, vomiting 
- [[Somnolence]], hallucinations, confusion, visual disturbances 
- Postural hypotension, abnormal involuntary movements 
- Headache

### Contraindications
[[Dopamine]] receptor agonists are contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. [[Dopamine]] receptor agonists are used with caution in clients with [[dyskinesia]], orthostatic hypotension, hepatic or renal impairment, cardiovascular disease, and a history of hallucinations or psychosis. Both [[ropinirole]] and [[pramipexole]] are [[Preg Cat C]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], and safety during pregnancy has not been established. 

There is an increased risk of [[CNS]] [[Depression]] when the [[Dopamine]] receptor agonists are administered with other [[CNS]] depressants. When administered with [[levodopa]], [[Dopamine]] receptor agonists increase the effects of [[levodopa]] (a lower dosage of [[levodopa]] may be required). In addition, when [[Dopamine]] receptor agonists are administered with [[levodopa]], there is an increased risk of hallucinations. When administered with [[ciprofloxacin]], there is an increased effect of the [[Dopamine]] receptor agonist.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
