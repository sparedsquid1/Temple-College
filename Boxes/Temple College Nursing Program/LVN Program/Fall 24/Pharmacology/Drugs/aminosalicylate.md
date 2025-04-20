---
DrugClass: "[[Antitubercular]]"
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Secondary (Second-Line) Drugs]]"
SecondaryDrugClass: 
SecondarySubClass: 
BrandName: Paser
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
C1=CC(=C(C=C1N)O)C(=O)O
```

### Brand name
`=this.BrandName`
### Generic name
`= this.file.name`

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage
MDR(Multi Drug resistant)-TB
4 g (1 packet) orally

### Contraindications
See `= this.DrugClassContra`

### Mechanisms of Action

### Side/Adverse Effects
See `= this.DrugClassAdverse`
Nausea, vomiting, diarrhea, abdominal pain, [[hypersensitivity reactions]]

### Interactions

`= this.ChemLink+this.file.name`
