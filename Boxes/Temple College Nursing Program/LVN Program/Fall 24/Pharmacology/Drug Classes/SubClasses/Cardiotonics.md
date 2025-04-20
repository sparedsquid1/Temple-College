---
DrugClass: "[[Cardiotonic and Antiarrhythmic Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Cardiotonics]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
**[[CNS]] Reactions** 
- Headache 
- Weakness, drowsiness 
- Visual disturbances (blurring or yellow halo— [[digoxin]]; increased brightness— [[ivabradine]]) 

**Cardiovascular and Gastrointestinal System Reactions** 
- Arrhythmias 
- Nausea and anorexia 

Because some clients are more sensitive to the side effects of [[digoxin]], dosage is calculated carefully and adjusted as the clinical condition indicates. There is a narrow margin of safety between the full therapeutic effects and the toxic effects of cardiotonic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. Even normal doses of a cardiotonic drug can cause toxic drug effects. Because substantial individual variations may occur, it is important to individualize the dosage. The term digitalis toxicity (or digitalis intoxication) is used to describe toxic drug effects that occur when [[digoxin]] is administered.

### Contraindications
The cardiotonics are contraindicated in the presence of digitalis toxicity and in clients with known hypersensitivity, ventricular failure, ventricular tachycardia, cardiac tamponade, restrictive cardiomyopathy, or AV block. 

The cardiotonics are given cautiously to clients with [[Electrolyte imbalance]] (especially hypokalemia, hypocalcemia, and hypomagnesemia), thyroid disorders, severe carditis, [[Heart]] block, myocardial infarction, severe pulmonary disease, acute glomerulonephritis, and impaired renal or hepatic function. 

[[digoxin]] is classified as a [[Preg Cat C]] drug and is used cautiously during pregnancy and lactation. Exposure to [[digoxin]] in a nursing infant is typically below an infant maintenance dose, yet caution should be exercised when [[digoxin]] is taken by a nursing woman. [[ivabradine]] should not be used by women who are pregnant or lactating. Effective birth control methods must be used, and this drug use should be discontinued before a woman attempts to conceive a child.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
