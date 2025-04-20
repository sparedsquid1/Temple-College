---
DrugClass: "[[Menopause and Andropause Drugs]]"
BrandName: 
DrugClassContra: "[[Selective Estrogen Receptor Modulators#Contraindications]]"
DrugClassAdverse: "[[Selective Estrogen Receptor Modulators#Adverse Reactions]]"
SubClass: "[[Selective Estrogen Receptor Modulators]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Common adverse reactions include hot flashes and vaginal discharge. Some women experience muscle spasms and excessive sweating. A greater risk of developing endometrial cancer may occur when using [[estrogen]]-based [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] together with a SERM.

### Contraindications
[[ospemifene]] should not be used by women diagnosed with breast cancer or hepatic disease. It also should not be used with [[Estrogens]], [[estrogen]] antagonists, fluconazole, or [[rifampin]]. [[raloxifene]] decreases the effectiveness of both [[warfarin]] and [[cholestyramine]]. Women taking [[raloxifene]] and having a procedure where prolonged bed rest is anticipated should discontinue the drug 72 hours prior to that procedure. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are not to be used by pregnant women.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
