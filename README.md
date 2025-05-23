Credit Risk Assessment using Machine Learning

This project focuses on building a predictive model for credit risk assessment to determine whether a borrower is likely to default on a loan. Using real-world financial data and machine learning algorithms, the model assists financial institutions in making data-driven lending decisions.

 Problem Statement

Loan default prediction is a critical task for banks and financial institutions. Manual decision-making often results in higher risk exposure. Our system uses machine learning techniques to predict the likelihood of default, based on features such as:

- Age
- Income
- Employment length
- Home ownership status
- Loan purpose
- Loan grade
- Loan amount
- Interest rate
- Credit history

---

 Skills & Technologies

 Data Science & Machine Learning

- Data Preprocessing: Handling missing values, encoding categorical variables, feature scaling.
- Exploratory Data Analysis (EDA): Correlation heatmaps, pair plots, distribution and box plots.
- Feature Engineering: Creating useful features to improve model performance.

 Machine Learning Algorithms

Implemented and compared the following models:

- Gaussian Naive Bayes
- Bernoulli Naive Bayes
- Decision Tree
- Random Forest
- Support Vector Classifier (SVC)
- Neural Network (MLPClassifier)
- Gradient Boosting (XGBoost)

 Evaluation Techniques

- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- ROC Curve & AUC
- Learning Curve Analysis
- Cross-validation using `GridSearchCV`



 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- XGBoost

---

 Dataset

-  `credit_risk_dataset.csv`
- Contains 32,581 records of borrowers' financial and demographic information.

---



 Results

| Model              | Accuracy | AUC   | Precision | Recall |
|-------------------|----------|-------|-----------|--------|
| GaussianNB         | 83.9%    | ~0.83 | Good      | Moderate |
| Decision Tree      | 90.8%    | ~0.91 | High      | High |
| Neural Network     | 92.0%    | High  | Very High | High |
| Gradient Boosting  | **93.6%**| **0.87** | **Best**  | **Balanced** |






 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/credit-risk-assessment.git
   cd credit-risk-assessment
