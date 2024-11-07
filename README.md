# Used Car Price Prediction

Used Car Price Prediction is a machine learning project that predicts the price of used cars based on various features like make, model, year, mileage, and other attributes. The project demonstrates the use of regression models to predict continuous variables, applied to a real-world dataset of used car prices.

## Features

- Data preprocessing and feature engineering for used car price prediction.
- Utilizes machine learning algorithms for regression tasks.
- Provides performance metrics for model evaluation.
- Simple user interface using Streamlit for interactive predictions.

## Dataset

The dataset used for this project consists of historical data on used car listings, including features such as the make, model, year, mileage, fuel type, and price.

## Prerequisites

Before running the Used Car Price Prediction project, ensure you have the following installed:

1. **Python** (>=3.8)
2. **Streamlit** (`pip install streamlit`)
3. **Pandas** (`pip install pandas`)
4. **NumPy** (`pip install numpy`)
5. **Scikit-Learn** (`pip install scikit-learn`)
6. **Matplotlib** (`pip install matplotlib`)
7. **Seaborn** (`pip install seaborn`)

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/abhimanyu726/Used_car_price_prediction.git
    cd Used_car_price_prediction
2. **Install the Dependencies**
Install the dependencies using pip:

    ```bash
    Copy code
    pip install -r requirements.txt
## Usage
1. **Run the Jupyter Notebook**
Open and run the Jupyter notebook used_car_price_prediction.ipynb for data exploration, model training, and evaluation.

    ```bash
    jupyter notebook used_car_price_prediction.ipynb
2. **Streamlit Interface**
For an interactive web-based prediction tool, use the Streamlit app:

    ```bash
    streamlit run app.py
Enter the required details (make, model, year, mileage, etc.) in the input fields.
The model will predict the likely price of the used car based on these inputs.
## Model
The project employs several machine learning algorithms to achieve optimal predictions. Models used include:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Each model’s performance is evaluated based on metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Results
Best Model: The Random Forest Regressor achieved the best performance in predicting used car prices with a low error margin.
Feature Importance: Features like car make, model, mileage, and year were identified as significant contributors to predicting car prices.
