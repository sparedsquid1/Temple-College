---
DrugClass: "[[Immune Blockers]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 49](kindle://book?action=open&asin=B09FRF11YJ&location=28643)"
Course: Pharmacology
Chapter: "49"
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
#### Immune Suppressent Drugs
##### Anti-Organ Rejection Agents
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Immunosuppressants]] or SecondarySubClass = [[Immunosuppressants]] or ThirdSubClass = [[Immunosuppressants]] and SubCat = "Anti-Organ Rejection Agents" or SubCat2 = "Anti-Organ Rejection Agents"
sort file.name asc
```

#### Disease-Specific Monoclonal Antibodies and Inhibitors
##### Asthma
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Monoclonal antibodies]] or SecondarySubClass = [[Monoclonal antibodies]] or ThirdSubClass = [[Monoclonal antibodies]] and SubCat = "Asthma" or SubCat2 = "Asthma"
sort file.name asc
```
##### Migraine Headaches
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Monoclonal antibodies]] or SecondarySubClass = [[Monoclonal antibodies]] or ThirdSubClass = [[Monoclonal antibodies]] and SubCat = "Migraine Headaches" or SubCat2 = "Migraine Headaches"
sort file.name asc
```

##### Multiple Sclerosis
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Monoclonal antibodies]] or SecondarySubClass = [[Monoclonal antibodies]] or ThirdSubClass = [[Monoclonal antibodies]] and SubCat = "Multiple Sclerosis" or SubCat2 = "Multiple Sclerosis"
sort file.name asc
```

##### Rheumatoid Arthritis
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Monoclonal antibodies]] or SecondarySubClass = [[Monoclonal antibodies]] or ThirdSubClass = [[Monoclonal antibodies]] and SubCat = "Rheumatoid Arthritis" or SubCat2 = "Rheumatoid Arthritis"
sort file.name asc
```

##### Psoriasis
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Monoclonal antibodies]] or SecondarySubClass = [[Monoclonal antibodies]] or ThirdSubClass = [[Monoclonal antibodies]] and SubCat = "Psoriasis" or SubCat2 = "Psoriasis"
sort file.name asc
```

##### VEGFR Antagonists—Eye Preparations for Macular Degeneration
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Monoclonal antibodies]] or SecondarySubClass = [[Monoclonal antibodies]] or ThirdSubClass = [[Monoclonal antibodies]] and SubCat = "VEGFR Antagonists—Eye Preparations for Macular Degeneration" or SubCat2 = "VEGFR Antagonists—Eye Preparations for Macular Degeneration"
sort file.name asc
```

##### Adjuncts Used to Treat HIV Infection With Antiretrovirals
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Monoclonal antibodies]] or SecondarySubClass = [[Monoclonal antibodies]] or ThirdSubClass = [[Monoclonal antibodies]] and SubCat = "Adjuncts Used to Treat HIV Infection With Antiretrovirals" or SubCat2 = "Adjuncts Used to Treat HIV Infection With Antiretrovirals"
sort file.name asc
```

