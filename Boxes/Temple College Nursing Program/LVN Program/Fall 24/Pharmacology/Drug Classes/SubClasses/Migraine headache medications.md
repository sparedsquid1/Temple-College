---
DrugClass: "[[Nonopioid Analgesics - Nonsteroidal Anti-inflammatory Drugs]]"
BrandName: 
DrugClassContra: "[[Migraine headache medications#Contraindications]]"
DrugClassAdverse: "[[Migraine headache medications#Adverse Reactions]]"
SubClass: "[[Migraine headache medications]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
These agents are generally well tolerated, with most adverse reactions mild and transient. The most common are dizziness, nausea, fatigue, pain, dry [[Mouth]], and flushing. 

**[[Cardiovascular system]] Reactions** 
- Coronary artery vasospasm
- Cardiac arrhythmias and tachycardia 
- Myocardial infarction
### Contraindications
These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with a known hypersensitivity to selective serotonin agonists and should only be used when a clear diagnosis of migraine headache has been established. 5-HT agonists should not be used in clients with ischemic [[Heart]] disease (such as angina or myocardial infarction), transient ischemic attacks (TIAs), or uncontrolled hypertension or those clients taking [[Monoamine]] oxidase inhibitor antidepressants. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] should be used cautiously in clients with hepatic or renal function impairment, such as the elderly or clients requiring dialysis. Because these are [[Preg Cat C]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], they should be used during pregnancy only when the benefit outweighs the risk to the fetus. Caution should be exercised when administering them to lactating mothers. 

The ergot derivatives (see Summary Drug Table: Nonsteroidal Anti-inflammatory [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and Migraine Medications) should not be used by HIV clients using protease inhibitors or clients taking macrolide antibiotics because of the risk of peripheral [[ischemia]].
### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
