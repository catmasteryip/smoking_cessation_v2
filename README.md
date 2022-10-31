# README

# Notebook explanation

1. feature_selection.ipynb is the code for feature selection by checking for alias, VIF and missing rate <br />
2. Learning.ipynb is the code for using sklearn methods to predict long-term outcome <br />
3. imbearn_ml.ipynb is the code for using imblearn ML algo to predict long-term outcome <br />

# Workflow

Feature selection by checking VIF, chi-square test and missing rate -> <br />
Organise features into baseline, M1, M2 and M3 subsets -> <br />
Machine learning method on long-term smoking cessation outcome -> <br />
Output prediction metrics, visualise sample characteristics and feature importance

# Visualisation

![alt text](https://github.com/catmasteryip/smoking_cessation_v2/blob/main/images/tableone.png?raw=true) <br />
Characteristics of subjects stratified by long-term smoking cessation status <br />

![alt text](https://github.com/catmasteryip/smoking_cessation_v2/blob/main/images/gini_importance_m3.png?raw=true) <br />
Gini importance of top 10 important factors in long-term cessation success using easy ensemble <br />
