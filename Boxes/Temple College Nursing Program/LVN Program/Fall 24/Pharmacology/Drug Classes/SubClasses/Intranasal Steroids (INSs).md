---
DrugClass: "[[Upper Respiratory System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Intranasal Steroids (INSs)]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Adverse reactions are typically mild and include an unpleasant smell or taste. Drying of the nasal passages resulting in irritation and nose bleeds ([[Epistaxis]])— especially when the weather is dry— may occur. Discontinuation of INS [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] is recommended when [[Epistaxis]] persists. Fungal infections (Candida albicans) of the nares are a rare reaction.

### Contraindications
Those hypersensitive to steroids should not take INSs. INSs are [[Preg Cat C]] and should be used only when the benefit outweighs the risk to the fetus. INSs are used cautiously in clients taking systemic steroids. In study subjects, the [[Blood]] level of [[budesonide]] was found to be twice that of an adult when also using systemically. This was thought to be attributed to weight differences. Some studies suggest there may be a slowing in growth rate of children using these products for extended periods (Lee et al., 2014).

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
