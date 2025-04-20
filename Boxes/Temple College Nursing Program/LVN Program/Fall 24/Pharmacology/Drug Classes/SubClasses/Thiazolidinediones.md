---
DrugClass: "[[Antidiabetic Drugs]]"
BrandName: 
DrugClassContra: "[[Antidiabetic Drugs#Contraindications]]"
DrugClassAdverse: "[[Antidiabetic Drugs#Side/Adverse Effects]]"
SubClass: "[[Thiazolidinediones]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
aliases:
  - TZDs
---
### Adverse Reactions 
See `= this.DrugClassAdverse`

Adverse reactions associated with the administration of TZDs include upper [[Respiratory]] infections, sinusitis, headache, [[Pharyngitis]], [[myalgia]], diarrhea, and back pain. Weight gain and hypoglycemia are more evident when used in combination therapy.

### Contraindications
See `= this.DrugClassContra`

TZDs are contraindicated for clients with symptomatic [[Heart]] failure. TZDs are not used to treat type 1 diabetes. [[rosiglitazone]] specifically should not be used in combined therapy with [[Insulin products]]. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously in clients with edema, cardiovascular disease, and [[Liver]] or kidney disease. Monitor both sexes for bone fractures, especially of upper limbs after the first year of therapy. TZDs are [[Preg Cat C]]. Premenopausal women, who do not ovulate, may begin to ovulate again and effective barrier birth control is recommended because TZD can decrease the effectiveness of oral contraceptives.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
