---
DrugClass: "[[Antiepileptics]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 28](kindle://book?action=open&asin=B09FRF11YJ&location=14677)"
Course: Pharmacology
Chapter: "28"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
[[acute lymphoblastic leukemia]] categories of antiepileptics are contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. [[phenytoin]] is contraindicated in clients with sinus bradycardia, sinoatrial block, [[Adams–Stokes syndrome]], and second- and third-degree atrioventricular block; it also is contraindicated during pregnancy and lactation ([[ethotoin]] and [[phenytoin]] are [[Preg Cat D]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]). [[ethotoin]] (Peganone) is contraindicated in clients with hepatic abnormalities. The [[succinimides]] are contraindicated in clients with bone marrow [[Depression]] or hepatic or renal impairment. A higher incidence of [[systemic lupus erythematosus]] has been found in clients taking [[Succinimides]]. 

The drug category oxazolidinedione has been associated with serious adverse reactions and fetal malformations; therefore, the last drug in that category was taken off the market. [[Carbamazepine]] should not be given within 14 days of [[Monoamine]] oxidase inhibitor antidepressants. 

[[carbamazepine]] is contraindicated in clients with bone marrow [[Depression]] or hepatic or renal impairment and during pregnancy ([[Preg Cat D]]). Valproic acid (Depakote) is not administered to clients with renal impairment or during pregnancy ([[Preg Cat D]]). [[oxcarbazepine]] (Trileptal), a nonspecified antiepileptic, may exacerbate [[Dementia]].


### Side/Adverse Effects 
At least 25% of those who experience adverse reactions will stop taking their medication (Kwan, 2000). Clients report side effects are intolerable. Adverse reactions that may occur with the administration of an antiepileptic drug include the following. 

[[CNS]] Reactions 
- Drowsiness, weakness, dizziness 
- Headache, [[somnolence]] 
- Nystagmus (constant, involuntary movement of the eyeball) 
- Ataxia (loss of control of voluntary movements, especially gait) 
- Slurred speech 

Gastrointestinal System Reactions 
- Nausea, vomiting 
- Anorexia 
- Constipation, diarrhea 
- Gingival hyperplasia (overgrowth of gum tissue) 
- Acute [[Liver]] failure (with the drug [[felbamate]])

Other Reactions 
- Skin rashes, pruritus, [[urticaria]] 
- Serious skin reactions, such as Stevens– Johnson syndrome, have been associated with the use of [[lamotrigine]] (Lamictal) 
- Hematologic changes, such as [[pancytopenia]] (decrease in [[acute lymphoblastic leukemia]] the cellular components of the [[Blood]]), [[leukopenia]], [[aplastic anemia]], and [[thrombocytopenia]], have occurred with administration of selected [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], including [[carbamazepine]] (Tegretol) and [[felbamate]] (Felbatol). See the Summary Drug Table: Antiepileptics for more information.

### Subclasses
#### Hydantoins
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and subclass = [[Hydantoins]] or SecondarySubClass = [[Hydantoins]]
sort file.name asc
```

#### Carboxylic acid derivatives
``` dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and subclass = [[Carboxylic acid derivatives]] or SecondarySubClass = [[Carboxylic acid derivatives]]
sort file.name asc
```

#### Hydantoins
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and subclass = [[Hydantoins]] or SecondarySubClass = [[Hydantoins]]
sort file.name asc
```

#### Benzodiazepines
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and subclass = [[Benzodiazepines]] or SecondarySubClass = [[Benzodiazepines]]
sort file.name asc
```

#### Nonspecified drugs
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and subclass = [[Nonspecified drugs]] or SecondarySubClass = [[Nonspecified drugs]]
sort file.name asc
```

