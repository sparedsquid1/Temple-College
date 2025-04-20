---
DrugClass: "[[Immunostimulants and Immunomodulators]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 48](kindle://book?action=open&asin=B09FRF11YJ&location=27993)"
Course: Pharmacology
Chapter: "48"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications


### Side/Adverse Effects 


### SubClasses
#### Interferons
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Interferons]] and SubCat = null
sort file.name asc
```

#### Colony Stimulating Factors
##### Hematopoietic Factors for Infection
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Interferons]] and SubCat = "Hematopoietic Factors for Infection"
sort file.name asc
```

##### Hematopoietic Factors for Anemia
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Interferons]] and SubCat = "Hematopoietic Factors for Anemia"
sort file.name asc
```

##### Adjuvant Agents
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and file.name = "Folic acid" or SubClass = [[Interferons]] and SubCat = "Adjuvant Agents"
sort file.name asc 
```
