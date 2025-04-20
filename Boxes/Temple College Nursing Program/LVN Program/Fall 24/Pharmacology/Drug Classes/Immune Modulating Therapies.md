---
DrugClass: "[[Immune Modulating Therapies]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 51](kindle://book?action=open&asin=B09FRF11YJ&location=30282)"
Course: Pharmacology
Chapter: "51"
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
#### Cytokines
##### Interferons
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cytokines]] or SecondarySubClass = [[Cytokines]] or ThirdSubClass = [[Cytokines]] and SubCat = "interferons" or SubCat2 = "interferons"
sort file.name asc
```

##### Interleukin
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cytokines]] or SecondarySubClass = [[Cytokines]] or ThirdSubClass = [[Cytokines]] and SubCat = "Interleukin" or SubCat2 = "Interleukin"
sort file.name asc
```

##### Monoclonal Antibodies 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Monoclonal Antibodies]] or SecondarySubClass = [[Monoclonal Antibodies]] or ThirdSubClass = [[Monoclonal Antibodies]] and SubCat = "Monoclonal Antibodies" or SubCat2 = "Monoclonal Antibodies"
sort file.name asc
```

#### Checkpoint and Other Inhibitors
##### Checkpoint Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Checkpoint Inhibitors" or SubCat2 = "Checkpoint Inhibitors"
sort file.name asc
```

##### B-cell Lymphoma-2 Inhibitor
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "B-cell Lymphoma-2 Inhibitor" or SubCat2 = "B-cell Lymphoma-2 Inhibitor"
sort file.name asc
```

##### EGFR Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "EGFR Inhibitors" or SubCat2 = "EGFR Inhibitors"
sort file.name asc
```

##### Hedgehog Pathway Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Hedgehog Pathway Inhibitors" or SubCat2 = "Hedgehog Pathway Inhibitors"
sort file.name asc
```

##### Histone Deacetylase Inhibitors 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Histone Deacetylase Inhibitors" or SubCat2 = "Histone Deacetylase Inhibitors"
sort file.name asc
```

##### IDH Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "IDH Inhibitors" or SubCat2 = "IDH Inhibitors"
sort file.name asc
```

##### Kinase Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Kinase Inhibitors" or SubCat2 = "Kinase Inhibitors"
sort file.name asc
```

##### Anti-VEGF
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Anti-VEGF" or SubCat2 = "Anti-VEGF"
sort file.name asc
```

##### Tyrosine Kinase-EGFR Inhibitors 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Tyrosine Kinase/EGFR Inhibitors" or SubCat2 = "Tyrosine Kinase/EGFR Inhibitors"
sort file.name asc
```

##### Nuclear Export Inhibitor 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Nuclear Export Inhibitor" or SubCat2 = "Nuclear Export Inhibitor"
sort file.name asc
```

##### PARP Enzyme Inhibitors 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "PARP Enzyme Inhibitors" or SubCat2 = "PARP Enzyme Inhibitors"
sort file.name asc
```

##### Proteasome Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Proteasome Inhibitors" or SubCat2 = "Proteasome Inhibitors"
sort file.name asc
```

##### Protein Synthesis Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Protein Synthesis Inhibitors" or SubCat2 = "Protein Synthesis Inhibitors"
sort file.name asc
```

##### Immunomodulators—Angiogenesis Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Immunomodulators—Angiogenesis Inhibitors" or SubCat2 = "Immunomodulators—Angiogenesis Inhibitors"
sort file.name asc
```

##### Immunity Vaccines
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Immunity Vaccines" or SubCat2 = "Immunity Vaccines"
sort file.name asc
```

##### Adoptive Cell Therapy 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Checkpoint inhibitors]] or SecondarySubClass = [[Checkpoint inhibitors]] or ThirdSubClass = [[Checkpoint inhibitors]] and SubCat = "Adoptive Cell Therapy" or SubCat2 = "Adoptive Cell Therapy"
sort file.name asc
```
