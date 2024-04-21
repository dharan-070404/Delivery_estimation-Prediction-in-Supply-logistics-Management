# Predictive Delivery Time Estimation

This project aims to predict the delivery time for online orders using machine learning techniques. By leveraging geographical data, shipping details, and historical order processing times, the model provides estimates for the time it takes for an order to be delivered to the customer.

## Project Structure

- **dataset4.csv:** Raw dataset before data preprocessing.
- here is the link for raw datasets we used in that data preprocessing code
https://drive.google.com/drive/folders/17y-fLRVxbznK-XWPo_FfmnEJeCAwSlUC?usp=drive_link
- **finaldata2.csv:** Processed dataset used for training and testing the model.
- **data_processing.ipynb:** Jupyter Notebook for cleaning and preprocessing the dataset.
- **model_creation.ipynb:** Jupyter Notebook for training the machine learning model and predicting delivery times for new inputs.

## Data Preprocessing

- **Distance Calculation:** Utilizes the Haversine formula to calculate distances between order locations.
- **Multiplier Assignment:** Assigns weighted factors to shipping modes to determine their impact on delivery times.
- **Approximate Time Calculation:** Estimates delivery times based on distance and shipping mode.
- **Transit Time Normalization:** Normalizes delivery times to a range of 1-4 for easier interpretation.

## Usage

1. Install dependencies using `pip install -r requirements.txt`.
2. Run `data_processing.ipynb` to preprocess the dataset.
3. Execute `model_creation.ipynb` to train the machine learning model.

## Acknowledgments

This project was inspired by the need to optimize delivery operations in the e-commerce industry.
