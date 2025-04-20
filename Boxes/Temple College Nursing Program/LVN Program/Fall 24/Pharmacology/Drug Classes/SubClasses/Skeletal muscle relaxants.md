---
DrugClass: "[[Skeletal Muscle, Bone, and Joint Disorder Drugs]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Skeletal muscle relaxants]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags: []
---
### Adverse Reactions 
Drowsiness is the most common reaction seen with the use of skeletal muscle relaxants. Additional adverse reactions are given in the Summary Drug Table: [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] Used to Treat Musculoskeletal, Bone, and Joint Disorders. Some of the adverse reactions that may occur with the administration of [[diazepam]] include drowsiness, sedation, sleepiness, lethargy, constipation or diarrhea, bradycardia or tachycardia, and rash.

### Contraindications
Skeletal muscle relaxants are contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. [[baclofen]] is contraindicated in skeletal muscle spasms caused by rheumatic disorders. [[carisoprodol]] is contraindicated in clients with a known hypersensitivity to [[meprobamate]]. Cyclobenzaprine is contraindicated in clients with a recent myocardial infarction, cardiac conduction disorders, and hyperthyroidism. In addition, cyclobenzaprine is contraindicated within 14   days of the administration of a [[Monoamine]] oxidase inhibitor ([[MAOI]]). Oral [[dantrolene]] is contraindicated during lactation and in clients with active hepatic disease and muscle spasm caused by rheumatic disorders.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
