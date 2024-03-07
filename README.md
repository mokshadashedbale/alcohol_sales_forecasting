# Alcohol Sales Forecasting with SARIMAX Model

This project focuses on forecasting alcohol sales using the SARIMAX (Seasonal Autoregressive Integrated Moving Average with Exogenous Regressors) model. The dataset used spans from January 1992 to January 2019, containing 234 records. The goal is to predict alcohol sales for the next 12 months, from February 2019 to January 2020.

## Dataset

The dataset used for this project is the alcohol sales dataset, which contains 234 records spanning from January 1992 to January 2019, with two columns: date and alcohol sales.

## Requirements
Python 3.x
Jupyter Notebook
pandas
numpy
statsmodels
matplotlib
seaborn
pmdarima


## Approach
1.Data Preprocessing: The dataset is loaded and preprocessed to ensure compatibility with SARIMAX modeling requirements. This includes handling missing values, converting date column to datetime format, and 
ensuring stationarity if needed.

2.Model Building: SARIMAX model is built using the statsmodels library. Appropriate parameters are selected through analysis and tunning.

3.Forecasting: Finally, the model is used to forecast alcohol sales for the next 12 months (February 2019 to January 2020)


## Files Included

- `alcohol_sales_forecasting.ipynb`:  Jupyter Notebook containing the SARIMAX model implementation..
- `Alcohol_Sales_dataset.csv`: CSV file containing the alcohol sales dataset used for analysis.


## Usage

1.Clone the repository.

2.Install the required dependencies mentioned in the requirements.

3.Open the Jupyter Notebook Alcohol_Sales_Forecasting.ipynb.

4. Run the code cells and generate forecasts

## Conclusion

The SARIMAX model provides a forecast for alcohol sales for the next 12 months, which can be used for planning and decision-making purposes.
