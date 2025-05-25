Car Price Prediction using Machine Learning

This project aims to predict the prices of cars based on various features using regression techniques. It is a part of the Machine Learning module end project for the Entri Elevate – Data Science and Machine Learning course.


---

Table of Contents

Overview

Dataset

Technologies Used

Project Structure

How to Run

Results

Conclusion



---

Overview

The primary goal of this project is to build a machine learning model that can predict car prices based on features such as brand, year, engine type, horsepower, and more. The steps involved include:

Data cleaning and preprocessing

Exploratory data analysis (EDA)


Model training and evaluation

Comparing models like Linear Regression, Random Forest, etc.



---

Dataset

The dataset contains car listings  with features such as:

Make

Model

Year

Engine Fuel Type

Transmission Type

Driven Wheels

Number of Doors

Market Category

Vehicle Size

Vehicle Style

Highway MPG

City MPG

Popularity

MSRP (Price)


> Note: The dataset is provided as part of the course material and is intended for educational purposes only.




---

Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook



---

Project Structure

car-price-prediction/
├── data/                      # Raw dataset files
├── notebooks/                 # EDA and model-building notebooks
├── images/                    # Visualizations for README
├── car_price_prediction.py    # (Optional) Script version of the notebook
├── requirements.txt           # List of dependencies
└── README.md                  # Project documentation


---

How to Run

1. Clone the repository:

git clone https://github.com/yourusername/car-price-prediction.git
cd car-price-prediction


2. Install the dependencies:

pip install -r requirements.txt


3. Launch the Jupyter Notebook:

jupyter notebook notebooks/car_price_prediction.ipynb




---

Results

Linear Regression R² Score: e.g., 0.87

Random Forest Regressor R² Score: e.g., 0.91

Top Influential Features:

Year

Engine HP

Vehicle Size



