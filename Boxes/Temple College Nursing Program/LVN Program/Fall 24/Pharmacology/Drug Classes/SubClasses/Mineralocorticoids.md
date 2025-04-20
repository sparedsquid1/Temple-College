---
DrugClass: "[[Pituitary and Adrenocortical Hormones]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Mineralocorticoids]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Adverse reactions may occur if the dosage is too high or prolonged or if withdrawal is too rapid. Administration of [[fludrocortisone]] may cause:
- Edema, hypertension, HF, enlargement of the [[Heart]] 
- Increased sweating, allergic skin rash 
- Hypokalemia, muscular weakness, headache, [[hypersensitivity reactions]] 

Because this drug has glucocorticoid and mineralocorticoid activity and is often given with [[Glucocorticoids]], adverse reactions of [[Glucocorticoids]] must be closely monitored as well (see [[Box 41.2]]).

### Contraindications
[[fludrocortisone]] is contraindicated in clients with hypersensitivity to [[fludrocortisone]] and in those with systemic fungal infections. [[fludrocortisone]] is used cautiously in clients with [[Addison disease]] or infection and during pregnancy ([[Preg Cat C]]) and lactation. [[fludrocortisone]] decreases the effects of [[Hydantoins]] and [[rifampin]]. There is a decrease in serum levels of [[Salicylates]] when those agents are administered with [[fludrocortisone]].

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
