---
DrugClass: 
BrandName: Folvite
DrugClassContra: "[[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drug Classes/SubClasses/Folic acid#Contraindications]]"
DrugClassAdverse: "[[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drug Classes/SubClasses/Folic acid#Adverse Reactions]]"
SubClass: "[[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drug Classes/SubClasses/Folic acid]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
SubCat: Adjuvant Agents
tags:
  - Drug
---
### Adverse Reactions 
 Few adverse reactions are associated with the administration of folic acid. Rarely, parenteral administration may result in allergic hypersensitivity. 
 
### Contraindications
Contraindications and Precautions Folic acid and [[leucovorin]] are contraindicated for treating pernicious anemia or for other anemias in which vitamin [[B12]] is deficient. Folic acid is a [[Preg Cat A]] drug and is generally considered safe for use during pregnancy. Pregnant women are more likely to experience folate deficiency because folic acid requirements increase during pregnancy. Pregnant women with a folate deficiency are at increased risk for complications of pregnancy and fetal abnormalities. The recommended dietary allowance (RDA) of folate during pregnancy is 0.4 mg/day and during lactation, 0.26–0.28 mg/day. Although the potential for fetal harm appears remote, the drug should be used cautiously and only within the RDA guidelines.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
