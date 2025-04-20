---
DrugClass: "[[Opioid Analgesics and Antagonists]]"
SubClass: "[[Opioid Analgesics]]"
DrugClassAdverse: "[[Opioid Analgesics#Adverse Reactions]]"
DrugClassContra: "[[Opioid Analgesics#Contraindications]]"
BrandName: ConZip, Ultram
SecondaryDrugClass: 
SecondarySubClass: 
SecondaryAdverse: 
SecondaryContra: 
ThirdDrugClass: 
ThirdSubClass: 
ThirdAdverse: 
ThirdContra: 
FourthDrugClass: 
FourthSubClass: 
FourthAdverse: 
FourthContra: 
Chapter: "15"
KindleLinkChap: "[Chapter 15](kindle://book?action=open&asin=B09FRF11YJ&location=8219)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
aliases: 
SubCat:
---
```smiles
CN(C)C[C@H]1CCCC[C@@]1(C2=CC(=CC=C2)OC)O
```

### Brand name
`=this.BrandName`

### Generic name
`= this.file.name`

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage
Moderate to severe chronic pain
Titrate individual dose starting at 25 mg up to 100 mg/ day

### Contraindications
See `= this.DrugClassContra`

### Interactionside/Adverse Effects
See `= this.DrugClassAdverse`
Same as [[morphine]]

### Interactions

`= this.ChemLink+this.file.name`

