---
DrugClass: "[[Antitubercular]]"
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Secondary (Second-Line) Drugs]]"
SecondaryDrugClass: 
SecondarySubClass: 
BrandName: Sirturo
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
CN(C)CC[C@@](C1=CC=CC2=CC=CC=C21)([C@H](C3=CC=CC=C3)C4=C(N=C5C=CC(=CC5=C4)Br)OC)O
```

### Brand name
`=this.BrandName`
### Generic name
`= this.file.name`

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage
MDR-TB
Only use in DOT setting: 400 mg daily (2 weeks), 200 mg (3 times weekly)

### Contraindications
See `= this.DrugClassContra`

### Mechanisms of Action

### Side/Adverse Effects
See `= this.DrugClassAdverse`
Nausea, headache, [[arthralgia]], chest pain, hemoptysis

### Interactions


`= this.ChemLink+this.file.name`
