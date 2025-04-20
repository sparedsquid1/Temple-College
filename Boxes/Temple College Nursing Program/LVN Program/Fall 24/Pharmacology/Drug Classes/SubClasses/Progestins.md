---
DrugClass: "[[Male and Female Hormones]]"
BrandName: 
DrugClassContra: 
DrugClassAdverse: 
SubClass: "[[Progestins]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
Administration of progestins by any route may result in many adverse reactions, although the incidence and intensity of these reactions vary. Progestin administration may result in the following: 
- Breakthrough bleeding, spotting, change in menstrual [[flow]], amenorrhea 
- Breast tenderness, edema, weight increase or decrease 
- Acne, chloasma or melasma, insomnia, mental [[Depression]] 

In addition to the adverse reactions seen with progestins, the use of a levonorgestrel implant system may result in bruising after insertion, scar tissue formation at the site of insertion, and hyperpigmentation at the implant site. The use of [[medroxyprogesterone]] contraceptive injection may result in the same adverse reactions as those associated with administration of any progestin.

### Contraindications
[[estrogen]] and progestin therapy is contraindicated in clients with known hypersensitivity to the [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]], breast cancer (except for metastatic disease), [[estrogen]]-dependent neoplasms, undiagnosed abnormal genital bleeding, and thromboembolic disorders. The progestins also are contraindicated in clients with cerebral hemorrhage or impaired [[Liver]] function. Both the [[Estrogens]] and progestins are classified as [[Preg Cat X]] [[Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs/Drugs|Drugs]] and are contraindicated during pregnancy. 

[[Estrogens]] are used cautiously in clients with [[Gallbladder]] disease, hypercalcemia (may lead to severe hypercalcemia in clients with breast cancer and bone metastasis), cardiovascular disease, and [[Liver]] impairment. Cardiovascular complications are greater in women who smoke and use [[estrogen]]. Progestins are used cautiously in clients with a history of migraine headaches, epilepsy, asthma, and cardiac or renal impairment. The FDA has issued concerns about the increased risk of birth control pills containing drospirenone. Research indicates chances of developing a [[Blood]] clot may be double that of other pills without drospirenone. Those most at risk are women with high [[Blood]] pressure or cholesterol, diabetes, or are overweight. Women are encouraged to discuss their individual risk for [[Blood]] clots with their primary health care provider before starting birth control pills with drospirenone (Casciotti et al., 2015).

The warnings associated with the use of oral contraceptives, notably the combined drug contraceptives, are the same as those for the [[Estrogens]] and progestins and include cigarette smoking (especially those older than 35   years of age), which increases the risk of cardiovascular side effects, such as venous and arterial thromboembolism, myocardial infarction, and thrombotic and hemorrhagic stroke. Also reported with oral contraceptive use are hepatic adenomas and other tumors, visual disturbances, [[Gallbladder]] disease, hypertension, and fetal abnormalities.



### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
