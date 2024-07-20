# Boston Housing Regression Analysis

This project involves data analysis and regression modeling on the Boston housing dataset. The primary objective is to predict the median value of owner-occupied homes (MEDV) using various features and to compare different regression models. The workflow includes data preprocessing, exploratory data analysis, model training, evaluation, and optimization using GridSearchCV.

## Requirements

- Python 3.7 or above
- Jupyter Notebook
- numpy
- pandas
- scikit-learn
- seaborn
- matplotlib

## Installation

Install the required packages using pip:

```bash
pip install numpy pandas scikit-learn seaborn matplotlib

Project Structure

Data Loading and Preprocessing:

Load the dataset.
Normalize the data using MinMaxScaler.
Exploratory Data Analysis (EDA):

Display the dataset.
Create a correlation heatmap to identify relationships between features.
Model Training and Evaluation:

Train various regression models:
Linear Regression
Ridge Regression
Lasso Regression
Elastic-Net Regression
Evaluate the models using cross-validation and calculate metrics like R² score and mean squared error.

