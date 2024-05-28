                                                                         Sales Prediction 
This project focuses on predicting sales based on advertising spends on TV, Radio, and Newspaper using a Linear regression  model. The dataset used in this project is provided in the file Sales.csv.

Project Overview
Sales prediction is a crucial task for businesses to make informed decisions about their marketing strategies. By analyzing the impact of advertising spends on different channels like TV, Radio, and Newspaper, businesses can allocate their resources more effectively to maximize sales.

Dataset
The dataset Sales.csv contains the following columns:

TV: Advertising spends on TV.
Radio: Advertising spends on Radio.
Newspaper: Advertising spends on Newspaper.
Sales: Total sales generated.
Steps Involved
Data Loading: The dataset is loaded using the Pandas library.

Data Preprocessing: No missing values or categorical data preprocessing is required.

Model Training: The RandomForestRegressor model is initialized and trained using the features (TV, Radio, Newspaper) to predict the target variable (Sales).

Model Evaluation: The model is evaluated using Mean Squared Error (MSE) and Mean Absolute Error (MAE) metrics.

Visualization:

Actual vs Predicted Sales: A scatter plot is created to visualize the relationship between actual and predicted sales.
Residual Plot: A plot of residuals (difference between actual and predicted sales) is created to check for model performance.
Feature Importance: A bar plot showing the importance of each feature (TV, Radio, Newspaper) in predicting sales is created.
Prediction of New Data: Predictions are made for new data points (advertising spends on TV, Radio, and Newspaper) to estimate future sales.

Instructions for Running the Project
Ensure you have Python installed on your system.
Install the required libraries mentioned in the requirements.txt file.
Download the dataset Sales.csv and place it in the project directory.
Run the sales_prediction.py file to execute the project.
View the results including model evaluation metrics, visualizations, and sales predictions.
