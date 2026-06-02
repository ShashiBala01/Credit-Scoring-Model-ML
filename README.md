# Credit Scoring Model using Machine Learning

## Project Overview

This project aims to predict an individual's creditworthiness using demographic and financial information. Multiple machine learning classification algorithms were implemented and compared to identify the most effective model.

## Objective

To classify individuals into different credit score categories (High, Average, and Low) based on their personal and financial attributes.

## Dataset Information

The original dataset contained 164 records and 8 features.

After data cleaning:

* 62 duplicate records were removed
* Final dataset size: 102 records
* Feature engineering was applied to create a new feature: Income_Per_Child

Final dataset shape: (102, 9)

## Features Used

* Age
* Gender
* Income
* Education
* Marital Status
* Number of Children
* Home Ownership
* Income_Per_Child

## Machine Learning Models

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 76%      |
| Decision Tree       | 100%     |
| Random Forest       | 95%      |

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Label Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Model Comparison

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Conclusion

The project successfully classified individuals into different credit score categories. Random Forest demonstrated strong performance and reliability, while Decision Tree achieved perfect accuracy on the test dataset but may be prone to overfitting due to the small dataset size.

## Author

Shashi Bala
B.Tech CSE (AI & ML)
