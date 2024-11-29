# Predict-the-Price-of-a-House
This project uses linear regression model building to predict house prices based on a single feature - area.

Since this is clearly a linear regression problem, we would build a linear regression model, train it, and test it. After which, we will deploy it and then use it to make predictions.

Linear regression is one of the supervised ML model algorithms. It is especially best for data where the target variable is numeric and continuous.

What is linear regression best used for?
Businesses use it to reliably and predictably convert raw data into business intelligence and actionable insights. Scientists in many fields, including biology and the behavioral, environmental, and social sciences, use linear regression to conduct preliminary data analysis and predict future trends.

If the goal is error (i.e variance) reduction in prediction or forecasting, linear regression can be used to fit a predictive model to an observed data set of values of the response (target/dependent) and explanatory (predictor/independent) variables.

The following steps were followed:
• Step 1: Collect data with house features and price

• Step 2: Fit a linear model to find the relationship between the ‘area’ feature and pri

• Step 3: Use this model to predict house prices for new data.

## Dataset
This project makes use of the homeprices dataset, which contains a number of features such as area, number of bedrooms, age of the house, etc, to predict the target variable - prices.
You can get the dataset via the [link](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)

## Tools/Applications/Softwares/Packages Used for the Project
The python programming language, along with libraries such as Sci-kit learn, pandas, numpy, Seaborn and matplotlib, was used for the explorations and visualizations contained in this work.

## Key Insights for Analysis/Investigation
In this project, I endeavoured to find out the effect of a single predictor variable, area of a house, on the price of the house.

## Summary of Findings
It was discovered that there is a strong positive correlation between the area and price of a house.
The linear regression model predicted high prices for houses with large area, vice versa.
