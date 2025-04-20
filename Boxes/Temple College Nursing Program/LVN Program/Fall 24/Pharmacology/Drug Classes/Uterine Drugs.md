---
DrugClass: "[[Uterine Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 44](kindle://book?action=open&asin=B09FRF11YJ&location=25702)"
Course: Pharmacology
Chapter: "44"
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
#### Oxytocics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Oxytocic drugs]] or SecondarySubClass = [[Oxytocic drugs]] and SubCat = null
sort file.name asc
```

##### Agents for Cervical Ripening
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Oxytocic drugs]] or SecondarySubClass = [[Oxytocic drugs]] and SubCat = "Agents for Cervical Ripening"
sort file.name asc
```

#### Tocolytics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass or ThirdDrugClass = this.DrugClass and SubClass = [[Tocolytics]] or SecondarySubClass = [[Tocolytics]] or ThirdSubClass = [[Tocolytics]] 
sort file.name asc
```

