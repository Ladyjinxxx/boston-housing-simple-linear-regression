# Boston Housing Price Prediction using Simple Linear Regression

## Project Overview

This project demonstrates the complete machine learning workflow for building a **Simple Linear Regression** model using the Boston Housing dataset. The objective is to predict the median house value (MEDV) using a single predictor variable selected based on correlation analysis.

The project includes data cleaning, exploratory data analysis, feature selection, model training, model evaluation, and visualization. It was developed as part of a Machine Learning internship task.

---

## Objectives

- Clean and preprocess the raw dataset.
- Perform exploratory data analysis (EDA).
- Identify the most suitable predictor variable.
- Build a Simple Linear Regression model.
- Evaluate the model using regression metrics.
- Visualize model performance through various plots.

---

## Dataset

**Dataset:** Boston Housing Dataset

The original dataset was provided in a raw format where all values were stored in a single column. The notebook performs preprocessing to separate the values into their respective attributes before analysis.

### Features

- CRIM
- ZN
- INDUS
- CHAS
- NOX
- RM
- AGE
- DIS
- RAD
- TAX
- PTRATIO
- B
- LSTAT

### Target Variable

- MEDV (Median Value of Owner-Occupied Homes)

---

## Project Workflow

1. Import required libraries
2. Mount Google Drive
3. Load the raw dataset
4. Clean and preprocess the data
5. Perform exploratory data analysis
6. Generate a correlation matrix and heatmap
7. Select the best predictor variable
8. Split the dataset into training and testing sets
9. Train the Simple Linear Regression model
10. Generate predictions
11. Evaluate model performance
12. Visualize regression results
13. Save outputs to Google Drive

---

## Machine Learning Model

**Algorithm**

- Simple Linear Regression

---

## Evaluation Metrics

The model is evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## Visualizations

The notebook generates the following figures:

- Correlation Heatmap
- Scatter Plot
- Regression Line
- Actual vs Predicted Values
- Residual Plot
- Residual Distribution Histogram

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

```
BostonHousingRegression/
│
├── LinearRegression.ipynb
├── README.md
├── dataset/
│   └── house Prediction Data Set.csv
│
├── outputs/
│   ├── Charts/
│   ├── Tables/
│   └── Predictions/
│
└── requirements.txt
```

---

## Results

The notebook automatically saves:

- Cleaned Dataset
- Correlation Matrix
- Model Coefficients
- Predictions
- Evaluation Metrics
- Analysis Summary
- High-resolution charts

---

## Future Improvements

Possible extensions for this project include:

- Multiple Linear Regression
- Feature Engineering
- Cross Validation
- Polynomial Regression
- Model Comparison with Decision Trees and Random Forests

---

## Author

**Lady Jean Y. Geverola**

BS Data Science  
University of the Philippines Mindanao
