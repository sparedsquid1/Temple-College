---
DrugClass: "[[Lower Gastrointestinal System Drugs]]"
BrandName: 
DrugClassContra: "[[Aminosalicylates#Contraindications]]"
DrugClassAdverse: "[[Aminosalicylates#Adverse Reactions]]"
SubClass: "[[Aminosalicylates]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Because these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are topical anti-inflammatory [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], the most common adverse reactions happen in the GI system and include abdominal pain, nausea, and diarrhea. Other general adverse reactions include headache, dizziness, [[Fever]], and weakness.


### Contraindications
Aminosalicylates are contraindicated in clients with a known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] or salicylate-containing [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. In addition, these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients who have hypersensitivity to sulfonamides and sulfites or intestinal obstruction, and in children younger than 2 years. Aminosalicylates are [[Preg Cat B]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] (except [[olsalazine]], which is in [[Preg Cat C]]); [[acute lymphoblastic leukemia]] are used with caution during pregnancy and lactation (safety has not been established).

### Drugs with subclass `= this.file.name`
#### Aminosalicylates (5-ASA)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Aminosalicylates (5-ASA)"
sort file.name asc
```

##### Biologics for Bowel Disorders
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Biologics for Bowel Disorders"
sort file.name asc
```

##### Miscellaneous Drugs for Bowel Disorders
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubCat = "Miscellaneous Drugs for Bowel Disorders"
sort file.name asc
```
