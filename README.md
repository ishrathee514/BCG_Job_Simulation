# BCG X – Data Science Job Simulation

Overview

This project simulates the work of a data scientist at BCG X, helping a utility company analyze customer churn behavior and develop predictive models to improve customer retention.

The project follows the full data science workflow including exploratory data analysis, feature engineering, machine learning modeling, and business insight generation.

The objective is to identify customers who are likely to churn and determine the key drivers behind customer attrition.

🎯 Business Problem

The energy provider PowerCo is experiencing customer churn and is concerned about losing customers to competitors.

The company suspects that customers may be leaving due to price sensitivity and changes in energy pricing.

The goal of the analysis is to determine the key factors that drive customer churn, evaluate whether pricing changes influence churn behavior, and develop predictive models that can identify customers at risk of leaving.

By understanding churn drivers, the company can design more effective customer retention strategies.

🧩 Project Structure
Task 1 — Exploratory Data Analysis (EDA)

Exploratory data analysis was conducted to understand the structure and characteristics of the data before building predictive models.

The analysis was performed on three primary datasets including customer data, pricing data, and churn indicators.

The objective of this step was to identify data quality issues, understand variable distributions, and discover potential relationships between customer characteristics and churn behavior.

Key analytical steps included inspecting data structures, validating data types, identifying missing values, performing descriptive statistical analysis, and visualizing variable distributions.

Several visualization techniques were used including histograms, boxplots, bar charts, and outlier detection methods to understand how variables behave across different customers.

The analysis revealed that the churn rate was approximately ten percent, customer consumption data showed positively skewed distributions, and some variables contained significant outliers.

It was also observed that certain categorical variables did not have a strong relationship with churn behavior.

These insights helped guide the next stage of feature engineering and modeling.

Task 2 — Feature Engineering

Feature engineering was performed to create new predictive variables that could improve machine learning model performance.

The process involved transforming raw data into structured variables that better represent customer behavior and pricing patterns.

Several techniques were applied including removing irrelevant columns, transforming date variables into useful time-based features, creating price sensitivity indicators, generating dummy variables for categorical attributes, and applying logarithmic transformations to handle skewed distributions.

New features were created to capture patterns such as price sensitivity, differences in off-peak prices across months, average price changes, maximum price differences, consumption stability, and customer tenure.

Data preparation steps included normalization, log transformations, outlier treatment, and correlation analysis to ensure the dataset was suitable for machine learning algorithms.

These transformations helped convert the dataset into a model-ready format.

Task 3 — Machine Learning Model

A Random Forest classification model was developed to predict customer churn.

The model uses multiple decision trees to identify complex relationships between customer attributes and churn outcomes.

Key predictive inputs included customer tenure, energy consumption levels, price sensitivity indicators, profit margins, and contract characteristics.

The model development workflow included splitting the dataset into training and testing sets, training the machine learning model, generating churn predictions, and evaluating model performance.

Model performance was evaluated using common classification metrics including accuracy, precision, recall, and F1 score.

The model achieved an accuracy of approximately eighty-five percent.

However, the model demonstrated lower recall for churned customers, indicating that additional feature engineering or model tuning could further improve predictive performance.

Feature importance analysis revealed that net margin, annual energy consumption, and customer tenure were among the strongest predictors of churn.

Interestingly, price sensitivity variables were not as influential as initially expected.

📈 Business Insights

Several important insights emerged from the analysis.

Customers with higher energy consumption were less likely to churn, suggesting that high-usage customers may have stronger relationships with the provider.

Pricing changes alone did not strongly explain customer churn behavior.

Instead, factors such as customer tenure and profitability were stronger indicators of whether customers remained with the company.

These findings suggest that retention strategies should focus on high-value customers and long-term relationships rather than focusing solely on price adjustments.

🛠 Skills Demonstrated

"Data Analysis",
"Exploratory Data Analysis",
"Feature Engineering",
"Machine Learning",
"Predictive Modeling",
"Model Evaluation",
"Python",
"Business Analytics",
"Statistical Analysis",
"Customer Churn Analysis",
"Data Visualization",
"Analytical Thinking"
