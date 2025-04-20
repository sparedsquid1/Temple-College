---
DrugClass: "[[Immune Blockers]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Immunosuppressants]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
 Because these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] interfere with the immune system, common adverse reactions include headache, chills, and [[Fever]]. Clients taking biologics may also feel nauseated or experience GI distress. Other adverse reactions experienced are itching, dizziness, and myalgias. Calcineurin inhibitors may cause gum hyperplasia, hair growth, or tremors. 
 
### Contraindications
Contraindications, Precautions, and Interactions Vaccination with live virus (such as the chickenpox or measles, mumps, and rubella [MMR] [[Vaccines]]) should not be given if the client is on an immunosuppressant agent. Because these agents decrease [[Immunity]], there is an increased risk of infection. Therefore, clients should be routinely monitored for [[neutropenia]] and [[infectious diseases]]. Clients with HIV+ should not take alefacept (used for plaque psoriasis). 

Calcineurin inhibitors are nephrotoxic in high doses and the [[BUN]] should be monitored frequently. Cardiac arrhythmias are more likely to occur if taking calcineurin inhibitors with antiarrhythmic medications. Severe reduction in red cells, white cells, and platelets is seen when those taking IMDH inhibitors are also taking angiotensin-converting enzyme inhibitor (ACEI) for hypertension. Many of the immunosuppressant agents interact with grapefruit juice and other citrus; consult a clinical nutritionist for client instruction on dietary restrictions.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
