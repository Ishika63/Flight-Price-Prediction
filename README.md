# Flight-Price-Prediction

This repository contains a Flight Price Prediction application built using Python and machine learning techniques. The application predicts the price of flights based on historical data and various features like route, airline, departure time, and more.

## Table of Contents

- [Project Structure](#project-structure)
- [Project Description](#project-description)
- [Features](#features)
- [Demo](#demo)
- [Libraries Used](#libraries-used)
- [Column Descriptions](#column-descriptions)

  

## Project Structure

The repository is organized as follows:

- `templates/`: Contains HTML templates for the web application.
  - `home.html`: The main template for the flight price prediction web page.
- `Data_Train.xlsx`: The training dataset used to train the machine learning model.
- `Test_set.xlsx`: The test dataset used to evaluate the model's performance.
- `app.py`: The Python script that runs the web application.
- `flight_price.ipynb`: Jupyter Notebook containing the data preprocessing, model training, and evaluation code.
- `styles.css`: CSS file for styling the web application.
- `flight_rf.pkl`: A pre-trained machine learning model saved as a pickle file.


## Project Description

The Flight Price Prediction application is designed to help users estimate the cost of flights based on various parameters such as source, destination, date, airline, and more. It leverages machine learning algorithms to provide accurate price predictions, helping travelers make informed decisions when booking flights.

## Features

- Predicts flight prices based on user input.
- Interactive web interface for easy use.
- Supports a wide range of airlines and routes.
- Provides insights into price trends.
- User-friendly and intuitive design.

## Demo

Flight Price Prediction App Screenshot:

![Flight_price](https://github.com/Ishika63/Flight-Price-Prediction/assets/80192358/e5e4ad77-b5cf-43e6-8d63-501d6812bda0)


## Libraries Used

The Flight Price Prediction application is built using the following libraries and tools:

- [Flask](https://flask.palletsprojects.com/): A web framework for creating the web interface.
- [Flask-CORS](https://flask-cors.readthedocs.io/): A Flask extension for handling Cross-Origin Resource Sharing (CORS) to allow requests from different domains.
- [scikit-learn](https://scikit-learn.org/): A machine learning library used for model creation and prediction.
- [Pickle](https://docs.python.org/3/library/pickle.html): Python's built-in module for serializing and deserializing objects.
- [Pandas](https://pandas.pydata.org/): A data manipulation and analysis library.
- [NumPy](https://numpy.org/): A library for numerical computing in Python.
- [Matplotlib](https://matplotlib.org/): A library for creating visualizations and plots.
- [Seaborn](https://seaborn.pydata.org/): A data visualization library based on Matplotlib.
- [ExtraTreesRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.ExtraTreesRegressor.html): A regression model from scikit-learn's ensemble module.
- [RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html): A regression model from scikit-learn's ensemble module for the machine learning model.



## Column Descriptions

The dataset used in this project contains the following columns:

1. **Airline**: The name of the airline carrier.

2. **Date_of_Journey**: The date of the flight journey.

3. **Source**: The departure city or airport.

4. **Destination**: The arrival city or airport.

5. **Route**: The flight route, including connecting airports if any.

6. **Dep_Time**: The departure time.

7. **Arrival_Time**: The arrival time at the destination.

8. **Duration**: The duration of the flight.

9. **Total_Stops**: The number of stops during the flight.

10. **Additional_Info**: Additional flight information, if any.

11. **Price**: The price of the flight ticket (the target variable for prediction).
