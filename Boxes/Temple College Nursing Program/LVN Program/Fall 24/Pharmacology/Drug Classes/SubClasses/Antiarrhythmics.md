---
DrugClass: "[[Cardiotonic and Antiarrhythmic Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Antiarrhythmics]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Adverse reactions associated with the administration of specific antiarrhythmic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are given in the Summary Drug Table: Antiarrhythmic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. General adverse reactions common to most antiarrhythmic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] include the following: 

**[[CNS]] Reactions** 
- Lightheadedness 
- Weakness 
- [[somnolence]] 

**[[Cardiovascular system]] Reactions**
- Hypotension 
- Arrhythmias
- Bradycardia 

**Other Reactions** 
- Urinary retention 
- Local inflammation 

[[acute lymphoblastic leukemia]] antiarrhythmic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] may cause new arrhythmias or worsen existing arrhythmias, even though they are administered to resolve an existing arrhythmia. This phenomenon is called the [[proarrhythmic effect]]. This effect ranges from an increase in frequency of PVCs to the development of more severe ventricular tachycardia to ventricular fibrillation and the effect may lead to death. Proarrhythmic effects may occur at any time, but they occur more often when excessive dosages are given, when the preexisting arrhythmia is life-threatening, or when the drug is given IV.

### Contraindications
The antiarrhythmic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with known hypersensitivity to these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. They are contraindicated during pregnancy and lactation. The antiarrhythmic drug [[amiodarone]] is a [[Preg Cat D]] drug, indicating that fetal harm can occur when the agent is administered to a pregnant woman. It is used only if the potential benefits outweigh the potential hazards to the fetus. Antiarrhythmic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with second- or third-degree AV block (if the client has no artificial pacemaker), severe HF, aortic stenosis, hypotension, and cardiogenic shock. [[quinidine]] is contraindicated in clients with [[myasthenia gravis]] or [[systemic lupus erythematosus]].

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
