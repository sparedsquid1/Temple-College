---
DrugClass: "[[Antianginal and Vasodilating Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 35](kindle://book?action=open&asin=B09FRF11YJ&location=19375)"
Course: Pharmacology
Chapter: "35"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
Beta- and [[Calcium channel blockers]] are contraindicated in clients who are hypersensitive to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and those with sick sinus syndrome, second- or third-degree atrioventricular block (except with a functioning pacemaker) or hypotension (systolic pressure less than 90   mm Hg). Beta-blockers are contraindicated in clients with asthma or emphysema. When discontinuing the drug, beta-blockers should always be tapered slowly, not abruptly stopped. The [[Calcium channel blockers]] are used cautiously during pregnancy ([[Preg Cat C]]) and lactation. 

[[Nitrates]] are contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], severe anemia, closed-angle glaucoma, postural hypertension, early MI (sublingual form), head trauma, cerebral hemorrhage (may increase intracranial hemorrhage), allergy to adhesive (transdermal system), or constrictive pericarditis. Clients taking phosphodiesterase inhibitors ([[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] for erectile dysfunction [ED]) should not use [[Nitrates]]. 
[[Nitrates]] are used cautiously in clients with the following: 
- Severe hepatic or renal disease 
- Severe head trauma Hypothyroidism

### Side/Adverse Effects 
Adverse reactions to the blocking [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] used for prophylaxis, usually are not serious and rarely require discontinuation of the drug therapy (see Chapter 34 for specifics). Adverse reactions associated with the [[Nitrates]] include the following: 
- [[CNS]] ([[CNS]]) reactions, such as headache (may be severe and persistent), dizziness, weakness, and restlessness 
- Other body system reactions, such as hypotension, flushing (caused by dilation of small capillaries near the surface of the skin), and rash 

The [[Nitrates]] are available in various forms (e.g., sublingual, translingual spray, transdermal, and parenteral). Some adverse reactions are a result of the method of administration. For example, sublingual nitroglycerin may cause a local burning or tingling in the oral cavity. However, the client must be aware that an absence of this effect does not indicate a decrease in the drug’s potency. Contact dermatitis may occur from use of the transdermal delivery system. 

In many instances, the adverse reactions associated with the [[Nitrates]] lessen and often disappear with prolonged use of the drug. However, for some clients, these adverse reactions become severe, and the primary health care provider may lower the dose until symptoms subside. The dose may then be slowly increased if the lower dosage does not provide relief from the symptoms of angina. See the Summary Drug Table: Antianginal and Vasodilating [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] for more information.


### Subclasses

#### Nitrates
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Nitrates]] or SecondarySubClass = [[Nitrates]]
sort file.name asc
```

#### Miscellaneous Antianginal Agents
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Miscellaneous Antianginal Agents]] or SecondarySubClass = [[Miscellaneous Antianginal Agents]]
sort file.name asc
```

#### Calcium Channel Blockers Used for Anginal Issues
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Calcium Channel Blockers Used for Anginal Issues]] or SecondarySubClass = [[Calcium Channel Blockers Used for Anginal Issues]]
sort file.name asc
```

#### Agents Used for Pulmonary Arterial Hypertension (PAH)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[Agents Used for Pulmonary Arterial Hypertension (PAH)]] or SecondarySubClass = [[Agents Used for Pulmonary Arterial Hypertension (PAH)]]
sort file.name asc
```

#### PD5E Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Drug Class", SecondarySubClass as "2nd Sub Class"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where file.name != DrugClass and DrugClass = this.DrugClass or SecondaryDrugClass = this.DrugClass and SubClass = [[PD5E Inhibitors]] or SecondarySubClass = [[PD5E Inhibitors]]
sort file.name asc
```
