---
DrugClass: "[[Skeletal Muscle, Bone, and Joint Disorder Drugs]]"
SubClass: "[[Disease-modifying antirheumatic drugs (DMARDs)-Biologics]]"
DrugClassContra: "[[Disease-modifying antirheumatic drugs (DMARDs)#Contraindications]]"
DrugClassAdverse: "[[Disease-modifying antirheumatic drugs (DMARDs)#Adverse Reactions]]"
SecondaryDrugClass: "[[Lower Gastrointestinal System Drugs]]"
SecondarySubClass: "[[Aminosalicylates]]"
BrandName: Humira
Chapter: "29"
KindleLinkChap: "[Chapter 29](kindle://book?action=open&asin=B09FRF11YJ&location=15248)"
KindleLink: 
tags:
  - Drug
  - Pharmacology
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
SecondaryContra: "[[Aminosalicylates#Contraindications]]"
SecondaryAdverse: "[[Aminosalicylates#Adverse Reactions]]"
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
RA; other autoimmune disorders (e.g., Crohn disease)
40 mg subcut every other week 

### Contraindications
See `= this.DrugClassContra`
See `= this.SecondaryContra`
See `= this.ThirdAdverse`

### Mechanisms of Action
- [Tumor necrosis factor](https://go.drugbank.com/drugs/DB00051#BE0000704)
    
    Inhibitor
    
    Antibody

### Side/Adverse Effects
See `= this.DrugClassAdverse`
See `= this.SecondaryAdverse`
See `= this.ThirdContra`
Irritation at injection site, increased risk of infections 

### Interactions

`= this.ChemLink+this.file.name`

