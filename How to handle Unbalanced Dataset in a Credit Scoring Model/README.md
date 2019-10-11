In a classification task a typical problem is the unbalanced dataset, the goal is to use techniques that allow overcome this issue.
For this purpose I've taken a dataset from Kaggle to build a credit scoring model: https://www.kaggle.com/ajay1735/hmeq-data
The project is developed in several step:
1) Baseline models (I've only encoded categorical variables and filled in missing values)
2) Resampling Methods applied to the baseline models
3) Stratified Cross-Validation applied to the baseline models
4) Resampling Methods (OVER-SAMPLING, UNDER-SAMPLING) and Stratified Cross-Validation applied to the baseline models
5) Resampling Methods (SMOTE, ADASYN) and Stratified Cross-Validation applied to the baseline models
