# Predicting-Sleep-Qaulity-using-Machine-learning


### Overview

This project focuses on predicting sleep quality by integrating geographic, physical, and lifestyle factors using machine learning models. The analysis leverages the All of Us Dataset to provide personalized health recommendations, aiming to enhance sleep quality and overall well-being.

### Motivation

1. Sleep and Health: Poor sleep quality is linked to conditions like cardiovascular diseases, obesity, and mental health disorders.

2. Key Problem: How can machine learning models predict sleep quality by integrating diverse data types for personalized recommendations?

### Challenges
1. Variability in sleep patterns across demographics and regions.
2. Complex relationships between physical activity and sleep outcomes.
3. Identifying key predictors for restful sleep efficiency in diverse populations.

## Workflow

1. Data Preprocessing
Data Collection and Cleaning: Ensured data quality from various sources.
Feature Engineering: Transform raw data into structured formats for analysis.
Data Filtering and Integration: Applied filters for consistent periods and combined data from different sources into a unified dataset.

2. Understanding Sleep Stages and Metrics
Light Sleep: Initial relaxation stage.
Deep Sleep: Restorative stage for repair and memory consolidation.
REM Sleep: Dreaming phase with brain activity.
Custom Metric: Combined sleep stages and disturbances (e.g., minutes awake/restless) for a holistic sleep quality score.

3. Building Machine Learning Models
Models Used: Random Forest Regressor and XGBoost for feature importance analysis.
Training Data: Fitbit data for accuracy improvement.
Evaluation Metrics: RMSE of 5.8753 and Accuracy of 91%.

4. Personalized Recommendations
Sleep Insights: Analysis of sleep patterns and factors.
Tailored Recommendations: Customized strategies to improve sleep.
Behavior Change Support: Techniques to promote healthier sleep habits.

5. Intuitive Web App Design
Dashboards: Monitor sleep patterns and quality.
Data Visualization: Engaging graphs and charts.
Scheduling Tools: Plan and maintain healthy sleep routines

### Result

1. Model Performance: RMSE of 5.88 and an accuracy of 91%.
2. Impact: Personalized insights and recommendations empower users to improve sleep quality.

### Technologies Used

Programming Language: Python

Libraries: pandas,numpy ,scikit-learn, matplotlib ,seaborn,pipeline, GridSearchCV

Machine Learning Libraries : GradientBoostingRegressor, RandomForestRegressor, xgboost

Data Source: All of Us Dataset

Tools: Jupyter Notebook, Fitbit APIs

### Acknowledgments

Special thanks to the hackathon organizers and the All of Us Research Program for providing data and resources.