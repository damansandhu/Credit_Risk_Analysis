# Credit_Risk_Analysis

## Overview of Analysis
  In this project we look at factors to predict if someone is at a high or low credit risk. We use models using (imbalanced-learn and scikit-learn libraries) and then evaluate these models using the resampling method. First models used randomoversampler and SMOTE algorithms and then undersample the data using clustercentroid algorithm. A balanced random forest classifier and easy ensemble calssifier was then used to reduce bias.
  
## Results:
* Logistic Regression Matrix
![log_reg](https://raw.githubusercontent.com/damansandhu/Credit_Risk_Analysis/main/Results/logistic_regression_matrix.png)

* Balanced Random Forest Classifier
![bal_ran](https://raw.githubusercontent.com/damansandhu/Credit_Risk_Analysis/main/Results/balanced_random_forest.png)

* SMOTE
![SMOTE](https://raw.githubusercontent.com/damansandhu/Credit_Risk_Analysis/main/Results/SMOTE_Report.png)

* Easy Ensemble
![ensemble](https://raw.githubusercontent.com/damansandhu/Credit_Risk_Analysis/main/Results/easy_ensemble.png)

## Summary

Our Logistic Regression model had an F1 score of 75%, the balanced random forest classifier had an accuracy score of 79.9%, the SMOTE classifier had an accurace score of 66.2%, and the easy ensemble classifier had an accuracy score of 91.5%. Out of the models the Easy Ensemble model had the highest accuracy. Not only did it have an accuracy score of 91.5%, but the F1 score was 91%, which takes into account precision and recall. Easy Ensemble model would be the model recommended to determine high and low credit risks in this scenario.
