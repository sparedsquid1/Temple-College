---
DrugClass: "[[Immunostimulants and Immunomodulators]]"
BrandName: 
DrugClassContra: "[[Interferons#Contraindications]]"
DrugClassAdverse: "[[Interferons#Adverse Reactions]]"
SubClass: "[[Interferons]]"
SecondaryDrugClass: "[[Cancer vaccines]]"
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Because the interferons activate the immune response, a cluster of symptoms similar to fighting influenza occur. These are referred to as “flu-like symptoms” because they mimic the bodily response to fight the flu. Flu-like symptoms generally include: 
- Chills 
- Cough 
- [[Fever]] 
- Headache 
- Malaise (generalized discomfort) 

 These adverse reactions are typically treated with [[acetaminophen]] and antihistamines. 
 
 PRACTICE CONSIDERATIONS Patti et al. (2020) found that drug administration during evening hours reduced flu-like symptoms compared with those clients who injected themselves in the morning. 
 
 Other symptoms may include nausea, muscle aches, fatigue, sore throat, reduced appetite, or diarrhea. Skin rashes, injection pain and inflammation, edema in the extremities, and antibody development can occur. 
 
 Given parenterally, injection sites are rotated to reduce site reactions. Switching to a drug with less frequent dosing (three times/week to weekly drug) may help reduce injection site irritation and increase client compliance with the dosing schedule

### Contraindications
 Interferons are contraindicated in clients with known hypersensitivity to the drug or any component of the drug. Neuropsychiatric symptoms including [[Depression]], confusion, and manic behavior have been noted in clients both with and without a psychiatric history. Asymptomatic elevation in [[Liver]] enzyme levels has occurred; therefore, clients should be cautioned regarding [[Alcohol]] intake while using the drug. Caution is used when administering to clients with cardiac or [[Liver]] disease, a history of seizure disorder, and thyroid problems. A reduction in WBC count makes clients susceptible to infection. 

Immunomodulators are not started during pregnancy, unless the woman is at high risk of MS activity. When on interferons, they are stopped when pregnancy is confirmed. Interferon has been found in breast milk (Hale, 2012).

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
