---
DrugClass: "[[Antidiabetic Drugs]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 40](kindle://book?action=open&asin=B09FRF11YJ&location=22730)"
Course: Pharmacology
Chapter: "40"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
Specific [[Insulin products]] are contraindicated when the client is hypoglycemic. Insulin is used cautiously in clients with renal or hepatic impairment and during pregnancy and lactation. The insulins are grouped in [[Preg Cat B]], except for [[insulin glargine]] and insulin aspart, which are in [[Preg Cat C]]. Insulin appears to inhibit milk production in lactating women and could interfere with breastfeeding. Lactating women may require adjustment in insulin dose and diet.


### Side/Adverse Effects 
The two major adverse reactions seen with insulin product administration are hypoglycemia (low [[Blood]] glucose or sugar level) and hyperglycemia (elevated [[Blood]] glucose or sugar level). The symptoms of hypoglycemia and hyperglycemia are listed in Table 40.1.
**Hypoglycemia** may occur when there is too much insulin in the bloodstream in relation to the available glucose (hyperinsulinism). Hypoglycemia may occur when: 
- The client eats too little food or goes too long between meals.
- The client has drastically increased demands (activity or illness). 
- The insulin given is incorrectly measured and is greater than that prescribed. 

**Hyperglycemia** may occur if there is too little insulin in the bloodstream in relation to the available glucose (hypoinsulinism). Hyperglycemia may occur when: 
- The client eats too much food. 
- Too little or no insulin is given. 
- The client experiences emotional stress, infection, surgery, pregnancy, or an acute illness. 

An individual can also become insulin resistant because antibodies develop against insulin. These clients have impaired receptor function and become so unresponsive to insulin that the dose requirement may be in excess of 500 units/ day, rather than the usual 40 to 60 units/ day. A long-acting glargine (insulin analogue) marketed as Toujeo contains 300 units/ mL. This high-potency insulin product in a concentrated form is used for clients requiring more than 200 units/ day.

### SubClasses
#### Insulin/ Insulin Analogue Preparations
##### Short- and Rapid-Acting Insulins
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Short- and Rapid-Acting Insulins]] or SecondarySubClass = [[Short- and Rapid-Acting Insulins]]
sort file.name asc
```

##### Intermediate-Acting Insulins
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Intermediate-Acting Insulins]] or SecondarySubClass = [[Intermediate-Acting Insulins]]
sort file.name asc
```

##### Long-Acting Insulins (All Insulin Analogues)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Long-Acting Insulins (All Insulin Analogues)]] or SecondarySubClass = [[Long-Acting Insulins (All Insulin Analogues)]]
sort file.name asc
```

##### Combined Insulins (Long-Short Acting)
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Combined Insulins (Long-Short Acting)]] or SecondarySubClass = [[Combined Insulins (Long-Short Acting)]]
sort file.name asc
```

#### Oral Antidiabetic Drugs (Hypoglycemics) and Other Agents
##### Biguanides
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Biguanides]] or SecondarySubClass = [[Biguanides]]
sort file.name asc
```

##### Glucagon-Like Peptide-1 Agonists
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Glucagon-Like Peptide-1 Agonists]] or SecondarySubClass = [[Glucagon-Like Peptide-1 Agonists]]
sort file.name asc
```

##### Sodium-Glucose Linked Transporter-2 Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Sodium-Glucose Linked Transporter-2 Inhibitors]] or SecondarySubClass = [[Sodium-Glucose Linked Transporter-2 Inhibitors]]
sort file.name asc
```

##### Dipeptidyl Peptidase-4 Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Dipeptidyl Peptidase-4 Inhibitors]] or SecondarySubClass = [[Dipeptidyl Peptidase-4 Inhibitors]]
sort file.name asc
```

##### Thiazolidinediones
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Thiazolidinediones]] or SecondarySubClass = [[Thiazolidinediones]]
sort file.name asc
```

##### Alpha-Glucosidase Inhibitors
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Alpha-Glucosidase Inhibitors]] or SecondarySubClass = [[Alpha-Glucosidase Inhibitors]]
sort file.name asc
```

##### Amylinomimetic
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Amylinomimetic]] or SecondarySubClass = [[Amylinomimetic]]
sort file.name asc
```

##### Sulfonylureas
###### Third Generation
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Sulfonylureas]] or SecondarySubClass = [[Sulfonylureas]] and SubCat = "Third Generation"
sort file.name asc
```

###### Second Generation
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Sulfonylureas]] or SecondarySubClass = [[Sulfonylureas]] and SubCat = "Second Generation"
sort file.name asc
```

###### First Generation
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Sulfonylureas]] or SecondarySubClass = [[Sulfonylureas]] and SubCat = "First Generation"
sort file.name asc
```

##### Meglitinides
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Meglitinides]] or SecondarySubClass = [[Meglitinides]]
sort file.name asc
```

##### Glucose-Elevating Agents
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Glucose-Elevating Agents]] or SecondarySubClass = [[Glucose-Elevating Agents]]
sort file.name asc
```


