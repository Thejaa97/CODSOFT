### TASK 2 -Sales Prediction using Python 💰📈

## Project Overview: 

This project aims to build a machine learning model which predicts sales based on the money spent on different platforms for marketing such as TV, Radio and Newspaper.

## Problem Statement:

Businesses need to predict future sales to make informed decisions regarding their marketing strategies, particularly in advertising. The key challenge is to accurately forecast sales based on advertising expenditure across different platforms (e.g., TV, radio, newspaper) and other related factors.

## Dataset Overview:

### The dataset includes the following features:

> TV: Money spent on TV Advertising

> Radio: Money spent on Radio Advertising

> Newspaper: Money spent on Newspaper Advertising

> Sales: Sales amount of a product/ a service

## Project Workflow:

1. Data preparation - By loading and cleaning dataset
   
![image](https://github.com/user-attachments/assets/875b2e1c-00b6-4ddb-a685-0a9ed6e0f57d) 

2. Exploratory Data Analysis (EDA) - Descriptive data analysis, Univariate Analysis, Correlation Analysis, Multicollinearity Analysis
3. Split dataset into training and testing sets
4. Model Selection (Linear Regression Model) - Model Building, Model Evaluation, Actual vs Predicted values Analysis and Model Testing

## Tools & Technologies:

### Programming Language: Python 
### Libraries :
#### Data Analysis : Numpy and Pandas
#### Data Visualization : Matplotlib and Seaborn
#### Machine Learning : Scikit-Learn
### Programming Environment: Visual Studio Code

## Results: 
![image](https://github.com/user-attachments/assets/4e72a97d-1162-4ef3-a29b-114a4e707b1f) 
![image](https://github.com/user-attachments/assets/218e51fb-bae4-46c4-a6ac-975aa54246e9) 
![image](https://github.com/user-attachments/assets/bfc946cc-5ee7-4a7e-9f66-90fd6312030e)
![image](https://github.com/user-attachments/assets/217b1acf-6d19-4701-8b91-f7d1d18defa1)
![image](https://github.com/user-attachments/assets/71c892c2-c594-40a1-b63f-b53bef318a52)
![image](https://github.com/user-attachments/assets/3b50df8f-03d9-4a1f-a23d-fd4c8f3e2cdf)
![image](https://github.com/user-attachments/assets/6744d1ea-f972-4e07-8e72-314521b720c7)
![image](https://github.com/user-attachments/assets/081c86ac-382d-4274-8ce0-b83dab02c382)
![image](https://github.com/user-attachments/assets/5f4682ab-fce0-4d19-89b1-c3305cc77fee)
![image](https://github.com/user-attachments/assets/5f7b1c90-0ff3-4502-b478-344480ddf08e)
![image](https://github.com/user-attachments/assets/798b6365-9539-4278-8a0f-aa7ca5d38790)

## Conclusion: 

The linear regression model fitted for predicting sales based on advertising expenditures demonstrates strong predictive performance. With a coefficient of determination (R²) of 0.9, the model explains approximately 90% of the variance in the target variable (Sales), indicating a high degree of accuracy in capturing the underlying relationship between the features and the target variable. This suggests that the model has effectively learned the influence of advertising expenditures on sales outcomes.

Moreover, the model's error metrics reinforce its reliability. The mean squared error (MSE) of 2.46 and the mean absolute error (MAE) of 1.22 indicate a relatively low deviation between the predicted and actual sales values. The comparatively low error values signify that the model's predictions are closely aligned with the observed data, further validating its suitability for forecasting future sales.

Among the advertising platforms considered, TV advertising exhibits the strongest positive correlation with sales, with a correlation coefficient of 0.9. This high correlation suggests that expenditures on TV advertising are highly influential in driving sales performance, more so than radio or newspaper advertising. The significant impact of TV advertising highlights the importance of allocating marketing budgets strategically, with greater emphasis on platforms that yield higher returns.
