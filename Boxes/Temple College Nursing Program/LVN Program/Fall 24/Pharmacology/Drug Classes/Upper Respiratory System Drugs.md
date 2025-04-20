---
DrugClass: "[[Upper Respiratory System Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 30](kindle://book?action=open&asin=B09FRF11YJ&location=15967)"
Course: Pharmacology
Chapter: "30"
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
#### Intranasal Steroids (INSs)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Intranasal Steroids (INSs)]]
sort file.name asc
```

#### First-Generation Antihistamines
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class", ThirdDrugClass as "3rd Drug Class", ThirdSubClass as "3rd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[First-Generation Antihistamines]] or SecondarySubClass = [[First-Generation Antihistamines]] or ThirdSubClass = [[First-Generation Antihistamines]]
sort file.name asc
```

#### Second-Generation Antihistamines
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Second-Generation Antihistamines]] or SecondarySubClass = [[Second-Generation Antihistamines]] or ThirdSubClass = [[Second-Generation Antihistamines]]
sort file.name asc
```

#### Decongestant
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Decongestant]] or SecondarySubClass = [[Decongestant]] or ThirdSubClass = [[Decongestant]]
sort file.name asc
```

#### Antitussive
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class", ThirdDrugClass as "3rd Drug Class", ThirdSubClass as "3rd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Antitussive]] or SecondarySubClass = [[Antitussive]] or ThirdSubClass = [[Antitussive]]
sort file.name asc
```

#### Mucolytic
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Mucolytic]] or SecondarySubClass = [[Mucolytic]] or ThirdSubClass = [[Mucolytic]]
sort file.name asc
```

#### Expectorant
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Expectorant]] or SecondarySubClass = [[Expectorant]] or ThirdSubClass = [[Expectorant]]
sort file.name asc
```
