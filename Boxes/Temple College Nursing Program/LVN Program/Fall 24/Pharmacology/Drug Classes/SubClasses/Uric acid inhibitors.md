---
DrugClass: "[[Skeletal Muscle, Bone, and Joint Disorder Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Uric acid inhibitors]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
**Gastrointestinal System Reactions**
- Nausea, vomiting, diarrhea 
- Abdominal pain 
**Other Reactions**
- Headache 
- Urinary frequency 

One adverse reaction associated with [[allopurinol]] is skin rash, which in some cases has been followed by serious [[hypersensitivity reactions]], such as exfoliative dermatitis and [[Stevens–Johnson syndrome]].

### Contraindications
The [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] used for gout are contraindicated in clients with known hypersensitivity. [[colchicine]] is contraindicated in clients with serious GI, renal, hepatic, or cardiac disorders and those with [[Blood dyscrasias]]. [[probenecid]] is contraindicated in clients with [[Blood dyscrasias]] or uric acid kidney stones and in children younger than 2   years. If clients are taking azathioprine (Imuran), [[mercaptopurine (6-MP)]], or [[theophylline]] they should not be prescribed [[febuxostat]].

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
