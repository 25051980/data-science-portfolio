# 🏃‍♀️ Human Activity Recognition with PCA and Decision Trees

This project is part of the EBAC Data Science curriculum and explores the impact of Principal Component Analysis (PCA) on human activity recognition using data from the UCI HAR Dataset. It evaluates performance with and without data standardisation and compares model accuracy using a Decision Tree Classifier.

## 📁 Dataset

- Source: UCI HAR Dataset (Human Activity Recognition Using Smartphones)
- Features: 561
- Activities: 6 distinct human activities
- Samples:
  - Training: 7,352
  - Testing: 2,947

## 🎯 Objectives

- Apply PCA with and without data standardisation
- Compare explained variance to determine optimal number of components for 90% variance
- Train and evaluate Decision Tree Classifiers using PCA-transformed data
- Compare accuracy between standardised and non-standardised versions

## 🧪 Experiments

### PCA Summary:
- 📉 Without Standardisation: 34 components to explain 90% of variance
- 📊 With Standardisation: 63 components to explain 90% of variance

### Decision Tree Classification (10 PCA Components, `ccp_alpha=0.001`):

| Metric                         | Without Standardisation | With Standardisation |
|-------------------------------|--------------------------|-----------------------|
| Accuracy (Training)           | 0.8912                   | 0.8587                |
| Accuracy (Testing)            | 0.8222                   | 0.7743                |

### ✅ Interpretation:

- Without standardisation yields slightly higher accuracy, likely because feature scaling removes valuable differences.
- Standardisation reduces variance dominance and overfitting, showing more generalised model behaviour.

## ⚙️ Key Libraries

- pandas
- scikit-learn (PCA, DecisionTreeClassifier, accuracy_score)
- matplotlib & seaborn

## 📊 Visual Analysis (recommended additions)

- Scree plots of explained variance
- Heatmaps of confusion matrices
- Plots comparing performance per PCA setting

## 📂 Project Files

- `X_train.txt`, `X_test.txt`, `y_train.txt`, `y_test.txt`
- PCA experiments with and without scaling
- Decision tree classification and evaluation

## 🙋 Author

**Samuel Walford**  
📊 Postgraduate in Data Science – PUC-Rio  
🎓 MSc Cyber Security Student – St Mary’s University, Twickenham  
🌐 Enthusiastic about combining machine learning and real-world signal processing data

---
**Link of the project**: ([GitHub](https://github.com/25051980/Mod27_2/blob/main/mod27_Tarefa02%20(1).ipynb)

📝 *This project highlights the importance of data preprocessing when using dimensionality reduction techniques in time series and classification tasks.*
