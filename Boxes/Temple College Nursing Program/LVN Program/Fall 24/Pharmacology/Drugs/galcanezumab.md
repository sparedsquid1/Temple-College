---
DrugClass: "[[Immune Blockers]]"
SubClass: "[[Monoclonal antibodies]]"
DrugClassAdverse: "[[Monoclonal antibodies#Adverse Reactions]]"
DrugClassContra: "[[Monoclonal antibodies#Contraindications]]"
BrandName: Emgality
SecondaryDrugClass: "[[Nonopioid Analgesics - Nonsteroidal Anti-inflammatory Drugs]]"
SecondarySubClass: "[[Migraine headache medications]]"
SecondaryAdverse: "[[Migraine headache medications#Adverse Reactions]]"
SecondaryContra: "[[Migraine headache medications#Contraindications]]"
ThirdDrugClass: 
ThirdSubClass: 
ThirdAdverse: 
ThirdContra: 
FourthDrugClass: 
FourthSubClass: 
FourthAdverse: 
FourthContra: 
Chapter: "49"
KindleLinkChap: "[Chapter 49](kindle://book?action=open&asin=B09FRF11YJ&location=28643)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
aliases: 
SubCat: Migraine Headaches
SubCat2: CGRP Biologics
---
```smiles

```

### Brand name
`=this.BrandName`

### Generic name
`= this.file.name`

### Drug class 
`= this.SecondaryDrugClass`
	`= this.SecondaryDrugClass.KindleLinkChap`
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage
Cluster and migraine prophylaxis
Cluster: 300 mg subcut at onset
Migraine: 120 mg subcut monthly 

### Contraindications
See `= this.DrugClassContra`
See `= this.SecondaryContra`

### Mechanisms of Action


### Side/Adverse Effects
See `= this.DrugClassAdverse`
See `= this.SecondaryAdverse`
Injection site reaction, antibody dev.

### Interactions

`= this.ChemLink+this.file.name`

