### Contraindications

### Adverse Reactions 

### Drugs with subclass benzodiazepines
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = [[Benzodiazepines]] or SecondarySubClass = [[Benzodiazepines]]
sort file.name asc
```
