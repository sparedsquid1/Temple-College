---
DrugClass: "[[Antitubercular]]"
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Primary (First-Line) Drugs]]"
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
Active TB
15– 30 mg/ kg/ day orally, maximum 3 g/ day orally; 50– 70 mg/ kg twice weekly orally
### Contraindications
See `= this.DrugClassContra`

### Mechanisms of Action

### Side/Adverse Effects
See `= this.DrugClassAdverse`
[[Hepatotoxicity]], nausea, vomiting, diarrhea, [[myalgia]], rashes
### Interactions
  
`= this.ChemLink+this.file.name`
