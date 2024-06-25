Diabetes Regression Analysis

Introduction
This coding task involves performing multiple linear regression analysis on the diabetes dataset. The primary objective is to understand the relationship between various independent variables and the progression of diabetes. This task includes data preprocessing, visualization, model training, and evaluation using different scaling techniques.

Description
The purpose of this task is to build a multiple linear regression model to predict the progression of diabetes based on several independent variables. The dataset used in this task contains various health-related measurements of individuals. By performing this regression analysis, we can determine how different factors contribute to the progression of diabetes.

Installation
To run this code locally, you need to have Python installed along with several libraries. You can install the required libraries using the following commands:
pip install pandas matplotlib scikit-learn
Ensure you have the diabetes_dirty.csv file in the same directory as your script.

Usage
Load the dataset: The script reads the dataset from a CSV file.
Data Preprocessing: The dataset is split into independent (X) and dependent (Y) variables, and further into training and test sets.
Data Visualization: Histograms and scatter plots are created to visualize the distribution of each variable and their relationship with the target variable.
Scaling: Two scaling techniques, StandardScaler and MinMaxScaler, are applied to the data.
Model Training and Evaluation: A multiple linear regression model is trained and evaluated using both scaled datasets. The intercepts, coefficients, and R-squared values are printed for comparison.

Running the Code
To run the code, execute the script in a Python environment. The script will display histograms and scatter plots for visual analysis. It will then print the model's intercepts, coefficients, and R-squared values for both scaling techniques.
The output will display intercepts, coefficients, and R-squared values for both scaling methods:
Using StandardScaler:
Using StandardScaler:
Intercept: -25.13322785293522
Coefficients: [   8.2612689   -23.06446772  135.63561351   84.9935688  -244.80178532
  162.87932677   46.32729542   72.03113268  191.18672297   13.3055384 ]

Using MinMaxScaler:
Intercept: -25.13322785293522
Coefficients: [   8.2612689   -23.06446772  135.63561351   84.9935688  -244.80178532
  162.87932677   46.32729542   72.03113268  191.18672297   13.3055384 ]
  R-squared with StandardScaler: -22.32035503095602
R-squared with MinMaxScaler: 0.45260276297191937

Credits
This project was developed by Javed Ahmed.


