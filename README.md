# Credit Card Fraud Detection

A machine learning project to detect fraudulent transactions using Random Forest.

## 🚀 Features
- Handles imbalanced dataset
- Hyperparameter tuning applied
- High recall for fraud detection

## 🛠️ Tech Stack
- Python
- NumPy, Pandas, Scikit-learn

## 📂 Dataset
- Credit Card Dataset
- Highly imbalanced data

## 📊 Model
- Random Forest with hyperparameter tuning

## 📈 Results
Improved fraud detection performance with strong recall on fraudulent transactions.

**ROC-AUC:** 0.9845  
**PR-AUC:** 0.8421  

### 🔍 Confusion Matrix
```
[[56815   49]
 [   11   87]]
```

### 📊 Classification Report
```
              precision    recall    f1-score    support

0             1.00        1.00      1.00        56864
1             0.64        0.89      0.74        98

accuracy                              1.00        56962
macro avg     0.82        0.94      0.87        56962
weighted avg  1.00        1.00      1.00        56962
```
