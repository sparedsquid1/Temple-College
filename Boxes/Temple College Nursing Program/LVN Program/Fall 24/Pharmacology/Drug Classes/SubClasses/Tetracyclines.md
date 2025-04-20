---
DrugClass: "[[Antibacterial(Drugs That Interfere With Protein Synthesis)]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Tetracyclines]]"
SecondaryDrugClass: 
SecondarySubClass: "[[Antibacterial(Drugs That Interfere With Protein Synthesis)]]"
KindleLinkChap: "[Chapter 8](kindle://book?action=open&asin=B09FRF11YJ&location=4155)"
Chapter: "8"
Course: Pharmacology
---
### Adverse Reactions 
Gastrointestinal System Reactions 
- Nausea or vomiting 
- Diarrhea 
- Epigastric distress 
- [[Stomatitis]]
- Sore throat

Other Reactions 
- Skin rashes 
- [[photosensitivity]] reaction ([[demeclocycline]] seems to cause the most serious [[photosensitivity]] reaction, whereas [[minocycline]] is least likely to cause this type of reaction)

### Contraindications
Tetracyclines are contraindicated in the client known to be hypersensitive to any of the tetracyclines; during pregnancy, because of the possibility of toxic effects to the developing fetus ([[Preg Cat D]]); during lactation; and in children younger than 9   years.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
