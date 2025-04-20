---
DrugClass: "[[Adrenergic Blocking]]"
SubClass: "[[Beta (β)-adrenergic blocking]]"
DrugClassContra: "[[Beta (β)-adrenergic blocking#Contraindications]]"
DrugClassAdverse: "[[Beta (β)-adrenergic blocking#Adverse Reactions]]"
SecondaryDrugClass: "[[Antihypertensive Drugs]]"
SecondarySubClass: "[[Beta (β)-adrenergic blocking]]"
BrandName: 
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
ThirdDrugClass: "[[Cardiotonic and Antiarrhythmic Drugs]]"
ThirdSubClass: "[[Antiarrhythmics]]"
ThirdContra: "[[Antiarrhythmics#Contraindications]]"
ThirdAdverse: "[[Antiarrhythmics#Adverse Reactions]]"
---

```smiles
CCCC(=O)NC1=CC(=C(C=C1)OCC(CNC(C)C)O)C(=O)C
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
Hypertension, ventricular arrhythmias
Hypertension: 400  mg orally in 1– 2 doses 
Arrhythmias: 400– 1200  mg/ day orally in divided doses

### Contraindications
See `= this.DrugClassContra`
See `= this.SecondaryContra`
See `= this.ThirdContra`

### Mechanisms of Action
- [Beta-1 adrenergic receptor](https://go.drugbank.com/drugs/DB01193#BE0000172)
    
    Partial agonist

### Side/Adverse Effects
See `= this.DrugClassAdverse`
See `= this.SecondaryAdverse`
See `= this.ThirdAdverse`
Bradycardia, dizziness, weakness, hypotension, nausea, vomiting, diarrhea, nervousness 

### Interactions

`= this.ChemLink+this.file.name`
