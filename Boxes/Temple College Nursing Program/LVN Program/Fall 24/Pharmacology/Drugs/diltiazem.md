---
DrugClass: "[[Antihypertensive Drugs]]"
SubClass: "[[Calcium channel blockers]]"
DrugClassContra: "[[Antihypertensive Drugs#Contraindications]]"
DrugClassAdverse: "[[Antihypertensive Drugs#Side/Adverse Effects]]"
SecondaryDrugClass: "[[Antianginal and Vasodilating Drugs]]"
SecondarySubClass: "[[Calcium Channel Blockers Used for Anginal Issues]]"
SecondaryAdverse: "[[Antianginal and Vasodilating Drugs#Side/Adverse Effects]]"
SecondaryContra: "[[Antianginal and Vasodilating Drugs#Contraindications]]"
ThirdDrugClass: "[[Cardiotonic and Antiarrhythmic Drugs]]"
ThirdSubClass: "[[Antiarrhythmics]]"
BrandName: Cardizem, Cardizem CD, Tiazac
Chapter: "33"
KindleLinkChap: "[Chapter 33](kindle://book?action=open&asin=B09FRF11YJ&location=17954)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
aliases: 
ThirdContra: "[[Antiarrhythmics#Contraindications]]"
ThirdAdverse: "[[Antiarrhythmics#Adverse Reactions]]"
---
```smiles
CC(=O)O[C@@H]1[C@@H](SC2=CC=CC=C2N(C1=O)CCN(C)C)C3=CC=C(C=C3)OC
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
Hypertension, chronic stable angina, atrial fibrillation/ flutter, paroxysmal superventricular tachycardia
Extended-release tablets/ capsules— hypertension: 120– 540 mg/ day

### Contraindications
See `= this.DrugClassContra`
See `= this.SecondaryContra`
See `= this.ThirdContra`

### Mechanisms of Action


### Side/Adverse Effects
See `= this.DrugClassAdverse`
See `= this.SecondaryAdverse`
See `= this.ThirdAdverse`
Headache, dizziness, AV block, bradycardia, edema, dyspnea, [[rhinitis]]

### Interactions

`= this.ChemLink+this.file.name`
