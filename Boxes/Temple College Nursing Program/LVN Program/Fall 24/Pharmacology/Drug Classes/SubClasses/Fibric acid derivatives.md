---
DrugClass: "[[Antihyperlipidemic Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Fibric acid derivatives]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
The adverse reactions associated with fibric acid derivatives include the following: 
- Nausea, vomiting, and GI upset 
- Diarrhea
- Cholelithiasis (stones in the [[Gallbladder]]) or cholecystitis (inflammation of the [[Gallbladder]]) 

If cholelithiasis is found, the primary health care provider may discontinue the drug. See the Summary Drug Table: Antihyperlipidemic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] for additional adverse reactions.

### Contraindications
The fibric acid derivatives are contraindicated in clients with hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and in those with significant hepatic or renal dysfunction or primary biliary cirrhosis because these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] may increase the already elevated cholesterol. The [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously during pregnancy ([[Preg Cat C]]) and not during lactation.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
