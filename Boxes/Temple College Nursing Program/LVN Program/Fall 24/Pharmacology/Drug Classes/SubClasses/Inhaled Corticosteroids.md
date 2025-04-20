---
DrugClass: "[[Lower Respiratory System Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Inhaled Corticosteroids]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
When used to manage chronic asthma, the [[Corticosteroids]] are most often given by inhalation. Systemic adverse reactions to the [[Corticosteroids]] are less likely to occur when the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are given by inhalation rather than taken orally. Occasionally, clients may experience reactions. 

**[[Respiratory]] System Reactions** 
- Throat irritation 
- Hoarseness 
- Upper [[Respiratory]] tract infection 
- Fungal infection of the [[Mouth]] and throat 

See Chapter 41 for adverse reactions after oral administration of the [[Corticosteroids]]. A more complete listing of the adverse reactions associated with the ICSs is found in the Summary Drug Table: Lower [[Respiratory]] System [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]].

### Contraindications
The ICSs are contraindicated in clients with hypersensitivity to the [[Corticosteroids]], acute bronchospasm, [[status asthmaticus]], or other acute episodes of asthma. [[beclomethasone]] is contraindicated for the relief of symptoms that can be controlled by a bronchodilator and other nonsteroidal medications and in the treatment of nonasthmatic bronchitis.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
