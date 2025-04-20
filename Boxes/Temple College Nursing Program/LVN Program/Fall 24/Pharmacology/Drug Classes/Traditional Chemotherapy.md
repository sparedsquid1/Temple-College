---
DrugClass: "[[Traditional Chemotherapy]]"
SubClass: 
DrugClassContra: 
DrugClassAdverse: 
BrandName: 
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: "[Chapter 50](kindle://book?action=open&asin=B09FRF11YJ&location=29267)"
Course: Pharmacology
Chapter: "50"
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
tags:
  - Drug
---
### Drug Class 
`= this.DrugClass`
	`= this.DrugClass.KindleLinkChap`

### Contraindications
The information discussed in this section is general, and the contraindications, precautions, and interactions for each traditional chemotherapy drug vary. The chemotherapy nurse should consult appropriate sources before administering any traditional chemotherapy drug. 

Traditional chemotherapy [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are contraindicated in clients with [[leukopenia]], [[thrombocytopenia]], anemia (reduced red [[Blood]] cells), serious infections, serious renal disease, or known hypersensitivity to the drug, and during pregnancy (see [[Box 50.2]] for pregnancy classifications of selected traditional chemotherapy [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]) or lactation.

Traditional chemotherapy [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are used cautiously in clients with renal or hepatic impairment, active infection, or other debilitating illnesses, or in those who have recently completed treatment with other traditional chemotherapy [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] or radiation therapy.


### Side/Adverse Effects 
Adverse reactions to traditional chemotherapy [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] can be viewed in three different time frames: immediate (during the actual administration), during therapy cycles, and long term (many years later, during survivorship). 

Immediate adverse reactions occur as a result of administration. These include nausea and vomiting from highly emetic [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] or the potential of intravenous (IV) [[extravasation]] (leakage into the surrounding tissues) of irritating solutions. Traditional chemotherapy [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] are potentially toxic, and their administration is often associated with serious adverse reactions. At times, some of these adverse effects are allowed because the only alternative is to stop treatment of cancer. A treatment plan is developed that will prevent, lessen, or treat most or [[acute lymphoblastic leukemia]] of the symptoms of a specific adverse reaction. An example of prevention is giving an antiemetic before administering a traditional chemotherapy drug known to cause severe nausea and vomiting. [[Box 50.1]] provides a list of those [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] most likely to cause nausea and vomiting.

An example of a treatment for an adverse reaction is the administration of an antiemetic and IV fluids with [[Boxes/Temple College Nursing Program/Pre & Co Reqs/Summer 23/Note holder/A & P II/Electrolytes|Electrolytes]] when severe vomiting is anticipated. When the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] listed in [[Box 50.1]] are given, antiemetic protocols should always be followed to reduce adverse reactions. Some [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], such as platinum-based agents, may damage certain organs during administration. Again, prechemotherapy protocols for IV fluid administration are initiated to prevent adverse reactions. 

Some of these reactions are dose-dependent; that is, their occurrence is more common or their intensity is more severe when multiple doses (or cycles) are used. Because the traditional chemotherapy [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] affect cancer cells and rapidly proliferating normal cells (i.e., cells in the bone marrow, GI tract, reproductive tract, and hair follicles), adverse reactions occur as the result of action on these cells. 

Adverse reactions common to many of the traditional chemotherapy [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] include bone marrow suppression (anemia, [[leukopenia]], [[thrombocytopenia]]), [[Stomatitis]] (inflammation of lining tissues), diarrhea, and hair loss. The most common reactions are [[leukopenia]] (reduced white [[Blood]] cells) and [[thrombocytopenia]] (reduced platelets), which may cause cycles of chemotherapy to be delayed until [[Blood]] cell counts can be raised. Some [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], especially the alkaloids, affect the nervous system. These adverse reactions can range from a peripheral tingling sensation to [[hand and foot syndrome]] (tiny capillary leaks in extremities, causing symptoms from skin color changes to numbness). 

Because the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] used to treat cancer are effective, many people are living with the disease either cured or in remission. Some of the adverse reactions to traditional chemotherapy [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] can have long-lasting effects. These include damage to the gonads, causing fertility problems, and to other specific organ systems, leading to cardiac, pulmonary, or neurologic problems. In addition, secondary cancers like [[Leukemia]] can be caused by the original cancer treatment. These problems are listed in the Summary Drug Table: Traditional Chemotherapy [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]]. Appropriate references should be consulted when administering these [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], because there are a variety of uses and dose ranges and, in some instances, many adverse reactions.

