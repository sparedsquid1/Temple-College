---
DrugClass: "[[Central Nervous System Stimulants]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 17](kindle://book?action=open&asin=B09FRF11YJ&location=9427)"
Course: Pharmacology
Chapter: "17"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
The [[CNS]] stimulants are contraindicated in clients with known hypersensitivity or convulsive disorders and in those with ventilation disorders (e.g., chronic obstructive pulmonary disease [COPD]). Do not administer [[CNS]] stimulants to clients with cardiac problems, severe hypertension, or hyperthyroidism. [[CNS]] stimulants are not recommended as treatment for [[Depression]]. Amphetamines and anorexiants should not be taken concurrently or within 14 days of antidepressant medications. In addition, amphetamines are contraindicated in clients with glaucoma. Most anorexiants are classified as [[Preg Cat X]] and should not be used during pregnancy. [[acute lymphoblastic leukemia]] of the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] used to treat narcolepsy cause hormonal changes in women and possibly congenital defects, therefore they should not be used during pregnancy.

### Side/Adverse Effects 
**Neuromuscular System Reactions** 
- Excessive [[CNS]] stimulation, headache, dizziness 
- Apprehension, disorientation, hyperactivity 

**Other Reactions** 
- Nausea, vomiting, cough, dyspnea 
- Urinary retention, tachycardia, palpitations 

### SubClasses
#### Amphetamines
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Amphetamines"
sort file.name asc
```

#### Analeptics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Analeptics"
sort file.name asc
```

#### Anorexiants
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Anorexiants"
sort file.name asc
```

#### Miscellaneous Drugs 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Miscellaneous Drugs"
sort file.name asc
```
