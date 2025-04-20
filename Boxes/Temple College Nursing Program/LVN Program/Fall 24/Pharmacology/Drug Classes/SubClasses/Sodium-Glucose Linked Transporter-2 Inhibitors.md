---
DrugClass: "[[Antidiabetic Drugs]]"
BrandName: 
DrugClassContra: "[[Antidiabetic Drugs#Contraindications]]"
DrugClassAdverse: "[[Antidiabetic Drugs#Side/Adverse Effects]]"
SubClass: "[[Sodium-Glucose Linked Transporter-2 Inhibitors]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
See `= this.DrugClassAdverse`

Yeast infections of the genital area can occur due to excretion of glucose in the urine. A rare, yet serious bacterial infection (necrotizing fasciitis) may result. Clients taking these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] may experience hypotension and hyperkalemia.


### Contraindications
See `= this.DrugClassContra`

Clients with end-stage kidney disease or those on dialysis should not take these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. [[canagliflozin]] and [[dapagliflozin]] increase diuresis, and dehydration may result. Hyperkalemia is more likely to happen if the client is taking ACE inhibitors, angiotensin II receptor blockers (both hypertension [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]), or [[Potassium-sparing diuretics]]. SGLT-2 inhibitors should be stopped prior to attempting pregnancy ([[Preg Cat C]]). Effect on the infant through lactation is not known at this time.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
