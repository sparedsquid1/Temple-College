---
DrugClass: "[[Antidiabetic Drugs]]"
BrandName: 
DrugClassContra: "[[Antidiabetic Drugs#Contraindications]]"
DrugClassAdverse: "[[Antidiabetic Drugs#Side/Adverse Effects]]"
SubClass: "[[Glucagon-Like Peptide-1 Agonists]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
aliases:
  - GLP-1s
---
### Adverse Reactions 
See `= this.DrugClassAdverse`

Adverse reactions are typically GI in [[nature]]: diarrhea, nausea and vomiting, and heartburn. Clients taking [[exenatide]] or [[liraglutide]] may experience headaches, and [[acute lymphoblastic leukemia]] clients should monitor injection sites for local irritation.

### Contraindications
See `= this.DrugClassContra`

The GLP-1s are contraindicated in clients with a personal or family history of thyroid (medullary) or other endocrine cancers. This drug should not be used to treat type 1 diabetes or DKA. GLP-1s should not be used with the dipeptidyl peptidase-4 (DPP-4) inhibitors because of the increased additive glycemic effect when combined. Observe client carefully for signs or symptoms of acute pancreatitis or declining kidney function. The [[Blood]] glucose can fall lower when taken with the following [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]: [[Androgens]], insulins, and pegvisomant (a somatostatin hormone). Clients may experience elevated [[Blood]] glucose when GLP-1 is taken with [[Corticosteroids]], danazol, luteinizing [[Hormones]], or thiazide [[Diuretics]]. Bleeding is prolonged if taken with vitamin K, and these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] will reduce the effectiveness of oral contraceptives. [[albiglutide]] should be stopped at least 1 month prior to attempting pregnancy ([[Preg Cat C]]); those taking [[exenatide]] are encouraged to sign up for monitoring programs. Effect on the infant through lactation is not known at this time.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
