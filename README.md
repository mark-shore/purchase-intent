# Predicting Purchase Intent with Supervised Learning

## Project Overview
This project analyzes website data to predict purchase intent. The performance of three machine learning models is compared to address this classification problem:
- Logistic Regression
- Random Forest
- Support Vector Machine

Predicting purchase intent has significant positive implications for businesses. Understanding the features that influence online shopping conversion can help companies:
- Optimize the conversion funnel
- Improve marketing ROI
- More accurately forecast revenue

## Data Overview
The dataset includes 12,330 sessions, 17 features, and 1 target `Revenue`.

Sakar, C. & Kastro, Y. (2018). *Online Shoppers Purchasing Intention Dataset* [Data set]. UCI Machine Learning Repository. Retrieved from [https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset)

## Data Cleaning
- Encoded categorical data
- Dropped entries labeled as 'Other' in `VisitorType`
- Created a new binary feature `NewVisitor`

## Exploratory Data Analysis
- Correlation matrix
- Pairwise plot
- Box plots

## Models
- Hyperparameter tuning using GridSearchCV
- Training of Logistic Regression, Random Forest, and Support Vector Machine models

## Results and Analysis
- ROC curves
- Confusion matrices
- Accuracy, recall, and F1 score

## Performance
- Random Forest achieved the highest accuracy of 90.6%
- Logistic Regression and SVM also performed well with accuracies of 88.3% and 89.7%, respectively
