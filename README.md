# House Price Prediction Using Linear Regression
This repository contains a Linear Regression model developed to predict house prices based on three key features: square footage, number of bedrooms, and bathrooms. This is Task 1 of my Machine Learning internship at **Prodigy InfoTech**.

## 📁 Files in this Repository
`Prodigy_ML_Task_1.ipynb:` Jupyter Notebook with code for data generation, model training, and evaluation.
`sample_submission.csv:` A synthetic dataset generated for this project.

## 📊 Dataset
The dataset is synthetically generated with the following features:

- **Square Footage:** A randomly generated integer between 800 and 3500.
- **Bedrooms:** A randomly generated integer between 1 and 6.
- **Bathrooms:** A randomly generated float between 1 and 4.
- **Price:** The target variable calculated using the formula:

Price=(100×Square Footage)+(20,000×Bedrooms)+(15,000×Bathrooms)+Random Noise

## 🚀 Project Workflow
1. **Data Generation:** The dataset is created using NumPy to simulate realistic house features and prices.
2. **Data Preprocessing:** The generated dataset is saved as a CSV file.
3. **Linear Regression Model:** A linear regression model is implemented to predict the price based on square footage, number of bedrooms, and bathrooms.
4. **Model Evaluation:** The model's performance is assessed using standard metrics like Mean Squared Error (MSE).

## 🛠️ Technologies Used
- **Python** for model development and data manipulation.
- **Pandas** and **NumPy** for handling the dataset and feature generation.
- **Scikit-learn** for building and evaluating the linear regression model.
- **Matplotlib** and **Seaborn** for data visualization.

## 📈 Results
The linear regression model provides insights into how features like square footage, number of bedrooms, and bathrooms affect house prices.
