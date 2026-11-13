# Customer Churn Predictor 📊

## Overview

Customer Churn Predictor is a machine learning project that uses customer data to predict whether a customer is likely to leave a telecommunications service provider.

The project explores customer behaviour, identifies patterns associated with churn, and builds a classification model using Logistic Regression.

The goal is to demonstrate how machine learning can help businesses understand customer retention and identify customers who may be at risk of leaving.

## Objectives

- Explore and understand customer churn data.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Prepare features for machine learning.
- Build a Logistic Regression classification model.
- Evaluate model performance using classification metrics.

## Technologies and Libraries

- Python
- Pandas – Data manipulation and analysis.
- NumPy – Numerical computations.
- Matplotlib – Data visualization.
- Seaborn – Statistical visualization.
- Scikit-learn – Model training and evaluation.

## Dataset

The project uses the Telco Customer Churn dataset, which contains customer demographic information, subscribed services, account details, and churn status.

The target variable is `Churn`, which indicates whether a customer has discontinued the service.

## Machine Learning Model

**Algorithm:** Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for classification. In this project, it predicts whether a customer belongs to the churn or non-churn category.

## Model Evaluation

The model was evaluated using accuracy, precision, recall, and F1-score.

| Metric | Score |
|---|---:|
| Accuracy | 79% |
| Precision (Churn: Yes) | 61% |
| Recall (Churn: Yes) | 53% |
| F1-score (Churn: Yes) | 57% |

### Performance Interpretation

The model achieved 79% overall accuracy. However, its recall for customers who churned was 53%, meaning it failed to identify a considerable proportion of actual churn cases.

This highlights the importance of evaluating classification models beyond accuracy, particularly when identifying the minority class is important.

## Project Structure

```text
customer-churn-predictor/
├── data/
├── notebooks/
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation and Usage

1. Clone the repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Navigate into the project directory:

   ```bash
   cd customer-churn-predictor
   ```

3. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

4. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

5. Open the Jupyter Notebook and run the analysis.

## Future Improvements

- Investigate class imbalance and experiment with SMOTE.
- Explore alternative classification algorithms.
- Perform hyperparameter tuning.
- Improve recall for customers who churn.
- Compare model performance using multiple evaluation metrics.

## Author

**Watutwe Lydiah**

BSc Data Science Student | Aspiring Data Scientist

- GitHub: [@watutwelydiah-byte](https://github.com/watutwelydiah-byte)

---

*This project was developed for learning and practical exploration of machine learning and predictive analytics.*
