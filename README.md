# simplelinreg

Linear-Regression
Python programs implementing Linear Regression models.


Introduction
According to Google - Linear regression is a linear approach to modelling the relationship between a scalar response (or dependent variable) and one or more explanatory variables (or independent variables). The case of one explanatory variable is called simple linear regression.
In my own words - Linear Regression is used to study the relationship between a set of variables. In this file we use 2 variables which is called Simple Linear Regression. If more than 2 variables it is called Multi Linear Regression. It is based on this type of learning called Supervised Learning.


Environment Setup
Install Jupyter Notebook - https://jupyter.org/
If you want to know more about jupyter notebook then watch the video in this link or watch any video of your choice - https://www.youtube.com/watch?v=jZ952vChhuI
Install Anaconda or Miniconda Python python distributioin - https://www.anaconda.com/distribution/
On how to open and run the python file in jupyter notebook refer this video - https://www.youtube.com/watch?v=DPi6CAkUUPY
Jupyter notebook files extension - .ipynb file
Make sure you install specific python packages to run this file:

1.NumPy
2.Matplotlib
3.Pandas
4.Seaborn

Contents
regression+example.ipynb -
In this file we have two set of programs, First by importing python packages(like NumPy, Matplotlib) we predict the linear model, Second by using basic standard formulas, we obtain the line equation values.

LinearRegressionBoston_RM.ipynb -
In this file we use code from different python packages. We implement with the boston.csv file and create a model that predicts the prices of the house indicated by the variable MEDV which is our target variable and the remaining are the feature variables based on which we will predict the value of a house. But in this program we will use only one feature variable that is the Average no of rooms indicated by the variable RM. \


boston.csv -
This file contains the dataset which is used to create the linear model. If you want to view the dataset in a proper format. Open the file in Excel. Dataset is used in LinearRegressionBoston_RM.ipynb file. \


LinearRegression_gm2008region.ipynb -
We create a linear model using Simple Linear Regression. Implemented using 'gm_2008_region.csv' dataset. In this file we add new extra features like seaborns heatmap function to identify best set of inputs in predicting best output score. \

gm_2008_region.csv -
Open the file as excel document to view the dataset. This dataset is used in 'LinearRegression_gm2008region.ipynb' and 'multiple_linear_regression.ipynb' files. \

multiple_linear_regression.ipynb -
We use Multiple Linear Regression technique in this file. Selecting mulitple inputs ['child_mortality','fertility','HIV','BMI_male','BMI_female'] and predicitng best model and score for the target variable ['life']. Dataset used is 'gm_2008_region.csv'.
