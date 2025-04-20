---
DrugClass: "[[Menopause and Andropause Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Female hormones]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Administration of [[Estrogens]] by any route may result in many adverse reactions, although the incidence and intensity of these reactions vary. Some of the adverse reactions seen with the administration of [[Estrogens]] are as follows: [[CNS]] Reactions Headache, migraine Dizziness, mental [[Depression]] Dermatologic Reactions Dermatitis, pruritus Chloasma (pigmentation of the skin) or melasma (discoloration of the skin), which may continue when use of the drug is discontinued Gastrointestinal Reactions Nausea, vomiting Abdominal bloating and cramps Genitourinary Reactions Breakthrough bleeding, withdrawal bleeding, spotting, changes in menstrual [[flow]] [[dysmenorrhea]], premenstrual-like syndrome, amenorrhea Vaginal candidiasis, cervical erosion, vaginitis Local Reactions Redness and irritation at the application site with transdermal system Pain at injection site or sterile abscess with parenteral form of the drug Ophthalmic Reactions Steepening of corneal curvature Intolerance to contact lenses
### Contraindications

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
