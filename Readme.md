# Insurance Premium Predictor

This project uses a dataset containing insurance data and creates a linear regression model to predict insurance premiums based on various features.

## Dependencies

- **numpy**
- **pandas**
- **matplotlib**
- **seaborn**
- **sklearn**

### Overview

1. **Data Collection and Analysis**: Load the insurance dataset and get an overview by checking the first few rows, shape, and dataset information.
2. **Categorical Features**:
   - Sex
   - Smoker
   - Region
3. **Data Preprocessing**: Identify and handle any missing values in the dataset. Also, encode the categorical features.
4. **Data Analysis**: Examine the distribution of various columns like age, gender, bmi, smoker status, and region.
5. **Model Training**: Split the data into training and test datasets, and then use a linear regression model for prediction.
6. **Model Evaluation**: Evaluate the model using the R squared value for both training and test datasets.
7. **Prediction**: Create a system to predict insurance costs for a given set of features.

### Usage

To get the prediction of the insurance premium for a given set of data:

input_data = (age, sex, bmi, children, smoker, region)

## For example

input_data = (19,1,27.9,0,0,0)
