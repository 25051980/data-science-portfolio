# 💳 Credit Scoring Streamlit App

A complete end-to-end machine learning project that predicts whether a customer is a good or bad credit risk based on personal and financial data. This project was developed as part of the **EBAC Data Science Course** and includes model training, evaluation, and a Streamlit application.

## 🚀 Highlights

- Streamlit app interface for user-friendly prediction
- Random Forest Classifier trained on real-world features
- Data preprocessing, EDA, and feature engineering included
- Reproducible Jupyter Notebooks and well-structured code
- Large model file hosted externally due to GitHub limitations

## 🧰 Technologies Used

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Streamlit
- Pickle

## 🗂️ Project Structure

```
credit-scoring-streamlit-app/
├── app.py                  # Streamlit front-end application
├── model_final.pkl         # Trained ML model (hosted via Google Drive)
├── model_final.pkl.ipynb   # Jupyter Notebook for model training
├── Mod38Projeto.ipynb      # Data cleaning and EDA notebook
├── demo.mp4                # Demo video of the application (optional)
└── README.md               # Project documentation
```

## 📥 How to Run

1. Clone this repository
2. Download the trained model from [Git Clone]( https://github.com/25051980/-credit_scoring_app
cd -credit_scoring_app)
3. Place `model_final.pkl` in the root folder
4. In your terminal:

```bash
streamlit run app.py
```

## 🧠 Model Details

The model predicts credit risk using features like:

- Time in employment
- Income and education
- Number of dependents
- Vehicle/property ownership
- Credit history flags

Model: **RandomForestClassifier**  
Evaluation metrics and hyperparameter tuning included in `model_final.pkl.ipynb`.

## 🎥 Demo Video

> *(Optional: Insert a link to your demo video if available)*

## 🙋 About the Author

**Samuel Walford**  
Data Science Postgraduate – PUC Rio  
Cyber Security MSc Student – St Mary’s University, Twickenham  
📫 [LinkedIn](https://www.linkedin.com/in/your-profile)

---

📝 *This project is part of my growing portfolio. Feedback and contributions are welcome!*
