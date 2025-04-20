---
DrugClass: "[[Upper Gastrointestinal System Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 38](kindle://book?action=open&asin=B09FRF11YJ&location=21363)"
Course: Pharmacology
Chapter: "38"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications


### Side/Adverse Effects 


### Subclasses
#### Acid neutralizers
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Class", SecondarySubClass as "Secondary Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Acid neutralizers]] or SecondarySubClass = [[Acid neutralizers]]
sort file.name asc
```

#### Acid reducers
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Class", SecondarySubClass as "Secondary Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Acid reducers]] or SecondarySubClass = [[Acid reducers]]
sort file.name asc
```

#### GI stimulants
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Class", SecondarySubClass as "Secondary Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[GI stimulants]] or SecondarySubClass = [[GI stimulants]]
sort file.name asc
```

#### Antiemetics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Class", SecondarySubClass as "Secondary Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Antiemetics]] or SecondarySubClass = [[Antiemetics]]
sort file.name asc
```
