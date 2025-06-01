# House Price Prediction

This repository contains a dataset and a machine learning model implemented in a Jupyter Notebook that predicts house prices based on various features. The dataset and the model are aimed at demonstrating regression modeling in a real-world context.

---

## Dataset

The dataset (`House_Price.csv`) contains information about houses, including features like:

* **Bedrooms**: Number of bedrooms in the house
* **Bathrooms**: Number of bathrooms in the house
* **Living Area**: Square footage of the living space
* **Lot Size**: Size of the lot in square footage
* **Floors**: Number of floors in the house
* **Waterfront**: Whether the house has a waterfront view
* **View**: Quality of the view from the house
* **Condition**: Overall condition of the house
* **Grade**: Overall grade of the construction and design
* **Year Built**: The year the house was built
* **Year Renovated**: The year the house was last renovated
* **Zipcode**: Location information
* **Price**: Target variable — the price of the house.

---

## Model Overview

The notebook (`prediction-house-price.ipynb`) walks through a typical machine learning workflow:

1. **Data Loading & Exploration**
   Loads the dataset, performs basic exploration, and displays summary statistics and visualizations to understand data distributions and relationships between features.

2. **Data Preprocessing**
   Handles missing values, encodes categorical variables, and scales numerical features if necessary.

3. **Model Building**
   Implements a regression model using scikit-learn, such as Linear Regression, Random Forest, or XGBoost.

4. **Model Evaluation**
   Splits the data into training and testing sets, trains the model, and evaluates it using metrics like RMSE (Root Mean Squared Error) and R² score.

5. **Prediction**
   Uses the trained model to make predictions on new/unseen data.
