---
DrugClass: 
BrandName: 
DrugClassContra: "[[Red Blood Cell Development#Contraindications]]"
DrugClassAdverse: "[[Red Blood Cell Development#Adverse Reactions]]"
SubClass: "[[Red Blood Cell Development]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Epoetin alfa (an EPO), [[darbepoetin alfa]], and methoxy polyethylene are usually well tolerated when used to maintain a hemoglobin level no higher than 12 g/dL. The most common adverse reactions include: 
- Hypertension 
- Headache 
- Nausea, vomiting, diarrhea 
- Rashes 
- Fatigue 
- [[arthralgia]] and skin reaction at the injection site 

See the Summary Drug Table: Immunostimulants and Immunomodulator [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] for more information on these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]].

### Contraindications
Contraindications and Precautions Epoetin alfa is contraindicated in clients with uncontrolled hypertension, those needing an emergency transfusion, and those with a hypersensitivity to human albumin. [[darbepoetin alfa]] (Aranesp) is contraindicated in clients with uncontrolled hypertension or in those allergic to the drug. Polycythemia (an overload of RBCs in the circulation) can occur if the hemoglobin is not carefully monitored and the dosage is too high. This can result in increased mortality, serious cardio or thromboembolic events in any client, and possible tumor progression in cancer clients. 

Epoetin alfa and [[darbepoetin alfa]] are used with caution in clients with hypertension, [[Heart]] disease, congestive [[Heart]] failure, or a history of seizures. Both these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are [[Preg Cat C]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and are used cautiously during pregnancy and lactation.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
