---
DrugClass: "[[Upper Respiratory System Drugs]]"
SubClass: "[[Intranasal Steroids (INSs)]]"
DrugClassContra: "[[Intranasal Steroids (INSs)#Contraindications]]"
DrugClassAdverse: "[[Intranasal Steroids (INSs)#Adverse Reactions]]"
SecondaryDrugClass: "[[Pituitary and Adrenocortical Hormones]]"
SecondarySubClass: "[[Anterior pituitary hormones]]"
BrandName: Nasacort AQ and HFA
Chapter: "30"
KindleLinkChap: "[Chapter 30](kindle://book?action=open&asin=B09FRF11YJ&location=15967)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
SecondaryContra: "[[Glucocorticoids#Contraindications]]"
SecondaryAdverse: "[[Glucocorticoids#Adverse Reactions]]"
SubCat: Glucocorticoids
---
```smiles
C[C@]12C[C@@H]([C@]3([C@H]([C@@H]1C[C@H]([C@@]2(C(=O)CO)O)O)CCC4=CC(=O)C=C[C@@]43C)F)O
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
[[Rhinitis]] (perennial and seasonal)
2 sprays per nare once daily

### Contraindications
See `= this.DrugClassContra`
See `= this.SecondaryContra`

### Interactionsde/Adverse Effects
See `= this.DrugClassAdverse`
See `= this.SecondaryAdverse`
[[Pharyngitis]]

### Interactions

`= this.ChemLink+this.file.name`

