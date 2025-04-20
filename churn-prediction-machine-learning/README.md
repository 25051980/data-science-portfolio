# 📞 Customer Churn Prediction – Machine Learning MVP

This project was developed as part of my postgraduate studies in Data Science and Analytics. It explores customer churn prediction in the telecommunications sector using machine learning classification techniques. The project delivers a Minimum Viable Product (MVP) to identify customers who are likely to cancel their service.

---

## 🧩 Problem Statement

Customer churn is a major concern for telecom companies, as it directly impacts revenue and increases acquisition and retention costs. With the ease of switching providers, customer loyalty has become a key challenge.

This project builds a supervised classification model to predict the likelihood of customer churn. The goal is to help the business take proactive retention actions based on customer behaviour, payment type, contract length, tenure, and service satisfaction.

---

## 🛠️ Tools and Libraries Used

- **Python**
- **Pandas / NumPy** – Data manipulation  
- **Matplotlib / Seaborn** – Visualization  
- **Scikit-learn** – Preprocessing, modeling, and evaluation  
- **Pipeline & ColumnTransformer** – Feature engineering  
- **GridSearchCV / KFold** – Model tuning  
- **Google Colab** – Development environment

---

## 🤖 ML Models Used

- Logistic Regression  
- Random Forest Classifier

Models were evaluated using metrics like:
- Accuracy
- Confusion Matrix
- ROC-AUC Curve
- Classification Report (Precision, Recall, F1-score)

---

## 📊 Summary of Results

- Dataset: Customer data from a telecom company
- Key insights:
  - Contract type, monthly charges, and service quality were strong churn indicators
  - Random Forest performed better than Logistic Regression
- The project delivers a ready-to-deploy MVP for customer churn prediction using interpretable results and a reproducible pipeline

---

## ▶️ How to Run the Notebook

Open the notebook in Google Colab:

👉 [Open in Google Colab](https://colab.research.google.com/drive/1eL2AosLzL98kIckKHk-rvHkpNCc1c1LQ)

The dataset is automatically loaded from this URL:

```python
url = 'https://raw.githubusercontent.com/25051980/MVP1/main/Churn.csv'
df = pd.read_csv(url)
