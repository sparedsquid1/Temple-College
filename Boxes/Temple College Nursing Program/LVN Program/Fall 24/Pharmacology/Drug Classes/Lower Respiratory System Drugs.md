---
DrugClass: "[[Lower Respiratory System Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 31](kindle://book?action=open&asin=B09FRF11YJ&location=16553)"
Course: Pharmacology
Chapter: "31"
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
#### Bronchodilators
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class", ThirdDrugClass as "3rd Drug Class", ThirdSubClass as "3rd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass or ThirdDrugClass = this.DrugClass and subclass and subclass = [[Bronchodilators]] or SecondarySubClass = [[Bronchodilators]] or ThirdSubClass = [[Bronchodilators]]
sort file.name asc
```

#### Mast Cell Stabilizer
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass or ThirdDrugClass = this.DrugClass and subclass and subclass = [[Mast Cell Stabilizer]] or SecondarySubClass = [[Mast Cell Stabilizer]] or ThirdSubClass = [[Mast Cell Stabilizer]]
sort file.name asc
```

#### Leukotriene Modifiers and Immunomodulators
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass or ThirdDrugClass = this.DrugClass and subclass and subclass =[[Leukotriene Modifiers and Immunomodulators]] or SecondarySubClass = [[Leukotriene Modifiers and Immunomodulators]] or ThirdSubClass = [[Leukotriene Modifiers and Immunomodulators]]
sort file.name asc
```

