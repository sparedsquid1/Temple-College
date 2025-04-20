---
DrugClass: "[[Menopause and Andropause Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 45](kindle://book?action=open&asin=B09FRF11YJ&location=26138)"
Course: Pharmacology
Chapter: "45"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
  - Pharmacology
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications


### Side/Adverse Effects 

### SubClasses
#### Female Hormone: Estrogens
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubCat = "Female Hormone: Estrogens"
sort file.name asc
```

#### Selective Estrogen Receptor Modulators
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Selective Estrogen Receptor Modulators]] or SecondarySubClass = [[Selective Estrogen Receptor Modulators]]
sort file.name asc
```

#### Antispasmatics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Antispasmatics]] or SecondarySubClass = [[Antispasmatics]]
sort file.name asc
```

#### Drugs to treat BPH
##### Antiadrenergic Drugs: Peripherally Acting
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass or ThirdDrugClass = this.DrugClass and SubClass = [[Drugs to treat BPH]] or SecondarySubClass = [[Drugs to treat BPH]] or ThirdSubClass = [[Drugs to treat BPH]] and SubCat = "Antiadrenergic Drugs: Peripherally Acting"
sort file.name asc
```

##### Androgen Hormone Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Drugs to treat BPH]] or SecondarySubClass = [[Drugs to treat BPH]] and SubCat = "Androgen Hormone Inhibitors"
sort file.name asc
```

##### Impotence Agents—Phosphodiesterase Type 5 (PD5E) Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Drugs to treat BPH]] or SecondarySubClass = [[Drugs to treat BPH]] and SubCat = "Impotence Agents—Phosphodiesterase Type 5 (PD5E) Inhibitors"
sort file.name asc
```

#### Hormonal Therapy for Breast, Endometrial, and Prostate Cancer
##### Gonadotropin-Releasing Hormone Antagonists
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" or SecondarySubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" and SubCat = "Gonadotropin-Releasing Hormone Antagonists"
sort file.name asc
```

##### Gonadotropin-Releasing Hormone Analogs
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" or SecondarySubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" and SubCat = "Gonadotropin-Releasing Hormone Analogs"
sort file.name asc
```

##### Antiandrogens
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" or SecondarySubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" and SubCat = "Antiandrogens"
sort file.name asc
```

##### Aromatase Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" or SecondarySubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" and SubCat = "Aromatase Inhibitors"
sort file.name asc
```

##### Progestins
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Progestins]] and SecondarySubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" or file.name = "megestrol"
sort file.name asc
```

##### Antiestrogen
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" or SecondarySubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" and SubCat = "Antiestrogen"
sort file.name asc
```

##### Antiestrogens—SERM Class
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" or SecondarySubClass = "Hormonal Therapy for Breast, Endometrial, and Prostate Cancer" and SubCat = "Antiestrogens—SERM Class"
sort file.name asc
```
