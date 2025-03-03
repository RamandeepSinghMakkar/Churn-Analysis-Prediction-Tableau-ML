# Churn-Analysis-Prediction-Tableau-ML
This project was created by   **Ramandeep Singh Makkar** [<img align="center" src= "https://github.com/CLorant/readme-social-icons/blob/main/large/filled/linkedin.svg" alt="LinkedIn" height="15" width="20" />](https://www.linkedin.com/in/ramandeep-singh-makkar) [<img align="center" src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Gmail_icon_%282020%29.svg" alt="Gmail" height="15" width="20" />](mailto:ramandeepsinghmakkar199@gmail.com)



## Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Tools and Technologies Used](#tools-and-technologies-used)
- [Skills Demonstrated](#skills-demonstrated)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Churn Prediction](#churn-prediction)
- [Exploratory Data Analysis for Predicted Data](#exploratory-data-analysis-for-predicted-data)
- [Business Insights & Recommendation](#business-insights--recommendation)


## Overview
Customer churn is a critical issue for businesses, and analyzing churn patterns helps in developing retention strategies. This project consists of two key parts:

1️⃣ Churn Analysis : Utilizing Tableau dashboards to explore customer behavior, identify key factors contributing to churn, and visualize trends that impact customer retention. Tableau Public Link .
![Churn Analysis](https://github.com/RamandeepSinghMakkar/Churn-Analysis-Prediction-Tableau-ML/blob/main/Plots/Churn%20Analysis.png)

2️⃣ Churn Prediction : Implementing three Machine Learning Classification models (Logistic Regression, Random Forest, KNN) to classify customers as potential churners, predict churn probability, and evaluate model accuracy using real customer data. Logistic Regression performed the best with an accuracy of 89.18%.
![Churn Prediction](https://github.com/RamandeepSinghMakkar/Churn-Analysis-Prediction-Tableau-ML/blob/main/Plots/churn%20prediction.png)


## Objectives

Identify Key Drivers Behind Customer Churn: Analyze customer data to pinpoint the primary factors contributing to churn.
Segment Customer Profiles: Classify customers according to their churn risk to understand which segments are most likely to leave the service.



## Tools and Technologies Used

Tableau: Data visualization, dashboards, and churn analysis.
Python (Jupyter Notebook): Data preprocessing and modeling.
Logistic Regression, Random Forest& KNN: Machine learning models for churn prediction.
Pandas & NumPy: Data manipulation and processing.
Git and GitHub: For Version Control.



# Skills Demonstrated

Data Visualization – Tableau dashboards for churn insights.
Exploratory Data Analysis (EDA) – Identifying key churn drivers.
Machine Learning – Implementing a churn prediction model(Logistic Regression, Random Forest, KNN).
Feature Engineering – Selecting key variables for ML.
Model Evaluation – Analyzing model accuracy & performance.
Data Cleaning - Handled missing values and ensured consistency in data types across all attributes.
Business Understanding – Applying data insights for decision-making.


# Exploratory Data Analysis (EDA) :--

Dataset :
This dataset, provided by Databel Telecom, is available for download on [Kaggle](https://www.kaggle.com/datasets/yichienchong/databel-telecom-customer-churn-dataset).  
The dataset consists of 29 columns and 6687 records.

1. The churn rate of Databel is 26.86%

2. Churn Category Reason :

Almost half of all customer churning are related to the competitor category (44.82%).

3. Churn Reason :

Top 5 reasons of churn customer in Databel :

Competitor made better offer (26.79%)
Competitor had better devices (26.26%)
Attitude of support person (17.95%)
Don't know (10.88%)
Competitor offered more data (9.73%)

![Churn Reason](https://github.com/RamandeepSinghMakkar/Churn-Analysis-Prediction-Tableau-ML/raw/main/Plots/Churn%20Reason.png)


4. Age Group :

The age group of 80-85 year old have the highest churn rates (52%) but they contain the least of people (only 25 customers).
![Age group](https://github.com/RamandeepSinghMakkar/Churn-Analysis-Prediction-Tableau-ML/blob/main/Plots/Age%20Group%20vs%20Number%20of%20Customers.png)

5. Churn Rate by Group of Customer :

The lowest churn rate (5.6%) is a customer group consisting of 6 people and conversely, the highest churn rate (32.85%) is for customers who are Not in a Group.

![Churn Rate by Group](https://github.com/RamandeepSinghMakkar/Churn-Analysis-Prediction-Tableau-ML/blob/main/Plots/Churn%20Rate%20by%20Group%20of%20Custome.png)



## Churn Prediction

Business Understanding :--

Problem Statement :

The goal is to develop a predictive model that accurately identifies customers who are likely to churn based on historical data. This will enable the business to take data-driven actions to prevent churn and improve customer retention rates.
Project Goal :

To build a Machine Learning model that predicts the likelihood of customer churn based on key factors such as customer behavior, service usage, contract details, and charges, allowing the business to intervene and retain valuable customers.
Objectives :

Develop a Machine Learning model to predict churn probability.
Identify the Most influential factors that contribute to customer churn.
Evaluate model performance using accuracy, precision, recall, and F1-score.
Compare actual vs. predicted churn to assess the effectiveness of the model.
Provide actionable insights for customer retention strategies.




# Exploratory Data Analysis for Predicted Data(EDA) :--

Tableau Prediction Analysis

After Using the Logistic Regression Model, further analysis for the predicted data is done by the model in Tableau.

1. Probability Distribution:

The overlapping histogram with more data towards the edges indicates the probabilities predicted gave us definative results.

![Churn Rate by Group](https://github.com/RamandeepSinghMakkar/Churn-Analysis-Prediction-Tableau-ML/blob/main/Plots/Probability%20Distribution.png)


2. High-Risk Segments:

High-risk segments such as customer service calls and international plan from different states effects the median prediction probabilities of churn.

![High-Risk Segments](https://github.com/RamandeepSinghMakkar/Churn-Analysis-Prediction-Tableau-ML/blob/main/Plots/High-Risk%20Segments.png)

3. Actual and predicted Churn:

Analyzed actual and predicted churn which has less values in the middle indicating good modelling.

![Actual and predicted Churn](https://github.com/RamandeepSinghMakkar/Churn-Analysis-Prediction-Tableau-ML/blob/main/Plots/Actual%20and%20predicted%20Churn.png)




## Business Insights & Recommendation :

### Insights : 
  - **High Churn in High Usage Customers:**
    > Customers with high day charges and frequent service calls are at a higher risk of churn, indicating dissatisfaction potentially due to billing or service issues.
    
  - **Regional Variations:**
    > Certain states with higher churn rates may require localized customer retention strategies.
    
  - **International Plan Sensitivity:**
    >Customers with international plans are more likely to churn, suggesting a need to reevaluate the pricing or quality of international services.

###  Recommendation :  

   - **Improve Customer Service:**
     >Focus on reducing the number of customer service calls by enhancing first-call resolution and proactively addressing common issues.
   
   - **Reassess International Plan Offerings:**
     >Consider revising international plans to make them more competitive and aligned with customer expectations.

   - **Targeted Retention Strategies:**
      > Use the model's predictions to identify high-risk customers and implement targeted retention campaigns, such as personalized offers or discounts for heavy day-time users.

The project successfully identified key drivers of customer churn and built a predictive model with strong performance metrics using Logistic Regression Model. The insights derived from the data and the model can be leveraged to implement effective churn reduction strategies, potentially leading to significant cost savings and improved customer satisfaction created using Tableau Public.


