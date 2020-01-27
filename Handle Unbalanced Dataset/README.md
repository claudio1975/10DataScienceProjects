In a classification task a typical problem is the imbalanced data set, so the goal is to use techniques that allow overcome this issue. For this purpose I've taken a data set from Kaggle to build a credit scoring model: https://www.kaggle.com/ajay1735/hmeq-data 

The project is developed both in R & Python and in several steps.

Python approach:

-Baseline models (I've only encoded categorical variables and filled in missing values)

-Resampling Methods applied to the baseline models

-Stratified Cross-Validation applied to the baseline models

-Resampling Methods (OVER-SAMPLING, UNDER-SAMPLING) and Stratified Cross-Validation applied to the baseline models

-Resampling Methods (SMOTE, ADASYN) and Stratified Cross-Validation applied to the baseline models

R approach:

-Baseline models with Caret 

-Resampling Methods with Caret (UNDER-SAMPLING, OVER-SAMPLING, SMOTE, ROSE)

-Resampling Method with H2O

