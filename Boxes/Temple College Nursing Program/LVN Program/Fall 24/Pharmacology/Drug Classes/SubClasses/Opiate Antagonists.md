---
DrugClass: "[[Opioid Analgesics and Antagonists]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Opiate Antagonists]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
**Generalized reactions include:**
- Nausea and vomiting 
- Sweating 
- Tachycardia 
- Increased [[Blood]] pressure 
- Tremors
### Contraindications
Antagonists are contraindicated in those with a hypersensitivity to the [[Opioid Antagonists]]. Antagonists are used cautiously in those who are pregnant ([[Preg Cat B]]), in infants of opioid-dependent mothers, and in clients with an opioid dependency or cardiovascular disease. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] also are used cautiously during lactation. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] may produce withdrawal symptoms in individuals who are physically dependent on the opioid. Antagonists may prevent the action or intended use of opioid [[Antidiarrheals]], antitussives, and [[Analgesics]].

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
