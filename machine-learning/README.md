# Machine Learning

This folder contains notebooks and projects focused on **classical machine learning** techniques. The projects cover the full data science workflow: data exploration, preprocessing, feature engineering, model training, evaluation, and interpretation.

All notebooks run in **Google Colab** — click the badge at the top of any notebook to get started instantly.

---

## Topics Covered

- Supervised learning: regression and classification
- Unsupervised learning: clustering and dimensionality reduction
- Feature engineering and selection
- Model evaluation: cross-validation, ROC/AUC, confusion matrices
- Model interpretability with SHAP and feature importance plots
- Pipelines and best practices with scikit-learn

---

## Projects

| Notebook | Description |
|---|---|
| `house_price_prediction.ipynb` | End-to-end regression pipeline predicting house prices using linear models, gradient boosting, and feature engineering |
| `customer_churn_classification.ipynb` | Binary classification with Random Forest and XGBoost, including SHAP-based model explanation |
| `kmeans_customer_segmentation.ipynb` | Unsupervised customer segmentation using K-Means and PCA for dimensionality reduction |
| `pipeline_best_practices.ipynb` | Demonstrates how to build robust, reusable scikit-learn pipelines with preprocessing and model steps |

---

## How to Run

1. Open any notebook in this folder.
2. Click the **"Open in Colab"** badge at the top of the notebook.
3. Run all cells from top to bottom (`Runtime → Run all`).

No local installation is required. All dependencies are installed within the notebook using `pip install`.

---

## Requirements

When running locally, the following packages are used:

```
numpy
pandas
matplotlib
seaborn
scikit-learn
xgboost
shap
```

Install them with:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost shap
```

---

*Back to [main portfolio](../README.md)*
