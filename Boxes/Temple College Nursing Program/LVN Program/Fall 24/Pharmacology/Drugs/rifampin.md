---
DrugClass: "[[Antitubercular]]"
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Primary (First-Line) Drugs]]"
SecondaryDrugClass: 
SecondarySubClass: 
BrandName: Rifadin, Rimactane
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
C[C@H]1/C=C/C=C(\C(=O)NC2=C(C(=C3C(=C2O)C(=C(C4=C3C(=O)[C@](O4)(O/C=C/[C@@H]([C@H]([C@H]([C@@H]([C@@H]([C@@H]([C@H]1O)C)O)C)OC(=O)C)C)OC)C)C)O)O)/C=N/N5CCN(CC5)C)/C
```

### Brand name
`=this.BrandName`
### Generic name
`= this.file.name`

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Dosage & Usage
Active TB, [[Hansen disease]]
10 mg/ kg (up to 600 mg/ day) orally, IV

### Contraindications
See `= this.DrugClassContra`

### Mechanisms of Action

### Side/Adverse Effects
See `= this.DrugClassAdverse`
Heartburn, drowsiness, fatigue, dizziness, epigastric distress, hematologic changes, renal insufficiency, rash, body fluid discoloration

### Interactions

`= this.ChemLink+this.file.name`
