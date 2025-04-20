---
DrugClass: "[[Menopause and Andropause Drugs]]"
BrandName: 
DrugClassContra: "[[Drugs to treat ED#Contraindications]]"
DrugClassAdverse: "[[Drugs to treat ED#Adverse Reactions]]"
SubClass: "[[Drugs to treat ED]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
The most common adverse reactions include headache, flushing, GI upset, nausea, and runny nose or congestion. [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] for ED should not be taken by men who use [[Nitrates]] (e.g., for anginal pain), because these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] affect smooth muscle. Clients with preexisting cardiac problems, especially those using [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] to lower [[Blood]] pressure, should discuss use with their primary health care provider before using the drug. Doses should be reduced in men with renal or hepatic impairment. Medical attention should be sought for erections sustained for more than 4 hours. Ocular problems may occur when using these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]; again, the primary health care provider should be consulted before use.

### Contraindications

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
