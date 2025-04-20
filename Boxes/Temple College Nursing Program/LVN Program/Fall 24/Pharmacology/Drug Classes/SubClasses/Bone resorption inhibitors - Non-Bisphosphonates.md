---
DrugClass: "[[Skeletal Muscle, Bone, and Joint Disorder Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Bone resorption inhibitors - bisphosphonates]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Adverse reactions with bisphosphonates include: 
- Nausea, diarrhea Increased or recurrent bone pain 
- Headache 
- [[Dyspepsia]] (GI discomfort), acid regurgitation, dysphagia 
- Abdominal pain 

Bisphosphonates are typically not an issue when the client is instructed in the proper administration of the drug

### Contraindications
These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients who are hypersensitive to the bisphosphonates. [[alendronate]] (Fosamax) and [[risedronate]] (Actonel) are contraindicated in clients with hypocalcemia. [[alendronate]] is a [[Preg Cat C]] drug and is contraindicated during pregnancy. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are also contraindicated in clients with delayed esophageal emptying or renal impairment. Concurrent use of these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] with hormone replacement therapy is not recommended. 

Administration of the biologic, [[denosumab]] (Prolia), is associated with hypokalemia, osteonecrosis of the jaw, infection, skin reactions, and atypical femoral fractures. Benefit of the drug versus harsh and unusual adverse reactions are monitored by the US Food and Drug Administration (FDA) in a program called Risk Evaluation and Mitigation Strategy (REMS). With this program, specific instruction and monitoring must occur and documentation sent to the FDA regarding administration of the drug and client knowledge of potential adverse reactions. 

Although these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] have not been studied, if a pregnant woman presents with malignancy, their use during the pregnancy may be justified if the potential benefit outweighs the potential risk to the fetus.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
