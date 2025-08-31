# HCC Survival Prediction

[![Python](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/ML-scikit--learn%20%7C%20imbalanced--learn-yellow)](https://scikit-learn.org/)

End-to-end **Machine Learning pipeline** for predicting **1-year survival** of patients with **Hepatocellular Carcinoma (HCC)**, 
based on real clinical data collected at **CHUC — Coimbra Hospital and University Center (Portugal)**.

> Developed as part of the course *Elements of Artificial Intelligence and Data Science* (FCUP, 2023/24).

---

## ✨ Project Highlights
- **Exploratory Data Analysis (EDA):** inspection of variable types, class distribution, missing values, outliers, correlations, and visualizations.
- **Data Preprocessing:** imputation, scaling, normalization, and feature engineering; addressing **class imbalance** with SMOTE.
- **Supervised Models:** Decision Tree, KNN, Random Forest, Gradient Boosting, Logistic Regression, MLP, SVC, and a Stacking ensemble.
- **Evaluation:** accuracy, precision, recall, ROC/AUC, confusion matrix, and cross-validation for robust performance assessment.
- **Key Results:**  
  - **Random Forest**: best performance (Cross-Validation ≈ 0.74)  
  - **Gradient Boosting**: strong results (CV ≈ 0.70)  
  - **SVC**: competitive baseline (CV ≈ 0.60)  

---

## 📂 Repository Structure
```
.
├── notebooks/
│   └── trabalho_HCD-2.ipynb      # Main notebook (code and experiments)
├── reports/
│   ├── trabalho_HCD-2.pdf        # Final report with results and discussion
│   └── readme_original.pdf       # Original README for academic submission
├── data/
│   └── README.md                 # Instructions for dataset placement
├── requirements.txt              # Dependencies
├── LICENSE                       # MIT License
└── README.md                     # This file
```

---

## ▶️ How to Run
1. Ensure **Python 3.10+** is installed.  
2. (Optional) Create a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate       # macOS/Linux
   .venv\Scripts\activate        # Windows
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Place the dataset file `hcc_dataset.csv` in the `data/` folder (not included in this repo).  
5. Launch Jupyter Notebook and run:
   ```bash
   jupyter notebook notebooks/trabalho_HCD-2.ipynb
   ```

---

## 🔧 Dependencies
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- imbalanced-learn  
- jupyter  
- ipykernel  

---

## 👩‍💻 Authors
- Catarina Abrantes  
- Liliana Silva  
- Mariana Fonseca  

---

## 📄 License
This project is licensed under the **MIT License** — see [LICENSE](./LICENSE) for details.
