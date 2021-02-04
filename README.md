# Data-Analysis and Processing

## Xizhuquan Co., Ltd
Based on python language with the package of xlrd, pandas, xlrd, xlwt, xlutils, openpyxl and so forth to manipulate excel files. Besides, it also collects, merges items and items' price into database to organize item prices for different companies, and calculate the total amount in a specific period.

## House_Prices
This dataset is from Kaggle. link: [House Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview)

### Description
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

### Check Order
1. data_description.txt: to understand the data and data description;

2. Data preparation.ipynb: this file includes checking columns, missing values, standardization for numerical data, feature imputation, feature merging, feature selection(filter method), delete outlier.... Besides, it can also check the sweet point price matching part.

3. My_House_Prices.ipynb: in this dataset, we tried linear regression model to predict the value of the sale price. After implementing experiments, we found that LR without penalty may not obtain better results, which is about 0.4 score. However, Lasso will obtain better results because it avoid overfitting, which is about 0.2 score, and the rank is about 4000.
