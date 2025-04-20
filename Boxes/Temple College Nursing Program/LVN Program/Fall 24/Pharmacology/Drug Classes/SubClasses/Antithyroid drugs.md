---
DrugClass: "[[Thyroid and Antithyroid Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drug Classes/SubClasses/Antithyroid drugs]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Generalized System Reactions
- Hay [[Fever]], sore throat, skin rash, [[Fever]], headache 
- Nausea, vomiting, paresthesias 

Severe System Reactions 
- Agranulocytosis (decrease in the number of white [[Blood]] cells) 
- Exfoliative dermatitis, [[granulocytopenia]], [[hypoprothrombinemia]] 
- Drug-induced [[hepatitis]], acute pancreatitis

### Contraindications
The antithyroid [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with hypersensitivity to the drug or any constituent of the drug. Mothers taking [[methimazole]] or [[propylthiouracil (PTU)]] should not breastfeed their children. Radioactive iodine ([[Preg Cat X]]) is contraindicated during pregnancy and lactation. 

[[methimazole]] and [[propylthiouracil (PTU)]] are used with extreme caution during pregnancy ([[Preg Cat D]]) because they can cause hypothyroidism in the fetus. However, if an antithyroid drug is necessary during pregnancy, [[propylthiouracil (PTU)]] is the preferred drug because it does not cross the [[placenta]]. The potential for bleeding increases when these products are taken with oral [[Anticoagulants]].

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
