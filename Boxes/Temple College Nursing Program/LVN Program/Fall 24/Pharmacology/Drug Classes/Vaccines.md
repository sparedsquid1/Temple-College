---
DrugClass: "[[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drug Classes/Vaccines]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 47](kindle://book?action=open&asin=B09FRF11YJ&location=27339)"
Course: Pharmacology
Chapter: "47"
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
#### Agents for Active Immunity
##### Vaccines, Bacterial (Routine Immunization)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Vaccines and Toxoids]] and SubCat = "Vaccines, Bacterial (Routine Immunization)"
sort file.name asc
```

##### Vaccines, Bacterial (Special Populations)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Vaccines and Toxoids]] and SubCat = "Vaccines, Bacterial (Special Populations)"
sort file.name asc
```

##### Vaccines, Viral (Routine Immunization)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Vaccines and Toxoids]] and SubCat = "Vaccines, Viral (Routine Immunization)"
sort file.name asc
```

##### Vaccines, Pandemic (Routine Immunization-Emergency Authorization)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Vaccines and Toxoids]] and SubCat = "Vaccines, Pandemic (Routine Immunization-Emergency Authorization)"
sort file.name asc
```

##### Vaccines, Viral (Special Populations)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Vaccines and Toxoids]] and SubCat = "Vaccines, Viral (Special Populations)"
sort file.name asc
```

##### Toxoids (Routine Immunization)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Vaccines and Toxoids]] and SubCat = "Toxoids (Routine Immunization)"
sort file.name asc
```

##### Combination Products (Viral/Bacterial Vaccine or Toxoid Together)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Vaccines and Toxoids]] and SubCat = "Combination Products (Viral/Bacterial Vaccine or Toxoid Together)"
sort file.name asc
```

#### Agents for Passive Immunity
##### Immuglobins
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Immune globulins and anitvenins]] and SubCat = "Immune Globulins"
sort file.name asc
```
##### Antivenins
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Immune globulins and anitvenins]] and SubCat = "Antivenins"
sort file.name asc
```
