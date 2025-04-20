---
DrugClass: "[[Antibacterial(That Disrupt the Bacterial Cell Wall)]]"
SubClass: "[[Penicillins]]"
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
Penicillins are contraindicated in clients with a history of hypersensitivity to penicillin or the [[Cephalosporins]]. 
Penicillins should be used cautiously in clients with renal disease, asthma, bleeding disorders, gastrointestinal (GI) disease, pregnancy ([[Preg Cat C]]) or lactation (may cause diarrhea or candidiasis in the infant), and history of allergies. Any indication of sensitivity is reason for caution.

### Side/Adverse Effects 
Gastrointestinal System reactions
- [[glossitis]] (inflammation of the [[Tongue]]) when given orally 
- [[Stomatitis]] (inflammation of the [[Mouth]]), dry [[Mouth]] 
- Gastritis 
- Nausea, vomiting 
- Diarrhea, abdominal pain 

Administration route reactions include pain at the injection site when given intramuscularly (IM) and irritation of the vein and phlebitis (inflammation of a vein) when given intravenously (IV). 

[[hypersensitivity reactions]] 
- A hypersensitivity (or allergic) reaction to a drug occurs in some individuals, especially those with a history of allergy to many substances. 
- Signs and Symptoms of Hypersensitivity to Penicillin and Other Antibiotics 
	- Skin rash 
	- [[urticaria]] (hives) 
	- Sneezing 
	- Wheezing 
	- Pruritus (itching) 
	- Bronchospasm (spasm of the [[bronchi]]) 
	- Laryngospasm (spasm of the [[Larynx]]) 
	- [[angioedema]] (also called angioneurotic edema)— swelling of the skin and mucous membranes, especially around and in the [[Mouth]] and throat 
	- Hypotension— can progress to shock 
	- Signs and symptoms resembling serum sickness— chills, [[Fever]], edema, joint and muscle pain, and malaise 

An anaphylactic reaction, which is a severe form of hypersensitivity, also can occur. Anaphylactic reactions occur more frequently after parenteral administration but can occur with oral use. This reaction is likely to be immediate and severe in susceptible individuals. Signs of anaphylactic reaction or shock include severe hypotension, loss of consciousness, and acute [[Respiratory]] distress. If not immediately treated, anaphylactic shock can be fatal. 

Once an individual is allergic to one penicillin, they are usually allergic to [[acute lymphoblastic leukemia]] of the penicillins. Those allergic to penicillin also have a higher incidence of allergy to the [[cephalosporins]]. Allergy to [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] in the same or related groups is called cross-sensitivity. For example, a person allergic to penicillin may also be sensitive to the [[Cephalosporins]]. Other Reactions 

Other more severe adverse reactions associated with penicillin include 
- hematopoietic ([[Blood]] cell) changes: 
- Anemia (low red [[Blood]] cell count) 
- [[thrombocytopenia]] (low platelet count) 
- [[leukopenia]] (low white [[Blood]] cell

### Drugs with subclass `= this.file.name` 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondarySubClass as "2nd Sub Class", ThirdSubClass as "3rd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and SubClass = [[Penicillins]] or SecondarySubClass = this.SubClass or ThirdSubClass = this.SubClass
sort file.name asc
```
