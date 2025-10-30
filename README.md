# Apparent Temperature Prediction with Weather Data

This project is a simple Machine Learning application in a Jupyter Notebook (`Hava_durumu.ipynb`) that aims to predict the **Apparent Temperature** using the `RandomForestRegressor` model on hourly weather data fetched from the Open-Meteo API.

##  Project Goal

Our main goal is to develop a regression model that can accurately predict the **Apparent Temperature** (the temperature felt by the human body) using standard weather measurements (real temperature, humidity, wind speed, etc.).

##  Files Used

* `Hava_durumu.ipynb`: The main Python notebook containing steps for data fetching, preparation, model training, evaluation, and visualization.

## ✨ Key Features

1.  **API Integration:** Automatically fetches hourly forecast data for the location of Ankara, Turkey (Lat: 39.9199, Lon: 32.8543) via the Open-Meteo API.
2.  **Data Preparation:** The retrieved data is converted into a Pandas DataFrame, and missing values are cleaned by filling them with the mean.
3.  **Machine Learning Model:** The `RandomForestRegressor` model is utilized to perform the prediction task.
4.  **Model Evaluation:** Model performance is measured using Root Mean Squared Error (RMSE) and R-Squared Score (R²) metrics.
5.  **Visualization:** Scatter plots comparing actual vs. predicted values and residual distribution plots (error analysis) are generated.

##  Technologies Used

This project utilizes the following Python libraries:

* `requests`: For fetching weather data from the Open-Meteo API.
* `pandas`: For data manipulation and processing.
* `numpy`: For numerical operations and mathematical functions.
* `scikit-learn (sklearn)`: For the Machine Learning model (RandomForestRegressor) and data splitting operations.
* `matplotlib` / `seaborn`: For visualizing data and model results.

##  Setup and Execution

Follow these steps to run the project on your local machine or Google Colab.

### Prerequisites

Install the required project libraries:

```bash
pip install pandas scikit-learn numpy requests matplotlib seaborn
