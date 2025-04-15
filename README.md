# Alpha Thalassemia Classification Comparative Analysis

This project applies machine learning models to classify alpha thalassemia phenotypes using CBC (Complete Blood Count) data. It focuses on two classification tasks:
- **Alpha Trait vs Silent Carrier** (`twoalphas`)
- **Alpha Carrier vs Normal** (`alphanorm`)

## Contents
- `alphanorm.ipynb`: Notebook for the **alpha carrier vs normal** classification task.
- `alphanorm.csv`: Dataset for the **alpha carrier vs normal** classification task.
- `twoalphas.ipynb`: Notebook for the **alpha trait vs silent carrier** classification task.
- `twoalphas.csv`: Dataset for the **alpha trait vs silent carrier** classification task.

## Methods
- Classical ML: Logistic Regression, SVM, Random Forest, AdaBoost
- Deep Learning: Feedforward ANN
- Evaluation Metrics: AUROC, F1 Score, Precision, Recall, Accuracy

## Results
- **AdaBoost** performed best for `twoalphas`
- **Random Forest** performed best for `alphanorm`
- ANNs showed promise but were affected by small dataset size

## Requirements
- Python 3.8+
- `scikit-learn`, `pandas`, `matplotlib`, `numpy`, `tensorflow`, `shap`, `imbalanced-learn`

## Dataset
The datasets used in this project (`twoalphas.csv` and `alphanorm.csv`) are sourced from the following Kaggle dataset:

> **Nival Kolambage. (2022).** *Alpha Thalassemia Dataset - Carriers vs Normal*. Kaggle.  
> [https://www.kaggle.com/dsv/3532313](https://www.kaggle.com/dsv/3532313)  
> DOI: [10.34740/KAGGLE/DSV/3532313](https://doi.org/10.34740/KAGGLE/DSV/3532313)  
> License: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)

This dataset is made available under the **Creative Commons Attribution-NonCommercial 4.0 International** license. You are free to share and adapt the material for non-commercial purposes with proper attribution.
