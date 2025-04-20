---
DrugClass: "[[Skeletal Muscle, Bone, and Joint Disorder Drugs]]"
SubClass: "[[Disease-modifying antirheumatic drugs (DMARDs)-Biologics]]"
DrugClassContra: "[[Disease-modifying antirheumatic drugs (DMARDs)#Contraindications]]"
DrugClassAdverse: "[[Disease-modifying antirheumatic drugs (DMARDs)#Adverse Reactions]]"
SecondaryDrugClass: "[[Lower Gastrointestinal System Drugs]]"
SecondarySubClass: "[[Aminosalicylates]]"
BrandName: Cimzia
Chapter: "29"
KindleLinkChap: "[Chapter 29](kindle://book?action=open&asin=B09FRF11YJ&location=15248)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
SecondaryAdverse: "[[Aminosalicylates#Adverse Reactions]]"
SecondaryContra: "[[Aminosalicylates#Contraindications]]"
SubCat: Biologics for Bowel Disorders
ThirdDrugClass: "[[Immune Blockers]]"
ThirdSubClass: "[[Monoclonal antibodies]]"
ThirdAdverse: "[[Monoclonal antibodies#Adverse Reactions]]"
ThirdContra: "[[Monoclonal antibodies#Contraindications]]"
SubCat2: Rheumatoid Arthritis
---
```smiles

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
RA, Crohn disease 
400 mg subcut every 2 weeks or monthly

### Contraindications
See `= this.DrugClassContra`
See `= this.SecondaryContra`
See `= this.ThirdContra`

### Mechanisms of Action

### Side/Adverse Effects
See `= this.DrugClassAdverse`
See `= this.SecondaryAdverse`
See `= this.ThirdAdverse`
URI and UTI symptoms 

### Interactions

`= this.ChemLink+this.file.name`

