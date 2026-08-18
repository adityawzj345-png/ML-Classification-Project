# Cardiovascular Disease Classification

## 📌 Project Overview
This project focuses on predicting cardiovascular disease using Machine Learning classification algorithms.
The project implements and compares multiple classification models to identify the best-performing model based on different evaluation metrics.

## 🎯 Objective
The main objective of this project is to build Machine Learning classification models and compare their performance in predicting cardiovascular disease.

## 🔧 Data Preprocessing
The following steps were performed during the Machine Learning workflow:
* Dataset loading and inspection
* Data cleaning
* Checking missing values
* Feature and target separation
* Train-Test Split
* Feature scaling where required
* Model training
* Model evaluation

## 🤖 Machine Learning Models
The following classification algorithms were implemented:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. K-Nearest Neighbors (KNN)
5. Support Vector Machine (SVM)
6. XGBoost Classifier

## 📊 Model Evaluation
The models were evaluated using:
* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## 🏆 Best Model
Among the evaluated models, **XGBoost** achieved the best performance.

### XGBoost Performance
| Metric    |  Score |
| --------- | -----: |
| Accuracy  | 71.60% |
| Precision | 71.80% |
| Recall    | 71.60% |
| F1 Score  | 71.51% |

## 📈 Result
XGBoost achieved an accuracy of **71.60%** on the test dataset and performed better than the other evaluated classification models.
Therefore, XGBoost was selected as the best-performing model for this project under the current preprocessing steps and model parameters.

## 🛠️ Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Google Colab / Jupyter Notebook

## 📂 Project Structure
```text
ML-Classification-Project/
│
├── cardiovascular_disease_dataset.ipynb
└── README.md
```

## 🚀 Future Improvements
The project can be further improved by implementing the following:
* Perform more extensive hyperparameter tuning for all classification models.
* Apply advanced feature selection techniques to identify the most important features.
* Handle class imbalance using techniques such as SMOTE if required.
* Perform cross-validation for more reliable model evaluation.
* Compare additional classification algorithms such as Gradient Boosting, AdaBoost, and LightGBM.
* Improve model performance through advanced preprocessing and feature engineering.
* Perform detailed error analysis to understand incorrect predictions.
* Add ROC-AUC and Precision-Recall curves for better model comparison.
* Implement explainable AI techniques such as SHAP to understand model predictions.
* Deploy the trained model as a web application using Flask, FastAPI, or Streamlit.

## 👨‍💻 Author
**Aditya Raj**
BCA – Data Science & Artificial Intelligence
Gopal Narayan Singh University

### 🔗 Project
This project was developed as part of Machine Learning and Data Science learning to understand the complete classification workflow, including preprocessing, model training, evaluation, comparison, and result interpretation.

---

⭐ If you find this project useful, feel free to explore, improve, and build upon it.
