---
DrugClass: "[[Antibacterial(That Disrupt the Bacterial Cell Wall)]]"
SubClass: "[[Cephalosporins]]"
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Course: Pharmacology
Chapter:
---
### Drug Class 
`= this.file.name`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
[[Carbapenems]], [[aztreonam]], and [[telavancin]] are contraindicated in clients who are allergic to cephalosporins and [[Penicillins]] and in clients with renal failure. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are not recommended in children younger than 3 months or for women during pregnancy ([[Preg Cat B]]) or lactation. [[Carbapenems]] are used cautiously in clients with [[CNS]] ([[CNS]]) disorders, seizure disorders, or renal or hepatic failure. The excretion of [[Carbapenems]] is inhibited when the drug is administered to a client also taking [[probenecid]]. [[aztreonam]] should be used cautiously in clients with renal or hepatic impairment. 
[[vancomycin]] should not be used in clients with a known hypersensitivity to the drug and is used cautiously in clients with renal or hearing impairment and during pregnancy ([[Preg Cat C]]) and lactation. When administered with other ototoxic and nephrotoxic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], additive effects may occur. In other words, one drug alone may not cause the hearing or kidney problem, but when another drug with similar adverse effects is given with [[vancomycin]], the client is more likely to experience a problem. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] should be used with caution in clients undergoing anticoagulant therapy because of an increased risk of bleeding.


### Side/Adverse Effects 
Gastrointestinal System Reactions 
- Nausea 
- Vomiting 
- Diarrhea 
Other Reactions 
- Headache 
- Dizziness 
- Malaise (general discomfort)
- Heartburn
- [[Fever]]
- [[nephrotoxicity]] (toxic to kidneys) 
- Hypersensitivity (allergic) reactions— may occur with administration of the cephalosporins and may range from mild to life-threatening. Mild [[hypersensitivity reactions]] include pruritus, [[urticaria]], and skin rashes; the more serious reactions include Stevens– Johnson syndrome and hepatic and renal dysfunction 
- [[aplastic anemia]] (deficient red [[Blood]] cell production) 
- [[toxic epidermal necrolysis]] (death of the epidermal layer of the skin)
- Positive direct Coombs test ([[cefepime]])


### Drugs with subclass `= this.file.name` 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "Secondary Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and SubClass = [[Cephalosporins]]
sort file.name asc
```
