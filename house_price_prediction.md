## House Price Prediction (Multiple Linear Regression)

**Project Link:**<a href="https://github.com/dilruu89/Kaggle/blob/main/02-regression-analysis-house-pricing.ipynb" target="_blank">House Price Prediction Jupyter Notebook</a>

**Project description:** In the business of real estate, estimating the prices of houses is an important task for agents, buyers, and sellers. One approach they often use is linear regression, a fundamental concept in machine learning. In this work, I am aiming to build a model that can predict the price of a house based on various features or attributes associated with that house. Linear regression is a simple yet effective algorithm for this task, especially when we have a dataset with numerical features and a target variable (house price) that we want to predict.


I used a dataset from a Kaggle competition named “House Prices: Advanced Regression Techniques”. It contains 1460 training data points and 80 features that help to predict the selling price of a house. 

```javascript
data = pd.read_csv('/kaggle/input/house-prices-advanced-regression-techniques/train.csv')

```

### Techniques/ Algorithms / Metrics

This analysis revolves around using linear regression to forecast house prices. This involves finding the optimal relationship between various features and the target output (house price). To improve the accuracy of predictions, I am using several feature selection methods. I also use graphical tools such as scatter plots, histograms, and correlation matrices. These visuals help to uncover patterns, trends, and potential anomalies within the data.

1. Multiple Linear Regression
2. Correlation Analysis
3. Mutual Information Regression
4. Backward Feature selection
5. Cross Validation, Mean Squared Error (MSE), R-squared ($R^2$)
