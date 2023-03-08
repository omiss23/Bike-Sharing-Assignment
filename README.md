# Bike-Sharing-Assignment
This repository contains a Jupyter notebook implementing a multiple linear regression model to predict demand for shared bikes using various factors, along with the necessary data and a README file.

This project is a multiple linear regression model built to predict the demand for shared bikes. The dataset used for this model is provided by a bike-sharing provider, BoomBikes. The company is trying to prepare itself to meet the demand for shared bikes once the ongoing quarantine situation ends across the nation due to Covid-19.

## Problem Statement
BoomBikes has contracted a consulting company to understand the factors on which the demand for these shared bikes depends. The consulting company has to help BoomBikes understand the following:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands.

## Dataset
The dataset used for this project is provided by BoomBikes. It consists of 730 observations and 16 columns. The dataset has both categorical and numerical features. Some of the features like 'weathersit' and 'season' have values as 1, 2, 3, 4 which have specific labels associated with them. These numeric values associated with the labels may indicate that there is some order to them, which is not the case. So, it is advisable to convert such feature values into categorical string values before proceeding with model building.

## Business Goal
The business goal of this project is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.

## Model Building
In the dataset provided, there are three columns named 'casual', 'registered', and 'cnt'. The variable 'casual' indicates the number of casual users who have made a rental. The variable 'registered' shows the total number of registered users who have made a booking on a given day. Finally, the 'cnt' variable indicates the total number of bike rentals, including both casual and registered. The model is built taking this 'cnt' as the target variable.

## Model Evaluation
The model's performance is evaluated based on the R-squared score calculated on the test set. The R-squared score on the test set holds some marks.

## Files in the Repository
- Bike_Sharing_Linear_Regression_Assignment.ipynb: a Jupyter notebook containing the model building and evaluation code.
- day.csv: the dataset used for model building.
- README.md: this file containing a summary of the project.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Installation and Setup
To run this project, you need to have Python 3.x installed on your system. Clone this repository to your local machine and install the required libraries using the following command:

```
pip install -r requirements.txt
```
After installing the libraries, open the Jupyter notebook using the following command:

```
jupyter notebook
```

This will open a new tab in your browser, where you can access the notebook.

## Conclusion
This project involved building a multiple linear regression model to predict the demand for shared bikes. The model achieved an R-squared score of 0.798 on the test set, which indicates that the model is good at predicting the demand for shared bikes. The management can use this model to understand the demand dynamics of a new market and manipulate the business strategy to meet the demand levels and meet the customer's expectations.
