# SCT_ML_Task1
🏡 House Price Prediction using Linear Regression
This project implements a Linear Regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms.

📌 Problem Statement
The goal is to build a regression model that can estimate the price of a house using the following features:

Square Footage (sqft)

Number of Bedrooms

Number of Bathrooms

📊 Dataset
You can use a CSV file with the following structure:

sqft	bedrooms	bathrooms	price
1500	3	2	250000
2000	4	3	350000

You may use any custom or open dataset (like from Kaggle) matching this format.

🧠 Model Used
Linear Regression from scikit-learn

Features: sqft, bedrooms, bathrooms

Target: price

🛠️ Requirements
Install the necessary libraries using pip:

bash
Copy
Edit
pip install pandas scikit-learn matplotlib
🚀 How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/house-price-predictor.git
cd house-price-predictor
Add your dataset (data.csv) in the project directory.

Run the Python script:

bash
Copy
Edit
python linear_regression.py
📈 Output
The model will display the coefficients for each feature.

It will evaluate performance using metrics like Mean Squared Error and R² Score.

A plot may also be generated showing the relationship between predicted and actual prices.


