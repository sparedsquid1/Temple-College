---
DrugClass: "[[Diuretics]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 32](kindle://book?action=open&asin=B09FRF11YJ&location=17407)"
Course: Pharmacology
Chapter: "32"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
Diuretics are contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], electrolyte imbalances, severe kidney or [[Liver]] dysfunction, and anuria (cessation of urine production). [[mannitol]] (an osmotic diuretic) is contraindicated in clients with active intracranial bleeding (except during craniotomy). The [[Potassium-sparing diuretics]] are contraindicated in clients with hyperkalemia and are not recommended for pediatric clients.

### Side/Adverse Effects 
Adverse reactions associated with any category of diuretics involve various body systems. 

**Neuromuscular System Reactions** 
- Dizziness, lightheadedness, headache 
- Weakness, fatigue 

**[[Cardiovascular system]] Reactions** 
- Orthostatic hypotension 
- Electrolyte imbalances, [[Glycosuria]] 

**Gastrointestinal System Reactions** 
- Anorexia 
- Nausea, vomiting 

**Other System Reactions** 
Dermatologic reactions include rash and [[photosensitivity]]. Extremity paresthesias (numbness or tingling) or flaccid muscles may indicate hypokalemia (low [[Blood]] potassium levels). Hyperkalemia (an increase in potassium level in the [[Blood]]), a serious event, may occur with the administration of [[Potassium-sparing diuretics]]. Hyperkalemia is most likely to occur in clients with an inadequate fluid intake and urine output, those with diabetes or renal disease, older adults, and those who are severely ill. 

In male clients taking [[spironolactone]], gynecomastia (breast enlargement) may occur. This reaction appears to be related to both dosage and the duration of therapy. The gynecomastia is usually reversible when therapy is discontinued, but in rare instances, some breast enlargement may

### Subclasses

#### Loop diuretics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Loop diuretics]]
sort file.name asc
```

#### Potassium-sparing diuretics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Potassium-sparing diuretics]]
```

#### Thiazides and related diuretics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Thiazides and related diuretics]]
```

#### Carbonic anhydrase inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Carbonic anhydrase inhibitors]] or SecondarySubClass = [[Carbonic anhydrase inhibitors]]
```

#### Osmotic diuretics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Osmotic diuretics]]
sort file.name asc
```
