# heart-disease-prediction-model
This project uses machine learning to analyze health-related data and predict whether a person is at risk of developing heart disease. The goal is to assist in early diagnosis using data-driven insights so that medical professionals can make better decisions.




# 🫀 Heart Disease Prediction Using Machine Learning

This project uses machine learning to predict the likelihood of heart disease based on various medical attributes. It is built in Python and includes:

- Data analysis and model training in Jupyter Notebook
- A saved ML model
- A simple Streamlit web app for making predictions

> ⚠️ **Disclaimer:** This project is for learning and educational purposes only. It must **not** be used for real medical diagnosis.

---

## 📂 Project Structure

A simple project layout could be:

```bash
heart-disease-prediction/
├── app.py                     # Streamlit web app
├── model.joblib               # Trained ML model (generated after training)
├── heart.csv                  # Dataset (UCI Heart Disease dataset)
├── README.md                  # Project documentation
├── requirements.txt           # Python dependencies
└── notebooks/
    └── heart_disease_prediction.ipynb  # Jupyter Notebook (optional)





🛠️ Technologies Used

Language: Python

Libraries:

pandas, numpy

scikit-learn

matplotlib, seaborn (for plots in the notebook)

joblib (for saving the model)






🧠 Machine Learning

Typical ML pipeline:

Load dataset (heart.csv)

Basic EDA (Exploratory Data Analysis)

Split into train and test sets

Train ML models such as:

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Support Vector Machine (SVM)

Evaluate with:

Accuracy

Confusion Matrix

Precision, Recall, F1-score

Choose best model and save it as model.joblib
