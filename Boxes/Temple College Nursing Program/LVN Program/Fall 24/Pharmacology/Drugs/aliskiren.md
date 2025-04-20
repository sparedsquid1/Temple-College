---
DrugClass: "[[Antihypertensive Drugs]]"
SubClass: "[[Direct Renin Inhibitors]]"
DrugClassContra: "[[Antihypertensive Drugs#Contraindications]]"
DrugClassAdverse: "[[Antihypertensive Drugs#Side/Adverse Effects]]"
SecondaryDrugClass: 
SecondarySubClass: 
SecondaryAdverse: 
SecondaryContra: 
ThirdDrugClass: 
ThirdSubClass: 
BrandName: Tekturna
Chapter: "33"
KindleLinkChap: "[Chapter 33](kindle://book?action=open&asin=B09FRF11YJ&location=17954)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
aliases:
---
```smiles
CC(C)[C@@H](CC1=CC(=C(C=C1)OC)OCCCOC)C[C@@H]([C@H](C[C@@H](C(C)C)C(=O)NCC(C)(C)C(=O)N)O)N
```

### Brand name
`=this.BrandName`

### Generic name
`= this.file.name`

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage
Hypertension
150 mg/ day orally, may increase to 300 mg/ day

### Contraindications
See `= this.DrugClassContra`

### Mechanisms of Action
- [Renin](https://go.drugbank.com/drugs/DB09026#BE0000270)
    
    Inhibitor

### Side/Adverse Effects
See `= this.DrugClassAdverse`
Diarrhea, URI symptoms

### Interactions

`= this.ChemLink+this.file.name`

