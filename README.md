# Determine the Median Value of Owner-Occupied
The project studies about how to determine the median value of owner - occupied (MEDV) using supervised and unsupervised machine learning

# Objective:
Determine the accurate MEDV and find the most accurate method to determine it

# Feature Data-Column:
1. CRIM: Per capita crime rate by town
2. ZN: Proportion of residential land zoned for lots over 25,000 sq. ft
3. INDUS: Proportion of non-retail business acres per town
4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
5. NOX: Nitric oxide concentration (parts per 10 million)
6. RM: Average number of rooms per dwelling
7. AGE: Proportion of owner-occupied units built prior to 1940
8. DIS: Weighted distances to five Boston employment centers
9. RAD: Index of accessibility to radial highways
10. TAX: Full-value property tax rate per $10,000
11. PTRATIO: Pupil-teacher ratio by town
12. B: 1000(Bk — 0.63)², where Bk is the proportion of [people of African American descent] by town
13. LSTAT: Percentage of lower status of the population
14. MEDV: Median value of owner-occupied homes in $1000s

# Supported Application:
Because this file is .ipynb you need to install Google Colaboration/Jupyter Notebook. You should Mount Drive to connect the Google Colaboration into your Google Drive
and place the csv file into a folder

# Step
## Regularized Regression
1. Split data for train, validation and testing purpose
2. Calculate VIF Scores as the basis to detect and drop multicollinear features
3. Find the best model (alpha) using Ridge regression and Lasso regression
4. Model Evaluation

## Unsupervised - Dimensional Reduction
1. Data preprocessing
2. Conduct Principal component analysis (PCA)
3. Modelling with PCA and without PCA
4. Predicting with PCA and without PCA

# Summary
1. The modeling using regressing with PCA reduced the accuracy to 2.3% (from the R-Squared) compared to without using PCA but it still higher than using regularized regression.
2. However, the computation of The modeling using regressing with PCA becomes more efficient because the features could be reduced from 10 to only four features and it was enough to cover 80.92% of information.
3. According to Chin (1998), the highest model usually has the r-squared of more than 0.67, which means the combination between each independent variable is strong enough to affect the value of the dependent variable. It implies the modeling using PCA is still categorized as the highest model because the R-Squared is more than 0.67.

