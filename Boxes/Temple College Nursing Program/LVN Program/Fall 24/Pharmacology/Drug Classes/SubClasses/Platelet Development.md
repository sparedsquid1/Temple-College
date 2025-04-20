---
DrugClass: 
BrandName: 
DrugClassContra: "[[Platelet Development#Contraindications]]"
DrugClassAdverse: "[[Platelet Development#Adverse Reactions]]"
SubClass: "[[Platelet Development]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
\General System Reactions 
- Headache 
- Fatigue 
- Muscle aches 
- [[Fever]] 
- Allergic reactions 

[[Cardiovascular system]] Reactions
- Peripheral edema 
- Palpitations 
- Atrial fibrillation 
- Emboli resulting in stroke and pulmonary edema 
- Capillary leak syndrome 

[[eltrombopag]] can be toxic to the [[Liver]]. [[Liver]] function studies are done before starting the drug and every 2 weeks while on drug therapy. See the Summary Drug Table: Immunostimulants and Immunomodulator [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] for more information on these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]].
### Contraindications
Thrombopoietin [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with known hypersensitivity to the drug or any component of the drug. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously in clients with renal failure and those with [[Liver]] failure. Clients should be monitored for cataract (eye) formation. It is a [[Preg Cat C]] drug, so women should use effective contraception and lactating clients should stop breastfeeding. 

Discontinuing either [[eltrombopag]] or [[romiplostim]] may result in platelet counts lower than the original diagnosed counts.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
