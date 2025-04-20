---
DrugClass: "[[Antibacterial(That Disrupt the Bacterial Cell Wall)]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 7](kindle://book?action=open&asin=B09FRF11YJ&location=3380)"
Course: Pharmacology
Chapter: "07"
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications

### Side/Adverse Effects 

### SubClasses
#### Penicillins
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "Secondary Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = [[Antibacterial(That Disrupt the Bacterial Cell Wall)]] and SubClass = [[Penicillins]]
sort file.name asc
```

#### Cephalosporins
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "Secondary Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = [[Antibacterial(That Disrupt the Bacterial Cell Wall)]] and SubClass = [[Cephalosporins]]
sort file.name asc
```


#### Miscellaneous Drugs That Inhibit Bacterial Cell Wall Synthesis
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "Secondary Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = [[Antibacterial(That Disrupt the Bacterial Cell Wall)]] and SubClass = [[Miscellaneous Drugs That Inhibit Bacterial Cell Wall Synthesis]]
sort file.name asc
```

#### Carbapenems
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "Secondary Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = [[Antibacterial(That Disrupt the Bacterial Cell Wall)]] and SubClass = [[Carbapenems]]
sort file.name asc
```
