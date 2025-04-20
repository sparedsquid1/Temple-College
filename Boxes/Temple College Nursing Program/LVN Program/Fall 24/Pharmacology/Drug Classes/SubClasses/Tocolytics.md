---
DrugClass: "[[Uterine Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Tocolytics]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Adverse reactions include the following: 
- To the mother 
	- Fatigue, flushing, headache, dizziness, diplopia 
	- Nausea, vomiting, stomach upset, heartburn 
	- Prolonged vaginal bleeding 
	- Sweating, hypotension, depressed reflexes, and flaccid paralysis are other adverse reactions associated with IV administration. They are related to hypocalcemia induced by the therapy 

- To the fetus 
	- Increased [[Heart]] rate 
	- Increased [[Blood]] sugar

### Contraindications
[[magnesium]] and [[Calcium channel blockers]] are contraindicated in clients with known hypersensitivity to these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], in clients with [[Heart]] block or myocardial damage, and when the woman is within 2 hr of delivery. [[terbutaline]] should not be used in women with [[Heart]] disease, hyperthyroid, or poorly controlled diabetes. [[magnesium]] is classified as a [[Preg Cat A]] drug, [[Calcium channel blockers]] are [[Preg Cat C]], and [[indomethacin]] is a [[Preg Cat B]] drug. Although these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are given for PTL, they still should be given cautiously during pregnancy.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
