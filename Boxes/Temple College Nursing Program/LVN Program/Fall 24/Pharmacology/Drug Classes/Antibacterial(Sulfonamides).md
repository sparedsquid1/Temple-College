---
DrugClass: "[[Antibacterial(Sulfonamides)]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 6](kindle://book?action=open&asin=B09FRF11YJ&location=3015)"
Course: Pharmacology
Chapter: "06"
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`
[[Pharmacology Chapt 6 with audio.pptx]]
### Contraindications
The sulfonamides are contraindicated in clients with hypersensitivity to the sulfonamides, during lactation, and in children younger than 2 years. The sulfonamides are not used near the end (at term) of pregnancy ([[Preg Cat D]]). If the sulfonamides are given near the end of pregnancy, significantly high [[Blood]] levels of the drug may occur, causing jaundice or hemolytic anemia in the neonate. In addition, the sulfonamides are not used for infections caused by group A beta-hemolytic (β-hemolytic) streptococci because the sulfonamides have not been shown to be effective in preventing the complications of rheumatic [[Fever]] or glomerulonephritis.

### Side/Adverse Effects 
The sulfonamides are capable of causing a variety of adverse reactions. Some of these are serious or potentially serious; others are mild. Anorexia (loss of appetite) is an example of a mild adverse reaction. An example of a serious reaction, [[Stevens–Johnson syndrome]], is explained in the Nursing Alert.

### Subclasses

#### Single Agents 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
	where file.name != DrugClass and DrugClass = [[Antibacterial(Sulfonamides)]] and SubClass = [[Single Agents]] or SecondarySubClass = [[Single Agents]] or ThirdSubClass = [[Single Agents]]
sort file.name asc
```

#### Topical Sulfonamide Preparations
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub" 
	where file.name != DrugClass and DrugClass = [[Antibacterial(Sulfonamides)]] and SubClass = [[Topical Sulfonamide Preparations]] or SecondarySubClass = [[Topical Sulfonamide Preparations]] or ThirdSubClass = [[Topical Sulfonamide Preparations]]
sort file.name asc
```

#### Urinary Anti-Infective Combinations
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub" 
	where file.name != DrugClass and DrugClass = [[Antibacterial(Sulfonamides)]] and SubClass = [[Urinary Anti-Infective Combinations]] or SecondarySubClass = [[Urinary Anti-Infective Combinations]] or ThirdSubClass = [[Urinary Anti-Infective Combinations]]
sort file.name asc
```
