---
DrugClass: "[[Cholinergic Blocking Drugs]]"
SubClass: "[[Cholinergic Blocking Urinary Antispasmodics]]"
DrugClassContra: "[[Cholinergic Blocking Drugs#Contraindications]]"
DrugClassAdverse: "[[Cholinergic Blocking Drugs#Side/Adverse Effects]]"
SecondaryDrugClass: "[[Menopause and Andropause Drugs]]"
SecondarySubClass: "[[Antispasmatics]]"
BrandName: Detrol, Detrol LA (long acting, extended release)
Chapter: "26"
KindleLinkChap: "[Chapter 26](kindle://book?action=open&asin=B09FRF11YJ&location=13703)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
SecondaryAdverse: "[[Antispasmatics#Adverse Reactions]]"
SecondaryContra: "[[Antispasmatics#Contraindications]]"
---
```smiles
CC1=CC(=C(C=C1)O)[C@H](CCN(C(C)C)C(C)C)C2=CC=CC=C2
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

### Dosage & Usage
Overactive bladder
2 mg orally, TID
extended release: 4 mg daily

### Contraindications
See `= this.DrugClassContra`
See `= this.SecondaryContra`

### Interactionsde/Adverse Effects
See `= this.DrugClassAdverse`
See `= this.SecondaryAdverse`
Dry [[Mouth]], constipation, headache, dizziness

### Interactions

`= this.ChemLink+this.file.name`

