---
DrugClass: "[[Antidiabetic Drugs]]"
BrandName: 
DrugClassContra: "[[Antidiabetic Drugs#Contraindications]]"
DrugClassAdverse: "[[Antidiabetic Drugs#Side/Adverse Effects]]"
SubClass: "[[Biguanides]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
See `= this.DrugClassAdverse`

Alone, [[metformin]] rarely causes hypoglycemia. However, clients receiving this drug in combination with insulin or other hypoglycemics (see other agents listed below) are at greater risk for hypoglycemia. A reduction or titration in the dosage of one of the antidiabetic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] may be required to prevent episodes of hypoglycemia when combination therapy is initiated. 

Nausea, vomiting, diarrhea, and increased flatulence are adverse reactions of [[metformin]]. It is taken with food to minimize adverse gastrointestinal (GI) effects.

### Contraindications
See `= this.DrugClassContra`

[[metformin]] should not be used if the client has poor kidney function (FDA, 2016). Risk for problems such as lactic acidosis is greater when the kidneys are impaired (stages 3– 5). There is a risk of acute kidney failure, which can lead to lactic acidosis, when contrast medium is used for radiologic studies. When contrast medium is used, [[metformin]] (or a product containing the drug) is stopped on the day of and 48 hr after the radiologic study. [[metformin]] may lead to vitamin [[B12]] malabsorption; clients should be monitored and supplements given as needed. The drug is also contraindicated in clients older than 80   years and during pregnancy ([[Preg Cat B]]) and lactation.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
