Task 1: Iris Dataset Exploration and Visualization

Objective
The objective of this task is to explore and visualize the Iris dataset using Python. The task focuses on loading the dataset, inspecting its structure, generating descriptive statistics, and creating visualizations to better understand feature distributions and relationships among variables.

Dataset Used
Dataset: Iris Dataset
Source: Seaborn Built-in Dataset
Number of Instances: 150
Number of Features: 4 numerical features and 1 categorical target variable.

Features
Sepal Length
Sepal Width
Petal Length
Petal Width
Species (Setosa, Versicolor, Virginica)

Models Applied
No machine learning model was applied in this task. The focus was on Exploratory Data Analysis (EDA) and data visualization using the following Python 

libraries:
Pandas
Seaborn
Matplotlib

Key Results and Findings:
Successfully loaded and inspected the Iris dataset using Pandas.
Examined the dataset structure using shape, columns, head(), info(), and describe().
Created a scatter plot to visualize the relationship between sepal length and sepal width across different Iris species.
Generated histograms to analyze the distribution of each numerical feature.
Used box plots to identify the spread of the data and detect potential outliers.
The visualizations showed that different Iris species exhibit distinct feature patterns, particularly in petal and sepal measurements, making the dataset suitable for classification tasks.



Task 2: Stock Price Prediction Using Linear Regression
Objective
The objective of this task is to predict the next day's closing stock price using historical stock market data. The project demonstrates how to collect financial data, prepare it for machine learning, train a regression model, and compare predicted prices with actual prices.

Dataset Used
Dataset: Apple Inc. (AAPL) Historical Stock Data
Source: Yahoo Finance (retrieved using the yfinance Python library)
Time Period: January 1, 2020 – January 1, 2025

Features Used:
Open Price
High Price
Low Price
Volume

Target Variable:
Next Day Closing Price (Next_Close)

Model Applied
Linear Regression
The model was trained using:
80% of the data for training.
20% of the data for testing.
The input features (Open, High, Low, and Volume) were used to predict the next trading day's closing price.

Key Results and Findings
Successfully downloaded historical stock market data using the yfinance library.
Created a new target variable (Next_Close) by shifting the closing price one day ahead.
Split the dataset into training and testing sets using an 80:20 ratio.
Trained a Linear Regression model to predict future closing prices.
Generated predictions for the testing dataset.
Visualized the actual and predicted closing prices using a line graph.
The comparison graph showed that the predicted stock prices closely followed the overall trend of the actual prices, demonstrating that Linear Regression can capture basic relationships in historical stock data. However, stock prices are influenced by many external factors, so more advanced models may provide improved prediction accuracy.



Task 3: Heart Disease Prediction Using Logistic Regression
Objective
The objective of this task is to build a machine learning model that predicts whether a patient is at risk of heart disease based on their medical information. The project includes data exploration, visualization, model training, performance evaluation, and identification of the most important features influencing the prediction.

Dataset Used:
Dataset: Heart Disease UCI Dataset
Source: Kaggle (UCI Heart Disease Dataset)

Features:
The dataset contains various patient health attributes, including:
Age
Sex
Chest Pain Type (cp)
Resting Blood Pressure (trestbps)
Cholesterol (chol)
Fasting Blood Sugar (fbs)
Resting ECG (restecg)
Maximum Heart Rate (thalch)
Exercise-Induced Angina (exang)
ST Depression (oldpeak)
Slope
Number of Major Vessels (ca)
Thalassemia (thal)

Target Variable:
num
0 = No Heart Disease
1 = Heart Disease (after converting the target into a binary classification problem)

Model Applied:
Logistic Regression

Data Preprocessing:
Inspected the dataset using head(), info(), and describe().
Checked for missing values.
Converted categorical variables into numerical variables using one-hot encoding (pd.get_dummies()).
Split the dataset into:
80% Training Data
20% Testing Data

Model Evaluation:
The model was evaluated using:
Accuracy Score
Confusion Matrix
ROC Curve
Area Under the Curve (AUC)
Additionally, the Logistic Regression coefficients were analyzed to identify the most important features affecting heart disease prediction.

Key Results and Findings:
Successfully explored and analyzed the Heart Disease UCI dataset.
Visualized the distribution of heart disease cases using a count plot.
Examined relationships among numerical features using a correlation heatmap.
Analyzed the age distribution of patients through a histogram.
Trained a Logistic Regression classifier to predict heart disease.
Evaluated the model using accuracy, ROC curve, AUC score, and confusion matrix.
Identified the top 10 most influential features using the model's coefficients and displayed them with a bar chart.
The model demonstrated its ability to classify patients based on their medical attributes and highlighted the health factors that contribute most to heart disease prediction.

