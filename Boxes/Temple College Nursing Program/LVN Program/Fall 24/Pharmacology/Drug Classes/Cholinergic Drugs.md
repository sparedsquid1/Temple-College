---
DrugClass: "[[Cholinergic Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 25](kindle://book?action=open&asin=B09FRF11YJ&location=13417)"
Course: Pharmacology
Chapter: "25"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.file.name`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in those with a hypersensitivity to the anticholinergic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], glaucoma (angle-closure glaucoma), pyloric or duodenal obstruction, peptic ulcers, prostatic hypertrophy, achalasia (failure of the muscles of the lower esophagus to relax, causing difficulty swallowing), [[myasthenia gravis]], and megacolon. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used with caution in clients with tachycardia, cardiac arrhythmias, hypertension, or hypotension; those with a tendency toward urinary retention; those with decreased [[Liver]] or kidney function; and those with obstructive disease of the [[Urinary system]] or GI tract. The cholinergic blocking [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are given with caution to the older adult.


### Side/Adverse Effects 
General adverse reactions include the following: 
- Nausea, diarrhea, abdominal cramping 
- Salivation 
- Flushing of the skin 
- Cardiac arrhythmias and muscle weakness

### Subclasses
#### Direct-Acting Cholinergics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and SubClass = [[Direct-Acting Cholinergics]]
sort file.name asc
```

#### Indirect-Acting (Anticholinesterase) Muscle Stimulants
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and SubClass = [[Indirect-Acting (Anticholinesterase) Muscle Stimulants]]
sort file.name asc
```
