# Introduction
This project is used to predict the IC50 value of Aromatase inhibitor. Aromatase inhibitor is a drug used in the treatment of breast cancer in postmenopausal women and gynecomastai in men.
This project consists five jupyter notebook and is inspired from Data Professor.

First part:
Bioactivity data is downloaded for Aromatase inhibitor by using ChEMBL Database and target protein for human is selected.

Second Part:
RDKit library is used to calculate the Lipinski descriptors using the bioactivity data obtained from part 1. Lipinski descriptors is used to evaluate the druglikenes of compounds
The Lipinski's Rule stated the following:
- Molecular weight < 500 Dalton
- Octanol-water partition coefficient (LogP) < 5
- Hydrogen bond donors < 5
- Hydrogen bond acceptors < 10

Third Part:
Padel descriptor software is used to prepare the machine learning input data which calcualte the molecular fingerprints based on the smiles string.

Fourt Part:
Regression Models with Random Forest is used to predict the IC50 values. IC50 value is used to calculate the Potency of drugs. Higher the IC value, lower potential and vice versa.


Fifth part:
 Model is deployed using the Streamlit library.
 




Credit: Data Professor
