# Creating_a_Logistic_Regression_to_Predict_Absenteeism
## by Mostafa Hasan

In this project, I created a model to predict absenteeism according to the available data using the logistic regression model in Python.

### Python libraries:
- pandas
- numpy
- sklearn
- sklearn.base
- sklearn.preprocessing
- sklearn.model_selection
- sklearn.linear_model
- pickle
- pymysql

### Module used:
- absenteeism_module.py

### Data files:
- Absenteeism_data.csv
- Absenteeism_new_data.csv

### Output:
- df_preprocessed.ipynb > Absenteeism_preprocessed.csv
- Absenteeism_Logistic_Regression.ipynb.ipynb > model, scaler
- Absenteeism_Integration.ipynb > Absenteeism_predictions.csv


### Note:
- In Absenteeism_Integration.ipynb, I imported the pymysql library to connect to MySQL to create a table containing the observed data for further investigation on Tableau.
