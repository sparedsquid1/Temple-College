---
DrugClass: "[[Adrenergic Blocking]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Beta (β)-adrenergic blocking]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 8](kindle://book?action=open&asin=B09FRF11YJ&location=4155)"
Chapter: "8"
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
- Generalized reactions that affect the body include orthostatic hypotension, bradycardia, dizziness, vertigo, and headache.
- Gastrointestinal (GI) reactions include hyperglycemia, nausea, vomiting, and diarrhea. 
- Bronchospasm (especially in those with a history of asthma). 

Many of these reactions are mild and may disappear with therapy. More serious adverse reactions include symptoms associated with [[Heart]] failure (i.e., dyspnea, weight gain, peripheral edema).

### Contraindications
These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with an allergy to beta blockers; in clients with sinus bradycardia, second- or third-degree [[Heart]] block; and in those with asthma, emphysema, and hypotension. When discontinuing the drug, beta blockers should always be tapered slowly, not abruptly stopped. The [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously in clients with diabetes, [[thyrotoxicosis]], or peptic ulcer.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
