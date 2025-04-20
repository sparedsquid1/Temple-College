---
DrugClass: "[[Antitubercular]]"
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Combination Primary Drugs]]"
SecondaryDrugClass: 
SecondarySubClass: 
BrandName: Rifater
Chapter: "10"
KindleLinkChap: "[Chapter 10](kindle://book?action=open&asin=B09FRF11YJ&location=5128)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
```smiles
C1=CN=CC=C1C(=O)NN
C[C@H]1/C=C/C=C(\C(=O)NC2=C(C(=C3C(=C2O)C(=C(C4=C3C(=O)[C@](O4)(O/C=C/[C@@H]([C@H]([C@H]([C@@H]([C@@H]([C@@H]([C@H]1O)C)O)C)OC(=O)C)C)OC)C)C)O)O)/C=N/N5CCN(CC5)C)/C
C1=CN=C(C=N1)C(=O)N
```

### Brand name
`=this.BrandName`
### Generic name
`= this.file.name`

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage
TB 
1– 2 tablets daily orally

### Contraindications
See `= this.DrugClassContra`

### Mechanisms of Action

### Side/Adverse Effects
See `= this.DrugClassAdverse`

### Interactions

`= this.ChemLink+this.BrandName`
