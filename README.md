# Car-Price-Prediction-Using-Machine-Learning 

This Python project is designed to predict the selling prices of cars based on their features using machine learning models. The project handles data loading, preprocessing, model training, and predictions. It also features a simple graphical user interface (GUI) developed with Tkinter for easy interaction with the model predictions.

README.md
**Requirements**

**To run this project, ensure you have Python installed along with the following libraries:**

pandas
numpy
seaborn
scikit-learn
xgboost
joblib
matplotlib
tkinter

**You can install these with the following pip command:**

bash
Copy code
pip install pandas numpy seaborn scikit-learn xgboost joblib matplotlib
Project Structure
car_data.xls: Dataset containing details about cars.
car_price_prediction.py: Main script for processing data, training models, and running the GUI.
Getting Started
Set up your environment Ensure that Python and the required packages are installed.

**Run the script Execute the script in your Python environment:**

bash
Copy code
python car_price_prediction.py
Using the GUI

Launch the GUI.
Input the car's features.
Click 'Predict' to see the predicted selling price.
How It Works
Data Preprocessing

Load the dataset and perform cleaning operations.
Encode categorical variables and remove outliers.
Calculate additional features like the car's age from its year of manufacture.
Model Training

Split the data into training and testing datasets.
Train multiple regression models (Linear Regression, Random Forest, Gradient Boosting, and XGBoost).
Evaluate model performance using the R-squared metric.
GUI for Predictions

A Tkinter-based GUI allows users to enter car attributes.
The GUI uses a trained model to predict and display the selling price based on the input.

**GUI Details**
The GUI prompts for the following inputs:
**Present_Price:** The original showroom price of the car.
**Kms_Driven:** Total kilometers the car has been driven.
**Fuel_Type:** Type of fuel (0: Petrol, 1: Diesel, 2: CNG).
**Seller_Type:** Type of seller (0: Dealer, 1: Individual).
**Transmission:** Type of transmission (0: Manual, 1: Automatic).
**Owner:** The number of previous owners.
**Age:** Age of the car from the current year.

**Note**
Make sure all inputs are provided in the correct format and datatype for accurate predictions. The application is set up to handle basic error checking.

This README provides all necessary instructions to get started with the car price prediction project, ensuring users can effectively interact with the system and understand its functionality.
