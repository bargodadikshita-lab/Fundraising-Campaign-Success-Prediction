# Fundraising Campaign Success Prediction System

## Overview

This project aims to predict whether a fundraising campaign will be successful before launch using Machine Learning techniques. The project is inspired by the fundraising needs of NayePankh Foundation and utilizes real-world Kickstarter campaign data to analyze factors affecting campaign success.

## Objective

The main objective of this project is to:

* Analyze fundraising campaign data.
* Identify factors influencing campaign success.
* Build Machine Learning models to predict campaign outcomes.
* Compare multiple models and evaluate their performance.
* Generate actionable insights for better fundraising strategies.

## Dataset

**Dataset Used:** Kickstarter Projects Dataset

The dataset contains information about crowdfunding campaigns, including:

* Category
* Main Category
* Currency
* Goal Amount
* Country
* Launch Date
* Deadline
* Campaign Status

### Target Variable

* Successful Campaign → 1
* Failed Campaign → 0

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

## Project Workflow

### 1. Data Preprocessing

* Removed unnecessary columns.
* Handled missing values.
* Converted categorical variables into numerical format.
* Created campaign duration feature.

### 2. Exploratory Data Analysis (EDA)

* Campaign Success Distribution
* Goal Amount Distribution
* Success Rate by Category
* Success Rate by Country
* Campaign Duration vs Success

### 3. Machine Learning Models

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

### 4. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Results

* Random Forest achieved the best performance among all models.
* Decision Tree performed better than Logistic Regression.
* Goal Amount was identified as the most important feature.
* Campaign Duration was the second most influential factor.

## Key Insights

* Failed campaigns outnumber successful campaigns.
* Moderate fundraising goals tend to have higher success rates.
* Campaign category significantly impacts fundraising outcomes.
* Campaign duration plays an important role in campaign performance.
* Success rates vary across different countries and categories.

## Prediction System

The trained Random Forest model can predict whether a campaign is likely to succeed or fail before launch based on:

* Goal Amount
* Category
* Main Category
* Country
* Currency
* Campaign Duration

This can help organizations make data-driven fundraising decisions and improve campaign planning.

## Conclusion

This project demonstrates how Machine Learning can be used to predict fundraising campaign success and support strategic decision-making. By leveraging campaign characteristics and historical data, organizations can better allocate resources and improve fundraising effectiveness.

## Future Improvements

* Hyperparameter Tuning
* Cross-Validation
* Deployment using Streamlit
* Real-Time Campaign Success Prediction Dashboard
* Campaign Recommendation System

## Author

Dikshita Bargoda

Machine Learning
