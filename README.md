####### 📊 Customer Churn Prediction & Explainability Report

## 🚀 Project Overview
Customer churn is a critical problem for businesses in telecom, banking, and SaaS industries. This project leverages **Machine Learning (ML) models** and **SHAP (SHapley Additive Explanations)** to **predict churn** and **explain why customers leave**.

## 🔍 Dataset
- **Source:** Telco Customer Churn Dataset
- **Size:** 7,043 customer records
- **Key Features:** `tenure`, `contract`, `monthly charges`, `online security`, `tech support`, etc.

## 🏆 Models & Performance
| Model                | Accuracy |
|----------------------|----------|
| Gradient Boosting   | **79.17% (Best Model)** |
| Logistic Regression | 78.39%   |
| XGBoost             | 77.39%   |
| RandomForest        | 77.04%   |

## 🔬 SHAP Explainability Insights
- **Contract Type & Tenure** are the most important churn predictors.
- Customers with **higher Monthly Charges** have a higher likelihood of churning.
- Lack of **Online Security & Tech Support** increases churn risk.

## 🎯 Business Recommendations
✔ **Offer longer contracts** to reduce churn (month-to-month customers churn the most).  
✔ **Target new customers early** (most churn happens within the first 6 months).  
✔ **Optimize pricing strategies** for high-risk customers.  
✔ **Improve customer support & security features** to increase retention.  
