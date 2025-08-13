# CREDIT-SCORE-NAIVE-BAYES-DECISION-T
💳 Bank Credit Scoring | Python, Decision Tree &amp; Naive Bayes Cleaned and balanced data with SMOTE, built a Decision Tree, fixed overfitting, and compared with Naive Bayes. Evaluated with Precision, Recall &amp; F1-Score for robust, reliable predictions.

# 📊 Bank Score Analysis with Decision Tree

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-%230F75BC.svg?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License](https://img.shields.io/badge/license-Educational-green)](#-license)

---

## 📝 About

This project presents a **predictive bank score analysis** using Python and a decision tree, focusing on explaining the process from data cleaning to model evaluation. It also includes a **comparison with Naive Bayes** performance.

---

## 🚀 Main Steps

- Data import and exploration  
- Cleaning: removal of nulls, duplicates, and outliers  
- Target balancing using SMOTE  
- Train-test split  
- DecisionTreeClassifier model building (`criterion='gini', random_state=0`)  
- Evaluation with metrics: Accuracy, Precision, Recall, F1-Score  
- Overfitting detection (100% train vs 56% test)  
- Feature importance extraction and visualization  
- Retraining using selected features (Home Ownership, Income)  
- Comparison with Naive Bayes  

---

## 📊 Results

| Metric                 | Full Model       | Optimized Model   | Naive Bayes    |
|------------------------|-----------------|-----------------|---------------|
| Train Accuracy          | 100% (overfitting) | -               | -             |
| Test Accuracy           | 56%             | Improved         | Slightly better |
| Class-wise Performance  | Good only for class 2 | Better for classes 0 & 1 | Slightly better |

The optimized model with fewer features achieved superior results, demonstrating the effectiveness of feature importance analysis.

---

## 📈 Visualizations

- Bar chart for class distribution  
- Confusion matrix for detailed analysis  
- Decision tree visualization  
- Feature importance chart  

---

## 🛠 Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Scikit-learn (DecisionTreeClassifier, Naive Bayes, SMOTE)  
- Jupyter Notebook  

---

## 🎓 Professor's Feedback

> The project is well-structured and executed, highlighting proper variable separation, balanced dataset validation, detailed metric analysis, and recognition of overfitting. Simplifying the model with relevant features significantly improved results, and the comparison with Naive Bayes was clear and well-justified. Excellent work!

---

## 📜 License

This project is for educational purposes and is available for **free, non-commercial use**.

---

## 📫 Contact

Feel free to reach out with any questions or suggestions!
