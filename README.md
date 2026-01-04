PRODIGY_ML_01
House Price Prediction using Linear Regression
📌 Project Overview
This project is part of my Machine Learning internship at Prodigy InfoTech. The objective is to build a predictive model using Linear Regression to estimate the sale price of houses.

📊 Dataset
The project utilizes the House Prices: Advanced Regression Techniques dataset from Kaggle.

Target Variable: SalePrice (The price of the house).

Key Features Used:

GrLivArea: Above grade (ground) living area square feet.

BedroomAbvGr: Number of bedrooms above basement level.

FullBath: Number of full bathrooms.

🛠️ Technologies Used
Python: Core programming language.

Pandas: For data cleaning and manipulation.

Scikit-Learn: For implementing the Linear Regression algorithm.

NumPy: For numerical computations.

🚀 Implementation Steps
Data Loading: Importing the train.csv dataset.

Feature Engineering: Selecting the most relevant numerical features (Square feet, Bedrooms, Bathrooms).

Data Splitting: Dividing the dataset into 80% Training and 20% Testing sets to evaluate performance.

Model Training: Training the LinearRegression model on the training data.

Evaluation: Calculating the Mean Squared Error (MSE) and R-squared score to check accuracy.

📈 Results
The model provides a numerical prediction of a house's value based on the input features. The R-squared score indicates how well the independent variables explain the variability of the house prices.
