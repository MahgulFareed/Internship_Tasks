# Internship Tasks - Machine Learning

These are my machine learning tasks that I completed during my internship. I worked on 3 different datasets and built models to solve real problems.

---

## Task 1 - Iris Dataset Analysis

For this task I explored the Iris flower dataset which has 150 samples of 3 different flower species. My goal was to understand the data through visualisations and then build a model to classify the species.

**What I did:**
- Loaded the dataset and checked its shape, columns and basic stats
- Checked for missing values (there were none)
- Made a scatter plot, histograms and box plots to explore the data
- Trained a KNN classifier to predict the flower species
- Evaluated the model using accuracy and confusion matrix

**What I found:**
- Setosa is very easy to identify because it is clearly separated from the other two
- Petal length and petal width are the most useful features for classification
- The model performed well on the test data

**File:** Iris_Dataset_Analysis.ipynb

---

## Task 2 - Credit Risk Prediction

In this task I built a model to predict whether a loan applicant will default on their loan or not. This is useful for banks to decide who to give loans to.

**What I did:**
- Loaded the loan dataset and explored the data
- Handled any missing values by filling with median or mode
- Visualised loan amount, income and employment status vs default rate
- Created a new feature called loan-to-income ratio
- Trained Logistic Regression and Decision Tree models
- Compared both models using accuracy, confusion matrix and ROC curve

**What I found:**
- People with a high loan compared to their income are more likely to default
- Unemployed applicants have a higher chance of defaulting
- Both models gave good results

**File:** Credit_Risk_Prediction.ipynb

---

## Task 3 - Customer Churn Prediction

Here I worked on a bank customer dataset to predict which customers are likely to leave the bank. This helps the bank keep their customers.

**What I did:**
- Cleaned the data and removed columns that are not useful like customer ID
- Encoded Gender using Label Encoding and Geography using One-Hot Encoding
- Made charts to explore churn rate by age, balance, country and gender
- Trained 3 models - Logistic Regression, Random Forest and Gradient Boosting
- Checked feature importance to see what affects churn the most

**What I found:**
- About 20% of customers churned
- Germany had the highest churn rate
- Age is the most important factor - older customers churn more
- Inactive members and customers with only 1 product are more likely to leave
- Random Forest and Gradient Boosting worked better than Logistic Regression

**File:** Customer_Churn_Prediction.ipynb

---

## Files in this repository

- README.md
- Iris_Dataset_Analysis.ipynb
- Credit_Risk_Prediction.ipynb
- Customer_Churn_Prediction.ipynb
- loan_default_prediction.csv
- Churn_Modelling.csv

---

## Libraries I used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## How to run

1. Install the libraries: pip install pandas numpy matplotlib seaborn scikit-learn
2. Open Jupyter Notebook
3. Run the cells from top to bottom
4. Make sure the CSV files are in the same folder as the notebooks
