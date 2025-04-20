---
DrugClass: "[[Antibacterial(That Disrupt the Bacterial Cell Wall)]]"
SubClass: "[[Carbapenems]]"
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
Carbapenems, [[aztreonam]], and [[telavancin]] are contraindicated in clients who are allergic to [[Cephalosporins]] and [[Penicillins]] and in clients with renal failure. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are not recommended in children younger than 3   months or for women during pregnancy ([[Preg Cat B]]) or lactation. Carbapenems are used cautiously in clients with [[CNS]] ([[CNS]]) disorders, seizure disorders, or renal or hepatic failure. The excretion of carbapenems is inhibited when the drug is administered to a client also taking [[probenecid]]. [[aztreonam]] should be used cautiously in clients with renal or hepatic impairment. [[vancomycin]] should not be used in clients with a known hypersensitivity to the drug and is used cautiously in clients with renal or hearing impairment and during pregnancy ([[Preg Cat C]]) and lactation. When administered with other ototoxic and nephrotoxic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], additive effects may occur. In other words, one drug alone may not cause the hearing or kidney problem, but when another drug with similar adverse effects is given with [[vancomycin]], the client is more likely to experience a problem. These [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] should be used with caution in clients undergoing anticoagulant therapy because of an increased risk of bleeding.

### Side/Adverse Effects 
The most common adverse reactions with these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] include nausea, vomiting, diarrhea, and rash. As with many other anti-infectives, there is a risk of [[pseudomembranous colitis]] (see Chapter 9). Assess stools for [[Blood]] when the client has diarrhea. Carbapenems also can cause an abscess or phlebitis at the injection site. An abscess is suspected if the injection site appears red or is tender and warm to the touch. Tissue sloughing at the injection site also may occur. [[nephrotoxicity]] (damage to the kidneys) and [[ototoxicity]] (damage to the organs of hearing) may be seen with the administration of [[vancomycin]] especially in clients with pre-existing kidney disease. Additional adverse reactions include chills, [[Fever]], [[urticaria]], and sudden fall in [[Blood]] pressure with parenteral administration. For more information, see Summary Drug Table: Anti-infective [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] That Inhibit Cell Wall Synthesis.


```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "Secondary Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and SubClass = [[Carbapenems]] or SecondarySubClass = [[Carbapenems]]
sort file.name asc
```
