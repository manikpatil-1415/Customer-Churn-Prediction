# Customer Churn Prediction using Python & Machine Learning

## 📌 Project Overview

This project predicts whether a customer is likely to churn using machine learning classification models.

The project includes data preprocessing, feature scaling, model training, evaluation, comparison, and feature importance analysis.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab
- GitHub

## 🤖 Machine Learning Models

The following models were tested:

1. Logistic Regression
2. Scaled Logistic Regression
3. Balanced Logistic Regression
4. Random Forest Classifier

## 📊 Model Performance

| Model | Accuracy |
|---|---:|
| Logistic Regression | 84.46% |
| Scaled Logistic Regression | 85.21% |
| Balanced Logistic Regression | 74.34% |
| Random Forest | **92.13%** |

Random Forest achieved the highest overall accuracy among the models tested.

## 🔍 Feature Importance

The most important features identified by the Random Forest model include:

- Total day minutes
- Customer service calls
- Total day charge
- International plan
- Total evening minutes
- Total night minutes

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score

The Random Forest model achieved **92.13% accuracy** on the test dataset.

## 📁 Project File

- `Customer_Churn_Prediction_ML.ipynb` — Complete Jupyter/Google Colab notebook containing the analysis and machine learning workflow.

## 🎯 Conclusion

Among the tested models, Random Forest performed the best based on overall accuracy. Feature importance analysis also helped identify the customer attributes that contributed most to churn prediction.

## 👨‍💻 Author

Manik Dnyaneshwar Patil
