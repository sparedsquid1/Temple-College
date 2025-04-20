---
DrugClass: "[[Nonopioid Analgesics - Nonsteroidal Anti-inflammatory Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 14](kindle://book?action=open&asin=B09FRF11YJ&location=7569)"
Course: Pharmacology
Chapter: "14"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications


### Side/Adverse Effects 


### SubClasses
#### Nonsteroidal Anti-inflammatory Drugs (NSAIDs)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Nonsterodial Anti-inflammatory Drugs]] or SecondarySubClass = [[Nonsterodial Anti-inflammatory Drugs]] or ThirdSubClass = [[Nonsterodial Anti-inflammatory Drugs]]
sort file.name asc
```

##### Primarily COX-2 Inhibitor
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Nonsterodial Anti-inflammatory Drugs]] or SecondarySubClass = [[Nonsterodial Anti-inflammatory Drugs]] or ThirdSubClass = [[Nonsterodial Anti-inflammatory Drugs]] and SubCat = "Primarily COX-2 Inhibitor" or SubCat2 = "Primarily COX-2 Inhibitor"
sort file.name asc
```

#### Agents for Migraines
##### Serotonin 5-HT Receptor Agonists
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Migraine headache medications]] or SecondarySubClass = [[Migraine headache medications]] or ThirdSubClass = [[Migraine headache medications]] and SubCat = "Serotonin 5-HT Receptor Agonists" or SubCat2 = "Serotonin 5-HT Receptor Agonists"
sort file.name asc
```

##### Ergotamine Derivatives
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Migraine headache medications]] or SecondarySubClass = [[Migraine headache medications]] or ThirdSubClass = [[Migraine headache medications]] and SubCat = "Ergotamine Derivatives" or SubCat2 = "Ergotamine Derivatives"
sort file.name asc
```

##### Calcitonin Gene-Related Peptide (CGRP) receptor antagonist 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Migraine headache medications]] or SecondarySubClass = [[Migraine headache medications]] or ThirdSubClass = [[Migraine headache medications]] and SubCat = "Calcitonin Gene-Related Peptide (CGRP) receptor antagonist" or SubCat2 = "Calcitonin Gene-Related Peptide (CGRP) receptor antagonist"
sort file.name asc
```

##### CGRP Biologics 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Migraine headache medications]] or SecondarySubClass = [[Migraine headache medications]] or ThirdSubClass = [[Migraine headache medications]] and SubCat = "CGRP Biologics" or SubCat2 = "CGRP Biologics"
sort file.name asc
```
