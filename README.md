# Exploring Heart Disease
## Overview
A popular dataset on Kaggle is the [Heart Disease UCI](https://www.kaggle.com/ronitf/heart-disease-uci) dataset. 

This [notebook](https://github.com/rebeccaebarnes/heart-disease/blob/master/heart_disease_exploration.ipynb) explores the dataset from a number of approaches, including initial data assessment and cleaning, uni/bi/multivariate exploration, predictive modeling, bayes rule, and an in-depth visualization progression. 

## Technologies Used
- Python
  - Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## Key Findings
- The sample used for the research appears to have been generated using matching for age and sex while having heart disease
- The individual numerical features that are the strongest predictors are `maximum heart rate achieved` and a feature called `old peak`
- These two features had the ability to predict heart disease with an accuracy of almost 70%
- This is not sufficient to produce a strong test based on Bayes Rule for increased change of having heart disease based on the test results
- More findings to come!
