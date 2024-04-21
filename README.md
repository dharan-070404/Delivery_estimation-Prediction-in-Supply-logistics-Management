#Predictive Delivery Time Estimation
This project aims to predict the delivery time for online orders using machine learning techniques. By leveraging geographical data, shipping details, and historical order processing times, the model provides estimates for the time it takes for an order to be delivered to the customer.

#Project Structure
dataset4.csv: raw dataset before data preprocessing
finaldata2.csv: Contains the dataset used for training and testing the model.
data_processing.ipynb: Script for cleaning and preprocessing the dataset.
model_creation.ipynb: Script for training the machine learning model and for predicting delivery times for new input.
#Data Preprocessing
Distance Calculation: Utilizes the Haversine formula to calculate distances between order locations.
Multiplier Assignment: Assigns weighted factors to shipping modes to determine their impact on delivery times.
Approximate Time Calculation: Estimates approximate delivery times based on distance and shipping mode.
Transit Time Normalization: Normalizes approximate delivery times to a range of 1-4 for easier interpretation.
Usage
Install dependencies using pip install -r requirements.txt.
Run data_processing.ipynb to preprocess the dataset.
Execute model_creation.ipynb to train the machine learning model.
#Acknowledgments
This project was inspired by the need to optimize delivery operations in the e-commerce industry.
