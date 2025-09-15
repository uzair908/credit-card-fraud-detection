# credit-card-fraud-detection
Credit Card Fraud Detection using the Random Forest model In Combination With and Without SMOTE
## 📌 Project Overview
This project builds a machine learning model to detect fraudulent credit card transactions using the **Kaggle Credit Card Fraud Dataset**.  
The model uses **Random Forest Classifier** with and without **SMOTE** to handle class imbalance.

## ⚡ Features
- Handles highly imbalanced dataset  
- Implements Random Forest Classifier (default parameters)  
- Compares results with and without SMOTE  
- Evaluates models using: Accuracy, Precision, Recall, F1-score, ROC-AUC, and Precision-Recall Curves  

## 📊 Results
| Model                     | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|----------------------------|----------|-----------|--------|----------|---------|
| Random Forest (with SMOTE) | 0.999403 | 0.827     | 0.827  | 0.827    | 0.964   |
| Random Forest (No SMOTE)   | 0.999569 | 0.941     | 0.816  | 0.874    | 0.963   |

## 🛠️ Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
