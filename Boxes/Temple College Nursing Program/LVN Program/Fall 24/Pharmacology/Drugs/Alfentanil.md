---
DrugClass: "[[Opioid Analgesics and Antagonists]]"
SubClass: "[[Opioid Analgesics]]"
DrugClassAdverse: "[[Opioid Analgesics#Adverse Reactions]]"
DrugClassContra: "[[Opioid Analgesics#Contraindications]]"
BrandName: Alfenta
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
CCC(=O)N(C1=CC=CC=C1)C2(CCN(CC2)CCN3C(=O)N(N=N3)CC)COC
```

### Brand name
`=this.BrandName`

### Generic name
`= this.file.name`

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage
Anesthetic adjunct
Individualize dosage and titrate to obtain desired effect

### Contraindications
See `= this.DrugClassContra`

### Mechanisms of Action
- [Mu-type opioid receptor](https://go.drugbank.com/drugs/DB00802#BE0000770)
    
    Agonist

### Side/Adverse Effects
See `= this.DrugClassAdverse`
[[Respiratory]] [[Depression]], skeletal muscle rigidity, constipation, nausea, vomiting

### Interactions

`= this.ChemLink+this.file.name`

