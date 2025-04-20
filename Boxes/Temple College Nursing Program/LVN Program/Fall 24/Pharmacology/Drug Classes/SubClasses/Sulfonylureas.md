---
DrugClass: "[[Antidiabetic Drugs]]"
BrandName: 
DrugClassContra: "[[Antidiabetic Drugs#Contraindications]]"
DrugClassAdverse: "[[Antidiabetic Drugs#Side/Adverse Effects]]"
SubClass: "[[Sulfonylureas]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
See `= this.DrugClassAdverse`

Adverse reactions associated with sulfonylureas include hypoglycemia, anorexia, nausea, vomiting, epigastric discomfort, weight gain, heartburn, and various vague neurologic symptoms, such as weakness and numbness of the extremities. Manipulating the dosing of these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] can often reduce the unpleasant reactions.

### Contraindications
See `= this.DrugClassContra`

The first-generation sulfonylureas ([[chlorpropamide]], [[tolazamide]], and [[tolbutamide]]) are contraindicated in clients with coronary artery disease or [[Liver]] or renal dysfunction. Other sulfonylureas are used cautiously in clients with impaired [[Liver]] function because [[Liver]] dysfunction can prolong the drug’s effect. In addition, sulfonylureas are used cautiously in clients with renal impairment and severe cardiovascular disease. There is a risk for cross-sensitivity with sulfonylureas and sulfonamides (sulfa anti-infectives). 

Sulfonylureas may have an increased hypoglycemic effect when administered with [[Anticoagulants]], clofibrate, fluconazole, [[Histamine H2 antagonists]], [[methyldopa]], [[Monoamine]] oxidase inhibitors, nonsteroidal anti-inflammatory [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], [[Salicylates]], sulfonamides, and [[Tricyclic Antidepressants]]. The hypoglycemic effect of sulfonylureas may be decreased when the agents are administered with beta blockers, [[Calcium channel blockers]], [[cholestyramine]], [[Corticosteroids]], [[Estrogens]], [[Hydantoins]], [[isoniazid]], oral contraceptives, phenothiazines, [[rifampin]], thiazide [[Diuretics]], and thyroid agents.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
