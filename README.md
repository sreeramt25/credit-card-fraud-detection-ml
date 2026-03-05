# Credit Card Fraud Detection

This project builds a machine learning model to detect fraudulent credit card transactions.

## Models Used
- **Logistic Regression** – Baseline model for fraud classification  
- **Random Forest** – Ensemble model used for improved prediction performance  

## Techniques Applied
- Handling **extreme class imbalance** in fraud data  
- **Cost-based threshold optimization** to minimize financial loss  
- **ROC Curve and AUC** for model discrimination evaluation  
- **Precision–Recall Curve** for performance evaluation on imbalanced data  
- **Feature Importance analysis** using Random Forest  

## Results

| Model | Optimal Threshold | Business Cost |
|------|------------------|--------------|
| Logistic Regression | 0.97 | ₹133,700 |
| Random Forest | 0.13 | **₹122,300** |

### Key Outcome
After optimizing the classification threshold using a **business cost function**, the **Random Forest model achieved the lowest financial loss**. Therefore, Random Forest was selected as the final model for fraud detection in this project.

## Dataset

The dataset is too large to upload to GitHub.

Download it here:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## ROC Curve

<img width="567" height="453" alt="roc_curve" src="https://github.com/user-attachments/assets/e3fdf7e8-c646-424a-afd1-e2ea1f91fcde" />

## Precision-Recall Curve

<img width="567" height="453" alt="pr_curve" src="https://github.com/user-attachments/assets/d8ea9f6f-f5e0-4ee6-9c03-485ef62fcc34" />


## Feature Importance
<img width="572" height="453" alt="feature_importance" src="https://github.com/user-attachments/assets/6ebce83e-dc5e-43de-9fa6-e9737e9d696b" />
