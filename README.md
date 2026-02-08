# CUSTOMER_PURCHASE_PREDICTION

## 📌 Project Overview
This project predicts whether an e-commerce customer is likely to make a purchase based on their behavior and engagement data.  
The model also segments users into intent levels and provides clear business recommendations for marketing actions.

Live Demo:  
https://e-commerce-customer-purchase-prediction.onrender.com/

##  Problem Statement
E-commerce platforms collect large amounts of customer behavior data, but marketing teams often spend money without knowing which users are most likely to convert.

This project aims to:
- Predict purchase probability
- Identify high-intent customers
- Reduce unnecessary marketing spend
- Enable data-driven decision making

## Solution Summary
- Preprocessed and encoded customer behavior data
- Engineered strong behavioral features
- Performed exploratory data analysis (EDA)
- Trained and evaluated multiple ML models
- Selected the best-performing model
- Converted predictions into business actions
- Deployed the solution as a web application

## Features Used
- Engagement Score  
- Cart Intent Score  
- Review Trust Score  
- Recommendation Influence  
- Satisfaction Score  
- Purchase Intent Score  
- Cart Friction Indicator  
- Multi-category User  
- Reviewer Indicator  

## Machine Learning Models
- Logistic Regression (Final Model)
- Random Forest (Comparison)
- Gradient Boosting (Comparison)

## Final Model: Logistic Regression  
Chosen for strong performance, stability, and interpretability.

## Model Performance
- Accuracy: ~91%
- ROC-AUC: ~0.98
- Balanced precision and recall
- No overfitting observed

## Intent Segmentation
Customers are classified based on predicted purchase probability:

| Probability Range | Intent Level | Business Action |
|------------------|-------------|-----------------|
| < 0.4 | Low Intent | No marketing spend |
| 0.4 – 0.7 | Medium Intent | Reminder / product recommendation |
| > 0.7 | High Intent | Target with offer or discount |

## Output Columns
- Purchase Probability
- Intent Segment
- Recommended Action

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- FastAPI
- Pickle
- Render (Deployment)

## 🚀 Deployment
The model is deployed as a web application where users can:
- Input customer behavior values
- View purchase probability
- See intent category
- Get marketing recommendations

Live App:  
https://e-commerce-customer-purchase-prediction.onrender.com/

## 💼 Business Value
- Optimizes marketing spend
- Improves conversion targeting
- Translates ML predictions into actions
- Ready for real-world usage
Industry-oriented Machine Learning Project  
Purchase Intent Prediction System
