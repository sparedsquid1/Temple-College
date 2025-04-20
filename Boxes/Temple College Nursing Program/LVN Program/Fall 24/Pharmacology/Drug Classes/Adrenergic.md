---
DrugClass: "[[Adrenergic]]"
SubClass: 
Chapter: "23"
KindleLinkChap: "[Chapter 23](kindle://book?action=open&asin=B09FRF11YJ&location=12272)"
KindleLink: 
tags:
  - Drug
BrandName: 
Course: Pharmacology
---

### Generic name
`= this.file.name`
### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`
	
### Dosage & Usage

### Contraindications
Adrenergic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with known hypersensitivity. [[isoproterenol]] is contraindicated in clients with tachyarrhythmias or [[Heart]] block caused by digitalis toxicity, ventricular arrhythmias, and angina pectoris. [[Dopamine]] is contraindicated in those with [[pheochromocytoma]] (adrenal gland tumor), unmanaged arrhythmias, and ventricular fibrillation. [[Epinephrine]] is contraindicated in clients with narrow-angle glaucoma and as a local anesthetic adjunct in fingers and toes. Norepinephrine is contraindicated in clients who are hypotensive from [[Blood]] volume deficits.


### Mechanisms of Action

### Side/Adverse Effects

### Interactions

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass and DrugClass = [[Adrenergic]]
sort file.name asc
```

