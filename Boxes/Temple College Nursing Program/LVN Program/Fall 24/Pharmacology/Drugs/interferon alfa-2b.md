---
DrugClass: "[[Immunostimulants and Immunomodulators]]"
SubClass: "[[Interferons]]"
DrugClassAdverse: "[[Interferons#Adverse Reactions]]"
DrugClassContra: "[[Interferons#Contraindications]]"
BrandName: Intron A
SecondaryDrugClass: "[[Immune Modulating Therapies]]"
SecondarySubClass: "[[Cytokines]]"
SecondaryAdverse: "[[Cytokines#Adverse Reactions]]"
SecondaryContra: "[[Cytokines#Contraindications]]"
ThirdDrugClass: 
ThirdSubClass: 
ThirdAdverse: 
ThirdContra: 
FourthDrugClass: 
FourthSubClass: 
FourthAdverse: 
FourthContra: 
Chapter: "47"
KindleLinkChap: "[Chapter 47](kindle://book?action=open&asin=B09FRF11YJ&location=27339)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
aliases: 
SubCat: interferons
---
```smiles
CC1=CN(C(=O)NC1=O)[C@H]2C[C@@H]([C@H](O2)CO)N=[N+]=[N-]
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
Chronic [[hepatitis]] B, Kaposi [[Sarcoma]], [[Lymphoma]], [[Melanoma]], hairy cell [[Leukemia]], genital warts
Dependent on condition being treated, given subcut or IM

### Contraindications
See `= this.DrugClassContra`
See `= this.SecondaryContra`

### Mechanisms of Action


### Side/Adverse Effects
See `= this.DrugClassAdverse`
See `= this.SecondaryAdverse`
Flu-like symptoms ([[Fever]], headache, muscle ache), fatigue, nausea 
Flu-like symptoms, fatigue, insomnia, alopecia, nausea, abdominal pain, cough, injection site reaction

### Interactions

`= this.ChemLink+this.file.name`

