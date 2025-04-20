---
DrugClass: "[[Antidiabetic Drugs]]"
SubClass: "[[Glucagon-Like Peptide-1 Agonists]]"
DrugClassAdverse: "[[Glucagon-Like Peptide-1 Agonists#Adverse Reactions]]"
DrugClassContra: "[[Glucagon-Like Peptide-1 Agonists#Contraindications]]"
BrandName: 
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
CC[C@@H](C)[C@@H](C(=O)N[C@H](C)C(=O)N[C@@H](CC1=CNC2=CC=CC=C21)C(=O)N[C@@H](CC(C)C)C(=O)N[C@@H](C(C)C)C(=O)N[C@@H](CCCCN)C(=O)NCC(=O)N[C@@H](CCCNC(=N)N)C(=O)N)NC(=O)[C@H](CC3=CC=CC=C3)NC(=O)[C@H](CCC(=O)O)NC(=O)[C@H](CCCCN)NC(=O)[C@@H](C)NC(=O)[C@@H](C)NC(=O)[C@H](CCC(=O)N)NC(=O)CNC(=O)[C@H](CCC(=O)O)NC(=O)[C@H](CC(C)C)NC(=O)[C@H](CC4=CC=C(C=C4)O)NC(=O)[C@H](CO)NC(=O)[C@H](CO)NC(=O)[C@H](C(C)C)NC(=O)[C@H](CC(=O)O)NC(=O)[C@H](CO)NC(=O)[C@H]([C@H](C)O)NC(=O)[C@H](CC5=CC=CC=C5)NC(=O)[C@H]([C@H](C)O)NC(=O)CNC(=O)[C@H](CCC(=O)O)NC(=O)CNC(=O)[C@H](CC6=CN=CN6)N
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
30 mg subcut, weekly

### Contraindications
See `= this.DrugClassContra`

### Mechanisms of Action
- [Glucagon-like peptide 1 receptor](https://go.drugbank.com/drugs/DB09043#BE0000857)
    
    Agonist

### Side/Adverse Effects
See `= this.DrugClassAdverse`
Nausea, vomiting, diarrhea, injection site reaction

### Interactions

`= this.ChemLink+this.file.name`

