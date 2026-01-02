# Churn Analysis in a Telecommunications Company

This project analyses customer churn in the telecommunications sector, with the objective of identifying customers at risk of cancelling their service and extracting actionable business insights.  
The work was developed as part of postgraduate-level training in **Data Science and Analytics** and focuses on combining exploratory analysis with supervised machine learning techniques.

---

## Project Overview

Customer churn is a critical challenge for telecommunications companies, directly affecting revenue, customer lifetime value, and long-term sustainability.  
This project aims to support proactive retention strategies by predicting churn and identifying the key factors that influence customer behaviour.

The analysis follows an end-to-end data science workflow, from data exploration to model evaluation and interpretation.

---

## Business Problem

Telecommunications providers operate in a highly competitive market where acquiring new customers is significantly more expensive than retaining existing ones.

The key questions addressed in this project are:
- Which customers are most likely to churn?
- What characteristics and behaviours are associated with churn?
- How can predictive models support data-driven retention decisions?

---

## Dataset Description

The dataset contains customer-level information, including:
- Contract and subscription details  
- Customer tenure  
- Billing and payment characteristics  
- Service usage indicators  

The target variable represents whether a customer has churned.

---

## Methodology

The project follows a structured analytical approach:

1. **Exploratory Data Analysis (EDA)**  
   - Analysis of feature distributions  
   - Identification of churn patterns and correlations  

2. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Feature scaling where appropriate  

3. **Model Development**  
   Several supervised classification models were trained and compared.

4. **Model Evaluation**  
   Performance was assessed using standard classification metrics and interpreted from a business perspective.

---

## Machine Learning Models

The following models were implemented and evaluated:

- Logistic Regression  
- Decision Tree  
- Random Forest  

Model performance was measured using:
- Accuracy  
- Precision  
- Recall  
- F1-score  

---

## Key Findings & Insights

- Contract type, tenure, and monthly charges emerged as strong predictors of churn  
- Tree-based models, particularly Random Forest, achieved the strongest overall performance  
- Visual analysis supported model interpretability and business understanding  

The results highlight how predictive analytics can support targeted retention strategies and operational decision-making.

---

## Tools & Technologies

- **Programming Language:** Python  
- **Libraries:**  
  - Pandas, NumPy – data manipulation  
  - Matplotlib, Seaborn – data visualisation  
  - SciPy – statistical analysis  
  - Scikit-learn – machine learning and preprocessing  
- **Environment:** Jupyter Notebook / Google Colab  

---

## How to Run

1. Open the notebook in **Google Colab**: (https://colab.research.google.com/drive/1Ftck_xA1TlEDK7MU9mOecA9ia6ZG9vsh?usp=sharing)
2. Install the required Python libraries  
3. Load the dataset  
4. Run the notebook cells sequentially to reproduce the analysis and results  

---

## Notes

This project demonstrates:
- Practical application of machine learning to a real-world business problem  
- A clear, structured data science workflow  
- Interpretation of results with a focus on business value rather than model performance alone  


