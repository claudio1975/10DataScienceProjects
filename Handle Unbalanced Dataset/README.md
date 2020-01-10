In a classification task a typical problem is the unbalanced dataset, so the goal is to use techniques that allow overcome this issue. For this purpose I've taken two datasets from Kaggle.

The first one to build a credit scoring model: https://www.kaggle.com/ajay1735/hmeq-data 
The project is developed in several step:
-Baseline models (I've only encoded categorical variables and filled in missing values)
-Resampling Methods applied to the baseline models
-Stratified Cross-Validation applied to the baseline models
-Resampling Methods (OVER-SAMPLING, UNDER-SAMPLING) and Stratified Cross-Validation applied to the baseline models
-Resampling Methods (SMOTE, ADASYN) and Stratified Cross-Validation applied to the baseline models

The second one to build a credit card scoring model: https://www.kaggle.com/yuzijuan/credit-card-scoring
The project is developed in several step:
-Baseline models 
-Applied Resampling Method with H2O

