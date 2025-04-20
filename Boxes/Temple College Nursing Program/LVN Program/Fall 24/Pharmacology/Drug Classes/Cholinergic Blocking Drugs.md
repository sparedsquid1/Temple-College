---
DrugClass: "[[Cholinergic Blocking Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 26](kindle://book?action=open&asin=B09FRF11YJ&location=13703)"
Course: Pharmacology
Chapter: "26"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.file.name`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
Cholinergic blocking [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] or glaucoma. Other clients for whom cholinergic blocking [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated are those with [[myasthenia gravis]], tachyarrhythmia, myocardial infarction, and [[Heart]] failure (unless bradycardia is present).

### Side/Adverse Effects 
Gastrointestinal System Reactions 
- Dry [[Mouth]], nausea, vomiting 
- Difficulty in swallowing, heartburn 
- Constipation 

[[CNS]] Reactions 
- Headache, flushing, nervousness 
- Drowsiness, weakness, insomnia 
- Nasal congestion, [[Fever]] 

Visual Reactions 
- Blurred [[Vision]] 
- Mydriasis (dilation of the pupil) 
- [[photophobia]]
- Cycloplegia (paralysis of [[accommodation]] or inability to focus the eye) 
- Increased ocular tension 

Genitourinary System Reactions 
- Urinary hesitancy and retention 
- Dysuria 

[[Cardiovascular system]] Reactions
- Palpitations
- Bradycardia (after low doses of [[atropine]])
- Tachycardia (after higher doses of [[atropine]]) 

Other Reactions 
- [[Urticaria]] 
- Decreased sweat production 
- Anaphylactic shock 
- Rash

### Subclasses

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and SubClass = null
sort file.name asc
```

#### Cholinergic Blocking Urinary Antispasmodics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and SubClass = [[Cholinergic Blocking Urinary Antispasmodics]]
sort file.name asc
```

#### Cholinergic Blocking Drugs for Parkinson Disease
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and SubClass = [[Cholinergic Blocking Drugs for Parkinson Disease]]
sort file.name asc
```

#### Cholinergic Blocking Drugs for Nonacute Respiratory Symptom Relief
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass and subclass = [[Cholinergic Blocking Drugs for Nonacute Respiratory Symptom Relief]]
sort file.name asc
```
