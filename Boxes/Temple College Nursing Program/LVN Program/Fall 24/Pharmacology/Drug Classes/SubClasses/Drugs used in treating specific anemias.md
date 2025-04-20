---
DrugClass: 
BrandName: 
DrugClassContra: "[[Drugs used in treating specific anemias#Contraindications]]"
DrugClassAdverse: "[[Drugs used in treating specific anemias#Adverse Reactions]]"
SubClass: "[[Drugs used in treating specific anemias]]"
SecondaryDrugClass: 
SecondarySubClass: 
KindleLinkChap: 
Chapter: 
Course: Pharmacology
ChemLink: https://pubchem.ncbi.nlm.nih.gov/#query=
---
### Adverse Reactions 
GI Reactions
- GI irritation 
- Nausea, vomiting 
- Constipation, diarrhea 
- Darker (black) stools 

Generalized System Reactions 
- Headache
- Backache
- Allergic reactions 

When given parenterally, additional adverse reactions include soreness, inflammation, and sterile abscesses at the IM injection site. When iron is administered by the IM route, a brownish discoloration of the skin may occur. Intravenous (IV) administration may result in phlebitis at the injection site.

### Contraindications
Contraindications and Precautions Iron supplements are contraindicated in clients with known hypersensitivity to the drug or any component of the drug. Iron compounds are contraindicated in clients with hemochromatosis or hemolytic anemia. Iron compounds are used cautiously in clients with hypersensitivity to [[aspirin (acetylsalicylic acid)]] because these clients may have a hypersensitivity to the tartrazine or sulfite [[Content]] of some iron compounds. 

The parenteral form of iron can cause anaphylactic-type reactions and should be used only when oral supplement is contraindicated.

### Drugs with subclass `= this.file.name`
```dataview
table BrandName as "Brand Name", DrugClass as "Drug Class", SubClass as "Sub Class", SecondaryDrugClass as "Secondary Drug Class", SecondarySubClass as "Secondary SubClass"
from #Drug and "Boxes/Temple College Nursing Program/LVN Program/Fall 24/Pharmacology/Drugs" 
	where SubClass = this.SubClass or SecondarySubClass = this.SubClass
sort file.name asc
```
