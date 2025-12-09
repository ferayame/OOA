# KNN hyperparameter tuning using Octopus Optimization Algorithm (OOA)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## **Objectives**

* Demonstrate the effectiveness of the Octopus Optimization Algorithm (OOA) in tuning KNN hyperparameters.
* Use the Heart Disease dataset as a benchmark to evaluate optimization results.
* Compare baseline KNN performance with OOA-optimized KNN.
* Compare OOA optimization with the IFOX algorithm.
* Visualize fitness convergence, evaluation metrics, and confusion matrices.

## Structure

```
OOA/
│
├── data/
│   └── Heart_Disease.csv
│
├── models/
│   ├── ooa_knn_model.joblib
├── results/
│
├── src/
│   ├── OOA-KNN.ipynb
│   └── data_analysis.ipynb
│
└── README.md
```

## Algorithms

### OOA

Used for hyperparameter tuning of KNN (k, p value, metric and distance). Implementation adapted from the original article [Octopus Optimization Algorithm: A Novel Single- and Multi-Objective Optimization Algorithm for Optimization Problems](https://doi.org/10.1007/s10586-025-05141-2).

### IFOX

Used for comparison, the code source was originally from [mwdx93/ifox](https://github.com/mwdx93/IFOX.git).
