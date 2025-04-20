---
DrugClass: "[[Upper Respiratory System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Decongestant]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
When used topically in prescribed doses, there are usually minimal systemic effects in most individuals. On occasion, nasal burning, stinging, and dryness may be seen. When the topical form is used frequently or if the liquid is swallowed, the same adverse reactions seen with the oral decongestants may occur. Use of oral decongestants may result in the following adverse reactions: 
- Tachycardia and other cardiac arrhythmias 
- Nervousness, restlessness, and insomnia 
- Blurred [[Vision]] 
- Nausea and vomiting

### Contraindications
Decongestants are contraindicated in clients with known hypersensitivity and in clients taking [[MAOI]] antidepressants. Sustained-release [[pseudoephedrine]] is contraindicated in children younger than 12   years.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
