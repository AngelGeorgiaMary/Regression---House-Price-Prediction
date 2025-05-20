# Regression---House-Price-Prediction
Utilized linear regression for forecasting housing market prices. Employed StandardScaler for data normalization and created visual representations to compare actual and forecasted values.

🏠 House Price Prediction using Linear Regression
This project demonstrates a simple yet effective regression approach to predict median house prices in California using the California Housing Dataset from Scikit-learn. The model is built using Linear Regression and evaluated based on performance metrics and visual inspection.

📊 Dataset
Source: Scikit-learn's fetch_california_housing()

Features:

Median income, house age, average number of rooms, population, etc.

Target:

MedHouseVal: Median house value in units of $100,000s

🛠️ Workflow Overview
Data Loading & Exploration:

Loaded California housing data and previewed basic statistics.

Preprocessing:

Checked for null values (none found).

Split data into features (X) and target (y).

Performed train-test split (80% train, 20% test).

Standardized features using StandardScaler.

Model Training:

Used a simple LinearRegression model from Scikit-learn.

Trained the model on the scaled training data.

Evaluation:

Calculated Mean Squared Error (MSE) and R² Score.

Visualized the model's performance by plotting actual vs predicted prices.

📈 Results
Metrics:

📉 Mean Squared Error (MSE): Low values indicate better fit.

📊 R² Score: Measures how well the model explains the variance (closer to 1 is better).

Plot: The scatter plot of actual vs. predicted prices gives a visual indication of model performance.
