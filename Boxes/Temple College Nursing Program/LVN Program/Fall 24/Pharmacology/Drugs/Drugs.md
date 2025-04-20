---
tags:
  - MOCs
  - LVN
  - Pharmacology
SearchName: dextro
---
https://www.ncbi.nlm.nih.gov/

#### Drug Search
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", subclass as "Sub Class", file.mtime as "Last modified"
WHERE contains(file.folder, "Fall 24") and contains(lower(file.name), lower(this.SearchName)) or contains(lower(BrandName), lower(this.SearchName)) or contains(DrugClass, this.SearchName) or contains(subclass, this.SearchName) and this.SearchName != null
sort file.mtime desc
```

#### Alphabetical listing of drugs
##### A Drugs 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "a") or startswith(file.name, "A")
sort file.name asc
```

##### B Drugs
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "b") or startswith(file.name, "B")
sort file.name asc
```

##### C Drugs
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "c") or startswith(file.name, "C")
sort file.name asc
```

##### D Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "d") or startswith(file.name, "D")
sort file.name asc
```

##### E Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "e") or startswith(file.name, "E")
sort file.name asc
```

##### F Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "f") or startswith(file.name, "F")
sort file.name asc
```

##### G Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "g") or startswith(file.name, "G")
sort file.name asc
```

##### H Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "h") or startswith(file.name, "H")
sort file.name asc
```

##### I Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "i") or startswith(file.name, "I")
sort file.name asc
```

##### J Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "j") or startswith(file.name, "J")
sort file.name asc
```

##### K Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "k") or startswith(file.name, "K")
sort file.name asc
```

##### L Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "l") or startswith(file.name, "L")
sort file.name asc
```

##### M Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "m") or startswith(file.name, "M")
sort file.name asc
```

##### N Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "n") or startswith(file.name, "N")
sort file.name asc
```

##### O Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "o") or startswith(file.name, "O")
sort file.name asc
```

##### P Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "p") or startswith(file.name, "P")
sort file.name asc
```

##### Q Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "q") or startswith(file.name, "Q")
sort file.name asc
```

##### R Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "r") or startswith(file.name, "R")
sort file.name asc
```

##### S Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "s") or startswith(file.name, "S")
sort file.name asc
```

##### T Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "t") or startswith(file.name, "T")
sort file.name asc
```

##### U Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "u") or startswith(file.name, "U")
sort file.name asc
```

##### V Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "v") or startswith(file.name, "V")
sort file.name asc
```

##### W Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "w") or startswith(file.name, "W")
sort file.name asc
```

##### X Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "x") or startswith(file.name, "X")
sort file.name asc
```

##### Y Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "y") or startswith(file.name, "Y")
sort file.name asc
```

##### Z Drugs

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub", FourthDrugClass as "4th Class", FourthSubClass as "4th Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs"
where startswith(file.name, "z") or startswith(file.name, "Z")
sort file.name asc
```


