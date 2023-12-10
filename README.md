# Airline Customer Satisfaction Analysis

## Project Overview

This project involves a thorough analysis of factors influencing customer satisfaction in the airline industry. Utilizing a dataset named 'Invistico_Airline_Cleaned.csv' gotten from Kaggle, the project aims to uncover insights that can aid airlines in enhancing their service quality and overall customer experience. The analysis encompasses a range of variables, including customer demographics, travel class, flight distance, and various service ratings.

## Objectives

To identify key factors that significantly impact customer satisfaction in the airline industry.
To develop a predictive model to forecast customer satisfaction based on these identified factors.
To provide actionable recommendations for service improvement based on the analysis findings.

## Data Description
The dataset contains various features such as customer age, type of travel (business/personal), class of travel, flight distance, and ratings for different services like seat comfort, inflight entertainment, food and drink, online support, and more. The target variable is customer satisfaction, categorized into 'satisfied' and 'dissatisfied'.

## Methodology
Data Preprocessing: The dataset underwent preprocessing which included encoding categorical variables and splitting the data into training and test sets.

Exploratory Data Analysis (EDA): We conducted EDA to explore distributions and relationships in the dataset, particularly focusing on how different factors correlate with customer satisfaction.

Predictive Modeling: A Random Forest Classifier was employed to predict customer satisfaction. The model's performance was evaluated using metrics like accuracy, precision, recall, and F1-score.

Feature Importance Analysis: Post-modeling, we conducted an analysis to determine which features were most influential in predicting customer satisfaction.

## Key Findings
Service quality factors such as inflight entertainment, seat comfort, and ease of online booking were identified as primary influencers of passenger satisfaction.
The Random Forest model achieved an accuracy of approximately 95.72%, demonstrating strong predictive capability.
The analysis provided insights that can guide airlines to prioritize areas for service improvement.

## Conclusion and Recommendations
The project concluded that enhancing certain aspects of service quality, particularly comfort and entertainment, could significantly improve customer satisfaction. Recommendations for airlines include focusing on these areas, minimizing delays, and offering better online services to enhance the overall customer experience.

## Tools and Technologies Used
Python (for data analysis and modeling)
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
Jupyter Notebook (for code execution and visualization)

## Future Work
Further research may include incorporating more granular data like specific customer feedback or broader operational metrics. Additional modeling techniques or variables could also be explored for deeper insights.

