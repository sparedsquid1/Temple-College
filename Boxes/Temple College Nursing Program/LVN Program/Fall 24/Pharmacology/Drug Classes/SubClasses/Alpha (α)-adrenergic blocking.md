---
DrugClass: "[[Adrenergic Blocking]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Alpha (α)-adrenergic blocking]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 24](kindle://book?action=open&asin=B09FRF11YJ&location=12809)"
Chapter: "24"
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Administration of an alpha-[[Adrenergic]] blocking drug may result in weakness, orthostatic hypotension, cardiac arrhythmias, hypotension, and tachycardia. See the Summary Drug Table: [[Adrenergic]] Blocking [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] for more information.

### Contraindications
Alpha-[[Adrenergic]] blocking [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients who are hypersensitive to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and in clients with coronary artery disease. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously during pregnancy ([[Preg Cat C]]) and lactation, after a recent myocardial infarction (MI), and in clients with renal failure or Raynaud disease. When [[phentolamine]] (Regitine) is administered with [[Epinephrine]] (a sympathomimetic), there is decreased vasoconstrictor and hypertensive action.


### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
