# Predicting Traffic Accidents Outcomes
This project uses Logistic Regression to predict the likelihood of injuries in traffic accidents based on factors such as weather conditions, road type, driver age, and traffic density.

## Table of Contents
1. Introduction
2. Methodology
3. Results
4. Conclusion

## Introduction
This project aims to predict injury outcomes in traffic accidents. The dataset includes features like driver age, traffic density, and weather conditions. The model helps in identifying risk factors to improve traffic safety.

## Methodology
Data Cleaning: Handled missing values and removed duplicates.

* EDA: Explored data through univariate and bivariate analysis.

* Preprocessing: Encoded categorical variables, scaled numerical features, and selected top predictors using RFE.

* Modeling: Applied Logistic Regression for binary classification (injury vs. no injury).

## Results
The model achieved an accuracy of 51%, with better recall in predicting injury outcomes. It showed that driver age and traffic density are significant predictors.

## Conclusion
While the model provides valuable insights into traffic safety, further improvements can be made by handling class imbalance and experimenting with more advanced models like Random Forests.
