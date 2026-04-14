# Credit Card Fraud Detection - ML

## 📌 Overview

This project builds a machine learning model to detect fraudulent credit card transactions using historical data. It analyzes patterns in transaction data to distinguish between normal and fraudulent activities.

## 🎯 Objectives

- Detect fraudulent transactions accurately
- Handle highly imbalanced dataset
- Minimize false positives and false negatives

## 📊 Dataset

- Total transactions: 284,807
- Features: 30 input features (V1–V28, Time, Amount)
- Target: `Class` (0 = Normal, 1 = Fraud)

## ⚙️ Technologies Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

## 🔍 Workflow

1. Import libraries
2. Load and explore dataset
3. Analyze class imbalance
4. Perform data visualization
5. Prepare training & testing data
6. Train Random Forest model
7. Evaluate using performance metrics

## 🤖 Model

- Algorithm: Random Forest Classifier

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Matthews Correlation Coefficient (MCC)

## 🚀 Results

The model achieves high accuracy and strong precision, effectively identifying fraudulent transactions while minimizing false alerts. Evaluation metrics confirm balanced performance despite dataset imbalance.

## ⚠️ Challenges

- Imbalanced dataset (very few fraud cases)
- Trade-off between precision and recall

## 🔮 Future Improvements

- Apply oversampling/undersampling techniques
- Try advanced models (XGBoost, Neural Networks)
- Hyperparameter tuning

## 📎 Conclusion

This project demonstrates how machine learning can help detect fraud efficiently and reduce financial risks using data-driven insights.
