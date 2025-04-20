---
DrugClass: "[[Antihypertensive Drugs]]"
SubClass: "[[Calcium channel blockers]]"
DrugClassContra: "[[Antihypertensive Drugs#Contraindications]]"
DrugClassAdverse: "[[Antihypertensive Drugs#Side/Adverse Effects]]"
SecondaryDrugClass: "[[Antianginal and Vasodilating Drugs]]"
SecondarySubClass: "[[Calcium Channel Blockers Used for Anginal Issues]]"
SecondaryAdverse: "[[Antianginal and Vasodilating Drugs#Side/Adverse Effects]]"
SecondaryContra: "[[Antianginal and Vasodilating Drugs#Contraindications]]"
ThirdDrugClass: "[[Uterine Drugs]]"
ThirdSubClass: "[[Tocolytics]]"
BrandName: Procardia, Procardia XL
Chapter: "33"
KindleLinkChap: "[Chapter 33](kindle://book?action=open&asin=B09FRF11YJ&location=17954)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
aliases: 
ThirdAdverse: "[[Tocolytics#Adverse Reactions]]"
ThirdContra: "[[Tocolytics#Contraindications]]"
---
```smiles
CC1=C(C(C(=C(N1)C)C(=O)OC)C2=CC=CC=C2[N+](=O)[O-])C(=O)OC
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
 Hypertension (sustained release only), [[vasospastic angina]], chronic stable angina 
10– 20 mg TID orally; may increase to 120 mg/ day 
Sustained release: 30– 60 mg/ day orally; may increase to 120 mg/ day

### Contraindications
See `= this.DrugClassContra`
See `= this.SecondaryContra`
See `= this.ThirdAdverse`

### Mechanisms of Action


### Side/Adverse Effects
See `= this.DrugClassAdverse`
See `= this.SecondaryAdverse`
See `= this.ThirdContra`
Headache, dizziness, weakness, edema, nausea, muscle cramps, cough, nasal congestion, wheezing 

### Interactions

`= this.ChemLink+this.file.name`

