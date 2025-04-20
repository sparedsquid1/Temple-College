---
DrugClass: "[[Antihypertensive Drugs]]"
SubClass: "[[Angiotensin II receptor antagonists]]"
DrugClassContra: "[[Antihypertensive Drugs#Contraindications]]"
DrugClassAdverse: "[[Antihypertensive Drugs#Side/Adverse Effects]]"
SecondaryDrugClass: 
SecondarySubClass: 
SecondaryAdverse: 
SecondaryContra: 
ThirdDrugClass: 
ThirdSubClass: 
BrandName: Micardis
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
CCCC1=NC2=C(N1CC3=CC=C(C=C3)C4=CC=CC=C4C(=O)O)C=C(C=C2C)C5=NC6=CC=CC=C6N5C
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
40– 80 mg/ day orally

### Contraindications
See `= this.DrugClassContra`

### Interactionside/Adverse Effects
See `= this.DrugClassAdverse`
Diarrhea, URI symptoms, sinusitis

### Interactions

`= this.ChemLink+this.file.name`

