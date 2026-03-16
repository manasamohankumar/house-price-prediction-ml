# House Price Prediction using Machine Learning

This project applies machine learning techniques to predict house prices based on property features such as square footage, number of bedrooms, bathrooms, and location.

Accurate house price prediction is valuable in the real estate industry because it helps buyers, sellers, and property analysts estimate property value and make informed decisions.

The goal is to evaluate different machine learning models and evaluates their performance to determine the most effective predictive approach.

## Project Structure

house-price-prediction-ml
│
├── data
│   └── house_data.csv
│
├── images
│   ├── price_distribution.png
│   ├── mse_comparison.png
│   └── r2_comparison.png
│
├── notebooks
│   └── House_Price_Prediction.ipynb
│
└── README.md

## Dataset

The dataset contains 21 features describing residential properties, including:
1. number of bedrooms
2. number of bathrooms
3. square footage of living area
4. lot size
5. number of floors
6. property condition and grade
7. geographical location features
8. The target variable is the house price.

## Data Preprocessing

Data preprocessing is essential for building reliable machine learning models.

The following steps were performed:
1. Loading and inspecting the dataset
2. Removing irrelevant columns such as id and date
3. Checking for missing values
4. Feature scaling using MinMaxScaler
5. Splitting the dataset into training and testing sets

These steps ensure the data is suitable for model training and evaluation.

## Predictive Models

Several machine learning models were implemented to predict house prices.

Models Used:
1. Linear Regression (LR)
2. Multilayer Perceptron (MLP) Neural Network
3. Tuned MLP architectures

Linear Regression was used as a baseline model, while neural networks were explored to capture more complex relationships within the dataset.

## Model Experiments and Evaluation

Multiple experiments were conducted to evaluate model performance.

The models were compared using:
1. Mean Squared Error (MSE)
2. R² (Coefficient of Determination)

Different neural network architectures were tested through hyperparameter tuning and architectural adjustments.

## Key Results

The results showed that:
1. Linear Regression provided a reasonable baseline prediction.
2. Neural network models captured nonlinear relationships in the data.
3. The Basic MLP model performed the best, explaining approximately 81% of the variance in house prices (R² ≈ 0.81).
4. This indicates that neural networks can provide stronger predictive performance for complex real estate data.

## Real-World Application
Machine learning models for house price prediction can support:

1. property valuation
2. real estate investment analysis
3. pricing strategy for sellers
4. housing market analysis

Such models can assist real estate professionals in making data-driven pricing decisions.

## Tools and Technologies

The project was implemented using:
1. Python
2. Pandas
3. NumPy
4. Scikit-learn
5. TensorFlow / Keras
6. Matplotlib
7. Jupyter Notebook

👩‍💻 Author
Manasa Mohan Kumar
