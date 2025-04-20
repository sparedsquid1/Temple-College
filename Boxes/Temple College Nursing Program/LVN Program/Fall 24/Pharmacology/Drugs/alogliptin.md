---
DrugClass: "[[Antidiabetic Drugs]]"
SubClass: "[[Dipeptidyl Peptidase-4 Inhibitors]]"
DrugClassAdverse: "[[Dipeptidyl Peptidase-4 Inhibitors#Adverse Reactions]]"
DrugClassContra: "[[Dipeptidyl Peptidase-4 Inhibitors#Contraindications]]"
BrandName: Nesina
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
Chapter: "40"
KindleLinkChap: "[Chapter 40](kindle://book?action=open&asin=B09FRF11YJ&location=22730)"
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
CN1C(=O)C=C(N(C1=O)CC2=CC=CC=C2C#N)N3CCC[C@H](C3)N
```

### Brand name
`=this.BrandName`

### Generic name
`= this.file.name`

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage
Type 2 diabetes
25 mg orally daily

### Contraindications
See `= this.DrugClassContra`

### Mechanisms of Action
- [Dipeptidyl peptidase 4](https://go.drugbank.com/drugs/DB06203#BE0000854)
    
    Inhibitor

### Side/Adverse Effects
See `= this.DrugClassAdverse`
Headache, nasopharyngitis

### Interactions

`= this.ChemLink+this.file.name`

