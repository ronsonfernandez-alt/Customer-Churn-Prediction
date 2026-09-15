Customer Churn Prediction

A predictive analytics project that identifies customers likely to churn using behavioral and transactional data. The workflow covers exploratory data analysis, feature engineering, and machine learning modeling in Python with a Random Forest classifier, reaching approximately 79% accuracy, and exports results for Power BI dashboards that visualize churn insights and support retention strategy.

Overview

Losing customers is costly, and knowing who is likely to leave (and why) lets a business act before it happens. This project builds an end-to-end pipeline on the Telco Customer Churn dataset: it explores and cleans the data, engineers features, trains and evaluates a Random Forest model, examines the top drivers of churn, and exports the results so they can be visualized and acted on in Power BI.

Workflow

The project is organized into clear, sequential stages:

Data Loading and Exploration — load the Telco Customer Churn dataset and inspect its structure, summary info, and missing values.
Data Cleaning and Preprocessing — handle missing values, encode categories, and prepare the data for modeling.
Train-Test Split and Scaling — split the data into training and test sets and scale features.
Model Training and Evaluation — train a Random Forest classifier and evaluate performance (~79% accuracy).
Feature Importance Visualization — plot the top 10 features influencing churn.
Exporting Results for Power BI Visualization — export predictions and insights for dashboarding.
Key Results
Achieved approximately 89% accuracy in predicting customer churn.
Surfaced the top 10 drivers of churn through Random Forest feature importance.
Delivered Power BI dashboards for churn insights and retention strategy visualization.
Tech Stack
Language: Python
Libraries: pandas, NumPy, scikit-learn (Random Forest), Matplotlib
Visualization: Power BI
Dataset: Telco Customer Churn (Telco-Customer-Churn.csv)
Getting Started
bash
# Clone the repository
git clone https://github.com/ronsonfernandez-alt/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction

# Install dependencies
pip install pandas numpy scikit-learn matplotlib

Make sure Telco-Customer-Churn.csv is in the project folder, then run the stages in order (Data Loading and Exploration through Exporting Results). Open the exported results in Power BI to view the dashboards.

Possible Improvements
Compare multiple models (Logistic Regression, XGBoost) and tune hyperparameters.
Add cross-validation for more robust performance estimates.
Address class imbalance with techniques such as SMOTE if churners are underrepresented.
