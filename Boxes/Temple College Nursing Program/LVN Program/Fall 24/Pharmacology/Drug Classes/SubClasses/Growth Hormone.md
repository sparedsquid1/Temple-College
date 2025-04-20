---
DrugClass: "[[Pituitary and Adrenocortical Hormones]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Growth Hormone]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
[[somatropin]] causes few adverse reactions when administered as directed. Antibodies to [[somatropin]] may develop in a small number of clients, resulting in a failure to experience response to therapy, namely, failure of the drug to produce growth in the child. Some clients may experience hypothyroidism or insulin resistance. Swelling, joint pain, and muscle pain may also occur.

### Contraindications
[[somatropin]] is contraindicated in clients with known hypersensitivity to [[somatropin]] or sensitivity to benzyl [[Alcohol]] and in those with epiphyseal closure or underlying cranial lesions (e.g., pituitary tumor). The drug is used cautiously in clients with thyroid disease or diabetes and during pregnancy ([[Preg Cat C]]) and lactation. Excessive amounts of [[Glucocorticoids]] may decrease the response to [[somatropin]].

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
