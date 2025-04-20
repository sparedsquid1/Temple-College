---
DrugClass: "[[Lower Respiratory System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Adrenergic Bronchodilators]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
**[[CNS]] Reactions** 
- Restlessness, irritability, headache 
- Nervousness, tremors 

**Cardiac and [[Respiratory]] System Reactions** 
- Tachycardia 
- Palpitations 
- Electrocardiographic changes 
- Increased respirations 

**Other Reactions** 
- Nausea, vomiting, [[Fever]] 
- Hyperglycemia, flushing, alopecia

### Contraindications
The xanthine derivatives are contraindicated in those with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], peptic ulcers, seizure disorders (unless well controlled with appropriate anticonvulsant medication), and serious uncontrolled arrhythmias.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```



