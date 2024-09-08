### TASK 2 -Movie Rating Prediction using Python 🎬

## Project Overview: 

This project aims to predict the ratings of movies based on various features such as genre, director, actors, and other key attributes using data analysis, feature engineering, and machine learning techniques. The goal is to build a model that can accurately estimate the rating a movie will receive from users or critics. The project provides insights into how different factors influence movie ratings and demonstrates the end-to-end process of data science modeling.

## Problem Statement:

In today’s entertainment industry, movie ratings play a significant role in determining a movie's success. By analyzing historical movie data, we can gain valuable insights into the factors that contribute to a movie's rating. The objective of this project is to predict a movie’s rating based on its characteristics, helping producers, critics, and viewers make informed decisions.

## Dataset Overview:

### The dataset includes the following features:

> Name: Movie title

> Year: Release year

> Duration: Length of the movie in minutes

> Genre: Genre(s) of the movie

> Rating: The actual rating given to the movie

> Votes: Number of votes received

> Director: Director of the movie

> Actor 1, Actor 2, Actor 3: Main actors featured in the movie

## Project Workflow:

1. Data preparation - By loading and cleaning dataset
   
![image](https://github.com/user-attachments/assets/c29b776a-fcb4-4296-9f2b-2f4711fd5600)

2. Exploratory Data Analysis (EDA) - Descriptive data analysis, Data visualization, Correlation Analysis
3. Feature Engineering - By dropping unnecessary feaures and creating new features(such as encoding features)
4. Split dataset into training and testing sets
5. Model Selection - Model Building, Model Evaluation, Actual vs Predicted values Analysis and Model Testing

## Tools & Technologies:

### Programming Language: Python 
### Libraries :
#### Data Analysis : Numpy and Pandas
#### Data Visualization : Matplotlib and Seaborn
#### Machine Learning : Scikit-Learn
### Programming Environment: Visual Studio Code

## Results: 
![image](https://github.com/user-attachments/assets/5ef0bf7e-aa9b-4b3a-bd25-78540d591838) 
![image](https://github.com/user-attachments/assets/9ee3cd03-48e9-412f-91ff-39522c3d295f)
![image](https://github.com/user-attachments/assets/0e69cc00-6257-43e0-ab35-97cbbef78162)
![image](https://github.com/user-attachments/assets/23d2dc15-b8c6-4f7e-8871-816b0d195ddf)
![image](https://github.com/user-attachments/assets/d22fb88b-fbc4-453f-b973-be4ec0edd611)
![image](https://github.com/user-attachments/assets/ddf79c51-8504-4800-9ded-22baca72a78d)
![image](https://github.com/user-attachments/assets/79f62295-160e-4f91-9771-a145cedc8936)
![image](https://github.com/user-attachments/assets/a1116767-6e69-41c5-bf83-fe2311cacced)
![image](https://github.com/user-attachments/assets/74a2c42c-bbf7-4dc9-a6f7-1cdf6d0978c0)

## Conclusion: 
The coefficient of the determination or the R2 score value of Random Forest model is 0.829 which greater than Linear Regression model and it means about 82.9% of the variance in the target variable(Rating) is strongly explained by the model. Also, the mean squared error value or the difference between actual and predicted value is 0.328 and the mean absolute error values is 0.38. Both values seem reasonably low and also both values less than Linear regression model's values. 
So, we found that the Random Forest Regressor provided significantly more accurate movie rating predictions than the Linear Regression model. 
The insights gained can help stakeholders in the movie industry make informed decisions regarding film production and marketing strategies.
