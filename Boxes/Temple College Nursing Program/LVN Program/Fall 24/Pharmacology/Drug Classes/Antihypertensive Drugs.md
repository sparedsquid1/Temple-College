---
DrugClass: "[[Antihypertensive Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 34](kindle://book?action=open&asin=B09FRF11YJ&location=18587)"
Course: Pharmacology
Chapter: "34"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
Antihypertensive [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with known hypersensitivity to the individual [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. 

The ACEIs and angiotensin II receptor blockers are contraindicated if the client has impaired renal function, salt or volume depletion, bilateral stenosis, or [[angioedema]]. They are also contraindicated during pregnancy ([[Preg Cat C]] during first [[trimester]] and [[Preg Cat D]] in the second and third trimesters) or during lactation. Use of the ACEIs and the angiotensin II receptor blockers during the second and third trimesters of pregnancy is contraindicated, because use may cause fetal and neonatal injury or death.

### Side/Adverse Effects 
When any antihypertensive drug is given, orthostatic (or postural) hypotension may result in some clients, especially early in therapy. Orthostatic hypotension occurs when the individual has a significant drop in [[Blood]] pressure (usually 10   mm Hg systolic or more) when assuming an upright position. The client can become dizzy and may fall, resulting in an injury. Butt et al. (2012) reported that the risk of hip fracture is increased by almost 50% for those older than 66 when they are started on antihypertensives. This is thought to be from fainting and falling related to orthostatic hypotension. 

**[[CNS]] Reactions** 
- Fatigue, [[Depression]], dizziness, headache, and syncope 

**[[Respiratory]] System Reactions** 
- Upper [[Respiratory]] infections (URIs) and cough 

**Gastrointestinal System Reactions** 
- Abdominal pain, nausea, diarrhea, constipation, gastric irritation, and anorexia 

**Other Reactions** 
- Rash, pruritus, dry [[Mouth]], tachycardia, hypotension, proteinuria, and [[neutropenia]] 

Additional adverse reactions that may occur when an antihypertensive drug is administered are listed in the Summary Drug Table: Antihypertensive [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. For the adverse reactions that may result when a diuretic is used as an antihypertensive drug, see the Summary Drug Table: [[Diuretics]] in Chapter 32.


### Subclasses
#### Beta (β)-adrenergic blocking
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Beta (β)-adrenergic blocking]] or SecondarySubClass = [[Beta (β)-adrenergic blocking]]
sort file.name asc
```

#### Antiadrenergic Drugs Centrally Acting
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Antiadrenergic Drugs Centrally Acting]] or SecondarySubClass = [[Antiadrenergic Drugs Centrally Acting]]
sort file.name asc
```

#### Antiadrenergic Drugs Peripherally Acting
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Antiadrenergic Drugs Peripherally Acting]] or SecondarySubClass = [[Antiadrenergic Drugs Peripherally Acting]]
sort file.name asc
```

#### Alpha-beta-adrenergic blocking
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Alpha-beta-adrenergic blocking]] or SecondarySubClass = [[Alpha-beta-adrenergic blocking]]
sort file.name asc
```

#### Calcium channel blockers
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Calcium channel blockers]] or SecondarySubClass = [[Calcium channel blockers]] or ThirdSubClass = [[Calcium channel blockers]]
sort file.name asc
```

#### Angiotensin-Converting Enzyme Inhibitors (ACE Inhibitors)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Angiotensin-Converting Enzyme Inhibitors (ACE Inhibitors)]] or SecondarySubClass = [[Angiotensin-Converting Enzyme Inhibitors (ACE Inhibitors)]]
sort file.name asc
```

#### Angiotensin II receptor antagonists
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Angiotensin II receptor antagonists]] or SecondarySubClass = [[Angiotensin II receptor antagonists]]
sort file.name asc
```

#### Direct Renin Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Direct Renin Inhibitors]] or SecondarySubClass = [[Direct Renin Inhibitors]]
sort file.name asc
```

#### Selective Aldosterone Receptor Antagonists
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Selective Aldosterone Receptor Antagonists]] or SecondarySubClass = [[Selective Aldosterone Receptor Antagonists]]
sort file.name asc
```

#### Vasodilators used in urgent hypertensive situations
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Vasodilators used in urgent hypertensive situations]] or SecondarySubClass = [[Vasodilators used in urgent hypertensive situations]]
sort file.name asc
```
