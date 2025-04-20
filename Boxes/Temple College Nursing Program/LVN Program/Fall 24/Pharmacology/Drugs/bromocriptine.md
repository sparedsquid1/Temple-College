---
DrugClass: "[[Antiparkinson]]"
SubClass: "[[Dopaminergic Drugs]]"
DrugClassContra: "[[Dopaminergic Drugs#Contraindications]]"
DrugClassAdverse: "[[Dopaminergic Drugs#Adverse Reactions]]"
SecondaryDrugClass: "[[Antidiabetic Drugs]]"
SecondarySubClass: "[[Meglitinides]]"
BrandName: Cycloset, Parlodel
Chapter: "27"
KindleLinkChap: "[Chapter 27](kindle://book?action=open&asin=B09FRF11YJ&location=14154)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
SecondaryContra: "[[Meglitinides#Contraindications]]"
SecondaryAdverse: "[[Meglitinides#Adverse Reactions]]"
ThirdDrugClass: "[[Pituitary and Adrenocortical Hormones]]"
ThirdSubClass: "[[Anterior pituitary hormones]]"
SubCat: Miscellaneous Hormones and Hormone Inhibitors
---
```smiles
CC(C)C[C@H]1C(=O)N2CCC[C@H]2[C@]3(N1C(=O)[C@](O3)(C(C)C)NC(=O)[C@H]4CN([C@@H]5CC6=C(NC7=CC=CC(=C67)C5=C4)Br)C)O
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
Parkinson disease, female endocrine imbalances, [[Acromegaly]], fibrocystic breast disease, diabetes mellitus type2 
10– 40 mg/ day orally

### Contraindications
See `= this.DrugClassContra`
See `= this.SecondaryContra`

### Mechanisms of Action

### Side/Adverse Effects
See `= this.DrugClassAdverse`
See `= this.SecondaryAdverse`
Drowsiness, sedation, dizziness, faintness, epigastric distress, anorexia
 
### Interactions

`= this.ChemLink+this.file.name`

