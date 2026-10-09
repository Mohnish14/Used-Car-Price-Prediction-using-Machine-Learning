# Used Car Price Prediction

## Brief Overview
This project applies Machine Learning regression techniques to predict the resale value of used cars. It features an interactive script that allows users to input specific vehicle details and receive an immediate price estimate.

## Link to Dataset
[Kaggle: Vehicle Dataset from Cardekho](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)

## Project Description
The automotive industry frequently struggles with accurately appraising the value of used cars. This project builds a predictive model to solve this. The workflow includes feature engineering (calculating car age, one-hot encoding categorical variables like Fuel Type and Transmission), training a Random Forest Regressor, and deploying an interactive command-line interface where users can input custom car specifications to get a real-time price prediction.

## Technologies Used
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-learn
* **Environment:** Jupyter Notebook / Python CLI

## Setup and Run Instructions
1. Download the dataset `car data.csv` and place it in the same directory as the script.
2. Install the necessary libraries by running: `pip install -r requirements.txt`
3. Run the Python script in your terminal or IDE.
4. The script will train the model and then prompt you to "Enter Vehicle Details for Prediction". Type your inputs and press Enter to see the predicted price.

## Key Information
* **Model Used:** Random Forest Regressor
* **Target Variable:** `Selling_Price`
* **Core Features:** Car Age, Present Price, Kms Driven, Fuel Type, Seller Type, Transmission.