# Data-Analysis and Processing (4 more projects)

## Xizhuquan Co., Ltd
Based on python language with the package of xlrd, pandas, xlrd, xlwt, xlutils, openpyxl and so forth to manipulate excel files. Besides, it also collects, merges items and items' price into database to organize item prices for different companies, and calculate the total amount in a specific period.

## House_Prices (Kaggle: also with docker to control the same deployment environment)
This dataset is from Kaggle. link: [House Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview)

### Description
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

### Check Order
1. data_description.txt: to understand the data and data description;

2. Data preparation.ipynb: this file includes checking columns, missing values, standardization for numerical data, feature imputation, feature merging, feature selection(filter method), delete outlier.... Besides, it can also check the sweet point price matching part.

3. My_House_Prices.ipynb: in this dataset, we tried linear regression model to predict the value of the sale price. After implementing experiments, we found that LR without penalty may not obtain better results, which is about 0.4 score. However, Lasso will obtain better results because it avoid overfitting, which is about 0.2 score, and the rank is about 4000.

## The Analysis of Single Chest-Mounted Accelerater Data Set by classification algorithm
This project aims to classify seven different types of human activities, such as walking, working at a computer, into target labels by using the data collected from a wearable accelerometer mounted, x, y and z-axis elements with classification algorithm, K Nearest Neighbor and Decision Tree. The dataset was obtained from UCI machine learning repository and processed by data retrieval and preparation, data exploration and data modelling. Moreover, hill climbing with the score of K Nearest Neighbor was used to make feature selection, and K-Fold cross-validation and nested loop have been used in tuning parameters for modifiers. Overall the accuracy of the prediction results was about 75 percent for both K Nearest Neighbor and Decision Tree algorithms. The challenges include unbalanced classes and a load of data on a computer's performance.  
The seven activities of activity recognition from single Chest-Mounted Accelerometer was predicted by two classification algorithms, KNN and DT. After feature selection, x, y, z acceleration have a positive contribution as training features by the hill-climbing algorithm. From the results, it can be seen that both KNN and DT have similar performance that is about 0.75, which may be influenced by unbalanced classes. GridsearchCV algorithm can bring a little bit higher performance in the search globality, but it requires many computing resource costs.

## The Analysis of Wine Datasets by KNN and Decision tree
The aim of this report was to classify 3 different types of wines into target labels by using
chemical elements by data modeling, and data exploration. As a classification data set, the K
Nearest Neighbor and Decision Tree have been used for modeling, and hill climbing, KCross
Validation and nested loop have been used in tuning parameters. Overall, the accuracy
of the prediction results was between 81%-99%. From the results obtained, it is
recommended that the K Nearest Neighbor model is more suitable.
