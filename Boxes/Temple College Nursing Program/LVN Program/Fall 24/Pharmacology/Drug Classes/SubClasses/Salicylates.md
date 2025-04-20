---
DrugClass: "[[Nonopioid Analgesics - Salicylates & NonSalicylate]]"
BrandName: 
DrugClassContra: "[[Salicylates#Contraindications]]"
DrugClassAdverse: "[[Salicylates#Adverse Reactions]]"
SubClass: "[[Salicylates]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Gastrointestinal (GI) system reactions include: 
- Gastric upset, heartburn, nausea, vomiting 
- Anorexia
- GI bleeding 

Although salicylates are relatively safe when taken as recommended on the label or by the primary health care provider, their use can occasionally result in more serious reactions. Loss of [[Blood]] through the GI tract may occur with salicylate use. The amount of [[Blood]] lost is insignificant when a single dose is taken. However, use of these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] over a long period, even in normal doses, can result in significant [[Blood]] loss. Some individuals are allergic to [[aspirin (acetylsalicylic acid)]] and other salicylates. Allergy to salicylates may be manifested by hives, rash, [[angioedema]], bronchospasm with asthma-like symptoms, and anaphylactoid (allergic) reactions.
### Contraindications
Salicylates are contraindicated in clients with known hypersensitivity to salicylates or nonsteroidal anti-inflammatory [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] ([[Nonsterodial Anti-inflammatory Drugs]]). Because salicylates prolong bleeding time, they are contraindicated in those with bleeding disorders or tendencies. These include clients with GI bleeding (from any cause), clients with [[Blood dyscrasias]] (abnormalities), and clients receiving anticoagulant or antineoplastic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. Salicylates are classified as [[Preg Cat D]] ([[aspirin (acetylsalicylic acid)]]) and C [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and should be used cautiously during pregnancy and lactation.
### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
