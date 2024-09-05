# Startup-Profit-Predictor
Startup Profit Prediction
This project aims to predict the profit of startups based on various features such as R&D Spend, Administration, Marketing Spend, and State. The dataset used in this project is from a Kaggle competition.

# Table of Contents
1. Installation
2. Data Preprocessing
3. Exploratory Data Analysis
4. Model Training
5. Results
6. Contributing

# Installation
To run this project, you will need to have the following libraries installed:
1. numpy
2. pandas
3. seaborn
4. matplotlib
5. scikit-learn
6. statsmodels

# Data Preprocessing
The dataset is checked for null values, and it is found that there are no null values. The categorical variable "State" is encoded using LabelEncoder.
The dataset is then split into training and testing sets using a 80:20 ratio.

# Exploratory Data Analysis
Histograms are plotted for each numeric feature to visualize their distributions. The mean, median, standard deviation, and kurtosis are calculated for each numeric feature. The skewness and kurtosis of the distributions are also analyzed.
A correlation heatmap is plotted to visualize the correlation between the features.

# Model Training
A linear regression model is trained on the training set. Grid search is used to find the best hyperparameters for the model.
The variance inflation factor (VIF) is calculated for each feature to check for multicollinearity.

# Results
The trained model is used to predict the profit on the training set. The actual values, predicted values, error, absolute error, and percentage error are calculated and stored in a DataFrame.
The DataFrame is sorted based on the percentage error in descending order to analyze the model's performance.

# Contributing
If you find any issues or have suggestions for improvement, feel free to create a new issue or submit a pull request.
