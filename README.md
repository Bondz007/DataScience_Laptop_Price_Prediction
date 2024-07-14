## Laptop Price Prediction Model 💻📈

This repository contains code for predicting laptop prices based on various attributes using machine learning algorithms in R.

### Overview ℹ️

The project utilizes several machine learning algorithms including Random Forest, XGBoost, and Decision Trees to predict the price of laptops from a given dataset (`laptops.csv`). Key attributes such as weight, operating system (OS), and company are used as predictors.

### Libraries Used 📚

- `stats`
- `dplyr`
- `randomForest`
- `xgboost`
- `e1071`
- `ggplot2`
- `caret`
- `mlbench`
- `tree`

### Data Preprocessing 🛠️

The dataset undergoes preprocessing steps:

- Cleaning screen size, RAM, and weight columns for numeric conversion.
- Splitting the dataset into training and testing sets with a 70/30 split.

### Models Implemented 🤖

#### Random Forest Model (RFM)

- Trained using `randomForest` package.
- Predicted prices for testing dataset.

#### XGBoost Model

- Implemented with `xgboost` package.
- Utilized as a boosting technique for regression.

#### Decision Tree Model (DTM)

- Created using `tree` package.
- Predicted prices using decision rules.

### Evaluation Metrics 📊

Evaluation metrics used:

- Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) for each model.
- R-squared value for model fit assessment.

### Feature Selection 🔍

Recursive Feature Elimination (RFE) using `caret` package to select optimal features for Random Forest and XGBoost models.

### Results 📊

- Detailed results including MSE, RMSE, and R-squared values for each model.
- Visualization of actual vs. predicted prices using `ggplot2`.

![2](https://github.com/user-attachments/assets/8f6f95fe-ddd3-4edc-944f-a4c42ca195af)

### Usage 🚀

1. Clone the repository.
2. Ensure all required libraries are installed (`install.packages`).
3. Run `laptop_price_prediction.R` to replicate the results.
4. Modify parameters or algorithms as needed for experimentation.
