---
DrugClass: "[[Anticoagulant and Thrombolytic Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Anticoagulants]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
The principal adverse reaction associated with anticoagulants is bleeding, which may range from very mild to severe. Bleeding may be seen in many areas of the body, such as the skin (bruising and petechiae), bladder, bowel, stomach, [[uterus]], and mucous membranes. Other adverse reactions are rare but may include the following: 
- Nausea, vomiting, abdominal cramping, diarrhea
- Alopecia (loss of hair) 
- Rash or [[urticaria]] (hives) 
- [[hepatitis]] (inflammation of the [[Liver]]), jaundice (yellowish discoloration of the skin and mucous membranes), [[thrombocytopenia]] (low platelet count), and [[Blood dyscrasias]] (disorders) 

Additional adverse reactions include local irritation when [[heparin]] is given by the subcutaneous (subcut) route. [[hypersensitivity reactions]] may also occur with any route of administration and include [[Fever]] and chills. More serious [[hypersensitivity reactions]] include an asthma-like reaction and an anaphylactic reaction. See the Summary Drug Table: Anticoagulant, Antiplatelet, and Thrombolytic Agents for additional adverse reactions.

### Contraindications
Anticoagulants are contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], active bleeding (except when caused by [[DIC]]), hemorrhagic disease, tuberculosis, [[Leukemia]], uncontrolled hypertension, gastrointestinal (GI) ulcers, recent surgery of the eye or [[CNS]], aneurysms, or severe renal or hepatic disease, and during lactation. Use during pregnancy can cause fetal death (oral agents are in [[Preg Cat X]] and parenteral agents are in [[Preg Cat C]]). The LMWHs are also contraindicated in clients with a hypersensitivity to pork products.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
