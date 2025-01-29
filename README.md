# Sales Prediction using Linear Regression

This project predicts **Sales** based on **Advertising Spending** across different media channels (TV, Radio, and Newspaper) using a **Linear Regression** model.

## Project Overview

The goal of this project is to build a predictive model that can forecast the sales of a company based on the advertising budget across various channels. The dataset includes the following features:

- **TV**: Advertising spend on TV (in thousands of dollars)
- **Radio**: Advertising spend on Radio (in thousands of dollars)
- **Newspaper**: Advertising spend on Newspaper (in thousands of dollars)
- **Sales**: Actual sales (in thousands of units)

## Data

The dataset contains 200 rows and 4 columns: `TV`, `Radio`, `Newspaper`, and `Sales`. The dataset is used to train a model to predict the `Sales` based on the other features.

### Data Source

The dataset for this project is sourced from a public dataset . It can be downloaded from the repository or used as an example.

## Installation

### 1. Clone the Repository

To clone this project to your local machine, use the following command:

```bash
git clone https://github.com/ivykogo/sales-prediction.git
```

### 2. Model Training and Evaluation:

  **Model Selection:** 
  Chosen Linear Regression as the initial model due to its interpretability and simplicity.
  
  **Model Training:**
  Split the data into training and testing sets.
  Trained a Linear Regression model on the training data.
  
  **Model Evaluation:**
  Evaluated the model's performance on the testing set using metrics such as:
  
  **R-squared:** 0.9059 
 
  **Mean Squared Error (MSE):** 2.9077
  
  **Mean Absolute Error (MAE):** 1.2748

### 3. Model Interpretation:

Analyzed the coefficients of the fitted model to comprehend the relative influence of each advertising channel on sales.

## Results and Insights
  
  **Model Performance:**
     Achieved an R-squared of 0.9059 on the test set, indicating that the model explains a significant portion of the variance in sales.
     Obtained a Mean Squared Error (MSE) of 2.9077 and a Mean Absolute Error (MAE) of 1.2748.
  **Feature Importance:**
     Analyzed the coefficients of the linear regression model to determine the relative importance of each advertising channel.
     Identified that **TV advertising** has the strongest positive correlation with sales, followed by **Radio** advertising.
     **Newspaper advertising** exhibited a comparatively weaker impact on sales.
