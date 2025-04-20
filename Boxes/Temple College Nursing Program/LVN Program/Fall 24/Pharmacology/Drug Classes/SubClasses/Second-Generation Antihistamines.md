---
DrugClass: "[[Upper Respiratory System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[First-Generation Antihistamines]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
**[[CNS]] Reactions** 
- Drowsiness or sedation 
- Disturbed coordination

**[[Respiratory]] System Reactions** 
*Anticholinergic actions of antihistamines affect the [[Respiratory]] system and include the following:* 
- Dryness of the [[Mouth]], nose, and throat 
- Thickening of bronchial secretions 

Second-generation preparations (e.g., [[loratadine]]) cause less drowsiness and fewer anticholinergic effects than some of the other antihistamines. Although these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are sometimes used to treat allergies, a drug allergy can occur with the use of an [[Antihistamine]]. Symptoms that may indicate an allergy to these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] include skin rash or [[urticaria]].
### Contraindications
Although antihistamines are classified as pregnancy categories B ([[chlorpheniramine]], [[cetirizine]], dexchlorpheniramine, [[clemastine]], [[diphenhydramine]], and [[loratadine]]) and C ([[brompheniramine]], [[desloratadine]], [[fexofenadine]], [[hydroxyzine]], and [[promethazine]]), they are contraindicated during pregnancy and lactation. 

First-generation [[Antihistamine]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and in newborns, premature infants, and nursing mothers. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are also contraindicated in individuals taking [[Monoamine]] oxidase inhibitor ([[MAOI]]) antidepressants or who have one of the following conditions: angle-closure glaucoma, peptic ulcer, symptomatic prostatic hypertrophy, and bladder neck obstruction. 

Second-generation antihistamines are contraindicated in clients with known hypersensitivity. [[cetirizine]] is contraindicated in clients who are sensitive to [[hydroxyzine]].

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
