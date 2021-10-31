# California-Housing-Price-Prediction

1. [Project Motivation](#ProjectMotivation)
2. [Installation](#installation)
3. [Data](#data)
4. [Implementation](#model)
5. [Results](#results)

## 1. Project Motivation <a name="ProjectMotivation"></a> 

1. Build a model of housing prices to predict median house values in California using the [California_Housing.xlsx](https://github.com/piyushkumar08/California-Housing-Price-Prediction/blob/main/California_housing.xlsx) dataset
2. Train the model to learn from the data to predict the median housing price in any district, given all the other metrics.
3. Predict housing prices based on median_income and plot the regression chart for it.

## 2. Installation <a name="installation"></a>

- [Jupyter Notebook](https://jupyter.org)
- Libraries :
  - pandas
  - numpy
  - Scikit-learn
     - model_selection 
     - preprocessing
     - linear_model
  -matplotlib
  -seaborn

## 3. Data<a name="data"></a> 

There are housing data available for 20640 different houses in California. 
Dataset Size : 20640 rows x 10 columns
Dataset Name : "[California_housing.xlsx](https://github.com/piyushkumar08/California-Housing-Price-Prediction/blob/main/California_housing.xlsx)"


## 4. Implementation <a name="model"></a> 
Step1 : Encoding of categorical data to numerical data using dummy values
Step2 : EDA for Location
Step3 : Missing Value Treatment
Step4 : Extraction of Dependent and Independent variables 
Step5 : Training and Testing data splitwith a ratio of 80:20
Step6 : Standardization of dependent variables
Step7 : Linear Regression modelling is done on train data and after that testing is performed
Step8 : RMSE calculation.
Step9 : Linear Regression modelling for one independent variable i.e income
Step10 : Visualisation for the model

## 5. Result<a name="results"></a>
The details of the results - [California_HousingPricePrediction.ipynb](https://github.com/piyushkumar08/California-Housing-Price-Prediction/blob/main/California_HousingPricePrediction.ipynb)
