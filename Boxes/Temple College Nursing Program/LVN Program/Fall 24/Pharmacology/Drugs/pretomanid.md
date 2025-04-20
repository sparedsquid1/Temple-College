---
DrugClass: "[[Antitubercular]]"
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Secondary (Second-Line) Drugs]]"
SecondaryDrugClass: 
SecondarySubClass: 
BrandName: 
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
C1[C@@H](COC2=NC(=CN21)[N+](=O)[O-])OCC3=CC=C(C=C3)OC(F)(F)F
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
200 mg daily orally

### Contraindications
See `= this.DrugClassContra`

### Mechanisms of Action

### Side/Adverse Effects
See `= this.DrugClassAdverse`
Nausea, vomiting, headache, peripheral neuropath, skin rash, acne, muscle/ abdominal pain, fatigue

### Interactions

`= this.ChemLink+this.file.name`
