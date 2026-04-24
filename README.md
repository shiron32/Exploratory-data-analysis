🚀 Project Title

Insurance Cost Analysis & Risk Profiling using Exploratory Data Analysis

📌 Project Overview

This project performs a comprehensive end-to-end Exploratory Data Analysis (EDA) on an insurance dataset to uncover key drivers of medical charges and prepare the data for predictive modeling.

The objective is to move beyond surface-level visualization and build a data-driven understanding of cost behavior, risk segmentation, and feature relationships that directly inform machine learning model design.

The dataset contains demographic and behavioral attributes such as age, BMI, smoking status, and region, with insurance charges as the target variable.

🎯 Project Objectives
Understand the distribution and structure of the dataset
Identify key factors influencing insurance charges
Detect data quality issues such as skewness or outliers
Analyze relationships between variables
Derive preprocessing strategies for machine learning
Translate findings into business-relevant insights
🧠 EDA Framework (Step-by-Step Thinking)

Your workflow should reflect structured reasoning, not just plots:

1. Data Understanding

Questions:

What are the features and their data types
Are there missing or inconsistent values
What is the size and structure of the dataset
2. Target Variable Analysis (Charges)

Questions:

What is the distribution of insurance charges
Is the distribution normal or skewed
Are there extreme values or outliers
Would transformation improve modeling performance

Insight to highlight:

Charges are right-skewed, indicating need for transformation
3. Univariate Analysis

Questions:

How are numerical features distributed (age, BMI, children)
Are there unusual patterns or anomalies
How are categorical features distributed (smoker, sex, region)
4. Bivariate Analysis (Feature vs Target)

Questions:

How does smoking status affect charges
Does BMI significantly influence cost
Is there a relationship between age and charges
Do regions show cost variation
Does number of children impact cost

Key Insight:

Smoking status is the strongest predictor of insurance charges
5. Multivariate Analysis

Questions:

Are there interaction effects (e.g., smoker + age, BMI + smoker)
Do combined factors explain cost better than individual features
Can high-risk groups be visually identified
6. Correlation & Feature Relationships

Questions:

Are numerical features correlated with each other
Is multicollinearity present
Which features have the strongest relationship with charges

Key Insight:

No significant multicollinearity among numerical features
7. Outlier Analysis

Questions:

Are there extreme charge values
Do outliers represent real-world high-risk cases
Should outliers be removed or retained
8. Risk Segmentation

Questions:

Can customers be grouped into low, medium, and high cost
What characteristics define high-risk individuals
How can this segmentation help business decisions
⚙️ Preprocessing Strategy (Derived from EDA)

Based on your findings, clearly state what you will do before modeling:

1. Target Transformation
Apply log transformation to handle skewness in charges
2. Encoding
Convert categorical variables using one-hot encoding
3. Feature Engineering
Create interaction features:
smoker × BMI
age × BMI
4. Scaling
Apply scaling if using linear models
5. Outlier Handling
Retain outliers if they represent real high-cost cases
Optionally cap extreme values
📊 Key Insights (Portfolio Highlights)
Insurance charges exhibit a right-skewed distribution, requiring transformation for effective modeling
Smoking status has a dominant impact on cost, significantly increasing charges
BMI and age show moderate correlation with charges, especially when combined with smoking
No strong multicollinearity detected, allowing stable model training
High-cost individuals can be clearly segmented, enabling risk-based pricing strategies
💼 Business Interpretation
Smoking behavior is the primary cost driver, suggesting targeted premium strategies
Risk segmentation enables insurers to design personalized pricing models
Feature interactions reveal that combined risk factors amplify costs significantly
The dataset is well-structured and suitable for predictive modeling pipelines
