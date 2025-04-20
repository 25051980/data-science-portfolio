# 🧮 SQL-Based Customer Behavior Analysis – Credit Usage Project

This project was developed as part of the EBAC Data Science course and focuses on using SQL to explore and analyze customer behavior patterns based on a simulated credit card dataset. The analysis aims to extract insights that support credit risk assessment and marketing strategy development.

---

## 🧩 Project Overview

Using a structured dataset representing credit card customer profiles, this project investigates customer activity, engagement, and demographic indicators. SQL queries are used to assess credit limits, transaction patterns, inactivity levels, and relationships between variables like age, gender, and income.

---

## 📌 Dataset Attributes

Some of the key columns in the dataset include:

- **Idade (age)**: Customer age  
- **Sexo (gender)**: M or F  
- **Dependentes**: Number of dependents  
- **Escolaridade (education)**: Highest education level  
- **Estado_civil (marital status)**  
- **Salario_anual (annual salary)**  
- **Tipo_cartao (card type)**  
- **qtd_produtos**: Number of products used  
- **Iteracoes_12m**: Interactions in the past 12 months  
- **Meses_inativo_12m**: Months of inactivity  
- **Limite_credito (credit limit)**  
- **Valor_transacoes_12m**: Total value of yearly transactions  
- **qtd_transacoes_12m**: Number of yearly transactions

---

## 📊 Key Insights

- Dataset contains **2,564 customers**
- Customers are mostly aged between **37 and 51 years**
- Analysis revealed patterns by:
  - Card type and transaction activity
  - Inactive months and income levels
  - Credit limits and education/marital status

All queries were executed using **standard SQL** syntax within a Jupyter Notebook environment.

---

## ▶️ How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Ensure a SQL runtime (e.g., SQLite or PostgreSQL with `ipython-sql`) is configured
3. Run each SQL cell sequentially to explore the dataset and reproduce the insights
