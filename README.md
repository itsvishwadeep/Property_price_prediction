# Property Price Prediction in Bangalore

## Overview
This project predicts property prices in Bangalore using a Linear Regression model. The prediction is based on user inputs for location, area (in square feet), number of bathrooms, and number of bedrooms. The dataset is sourced from Kaggle, and a simple HTML frontend is used for input and output.

## Dataset
The dataset includes:
- Location
- Area (in square feet)
- Number of Bathrooms
- Number of Bedrooms
- Price per square ft

## Installation
To run this project, install the required libraries:
```bash
pip install pandas
pip install numpy
pip install scikit-learn
pip install matplotlib
pip install joblib
pip install Flask
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/itsvishwadeep/Property_price_prediction
cd Property-price-prediction
```
2. Run the model:
```bash
jupyter notebook Property_Price_Prediction.ipynb
```
3. Open the HTML file to use the frontend:
```bash
open index.html
```
4. Enter the property details (location, area, number of bathrooms, number of bedrooms) in the HTML form to get the predicted price.

## Contributing
Contributions are welcome! Feel free to suggest improvements or open an issue.
