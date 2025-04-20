---
DrugClass: "[[Antidiabetic Drugs]]"
BrandName: 
DrugClassContra: "[[Antidiabetic Drugs#Contraindications]]"
DrugClassAdverse: "[[Antidiabetic Drugs#Side/Adverse Effects]]"
SubClass: "[[Meglitinides]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
See `= this.DrugClassAdverse`

Adverse reactions associated with the administration of the meglitinides include upper [[Respiratory]] tract infection, headache, [[rhinitis]], bronchitis, headache, back pain, and hypoglycemia.

### Contraindications
See `= this.DrugClassContra`

[[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] reducing the hypoglycemic effect of meglitinides include [[Corticosteroids]], [[carbamazepine]], and [[rifampin]]. Debilitated, malnourished, or older clients are typically more susceptible to the hypoglycemic effects when taking these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. Considered [[Preg Cat C]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], they have not been studied sufficiently to render safe to take while pregnant or when lactating.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
