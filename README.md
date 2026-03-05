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

<img width="536" height="470" alt="roc" src="https://github.com/user-attachments/assets/66972fc5-b2ef-4cfe-be9c-87d0383794be" />

## Precision-Recall Curve

<img width="536" height="470" alt="PR" src="https://github.com/user-attachments/assets/94b568ce-b562-409b-935f-78f0238707ef" />

## Feature Importance

<img width="708" height="470" alt="feature" src="https://github.com/user-attachments/assets/f659d105-d97a-451e-80f3-44821d675f1c" />

