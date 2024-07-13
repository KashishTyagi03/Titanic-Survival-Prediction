# Titanic-Survival-Prediction 
### Titanic Survival Prediction Analysis

This notebook provides a comprehensive analysis for predicting Titanic survival outcomes using various data science and machine learning techniques. Below is a summary of the steps and processes undertaken in the notebook:

#### Importing Libraries
The necessary libraries for data manipulation, visualization, and machine learning are imported:
- `pandas` and `numpy` for data manipulation
- `seaborn` and `matplotlib` for data visualization
- `sklearn` for machine learning models and evaluation

#### Data Loading and Initial Exploration
The Titanic dataset is loaded from a CSV file, followed by an initial exploration:
- Displaying the first and last few rows of the dataset
- Checking the shape of the dataset
- Assessing the data types and missing values

#### Handling Missing Values
To address missing values in the dataset:
- The mean value is used to fill missing values in the `Age` column
- The mode value is used to fill missing values in the `Embarked` column

#### Data Visualization
Several visualizations are created to understand the distribution and relationships of different features:
- Count plots of `Sex`, `Survived`, `Parch`, and `SibSp`
- Grouped plots to explore survival rates based on `Sex`, `Pclass`, and `Embarked`

#### Data Preprocessing
The preprocessing steps involve converting categorical variables into numerical data:
- Encoding `Sex` and `Embarked` columns
- Dropping irrelevant columns such as `PassengerId`, `Name`, and `Ticket`

#### Feature Selection and Model Training
- Separating features (`X`) and target (`y`) variables
- Splitting the data into training and testing sets
- Training a Logistic Regression model on the training data
- Evaluating the model using accuracy, precision, recall, and classification report metrics

#### Conclusion
This notebook provides a thorough approach to data cleaning, visualization, preprocessing, and model training to predict the survival of passengers on the Titanic. The steps detailed here ensure a clear and methodical approach to handling and analyzing the Titanic dataset.

This analysis and the steps involved can be a valuable reference for similar machine learning projects, highlighting the importance of data preparation and proper evaluation metrics.

You can view and run this analysis using the provided Jupyter Notebook file in this repository.
