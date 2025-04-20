### Contraindications

### Adverse reactions

### Drugs with subclass 2nd Gen

```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = [[2nd Gen]] or SecondarySubClass = [[2nd Gen]]
sort file.name asc
```
