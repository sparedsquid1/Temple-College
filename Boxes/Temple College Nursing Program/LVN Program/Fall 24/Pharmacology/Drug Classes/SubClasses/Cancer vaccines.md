---
DrugClass: "[[Immune Modulating Therapies]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Cancer vaccines]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Treatment cancer [[Vaccines]] involve making the drug from the client’s own tumor cells (autologous) or using many different cancer cells to induce a response (allogeneic). Clients are observed during and after infusion for reaction. Anaphylactic reactions may occur as an acute infusion reaction. Clients with cardiac or pulmonary conditions should be closely monitored during infusion. Other adverse reactions include nausea, vomiting, fatigue, headache, and muscle and joint pain. Because the drug is used to treat prostate cancer, it should not be given to women.

### Contraindications

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
