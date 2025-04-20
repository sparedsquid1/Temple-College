---
DrugClass: "[[Antidiabetic Drugs]]"
BrandName: 
DrugClassContra: "[[Antidiabetic Drugs#Contraindications]]"
DrugClassAdverse: "[[Antidiabetic Drugs#Side/Adverse Effects]]"
SubClass: "[[Alpha-Glucosidase Inhibitors]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
aliases:
  - α-glucosidase
  - AGIs
---
### Adverse Reactions 
See `= this.DrugClassAdverse`

Increasing the dose of these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] should be done slowly to reduce the GI adverse reactions of bloating, flatulence, and diarrhea. The use of these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] in the United States is limited because of the unpleasant and not well-tolerated adverse GI reactions.

### Contraindications
See `= this.DrugClassContra`

Alpha-glucosidase inhibitors are contraindicated in clients with preexisting GI problems, such as irritable bowel syndrome or Crohn disease. They should not be used for DKA or if the client has cirrhosis. [[Digestive]] enzymes may reduce the effect of [[miglitol]]. [[acarbose]] and [[miglitol]] are used cautiously in clients with renal impairment. Considered [[Preg Cat B]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], they have not been studied sufficiently to render safe to take while pregnant or when lactating.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
