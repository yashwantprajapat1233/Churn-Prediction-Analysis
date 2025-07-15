# 📊 Customer Churn Prediction & Analysis

This project uses machine learning (Random Forest) and Power BI to predict customer churn and visualize key insights to aid business decision-making.

## 🚀 Project Overview

Customer churn is a major concern for businesses, especially in subscription-based industries. This project leverages data analysis and machine learning to identify customers at risk of churning and provides actionable insights through an interactive Power BI dashboard.

## 🧠 Machine Learning Model

- **Algorithm**: Random Forest Classifier
- **Language**: Python (Jupyter Notebook)
- **Libraries Used**:
  - `pandas`, `numpy` for data processing
  - `scikit-learn` for model building and evaluation
  - `matplotlib`, `seaborn` for EDA and visualization

### Model Metrics
🧠 Machine Learning Model
Algorithm: Random Forest Classifier

Language: Python (Jupyter Notebook)

✅ Model Performance
Metric	Class 0 (Not Churned)	Class 1 (Churned)	Overall
Precision	0.86	0.78	0.84 (weighted)
Recall	0.92	0.65	0.84 (accuracy)
F1-Score	0.89	0.71	0.84 (weighted)
Support	847	355	1202

Confusion Matrix:


[[783  64]
 [126 229]]

 The model performs well on identifying non-churned customers with high precision and recall.
 It also reasonably identifies churned customers, though with slightly lower recall, which is common in imbalanced datasets.

> The model was trained to classify whether a customer will churn or not, using demographic and behavioral attributes.

## 📈 Power BI Dashboard

The `.pbix` file contains an interactive dashboard that includes:
- Total churned vs retained customers
- Churn breakdown by gender, tenure, and geography
- Monthly churn trend
- Predicted churn count from ML model
- Filterable views for targeted analysis

### 📌 Sample Visuals
- KPI Cards for total customers and churn rate
- Bar/column charts for segment-wise churn
- Slicers to dynamically analyze churn patterns

## 📂 Project Structure

📁 Churn-Prediction-Analysis/
├── churn_prediction_model.ipynb # Jupyter notebook with data processing and model
├── Churn Analysis.pbix # Power BI report file
├── predictions.csv # Model output used in Power BI
└── README.md # Project documentation


🎯 Future Enhancements
Add prediction confidence scoring

Deploy model via Streamlit or Flask

Schedule automatic data refresh and model retraining

🤝 Acknowledgements
Scikit-learn

Power BI

Python

Author: Yashwant Prajapat

