---
DrugClass: "[[Upper Respiratory System Drugs]]"
SubClass: "[[Intranasal Steroids (INSs)]]"
DrugClassContra: "[[Intranasal Steroids (INSs)#Contraindications]]"
DrugClassAdverse: "[[Intranasal Steroids (INSs)#Adverse Reactions]]"
SecondaryDrugClass: "[[Lower Respiratory System Drugs]]"
SecondarySubClass: "[[Inhaled Corticosteroids]]"
BrandName: Rhinocort
Chapter: "30"
KindleLinkChap: "[Chapter 30](kindle://book?action=open&asin=B09FRF11YJ&location=15967)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
ThirdDrugClass: "[[Pituitary and Adrenocortical Hormones]]"
ThirdSubClass: "[[Anterior pituitary hormones]]"
ThirdAdverse: "[[Glucocorticoids#Adverse Reactions]]"
ThirdContra: "[[Glucocorticoids#Contraindications]]"
SubCat: Glucocorticoids
---
```smiles
CCCC1O[C@@H]2C[C@H]3[C@@H]4CCC5=CC(=O)C=C[C@@]5([C@H]4[C@H](C[C@@]3([C@@]2(O1)C(=O)CO)C)O)C
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
[[Rhinitis]] (perennial and seasonal)
Up to 4 sprays per nare, once daily

### Contraindications
See `= this.DrugClassContra`

### Mechanisms of Action

### Side/Adverse Effects
See `= this.DrugClassAdverse`
[[Epistaxis]] 
### Interactions

`= this.ChemLink+this.file.name`

