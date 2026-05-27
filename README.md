# Ad Click Prediction & CTR Analytics Dashboard
<img width="1802" height="1056" alt="Screenshot 2026-05-26 at 5 16 08 PM" src="https://github.com/user-attachments/assets/f83fb4aa-f600-4c4d-89fa-8bb7b37209f9" />

<h3>Data Sources</h3>
Sales Data: The primary dataset used for this analysis is the "ad_click_dataset.csv" file. 

<h3>Project Overview</h3>

This dataset provides insights into user behavior and online advertising, specifically focusing on predicting whether a user will click on an online advertisement. It contains user demographic information, browsing habits, and details related to the display of the advertisement. This dataset is ideal for building binary classification models to predict user interactions with online ads.

## Business Problem

Online advertising platforms need to understand which users are more likely to click on ads in order to improve targeting and campaign performance.
This project analyzes user behavior, device usage, demographics, and browsing patterns to identify key factors influencing ad click performance.

<h3>Goal</h3>

The objective of this dataset is to predict whether a user will click on an online ad based on their demographics, browsing behavior, the context of the ad's display, and the time of day. 
You will need to clean the data, understand it and then apply machine learning models to predict and evaluate data. It is a really challenging request for this kind of data. This data can be used to improve ad targeting strategies, optimize ad placement, and better understand user interaction with online advertisements.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Tableau
- Jupyter Notebook
- Data Visualization
- Machine Learning

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Preprocessing
5. Machine Learning Modeling
6. Dashboard Development
7. Business Insights & Visualization

## Key Insights

- Desktop users showed the highest CTR performance
- Shopping and Social Media audiences had stronger engagement
- Afternoon and Morning periods generated the highest CTR
- Age groups 25–35 demonstrated the strongest click behavior

## Model Performance

Random Forest Classifier achieved:
- Test accuracy: 79%
- Cross-validation accuracy: 79%

## Tableau Dashboard
[View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/elena.bolotin/viz/Ad_Click_Performance_Dashboard/AdClickPerformanceAnalysis)

The interactive dashboard includes:
- CTR by Device Type
- CTR by Time of Day
- CTR by Browsing History
- Feature Importance Analysis
- Audience Segment Analysis


## Future Improvements

- Hyperparameter tuning
- Additional feature engineering
- A/B testing simulation
- Deployment with Streamlit
