# Which Resume Attributes Drive Job Callbacks?

This repository contains code for analyzing the factors that influence job callbacks using a dataset of resumes and job advertisements. The code includes data preprocessing, visualization, and machine learning techniques to identify the attributes that have the strongest impact on callback rates.

![Data](https://github.com/shahjahnavi/resume_attributes_job_callbacks/assets/138523298/2636fa3b-609d-45ae-9448-94349acf250a)


## Data Preprocessing

The code begins by importing the necessary libraries and loading the resume dataset. The data is then cleaned and preprocessed by handling missing values, converting categorical variables to numerical representations, and removing irrelevant columns.

## Data Visualization

To gain insights into the data, various visualizations are created using matplotlib and seaborn libraries. These visualizations include scatter plots, bar charts, and heatmaps, which help to identify patterns and relationships between variables.

![Correlation Heat-Map](https://github.com/shahjahnavi/resume_attributes_job_callbacks/assets/138523298/d26cfca8-f8a1-4eaa-9ff6-1bd86eb0acd5)


## Univariate Analysis

Univariate analysis is performed to examine the distribution of individual variables and their relationship with the target variable (received callback). This analysis reveals that certain attributes, such as job_city, job_industry, and resume_quality, have a significant impact on callback rates.

## Bivariate Analysis

Bivariate analysis is conducted to explore the interactions between pairs of variables. For instance, the relationship between job_city and callback rates is examined across different gender groups.

![Image](https://github.com/shahjahnavi/resume_attributes_job_callbacks/assets/138523298/a474e770-7454-4215-9424-94bd5347f3dd)

![Image](https://github.com/shahjahnavi/resume_attributes_job_callbacks/assets/138523298/49eec840-dd3e-421d-934e-6f7905d41149)


## Machine Learning

Three machine learning algorithms - logistic regression, support vector machines (SVM), and K-nearest neighbors (KNN) - are applied to predict callback rates based on the resume attributes. The results indicate that logistic regression and random forest models achieve the highest accuracy.

## Feature Importance

The feature importance of the resume attributes is determined using the decision tree classifier. This analysis reveals the relative contribution of each attribute towards predicting callback rates.

## Conclusion

The analysis provides valuable insights into the factors that influence job callbacks. The results suggest that resume quality, job industry, and job city play a significant role in determining callback likelihood. These findings can be useful for job seekers in tailoring their resumes to specific industries and cities to increase their chances of receiving callbacks.
