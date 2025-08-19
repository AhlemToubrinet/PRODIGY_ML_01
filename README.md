# PRODIGY_ML_01: House Price Prediction using Linear Regression

## Project Overview
This project implements a machine learning solution to predict house prices based on key features like square footage, bedrooms, and bathrooms. Developed as part of a Prodigy Infotech internship task, it demonstrates fundamental regression techniques using the Kaggle House Prices dataset.

## Features
- **Multiple Models**:
  - Simple Linear Regression (single feature)
  - Multiple Linear Regression
- **Evaluation Metrics**: MSE, R² Score
- **Visualizations**: Feature-target relationships and prediction comparisons

## Dataset
The [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) dataset from Kaggle contains:
- 79 explanatory variables
- 1,460 training examples
- Key features used:
  - `GrLivArea`: Above grade living area (sq ft)
  - `BedroomAbvGr`: Bedrooms above grade
  - `FullBath`: Full bathrooms
  - `HalfBath`: Half bathrooms
  - `SalePrice`: Target variable

## Installation
1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/PRODIGY_ML_01.git
   cd PRODIGY_ML_01
2. **Create and activate a virtual environment (recommended)**:
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook House_Price_Prediction.ipynb
