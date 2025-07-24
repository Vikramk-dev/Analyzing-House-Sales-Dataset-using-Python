# Analyzing-House-Sales-Dataset-using-Python

## 🏠 House Sales Analysis – King County, USA

This project presents an end-to-end **data analysis and visualization** of house sales data from King County, Washington (USA), including Seattle. The analysis is performed using Python and various data science libraries to uncover insights from the housing market between May 2014 and May 2015.

---

## 📌 Project Objectives

- Understand the structure and patterns in King County house sales data
- Clean and preprocess the dataset for analysis
- Visualize key metrics affecting house prices
- Derive insights to inform decision-making in the real estate market

---

## 📁 Repository Structure
├── housing.csv # Dataset: House sales in King County

├── House_Sales_in_King_Count_USA.ipynb # Jupyter notebook with full analysis

└── README.md # Project documentation


---

## 📊 Dataset Summary

- **Source:** [Kaggle - King County House Sales](https://www.kaggle.com/harlfoxem/housesalesprediction)
- **Size:** 21,613 rows × 21 columns
- **Period:** May 2014 – May 2015
- **Features Include:**
  - `price`, `bedrooms`, `bathrooms`, `sqft_living`, `floors`, `waterfront`
  - `condition`, `grade`, `zipcode`, `lat`, `long`, `yr_built`, etc.

---

## 🛠️ Technologies & Libraries

- **Python 3**
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Jupyter Notebook](https://jupyter.org/)

---

## 📈 Key Exploratory Analysis

- **Data Cleaning:**
  - Removed duplicates
  - Checked for and handled missing values
  - Converted datatypes (e.g., date columns)

- **Visualizations:**
  - Price distribution and outliers
  - Correlation heatmap
  - Price trends by zipcode
  - Impact of number of bedrooms, bathrooms, and square footage
  - Influence of waterfront and home grade on price

---

## 📌 Insights Discovered

- Homes with **waterfront views** command significantly higher prices.
- **Grade** and **living area** are strong predictors of price.
- Certain **zipcodes** consistently have higher median house prices.
- **Renovated homes** and those with better condition tend to sell for more.
---
