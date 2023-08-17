# Calories_Burnt_Prediction-

This project helps predict how many calories you will burn during a specific period of time. It takes some parameters, such as your duration of exercise, the average heartbeats per minute, body temperature, height, and weight, and uses the XGBoost Regressor model to predict the calories burned.

XGBoost is an efficient implementation of gradient boosting that can be used for regression predictive modeling

## Dataset source:
Kaggle: 2 CSV Files 

    a. Exercise.csv: https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos?select=exercise.csv
    b. Calories.csv: https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos?select=calories.csv
    
    
## Libraries to install 
Numpy, Pandas, Scikit-Learn, Matlotlib, Seaborn, and PyXGBoost


## Platform to Implementation
We use Jupyter Notebook to implement this project

## Workflow
•	First step: collect data.
We need data to train the ML model so that it can find out what is the amount of calories going to burn

•	Second step: Data Preprocessing – We clean the data before feeding it into MLmodel

•	Third Step: Data Analysis   (understanding the dataset better, which enables making better predictions)
Use some visualisation techniques to plot data in plots n graphs

•	Train Test Split: Split the data into a training dataset and a testing dataset
Train data – train our ml model
Test data: Evaluate/Test data

•	After the split, we need to train our ML Algorithm, in this case, we are going to use: XGBoost Regressor(ml model).
(XGBoost Regressor is a regression algorithm that is an analysis that is a statistical technique to model the connection between dependent (target) and independent (predictor) variables with one or more unbiased variables. In machine learning the XGBoost algorithm performs well since it has robust handling of many variety of data types, relationships, distributions, and the many hyperparameters that you can fine-tune. XGBoost regressor can be used for regression, classification for both binary and multiclass, and ranking problems.)

We train the XGBoost regressor with training data.
We use a regressor because this is an example of a regression problem


•	Evaluate the model with test data. 
We use Mean Absolute Error to check the accuracy of our prediction. In our case, we got a value of 1.48 for MEA which means our prediction is best and XGBoost Regressor is a good ML model
![image](https://user-images.githubusercontent.com/45625862/182100947-5560c745-3826-464a-a7d9-d1c9b26818c5.png)




