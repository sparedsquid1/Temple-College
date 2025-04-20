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
**[[Cardiovascular system]] Reactions **
- Tachycardia, palpitations, or cardiac arrhythmias 
- Hypertension 

**Other Reactions** 
- Nervousness, [[anxiety]] 
- Insomnia 

When these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are taken by inhalation, excessive use (e.g., more than the recommended dose times) may result in paradoxical bronchospasm.

### Contraindications
The [[Adrenergic]] [[Bronchodilators]] are contraindicated in clients with known hypersensitivity to the drug, cardiac arrhythmias associated with tachycardia, organic brain damage, cerebral arteriosclerosis, and narrow-angle glaucoma. [[salmeterol]] is contraindicated during acute bronchospasm.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```



