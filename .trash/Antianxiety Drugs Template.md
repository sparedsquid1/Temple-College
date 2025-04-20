---
DrugClass: "[[Antianxiety]]"
SubClass: 
DrugClassContra: "[[Antianxiety#Contraindications]]"
DrugClassAdverse: "[[Antianxiety#Side/Adverse Effects]]"
SecondaryDrugClass: 
SecondarySubClass: 
BrandName: 
Chapter: "19"
KindleLinkChap: "[Chapter 19](kindle://book?action=open&asin=B09FRF11YJ&location=10180)"
KindleLink: 
tags:
  - Drug
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
```smiles

```

### Brand name
`= this.BrandName`
### Generic name
`= this.file.name`
### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage

### Contraindications
See `= this.drugclasscontra`

### Mechanisms of Action

### Side/Adverse Effects
See `= this.drugclassadverse`

### Interactions

`= this.ChemLink+this.file.name`