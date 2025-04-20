---
DrugClass: "[[Antihyperlipidemic Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Miscellaneous Antihyperlipidemic Drugs]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
**Gastrointestinal System Reactions** 
- Nausea, vomiting, abdominal pain 
- Diarrhea 

**Other Reactions** 
- Severe, generalized flushing of the skin; sensation of warmth 
- Severe itching or tingling 
- Generalized muscle aches and flu-like symptoms

### Contraindications
[[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/niacin|niacin]] is contraindicated in clients with known hypersensitivity to [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/niacin|niacin]], active peptic ulcer, hepatic dysfunction, and arterial bleeding. The drug is used cautiously in clients with renal dysfunction, high [[Alcohol]] consumption, unstable angina, gout, and pregnancy ([[Preg Cat C]]). Increased uric acid levels and possible risk of tendon rupture can occur with the use of bempedoic acid. Pregnant and lactating women should not use bempedoic acid or [[ezetimibe]].

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
