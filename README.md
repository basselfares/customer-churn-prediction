# Customer Churn Prediction

A supervised learning project to predict whether a Telco customer will churn using account and service data.

## Dataset

- Source: [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- 7,043 rows × 21 columns  
- Target: Churn (Yes/No)

## Models

- Logistic Regression
- Random Forest
- SVM

Evaluated using accuracy, recall, precision, and ROC curves.

## Results

Logistic Regression showed the best balance of accuracy and recall. Full results and visualizations are in the notebook.

## Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook notebooks/customer_churn_prediction.ipynb
