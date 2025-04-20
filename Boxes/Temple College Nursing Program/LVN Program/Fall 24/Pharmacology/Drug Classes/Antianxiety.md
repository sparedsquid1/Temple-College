---
DrugClass: "[[Antianxiety]]"
BrandName: 
SubClass: 
Chapter: "19"
KindleLinkChap: "[Chapter 19](kindle://book?action=open&asin=B09FRF11YJ&location=10180)"
KindleLink: 
tags:
  - Drug
---

### Drug class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
Do not administer antianxiety [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] to clients with known hypersensitivity, psychoses, and acute narrow-angle glaucoma. The [[Benzodiazepines]] are contraindicated during pregnancy ([[Preg Cat D]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]) and labor. Reports of floppy infant syndrome manifested by sucking difficulties, lethargy, and hypotonia have been seen in the newborn of a mother using [[Benzodiazepines]]. Lactating women should also avoid the [[Benzodiazepines]] because of the effect on the infant (lethargy and weight loss). Owing to a specific enzyme reaction, grapefruit or its juice should not be taken if the client is on [[Buspirone]] and [[diazepam]]. [[Buspirone]] is a [[Preg Cat B]] drug, and [[hydroxyzine]] is a [[Preg Cat C]] drug. Their safety is still questionable because adequate studies have not been performed in pregnant women. [[acute lymphoblastic leukemia]] of these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated when clients are in a coma or shock and if the vital signs of the client in acute alcoholic intoxication are low.

### Interactionsse Effects
Frequent, early reactions include:
- Mild drowsiness or sedation 
- Light-headedness or dizziness 
- Headache 
Other adverse body system reactions include: 
- Lethargy, apathy, fatigue 
- Disorientation 
- Anger 
- Restlessness 
- Nausea, constipation or diarrhea, dry [[Mouth]] 
- Visual disturbances

### Subclasses
#### Benzodiazepines
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass and SubClass = [[Benzodiazepines]] and DrugClass = [[Antianxiety]]
sort file.name asc
```


#### Nonbenzodiazepines
```dataview
	table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass and SubClass = [[Nonbenzodiazepines]] or SecondarySubClass = [[Nonbenzodiazepines]] and DrugClass = [[Antianxiety]] or SecondaryDrugClass = [[Antianxiety]]
sort file.name asc
```

#### Benzodiazepine Antidote
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
where file.name != DrugClass and DrugClass and SubClass = [[Benzodiazepine Antidote]] and DrugClass = [[Antianxiety]]
sort file.name asc
```
