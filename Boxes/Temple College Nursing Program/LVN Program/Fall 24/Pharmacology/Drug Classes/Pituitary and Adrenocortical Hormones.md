---
DrugClass: "[[Pituitary and Adrenocortical Hormones]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 41](kindle://book?action=open&asin=B09FRF11YJ&location=23770)"
Course: Pharmacology
Chapter: "41"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications


### Side/Adverse Effects 


### SubClasses
#### Posterior pituitary hormones
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Posterior pituitary hormones]] or SecondarySubClass = [[Posterior pituitary hormones]] or ThirdSubClass = [[Posterior pituitary hormones]]
sort file.name asc
```

#### Anterior pituitary hormones
##### Gonadotropins: Ovarian Stimulants
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Anterior pituitary hormones]] or SecondarySubClass = [[Anterior pituitary hormones]] or ThirdSubClass = [[Anterior pituitary hormones]] and SubCat = "Gonadotropins: Ovarian Stimulants"
sort file.name asc
```

##### Gonadotropin-Releasing Hormones/Synthetics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Anterior pituitary hormones]] or SecondarySubClass = [[Anterior pituitary hormones]] or ThirdSubClass = [[Anterior pituitary hormones]] and SubCat = "Gonadotropin-Releasing Hormones/ Synthetics"
sort file.name asc
```

##### Gonadotropin-Releasing Hormone Antagonists
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Anterior pituitary hormones]] or SecondarySubClass = [[Anterior pituitary hormones]] or ThirdSubClass = [[Anterior pituitary hormones]] and SubCat = "Gonadotropin-Releasing Hormone Antagonists"
sort file.name asc
```

##### Nonsteroidal Ovarian Stimulant
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Anterior pituitary hormones]] or SecondarySubClass = [[Anterior pituitary hormones]] or ThirdSubClass = [[Anterior pituitary hormones]] and SubCat = "Nonsteroidal Ovarian Stimulant"
sort file.name asc
```

##### Growth Hormone and Hormone Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Anterior pituitary hormones]] or SecondarySubClass = [[Anterior pituitary hormones]] or ThirdSubClass = [[Anterior pituitary hormones]] and SubCat = "Growth Hormone and Hormone Inhibitors"
sort file.name asc
```

##### ACTH
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Anterior pituitary hormones]] or SecondarySubClass = [[Anterior pituitary hormones]] or ThirdSubClass = [[Anterior pituitary hormones]] and SubCat = "ACTH"
sort file.name asc
```

##### Glucocorticoids
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Anterior pituitary hormones]] or SecondarySubClass = [[Anterior pituitary hormones]] or ThirdSubClass = [[Anterior pituitary hormones]] and SubCat = "Glucocorticoids"
sort file.name asc
```

##### Mineralocorticoids
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Anterior pituitary hormones]] or SecondarySubClass = [[Anterior pituitary hormones]] or ThirdSubClass = [[Anterior pituitary hormones]] and SubCat = "Mineralocorticoids"
sort file.name asc
```

##### Miscellaneous Hormones and Hormone Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Anterior pituitary hormones]] or SecondarySubClass = [[Anterior pituitary hormones]] or ThirdSubClass = [[Anterior pituitary hormones]] and SubCat = "Miscellaneous Hormones and Hormone Inhibitors"
sort file.name asc
```
