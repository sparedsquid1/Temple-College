---
DrugClass: "[[Nonopioid Analgesics - Nonsteroidal Anti-inflammatory Drugs]]"
BrandName: 
DrugClassContra: "[[Nonsterodial Anti-inflammatory Drugs#Contraindications]]"
DrugClassAdverse: "[[Nonsterodial Anti-inflammatory Drugs#Adverse Reactions]]"
SubClass: "[[Nonsterodial Anti-inflammatory Drugs]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
aliases:
  - NSAIDs
  - NSAID
---
### Adverse Reactions 
**Gastrointestinal System Reactions** 
- Nausea, vomiting, [[Dyspepsia]] 
- Anorexia, dry [[Mouth]] 
- Diarrhea, constipation 
- Epigastric pain, indigestion, abdominal distress or discomfort, bloating 
- Intestinal ulceration, [[Stomatitis]] 
- Jaundice 

**[[CNS]] Reactions** 
- Dizziness, [[anxiety]], lightheadedness, vertigo 
- Headache
- Drowsiness, [[somnolence]] (sleepiness), insomnia
- Confusion, [[Depression]]
- Stroke, psychic disturbances 

**[[Cardiovascular system]] Reactions**
- Decrease or increase in [[Blood]] pressure
- Congestive [[Heart]] failure, cardiac arrhythmias 
- Myocardial infarction 

**Renal System Reactions**
- Polyuria (excessive urination), dysuria (painful urination), oliguria (reduced urine output) 
- Hematuria ([[Blood]] in the urine), [[cystitis]] 
- Elevated [[Blood]] urea nitrogen 
- Acute renal failure in those with impaired renal function

**Hematologic System Reactions**
- [[pancytopenia]] (reduction in [[Blood]] cell components), [[thrombocytopenia]] (reduced platelet count) 
- [[neutropenia]] (abnormally few [[Neutrophils]]), eosinophilia (low eosinophil count), [[leukopenia]] (reduced white [[Blood]] cell count), agranulocytosis (reduced granulocyte count) 
- [[aplastic anemia]] 

**[[Integumentary System]] Reactions** 
- Rash, erythema (redness), irritation, skin eruptions
- Ecchymosis (subcutaneous hemorrhage), purpura (excessive skin hemorrhage causing red-purple patches under the skin) 
- Exfoliative dermatitis, [[Stevens–Johnson syndrome]] 

**Metabolic/[[Endocrine System]] Reactions** 
- Decreased appetite, weight increase or decrease 
- Flushing, sweating
- Menstrual disorders, vaginal bleeding 
- Hyperglycemia or hypoglycemia (high or low [[Blood]] sugar) 

**Sensory and Other Reactions** 
- Taste change
- [[rhinitis]] (runny nose)
- Tinnitus (ringing in the ears)
- Visual disturbances, blurred or diminished [[Vision]], diplopia (double [[Vision]]), swollen or irritated eyes, [[photophobia]] (sensitivity to light), reversible loss of color [[Vision]] 
- Thirst, [[Fever]], chills 
- Vaginitis
### Contraindications
The NSAIDs are contraindicated in clients with known hypersensitivity. There is a cross-sensitivity to other NSAIDs, meaning if a client is allergic to one NSAID, there is an increased risk of an allergic reaction with any other NSAID. Hypersensitivity to [[aspirin (acetylsalicylic acid)]] is a contraindication for [[acute lymphoblastic leukemia]] NSAIDs. In general, NSAIDs are contraindicated during the third [[trimester]] of pregnancy and during lactation. Also, they are not to be used for postoperative pain following CABG surgery. Some NSAIDs are not used to treat rheumatoid arthritis or [[Osteoarthritis]]; these include [[ketorolac]], [[mefenamic]], and [[meloxicam]]. [[celecoxib]] is contraindicated in clients who are allergic to sulfonamides or have a history of cardiac disease or stroke. [[ibuprofen]] is contraindicated in those who have hypertension, peptic ulceration, or GI bleeding. Arthrotec combines [[diclofenac]] and [[misoprostol]] (abortifacient), and should not be taken by pregnant women.
### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
