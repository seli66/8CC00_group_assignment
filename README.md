# 8CC00_group_assignment
Advanced Programming Group Assignment

## Predicting PKM2 and ERK2 Inhibition with XGBoost

This project aims to develop predictive models for PKM2 and ERK2 inhibition based on molecular descriptors derived from SMILES representations of molecules. The workflow involves data preprocessing, feature extraction, dimensionality reduction, model training with hyperparameter tuning, and threshold optimization.

### Key Functions in XGBoost.ipynb:
- `compute_descriptors(smiles)`: Computes molecular descriptors for a given SMILES string.
- `evaluate_model(model, X_val, y_val, label, threshold=0.5, print_info=False)`: Evaluates model performance and prints detailed metrics.

### Repository Contents:
- `data/tested_molecules.csv`: Training dataset with molecular SMILES and inhibition labels.
- `data/untested_molecules-3.csv`: Test dataset with molecular SMILES.
- `data/pred.csv`: Predicted inhibition results for the test dataset.
- `xgboost.ipynb`: Notebook that contains the final algorithm of choice: XGBoost along with the required data analysis.
- `data_analytics/...`: Notebooks that we made to explore the dataset.
- `other_approaches/...`: Notebooks with all the other approaches we took for our model.
