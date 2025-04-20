---
DrugClass: "[[Skeletal Muscle, Bone, and Joint Disorder Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 29](kindle://book?action=open&asin=B09FRF11YJ&location=15248)"
Course: Pharmacology
Chapter: "29"
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
##### Skeletal muscle relaxants
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Skeletal muscle relaxants]] or SecondarySubClass = [[Skeletal muscle relaxants]] or ThirdSubClass = [[Skeletal muscle relaxants]]
sort file.name asc
```

##### Disease-modifying antirheumatic drugs (DMARDs)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Disease-modifying antirheumatic drugs (DMARDs)]] or SecondarySubClass = [[Disease-modifying antirheumatic drugs (DMARDs)]] or ThirdSubClass = [[Disease-modifying antirheumatic drugs (DMARDs)]]
sort file.name asc
```

##### Disease-modifying antirheumatic drugs (DMARDs)-Biologics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Disease-modifying antirheumatic drugs (DMARDs)-Biologics]] or SecondarySubClass = [[Disease-modifying antirheumatic drugs (DMARDs)-Biologics]] or ThirdSubClass = [[Disease-modifying antirheumatic drugs (DMARDs)-Biologics]]
sort file.name asc
```

##### Bone resorption inhibitors - Bisphosphonates
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Bone resorption inhibitors - bisphosphonates]] or SecondarySubClass = [[Bone resorption inhibitors - bisphosphonates]] or ThirdSubClass = [[Bone resorption inhibitors - bisphosphonates]]
sort file.name asc
```

##### Bone resorption inhibitors - Non-Bisphosphonates
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Bone resorption inhibitors - Non-Bisphosphonates]] or SecondarySubClass = [[Bone resorption inhibitors - Non-Bisphosphonates]] or ThirdSubClass = [[Bone resorption inhibitors - Non-Bisphosphonates]]
sort file.name asc
```

##### Uric acid inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"  
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Uric acid inhibitors]] or SecondarySubClass = [[Uric acid inhibitors]] or ThirdSubClass = [[Uric acid inhibitors]]
sort file.name asc
```
