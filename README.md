# Fundraising Campaign Success Prediction System

## Overview

This project aims to predict whether a fundraising campaign will be successful before launch using Machine Learning techniques. The project is inspired by the fundraising needs of NayePankh Foundation and utilizes real-world Kickstarter campaign data to analyze factors affecting campaign success.

## Objective

The main objectives of this project are to:

* Analyze fundraising campaign data.
* Identify factors influencing campaign success.
* Build Machine Learning models to predict campaign outcomes.
* Compare multiple models and evaluate their performance.
* Generate actionable insights for better fundraising strategies.

## Dataset

**Dataset Used:** Kickstarter Projects Dataset

**Dataset Source:** Kaggle Kickstarter Projects Dataset

For this project, only the **first CSV file** from the Kickstarter dataset collection was used. During development, the file was renamed and used as:

**File Name Used:** `funding campaign.csv`

The dataset contains information about real-world crowdfunding campaigns, including:

* Category
* Main Category
* Currency
* Goal Amount
* Country
* Launch Date
* Deadline
* Campaign Status

### Features Used

* Category
* Main Category
* Currency
* Goal Amount
* Country
* Campaign Duration (created during feature engineering)

### Target Variable

* Successful Campaign → 1
* Failed Campaign → 0

### Dataset Availability

Due to GitHub file size limitations, the dataset is not included in this repository. The original dataset can be downloaded from Kaggle:

Dataset Link: https://www.kaggle.com/datasets/kemical/kickstarter-projects

**Note:** This project utilizes only the first CSV file from the dataset collection, which was renamed to `funding campaign.csv` during development in Google Colab.

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

The following visualizations were created:

* Campaign Success Distribution
* Goal Amount Distribution
* Success Rate by Category
* Success Rate by Country
* Campaign Duration vs Success

### 3. Machine Learning Models

The following classification models were trained and evaluated:

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

### Model Performance

* Random Forest achieved the highest Accuracy and F1 Score.
* Decision Tree performed better than Logistic Regression.
* Random Forest was selected as the best-performing model.

### Feature Importance

The most influential features were:

1. Goal Amount
2. Campaign Duration
3. Category
4. Main Category
5. Country
6. Currency

## Key Insights

* Failed campaigns outnumber successful campaigns.
* Moderate fundraising goals tend to have higher success rates.
* Campaign category significantly impacts fundraising outcomes.
* Campaign duration plays an important role in campaign performance.
* Success rates vary across different countries and categories.
* Goal amount is the strongest predictor of campaign success.

## Prediction System

A Random Forest-based prediction system was developed to predict whether a campaign is likely to succeed or fail before launch.

The model uses:

* Goal Amount
* Category
* Main Category
* Country
* Currency
* Campaign Duration

This enables organizations to make data-driven fundraising decisions and optimize campaign planning.

## Business Recommendations

* Set realistic fundraising goals.
* Focus on campaign categories with historically higher success rates.
* Maintain optimal campaign durations.
* Use predictive analytics before launching campaigns.
* Allocate resources toward campaigns with higher predicted success probabilities.

## Conclusion

This project demonstrates how Machine Learning can be used to predict fundraising campaign success and support strategic decision-making. By leveraging campaign characteristics and historical data, organizations can improve fundraising effectiveness, optimize resource allocation, and increase the likelihood of successful campaigns.

## Future Improvements

* Hyperparameter Tuning
* Cross-Validation
* Streamlit Deployment
* Real-Time Campaign Success Dashboard
* Campaign Recommendation System
* Success Probability Predictor

## Repository Contents

* `fundraising_prediction.ipynb` – Complete Google Colab Notebook
* `Project_Report.pdf` – Detailed Project Report
* `README.md` – Project Documentation

## Author

**Dikshita Bargoda**

Machine Learning 
