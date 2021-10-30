# California-Housing-Price-Prediction

1. [Project Motivation](#ProjectMotivation)
2. [Installation](#installation)
3. [Data](#data)
4. [Implementation](#model)
5. [Results](#results)

## 1. Project Motivation <a name="ProjectMotivation"></a> 

1. Build a model of housing prices to predict median house values in California using the California_Housing.xlsx.
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
  

## 3. Data<a name="data"></a> 

There are housing data available for 20640 different houses in California. 
Dataset Size : 20640 rows x 10 columns
Dataset Name : "California_housing.xlsx"


## 4. Implementation <a name="model"></a> 
Step1 : Missing Value Treatment
Step2 : Encoding of categorical data to numerical data using dummy values
Step3 : Extraction of Dependent and Independent variables 
Step4 : Training and Testing data splitwith a ratio of 80:20
Step5 : Standardization of dependent variables
Step6 : Linear Regression modelling is done on train data and after that testing is performed
Step7 : RMSE calculation.

## 5. Result<a name="results"></a>
The details of the results are there in the jupyter notebook.
