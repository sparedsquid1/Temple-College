---
DrugClass: "[[Adrenergic Blocking]]"
BrandName: 
DrugClassContra: "[[Beta (β)-adrenergic blocking#Contraindications]]"
DrugClassAdverse: "[[Beta (β)-adrenergic blocking#Adverse Reactions]]"
SubClass: "[[Alpha-beta-adrenergic blocking]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 8](kindle://book?action=open&asin=B09FRF11YJ&location=4155)"
Chapter: "8"
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Most adverse effects of alpha/ beta-[[Adrenergic]] blocking [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are mild and do not require discontinuation of therapy. General body system adverse reactions include fatigue, dizziness, hypotension, drowsiness, insomnia, weakness, diarrhea, dyspnea, chest pain, bradycardia, and skin rash.

### Contraindications
Alpha/ beta-[[Adrenergic]] blockers are contraindicated in clients with hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], bronchial asthma, decompensated HF, and severe bradycardia. The [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously in clients with drug-controlled HF, chronic bronchitis, or impaired hepatic or cardiac function; in those with diabetes; and during pregnancy ([[Preg Cat C]]) and lactation.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
