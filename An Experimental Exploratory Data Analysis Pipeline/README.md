The goal of this project is to develop several step for a wide exploratory data analysis that overcome its limits.
For this goal I've developed a process for a classification problem: predict the propensity to fund a loan by customers.
With this pipeline I overcome the visualization step, because I go deeply into the data set with statistics analysis of the features, dropping not helpful variables. I create features that improve the prediction and finally I have a peek at the several baseline models (without tuning) also trying to extract best features for a better interpretation of the models.
The Modelling part is split into 2 steps: the first one applying models to the unbalanced target variable, the second one handling the unbalanced target variable with a resample method: over-sampling. 
For this purpose I've used a data set from CrowdAnalytix: https://www.crowdanalytix.com/contests/propensity-to-fund-mortgages
