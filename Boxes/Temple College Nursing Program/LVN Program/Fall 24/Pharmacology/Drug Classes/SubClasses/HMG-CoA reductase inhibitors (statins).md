---
DrugClass: "[[Antihyperlipidemic Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[HMG-CoA reductase inhibitors (statins)]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
The statins are usually well tolerated. Adverse reactions, when they do occur, are often mild and transient and do not require discontinuing therapy. These reactions may include the following. 

**[[CNS]] Reactions**
- Headache
- Dizziness
- Insomnia
- Memory and cognitive impairment 

**Gastrointestinal System Reactions** 
- Flatulence, abdominal pain, cramping 
- Constipation, nausea
- Hyperglycemia in nondiabetic clients 

Clients may experience leg pain or cramping. This can be an indication of a more serious condition— ,.

### Contraindications
The statins are contraindicated in individuals with hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] or serious [[Liver]] disorders, and during pregnancy ([[Preg Cat X]]) and lactation. In some individuals with diabetes risk factors, statin [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] may elevate serum glucose and HbA1c levels. 

These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously in clients with a history of alcoholism, non– [[Alcohol]]-related [[Liver]] disease, acute infection, hypotension, trauma, endocrine disorders, visual disturbances, and myopathy.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