### SubClasses
#### Cell cycle–specific agents 
##### Plant Alkaloids
###### vinca alkaloids
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– specific agents]] or SecondarySubClass = [[Cell cycle– specific agents]] or ThirdSubClass = [[Cell cycle– specific agents]] and SubCat = "vinca alkaloids" or SubCat2 = "vinca alkaloids"
sort file.name asc
```

###### Taxanes
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– specific agents]] or SecondarySubClass = [[Cell cycle– specific agents]] or ThirdSubClass = [[Cell cycle– specific agents]] and SubCat = "Taxanes" or SubCat2 = "Taxanes"
sort file.name asc
```

###### Podophyllotoxins
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– specific agents]] or SecondarySubClass = [[Cell cycle– specific agents]] or ThirdSubClass = [[Cell cycle– specific agents]] and SubCat = "Podophyllotoxins" or SubCat2 = "Podophyllotoxins"
sort file.name asc
```

###### Camptothecin Analogs
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– specific agents]] or SecondarySubClass = [[Cell cycle– specific agents]] or ThirdSubClass = [[Cell cycle– specific agents]] and SubCat = "Camptothecin Analogs" or SubCat2 = "Camptothecin Analogs"
sort file.name asc
```

###### Antimetabolites
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– specific agents]] or SecondarySubClass = [[Cell cycle– specific agents]] or ThirdSubClass = [[Cell cycle– specific agents]] and SubCat = "Antimetabolites" or SubCat2 = "Antimetabolites"
sort file.name asc
```

###### Miscellaneous Agents
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– specific agents]] or SecondarySubClass = [[Cell cycle– specific agents]] or ThirdSubClass = [[Cell cycle– specific agents]] and SubCat = "Miscellaneous Agents" or SubCat2 = "Miscellaneous Agents"
sort file.name asc
```

#### Cell cycle–nonspecific agents
##### Alkylating Drugs
###### nitrogen mustard derivatives
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "nitrogen mustard derivatives" or SubCat2 = "nitrogen mustard derivatives"
sort file.name asc
```

###### Ethyleneimines
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "Ethyleneimines" or SubCat2 = "Ethyleneimines"
sort file.name asc
```

###### Alkyl Sulfonate
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "Alkyl Sulfonate" or SubCat2 = "Alkyl Sulfonate"
sort file.name asc
```

###### Hydrazines
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "Hydrazines" or SubCat2 = "Hydrazines"
sort file.name asc
```

###### Nitrosoureas
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "Nitrosoureas" or SubCat2 = "Nitrosoureas"
sort file.name asc
```

###### Platinum-Based Drugs
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "Platinum-Based Drugs" or SubCat2 = "Platinum-Based Drugs"
sort file.name asc
```

###### Antibiotics
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "Antibiotics" or SubCat2 = "Antibiotics"
sort file.name asc
```

##### Miscellaneous Agents 
###### dna inhibitor
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "dna inhibitor" or SubCat2 = "dna inhibitor"
sort file.name asc
```

###### adrenocortical inhibitor 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "adrenocortical inhibitor" or SubCat2 = "adrenocortical inhibitor"
sort file.name asc
```

###### enzymes
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "enzymes" or SubCat2 = "enzymes"
sort file.name asc
```

###### antimicrotubule agents 
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "antimicrotubule agents" or SubCat2 = "antimicrotubule agents"
sort file.name asc
```

###### retinoids
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "2nd Class", SecondarySubClass as "2nd Sub", ThirdDrugClass as "3rd Class", ThirdSubClass as "3rd Sub"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
Where file.name != this.DrugClass and SubClass = [[Cell cycle– nonspecific agents]] or SecondarySubClass = [[Cell cycle– nonspecific agents]] or ThirdSubClass = [[Cell cycle– nonspecific agents]] and SubCat = "retinoids" or SubCat2 = "retinoids"
sort file.name asc
```
