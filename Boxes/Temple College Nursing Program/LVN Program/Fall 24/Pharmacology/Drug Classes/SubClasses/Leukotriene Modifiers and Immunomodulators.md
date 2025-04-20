---
DrugClass: "[[Lower Respiratory System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Inhaled Corticosteroids]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
- [[CNS]] reaction includes headache. 
- Generalized body system reactions include flu-like symptoms. 
- Immunomodulators may cause anaphylactic reactions. 
- Emergency equipment should be available when administering this medication.

### Contraindications
These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with known hypersensitivity, bronchospasm in acute asthma attacks, or [[Liver]] disease ([[zileuton]]). They should be used cautiously in pregnancy and not at [[acute lymphoblastic leukemia]] during lactation ([[zafirlukast]], [[montelukast]], and [[omalizumab]] are [[Preg Cat B]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and [[zileuton]] is a [[Preg Cat C]] drug).

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
