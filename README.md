# Ad Click Prediction & CTR Analytics Dashboard

<h3>Data Sources</h3>
Sales Data: The primary dataset used for this analysis is the "ad_click_dataset.csv" file. 

<h3>Project Overview</h3>

This dataset provides insights into user behavior and online advertising, specifically focusing on predicting whether a user will click on an online advertisement. It contains user demographic information, browsing habits, and details related to the display of the advertisement. This dataset is ideal for building binary classification models to predict user interactions with online ads.

## Business Problem

Online advertising platforms need to understand which users are more likely to click on ads in order to improve targeting and campaign performance.
This project analyzes user behavior, device usage, demographics, and browsing patterns to identify key factors influencing ad click performance.

<h3>Features</h3>

<b>id:</b> Unique identifier for each user.

<b>full_name:</b> User's name formatted as "UserX" for anonymity.

<b>age:</b> Age of the user (ranging from 18 to 64 years).

<b>gender:</b> The gender of the user (categorized as Male, Female, or Non-Binary).

<b>device_type:</b> The type of device used by the user when viewing the ad (Mobile, Desktop, Tablet).

<b>ad_position:</b> The position of the ad on the webpage (Top, Side, Bottom).

<b>browsing_history:</b> The user's browsing activity prior to seeing the ad (Shopping, News, Entertainment, Education, Social Media).

<b>time_of_day:</b> The time when the user viewed the ad (Morning, Afternoon, Evening, Night).

<b>click:</b> The target label indicating whether the user clicked on the ad (1 for a click, 0 for no click).

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
- Accuracy: 79%
- Cross-validation score: 79%

## Tableau Dashboard

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
