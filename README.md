# Forest Fire Prediction Project in Data Science Course

## 1. The problem we address 
In this project we are trying to address the disadvantages of forest fires to be able to salvage as much as we can from the damage caused by forest fires by predicting its occurrence. If the forest fires are predicted accurately, citizens could leave immediately and prepare for that course of action ahead of time. There will be time to make an evacuation plan to minimize the loss of human lives. 
***
## 2. Expected Results 
Getting to understand the features of this database and the science behind first fires; we expected some of
the analytics. for example:
1. Fires are expected to happen seasonally every year in months more than other
2. dry weather will contribute to more frequent fires there for low humidity translated to more fires
3. High winds make fires spread faster therefore bigger lands are burned in high wind low humidity
months
4. Rain of course is a huge factor because Month having no rainfall is more prone to catch forest fire
***
## 3. Collected Dataset 
    Source: https://archive.ics.uci.edu/ml/datasets/forest+fires

***
## 4. Data Analysis Plan 
    1. Data Analytics of the dataset is made to better understand the data features and their correlation with one another. Along with visualizing the features.
    2. Searching for outliers and null values in the dataset. The null values is going to be filled either (mean,median or mode) while the outliers will be handled by (z score)
    3. Skewed features will be handled by normal scaling
    4. Feature selection is done by Recursive Feature Elimination which chooses the most correlated features and ignores the most correlated ones. Also PCA is tried.
    5. Different Models are tried and tested to see which will yield the highest accuracy
    6. A final evaluation of each model


