# Car Crash Analysis

## Problem Statement

Road accidents generate large volumes of structured data but predicting accident severity in real time remains a challenge. 

The goal of this project is to build a machine learning model that predicts whether a road accident will be fatal or non-fatal using features such as vehicle characteristics, environmental conditions, road attributes, and time-related factors.

This model aims to assist in identifying high-risk situations and understanding the factors most strongly associated with fatal outcomes.

As an additional component, the project includes a heatmap of fatal accident locations to visualize geographical risk patterns.

## Workflow

This project involved:
* Data scraping (data taken from NHTSA)
* Data cleaning, preprocessing of mixed (numerical and categorical features)
* Performing feature engineering (the OVERSPD feature is engineered)
* Training multiple ML models
* Creating an ensemble of the ML models
* Selecting the best model of them all based on their ROC-AUC score.

## Conclusion

The analysis shows that Speed, Alcohol Involvement, OverSpeed (engineered feature), and Speed Limit are the most influential factors, together contributing roughly 60% of the model’s feature importance.

The next most important features include airbag deployment, ejection, and weather conditions.

These findings reinforce the role of risky driving behavior and other conditions in determining accident severity.
