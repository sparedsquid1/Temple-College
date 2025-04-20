---
DrugClass: "[[Adrenergic Blocking]]"
SubClass: "[[Antiadrenergic Drugs Peripherally Acting]]"
DrugClassContra: "[[Adrenergic Blocking#Contraindications]]"
DrugClassAdverse: "[[Adrenergic Blocking#Side/Adverse Effects]]"
SecondaryDrugClass: "[[Antihypertensive Drugs]]"
SecondarySubClass: "[[Antiadrenergic Drugs Peripherally Acting]]"
BrandName: Cardura
Chapter: "24"
KindleLinkChap: "[Chapter 24](kindle://book?action=open&asin=B09FRF11YJ&location=12809)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
SecondaryAdverse: "[[Antihypertensive Drugs#Side/Adverse Effects]]"
SecondaryContra: "[[Antihypertensive Drugs#Contraindications]]"
ThirdDrugClass: "[[Menopause and Andropause Drugs]]"
ThirdSubClass: "[[Drugs to treat BPH]]"
ThirdAdverse: "[[Drugs to treat BPH#Adverse Reactions]]"
ThirdContra: "[[Drugs to treat BPH#Contraindications]]"
SubCat: "Antiadrenergic Drugs: Peripherally Acting"
---
```smiles
COC1=C(C=C2C(=C1)C(=NC(=N2)N3CCN(CC3)C(=O)C4COC5=CC=CC=C5O4)N)OC
```

### Brand name
`=this.BrandName`
### Generic name
`= this.file.name`
### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`
`= this.SecondaryDrugClass`
	`= this.SecondaryDrugClass.KindleLinkChap`
`= this.ThirdDrugClass`
	`= this.ThirdDrugClass.KindleLinkChap`
	
### Dosage & Usage
Hypertension, [[BPH]] 
Hypertension: 1– 8 mg orally daily 
[[BPH]]: 1– 16 mg orally daily
### Contraindications
See `= this.DrugClassContra`
See `= this.SecondaryContra`
See `= this.ThirdAdverse`

### Mechanisms of Action

### Side/Adverse Effects
See `= this.DrugClassAdverse`
See `= this.SecondaryAdverse`
See `= this.ThirdContra`
Headache, dizziness, fatigue

### Interactions

`= this.ChemLink+this.file.name`

 