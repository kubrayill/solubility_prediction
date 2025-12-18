
This project implements the **ESOL (Estimated SOLubility)** model to predict the aqueous solubility of drug-like molecules using machine learning and the RDKit library.

The goal is to predict the `LogS` value of a molecule based on its chemical structure. We use four key molecular descriptors:
1. **LogP**: Octanol-water partition coefficient.
2. **Molecular Weight**: Size of the molecule.
3. **Rotatable Bonds**: Molecular flexibility.
4. **Aromatic Proportion**: The ratio of aromatic atoms to heavy atoms.

* **RDKit**: For chemical informatics and descriptor calculation.
* **Scikit-Learn**: For the Linear Regression model.
* **Pandas/NumPy**: For data manipulation.
* **Seaborn/Matplotlib**: For performance visualization.

The model achieved an **R² score of [Insert your score here, e.g., 0.87]** on the test set.
![Model Performance](Unknown.png)