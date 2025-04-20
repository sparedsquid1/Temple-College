---
DrugClass: "[[Cardiotonic and Antiarrhythmic Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 37](kindle://book?action=open&asin=B09FRF11YJ&location=20599)"
Course: Pharmacology
Chapter: "37"
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
#### Cardiotonics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Cardiotonics]] or SecondarySubClass = [[Cardiotonics]]
sort file.name asc
```

#### Antiarrhythmics
##### Class I: sodium channel blockers 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name = "procainamide" or file.name = "quinidine" or file.name = "lidocaine" or file.name = "mexiletine" or file.name = "flecainide" or file.name = "propafenone" or file.name = "disopyramide"
sort file.name asc
```

##### Class II: beta-adrenergic (β-adrenergic) blockers 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class" , FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name = "acebutolol" or file.name = "esmolol" or file.name = "propranolol"
sort file.name asc
```

##### Class III: potassium channel blockers 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name = "amiodarone" or file.name = "dofetilide" or file.name = "dronedarone" or file.name = "ibutilide" or file.name = "sotalol"
sort file.name asc
```

##### Class IV: calcium channel blockers 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name = "diltiazem" or file.name = "verapamil"
sort file.name asc
```

##### Class V: other antiarrhythmics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name = "adenosine" or file.name = "digoxin"
sort file.name asc
```
