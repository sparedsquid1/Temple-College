---
DrugClass: "[[Opioid Analgesics and Antagonists]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 15](kindle://book?action=open&asin=B09FRF11YJ&location=8219)"
Course: Pharmacology
Chapter: "15"
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
#### Agonists (Activate Receptors and Cause Action) 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Opioid Analgesics]] or SecondarySubClass = [[Opioid Analgesics]] or ThirdSubClass = [[Opioid Analgesics]] and SubCat = null
sort file.name asc
```

#### Agonists–Antagonists (Activate/Blocks Receptors, Causing Effect to a Lesser Extent) 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Opioid Analgesics]] or SecondarySubClass = [[Opioid Analgesics]] or ThirdSubClass = [[Opioid Analgesics]] and SubCat = "Agonists–Antagonists (Activate/Blocks Receptors, Causing Effect to a Lesser Extent)"
sort file.name asc
```

#### Antagonists (Blocks Receptors, Reverses the Effect of the Opiate)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Opioid Analgesics]] or SecondarySubClass = [[Opioid Analgesics]] or ThirdSubClass = [[Opioid Analgesics]] and SubCat = "Antagonists (Blocks Receptors, Reverses the Effect of the Opiate)"
sort file.name asc
```
