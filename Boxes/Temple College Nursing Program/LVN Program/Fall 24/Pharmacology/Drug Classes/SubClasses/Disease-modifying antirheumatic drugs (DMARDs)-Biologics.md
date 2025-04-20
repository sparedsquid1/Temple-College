---
DrugClass: "[[Skeletal Muscle, Bone, and Joint Disorder Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Disease-modifying antirheumatic drugs (DMARDs)-Biologics]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Immunosuppressive [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] can cause the following adverse reactions: 
- Nausea 
- [[Stomatitis]] 
- Alopecia (hair loss) 

The adverse reactions to sulfa-based [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], such as [[sulfasalazine]], include ocular changes, gastrointestinal (GI) upset, and mild [[pancytopenia]]. Biologic DMARDs produce flu-like symptoms. Because they reduce the immune response, [[infectious diseases]] such as tuberculosis are a concern. The most common adverse reaction to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] given by injection is skin irritation. For more information, see the Summary Drug Table: [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] Used to Treat Musculoskeletal, Bone, and Joint Disorders.

### Contraindications
[[acute lymphoblastic leukemia]] categories of DMARDs are contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. Clients with renal insufficiency, [[Liver]] disease, [[Alcohol]] abuse, [[pancytopenia]], or folate deficiency should not take [[methotrexate]]. Women who are pregnant or attempting to become pregnant should not use [[leflunomide]]. Biologic DMARDs should not be used in clients with [[Heart]] failure or [[neurologic demyelinating diseases]]. [[Anakinra]] (Kineret) should not be used in combination with [[etanercept]], [[adalimumab]], or [[infliximab]].


### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
