# Car Price Prediction 🚗💰


## Table of Contents

1. [Introduction](#introduction)
2. [Deployment](#deployment)
3. [Demo](#demo)
4. [Tools Used](#tools-used)
5. [Libraries](#libraries)
6. [Algorithms Used](#algorithms-used)
7. [Results](#results)
8. [Files Structure](#files-structure)
9. [Installation](#installation)
10. [Usage](#usage)
11. [Future Work](#future-work)
12. [License](#License)

## Introduction 📝

This project focuses on predicting car prices using machine learning techniques. The dataset used consists of various features such as mileage, brand, model, etc., and the target variable is the price of the car. The goal is to build a model that accurately predicts the price of a car given its features.

### Deployment 🚀

[Deployment Link](https://carpricepredict-crlkxz3lbkn.streamlit.app/)

### Demo

![Car_Price](https://github.com/neerajcodes888/Data-Science/assets/98253646/70f2cbf1-e153-4877-afac-80dca565a0d0)

## Tools Used 🔧

- Python
- Streamlit

## Libraries 📚

- scikit-learn (sklearn)
- Plotly
- Pandas
- NumPy

## Algorithms Used 🤖

1. Decision Tree
2. Random Forest (yielding highest accuracy)
3. XGBoost
4. Linear Regression

## Results 📊

The Random Forest algorithm yielded the highest accuracy among the algorithms tested. Here are the accuracy scores for each algorithm:

| Algorithm         | Accuracy Score |
|-------------------|----------------|
| Decision Tree     | 0.94           |
| Random Forest     | 0.9477 (highest) |
| XGBoost           | 0.9474           |
| Linear Regression | 0.81           |

## Files Structure 📂

| File/Folder          | Description                                                  |
|----------------------|--------------------------------------------------------------|
| Prediction_model/    | Directory containing the trained machine learning models.    |
| Prediction.ipynb     | Jupyter notebook for training the machine learning models.   |
| app.py               | Streamlit web application for interacting with the models.    |
| car_data.xls         | Dataset containing car features and prices.                  |
| requirements.txt     | List of Python dependencies required for the project.  
## Installation 🛠️



## Usage ℹ️

Train the model:

```bash
python  prediction.ipynb
```

Run the Streamlit app:

```bash
streamlit run app.py
```


## Future Work 🔮

Some potential areas for future improvement and expansion include:

- Incorporating additional features such as car age, fuel type, and condition.
- Experimenting with more advanced machine learning algorithms.
- Fine-tuning model hyperparameters for improved performance.
- Building a user interface for data input and displaying predictions in the Streamlit app.
- Handling outliers and missing data more effectively.
- Implementing feature engineering techniques to create more informative features.



