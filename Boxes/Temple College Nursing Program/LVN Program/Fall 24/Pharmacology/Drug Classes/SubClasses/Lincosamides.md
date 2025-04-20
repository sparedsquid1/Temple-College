---
DrugClass: "[[Antibacterial(Drugs That Interfere With Protein Synthesis)]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Lincosamides]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 8](kindle://book?action=open&asin=B09FRF11YJ&location=4155)"
Chapter: "8"
Course: Pharmacology
---
### Adverse Reactions 
Gastrointestinal System Reactions 
- Abdominal pain 
- Esophagitis 
- Nausea 
- Vomiting 
- Diarrhea 

Other Reactions 
- Skin rash 
- [[Blood dyscrasias]]

### Contraindications
The lincosamides are contraindicated in infants younger than 1 month and in clients 
- Hypersensitive to the lincosamides 
- With minor bacterial or viral infections

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```


