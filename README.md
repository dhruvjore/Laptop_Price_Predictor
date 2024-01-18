# Laptop Price Prediction Project
## Overview
This project aims to predict the price of a laptop based on its specifications using machine learning techniques. The model is built using Linear Regression, a simple yet effective algorithm for predicting numerical values. The project is deployed, allowing users to input laptop specifications and receive a predicted price.

## Model Training
The machine learning model is trained using Linear Regression on a dataset containing laptop specifications and their corresponding prices. The training code can be found in the train_model.ipynb Jupyter Notebook. The notebook includes data preprocessing, feature engineering, model training, and evaluation steps.
To retrain the model with new data, update the dataset and run the notebook.

## Deployment
The project is deployed using a web application built with Flask. The deployment code is in the app.py file. The trained model is loaded and used to make predictions based on user input.
The deployment is currently set up locally. For production deployment, consider using platforms like Heroku, AWS, or Azure.

## Technologies Used
Python
Flask
scikit-learn
HTML/CSS
