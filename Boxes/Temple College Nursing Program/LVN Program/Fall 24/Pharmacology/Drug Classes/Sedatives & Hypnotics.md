---
DrugClass: "[[Sedatives & Hypnotics]]"
BrandName: 
SubClass: 
Chapter: "20"
KindleLinkChap: "[Chapter 20](kindle://book?action=open&asin=B09FRF11YJ&location=10565)"
KindleLink: 
tags:
  - Drug
Course: Pharmacology
DrugClassContra: "[[Sedatives & Hypnotics#Contraindications]]"
DrugClassAdverse: "[[Sedatives & Hypnotics#Side/Adverse Effects]]"
---

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage

### Contraindications
These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with known hypersensitivity to sedatives or hypnotics. Do not administer these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] to comatose clients, those with severe [[Respiratory]] problems, those with a history of drug and [[Alcohol]] habitual use, or pregnant or lactating women. Because of a specific enzyme reaction, grapefruit or its juice should not be taken if the client is on [[triazolam]] or [[zaleplon]]. The [[Barbiturates]] are classified as [[Preg Cat D]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. [[Benzodiazepines]] (e.g., [[estazolam]], [[temazepam]], [[triazolam]]) used for sedation are classified as [[Preg Cat X]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. Most [[Nonbenzodiazepines]] are [[Preg Cat B]] or C [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]].

### Interactionsde/Adverse Effects
Nervous system reactions include dizziness, drowsiness, and headache. A common gastrointestinal reaction is nausea.


### Interactions

### Subclasses
#### Benzodiazepine
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass and SubClass = [[Benzodiazepines]] and DrugClass = this.DrugClass
sort file.name asc
```

#### Nonbenzodiazepines
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass and SubClass = [[Nonbenzodiazepines]] and DrugClass = this.DrugClass
sort file.name asc
```

#### Barbiturates
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass and SubClass = [[Barbiturates]] and DrugClass = this.DrugClass
sort file.name asc
```

#### Nonbarbiturates
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass and SubClass = [[Nonbarbiturates]] and DrugClass = this.DrugClass
sort file.name asc
```
