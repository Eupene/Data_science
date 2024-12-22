Health Insurance Premium Prediction and Utilization Analysis
This project aims to develop a predictive model to assist a health insurance organization in accurately determining the premium to charge subscribers. The objective is to minimize risks, maximize profitability, and identify potential low-cost subscribers.

Project Overview
Problem Statement
Health insurance organizations face challenges in determining appropriate premiums due to variability in subscriber expenses. Current approaches often lead to:

Undercharging high-expense subscribers, resulting in losses.
Overcharging low-expense subscribers, deterring potential customers.
The goal is to build a predictive model capable of:

Estimating the total cost (utilization) for a subscriber based on their characteristics.
Identifying least-cost subscribers to optimize profit margins.
Objectives
Predict Utilization: Predict the total expenses incurred by a subscriber.
Premium Recommendation: Determine appropriate premiums based on risk profiles.
Subscriber Segmentation: Identify low-cost subscribers for targeted marketing.
Dataset Description
The dataset contains 2,500 observations and the following features:

Feature	Description
Enrolee	Subscriber identifier
Gender	Gender of the subscriber
Marital Status	Whether the subscriber is married or not
Age	Age of the subscriber
Policy Start Date	Date when the subscriber joined the scheme
Policy End Date	Date when the subscriber exited the scheme
Base Premium	Minimum charge for all subscribers
Smokes	Whether the subscriber smokes
Work Industry	Industry of employment
Pre-existing Condition	Presence of pre-existing health conditions
Premium after Risk Loading	Amount charged annually post-risk adjustments
Hypertension	Presence of hypertension
Diabetes	Presence of diabetes
Dyslipidaemia	Presence of Dyslipidaemia/Hyperlipidaemia
Refractive Error	Presence of refractive error
Spondylosis	Presence of spondylosis
Stomach Ulcer	Presence of stomach ulcer
No. of Hospital Visits	Number of hospital visits in a year
Consultation Charges (GP)	Charges for general practitioner services
Consultation Charges (SP)	Charges for specialist practitioner services
Cost of Drugs	Cost of drugs covered under the scheme
Cost of Lab Services	Cost of lab services requested in a year
No. of Lab Visits	Number of times lab services were requested
No. of GP Visit	Number of GP visits in a year
No. of SP Visit	Number of SP visits in a year
Utilization	Total cost incurred by the subscriber within a year
Approach and Methodology
Data Preprocessing

Handle missing values and outliers.
Recoding features for improved analysis.
Feature engineering to create new insights.
Exploratory Data Analysis (EDA)

Visualize relationships between variables.
Understand distributions and trends.
Predictive Modeling

Regression models for predicting Utilization.
Classification models for subscriber segmentation.
Evaluation Metrics

Regression: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R².
Classification: Precision, Recall, F1 Score, AUC-ROC.
Deployment

Recommendations for premium determination.
Segmenting least-cost subscribers for marketing.
Project Deliverables
Presentation

Summary of findings and methodology.
Visualizations and key insights.
Predictive model performance evaluation.
Report


