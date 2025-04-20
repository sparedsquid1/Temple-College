---
DrugClass: "[[Antidiabetic Drugs]]"
BrandName: 
DrugClassContra: "[[Antidiabetic Drugs#Contraindications]]"
DrugClassAdverse: "[[Antidiabetic Drugs#Side/Adverse Effects]]"
SubClass: "[[Amylinomimetic]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
See `= this.DrugClassAdverse`

Adverse reactions of amylin include nausea, vomiting, decreased appetite, abdominal pain, headache, pain or irritation at injection site, and hypoglycemia.

### Contraindications
See `= this.DrugClassContra`

Do not use if problems with stomach emptying exist. This drug should not be used if client is taking a drug that slows GI motility, such as an alpha-glucosidase inhibitor. [[pramlintide]] injection will delay the onset of action if taken at the same time as an oral antidiabetic medication. Considered [[Preg Cat C]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], they have not been studied sufficiently to render safe to take while pregnant or when lactating.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
