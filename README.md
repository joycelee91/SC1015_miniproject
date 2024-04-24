<img width="1530" alt="image" src="https://github.com/joycelee91/SC1015_miniproject/assets/153515423/57accbc2-de27-40fc-a56e-6c0c4e3aaaba"># SC1015_miniproject

## About


This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on car price prediction from [Used Vehicle Dataset](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho). For detailed walkthrough, please refer the source code in order from:

1. [Data Extraction](https://github.com/joycelee91/SC1015_miniproject/blob/cddf0128614ab1f4ccd28bd6164f7baa0b3d6a28/car-price-prediction%20(1).ipynb#L1)
2. [Data Analysis and Visualisation](https://github.com/joycelee91/SC1015_miniproject/blob/cddf0128614ab1f4ccd28bd6164f7baa0b3d6a28/car-price-prediction%20(1).ipynb#L1041)
3. [Linear Regression Model](https://github.com/joycelee91/SC1015_miniproject/blob/cddf0128614ab1f4ccd28bd6164f7baa0b3d6a28/car-price-prediction%20(1).ipynb#L2905)
4. [Random Forest Model](https://github.com/joycelee91/SC1015_miniproject/blob/cddf0128614ab1f4ccd28bd6164f7baa0b3d6a28/car-price-prediction%20(1).ipynb#L3755)

## Contibutors

1. @joycelee91 : Data Extraction and Analysis


## Problem and Goal

- How to predict the selling price of used cars using regression models?
- Which model is most suitable in predicting salesprice?

  Our goal is to create a model that accurately predicts the optimal selling price for used cars. This model aims to enhance the reliability of transactions in the second-hand car market by providing both customers and companies with the best available price.



## Models Used
1. Linear Regression Model
2. Random Forest Model



## Conclusion
1. Present_price has the highest linear correlation value with selling_price.
2. Kms_Driven and owner are 2 of the most unrelated variables in predicting selling price as both of them have pretty low linear correlation value.
3. Removing outliers improved the performance of linear regression model.
4. Linear regression model is a better model in predicting selling price compared to random forest model, this might be due to our dataset is small resulting in the overfitting of random forest model.


## New Things Learned from The Project
1. Collaborating using GitHub
2. Random Forest Model



## Insights

1. There's a big difference in the MSE values for the first linear regression model on the training and testing data. We think this might be because there are fewer outliers data points in the testing data, the size of the testing data is small, or the model we used is too simple.
2. It's surprising that the linear regression model works better than the random forest model. Both times we tried the random forest model, it ended up with potential overfitting, suggesting it was remembering specific examples too much instead of learning general patterns. This makes it not do well when we use it on new data, especially when the dataset is small.
3. To improve our linear regression models, we sugeest that using a larger dataset and reducing the skewness of variables using logarithmic will boost the performance of our models.
4. To make our random forest model better, we need to be careful in tuning the parameters such as how many trees it uses, how deep each tree goes, and how many examples it needs in each bunch.


## Reference

  




