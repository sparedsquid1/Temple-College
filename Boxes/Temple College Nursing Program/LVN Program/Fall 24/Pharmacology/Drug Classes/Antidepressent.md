---
DrugClass: "[[Antipsychotics]]"
Chapter: "22"
tags:
  - Drug
KindleLinkChap: "[Chapter 22](kindle://book?action=open&asin=B09FRF11YJ&location=11697)"
Course: Pharmacology
---

### Contraindications
[[Antipsychotics]] are contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], in comatose clients, in those who are severely depressed, and in those who have bone marrow [[Depression]], [[Blood dyscrasias]], Parkinson disease (specifically, [[haloperidol]]), [[Liver]] impairment, coronary artery disease, or severe hypotension or hypertension. Because of a specific enzyme reaction, grapefruit or its juice should not be taken if the client is on the drug [[quetiapine]] or [[pimozide]]. Antipsychotic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are classified as [[Preg Cat C]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] (except for [[clozapine]], which is [[Preg Cat B]]). Safe use of these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] during pregnancy and lactation has not been clearly established. [[Antipsychotics]] should be used only when clearly needed and when the potential benefit outweighs any potential harm to the fetus.

Antipsychotic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously in clients with [[Respiratory]] disorders, glaucoma, prostatic hypertrophy, epilepsy, decreased renal function, and peptic ulcer disease.

### Interactionsde/Adverse Effects
- Sedation, headache, hypotension 
- Dry [[Mouth]], nasal congestion 
- [[urticaria]], [[photophobia]] (intolerance to light), [[photosensitivity]] (abnormal sensitivity when exposed to light). 
- [[photosensitivity]] can result in severe sunburn when clients taking antipsychotic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are exposed to the sun or ultraviolet light, such as that used in a tanning bed.
- [[EPS]]
- [[Tardive Dyskinesia]]

### Interactions

### Subclasses
#### 1st GEN
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Class", SecondarySubClass as "Secondary Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass and DrugClass = [[Antipsychotics]] and SubClass = [[1st Gen]] or SecondaryDrugClass =[[1st Gen]]
sort file.name asc
```

#### 2nd GEN
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Class", SecondarySubClass as "Secondary Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and SubClass = [[2nd Gen]]
or SecondarySubClass = [[2nd Gen]] 
sort file.name asc
```


