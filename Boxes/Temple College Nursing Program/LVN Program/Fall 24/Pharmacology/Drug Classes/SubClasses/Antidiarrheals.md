---
DrugClass: "[[Lower Gastrointestinal System Drugs]]"
BrandName: 
DrugClassContra: "[[Antidiarrheals#Contraindications]]"
DrugClassAdverse: "[[Antidiarrheals#Adverse Reactions]]"
SubClass: "[[Antidiarrheals]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
**Gastrointestinal System Reactions** 
- Anorexia, nausea, vomiting, and constipation 
- Abdominal discomfort, pain, and distention 

**Other System Reactions** 
- Dizziness, drowsiness, and headache 
- Sedation and euphoria Rash

### Contraindications
These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients whose diarrhea is associated with organisms that can harm the intestinal [[Mucosa]] (Escherichia coli, Salmonella, and Shigella spp.). Clients with [[pseudomembranous colitis]], abdominal pain of unknown origin, and obstructive jaundice also should not take antidiarrheals. Antidiarrheal [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in children younger than 2   years.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
