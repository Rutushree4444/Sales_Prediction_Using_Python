
---

# 2. `README.md` — Sales Prediction Using Python

For your **Sales Prediction** project, use this:

```markdown
# Sales Prediction Using Python

## Project Overview

This project uses Machine Learning regression techniques to predict sales based on advertising expenditure across different advertising channels.

The dataset contains advertising budgets for TV, Radio, and Newspaper along with the corresponding Sales values.

The project demonstrates the complete Machine Learning workflow, including data exploration, visualization, model training, prediction, evaluation, and interpretation.

## Objectives

- Analyze advertising expenditure and sales data.
- Perform data cleaning and preprocessing.
- Understand relationships between advertising channels and sales.
- Visualize the relationship between advertising expenditure and sales.
- Build regression models for sales prediction.
- Compare the performance of different Machine Learning models.
- Identify the relative importance of advertising channels.

## Dataset

The dataset contains advertising budgets and corresponding sales values.

### Features

- TV Ad Budget ($)
- Radio Ad Budget ($)
- Newspaper Ad Budget ($)

### Target

- Sales ($)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Exploratory Data Analysis

The following analysis is performed:

- Dataset inspection
- Descriptive statistics
- Missing value checking
- Sales distribution visualization
- Sales vs TV advertising scatter plot
- Sales vs Radio advertising scatter plot
- Sales vs Newspaper advertising scatter plot
- Correlation heatmap

## Machine Learning Models

Two regression models are used:

### 1. Linear Regression

Linear Regression is used as the baseline model for predicting sales from advertising expenditure.

### 2. Random Forest Regression

Random Forest Regression is used as an additional Machine Learning model to capture non-linear relationships between advertising expenditure and sales.

## Model Evaluation

The models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The model results are compared to understand their predictive performance.

## Additional Analysis

A residual plot is created to analyze prediction errors.

Feature importance from the Random Forest model is also examined to understand the relative contribution of each advertising channel to the model's predictions.

Feature importance indicates predictive contribution and should not be interpreted as proof of a causal effect on sales.

## Machine Learning Workflow

1. Import libraries
2. Load the dataset
3. Inspect the dataset
4. Clean the data
5. Generate descriptive statistics
6. Perform Exploratory Data Analysis
7. Create visualizations
8. Generate a correlation heatmap
9. Select features and target
10. Split the data into training and testing sets
11. Train Linear Regression
12. Train Random Forest Regression
13. Make predictions
14. Evaluate both models
15. Compare model performance
16. Analyze residuals
17. Analyze feature importance
18. Interpret the results

## Project Structure

```text
sales-prediction-ml/
│
├── Sales_Prediction_Using_Python.ipynb
├── Advertising.csv
└── README.md
