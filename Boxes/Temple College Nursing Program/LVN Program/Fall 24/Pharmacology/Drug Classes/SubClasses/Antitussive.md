---
DrugClass: "[[Upper Respiratory System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Antitussive]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
When used as directed, nonprescription cough medicines produce few adverse reactions. However, those that are combined with an [[Antihistamine]] may cause: 
- Lightheadedness 
- Dizziness 
- Drowsiness or sedation

### Contraindications
Antitussives, expectorants, and mucolytics are contraindicated in clients with known hypersensitivity to these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. Opioid antitussives (those with [[codeine]]) are contraindicated in premature infants or during labor when delivery of a premature infant is anticipated. Mucolytics are not recommended for use by clients with asthma. The [[Expectorant]] potassium iodide is contraindicated during pregnancy ([[Preg Cat D]]).

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd SubClass", ThirdDrugClass as "3rd Drug Class", ThirdSubClass as "3rd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass or ThirdSubClass = this.SubClass
sort file.name asc
```
