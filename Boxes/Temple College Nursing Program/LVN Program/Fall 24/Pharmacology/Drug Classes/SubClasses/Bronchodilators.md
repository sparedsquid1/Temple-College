---
DrugClass: "[[Lower Respiratory System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Bronchodilators]]"
SecondaryDrugClass: 
SecondarySubClass: "[[Xanthine Derivative Bronchodilators\r\r]]"
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
[[Adrenergic Bronchodilators#Adverse Reactions]]
[[Xanthine Derivative Bronchodilators#Adverse Reactions]]

### Contraindications
[[Adrenergic Bronchodilators#Contraindications]]
[[Xanthine Derivative Bronchodilators#Contraindications]]

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class", ThirdDrugClass as "3rd Drug Class", ThirdSubClass as "3rd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass or ThirdSubClass = this.SubClass
sort file.name asc
```



