---
DrugClass: "[[Antihyperlipidemic Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Bile acid resins]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
- Constipation (may be severe and occasionally result in fecal impaction), aggravation of hemorrhoids, abdominal cramps, flatulence, nausea 
- Increased bleeding tendencies related to vitamin K malabsorption, and vitamin A and D deficiencies

### Contraindications
The [[Bile]] acid resins are contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. [[Bile]] acid resins are also contraindicated in those with complete biliary obstruction. 

These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously in clients with diabetes, [[Liver]], peptic ulcer, or kidney disease. [[Bile]] acid resins should be used cautiously during pregnancy ([[Preg Cat C]]) and lactation (decreased absorption of [[Vitamins]] may affect the infant).

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
