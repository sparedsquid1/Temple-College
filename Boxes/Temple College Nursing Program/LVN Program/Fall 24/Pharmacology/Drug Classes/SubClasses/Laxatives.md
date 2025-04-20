---
DrugClass: "[[Lower Gastrointestinal System Drugs]]"
BrandName: 
DrugClassContra: "[[Laxatives#Contraindications]]"
DrugClassAdverse: "[[Laxatives#Adverse Reactions]]"
SubClass: "[[Laxatives]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Constipation may occur as an adverse drug reaction. When the client has constipation as an adverse reaction to another drug, the primary health care provider may prescribe a stool softener or another laxative to prevent constipation during the drug therapy. Box 39.2 lists some of the drug classifications known to cause constipation.
Laxatives may cause diarrhea and a loss of water and [[Boxes/Temple College Nursing Program/Pre & Co Reqs/Summer 23/Note holder/A & P II/Electrolytes|Electrolytes]], abdominal pain or discomfort, nausea, vomiting, perianal irritation, fainting, bloating, flatulence, cramps, and weakness. 
Prolonged use of a laxative can result in serious electrolyte imbalances, as well as the “laxative habit,” that is, dependence on a laxative to have a bowel movement. Some of these products contain tartrazine (a yellow food dye), which may cause allergic-type reactions (including bronchial asthma) in susceptible individuals. Obstruction of the esophagus, stomach, small intestine, and colon has occurred when bulk-forming laxatives are administered without adequate fluid intake or in clients with intestinal stenosis.

### Contraindications
Laxatives are contraindicated in clients with known hypersensitivity and those with persistent abdominal pain, nausea, vomiting of unknown cause, or signs of acute appendicitis, fecal impaction, intestinal obstruction, or acute [[hepatitis]]. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used only as directed because excessive or prolonged use may cause physical dependence on them for normal bowel movements. 
[[magnesium]] is used cautiously in clients with any degree of renal impairment. Laxatives are used cautiously in clients with rectal bleeding, in pregnant women, and during lactation. The following laxatives are [[Preg Cat C]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]: cascara sagrada, [[docusate]], [[glycerin]], phenolphthalein, [[magnesium]], and senna. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used during pregnancy only when the benefits clearly outweigh the risks to the fetus.

### Drugs with subclass `= this.file.name`
##### Bulk-Producing Laxatives
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Bulk-Producing Laxatives"
sort file.name asc
```

##### Emollients
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Emollients"
sort file.name asc
```

##### Stool Softeners Surfactants
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Stool Softeners/ Surfactants"
sort file.name asc
```

##### Hyperosmotic Agents
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Hyperosmotic Agents"
sort file.name asc
```

##### Irritant or Stimulant Laxatives
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Irritant or Stimulant Laxatives"
sort file.name asc
```

##### Saline Laxatives
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Saline Laxatives"
sort file.name asc
```

##### Bowel Evacuants
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Bowel Evacuants"
sort file.name asc
```
