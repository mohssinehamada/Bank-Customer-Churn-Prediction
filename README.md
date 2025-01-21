# Bank Customer Churn Prediction

This project analyzes a bank customer churn dataset using machine learning techniques. The objective is to predict whether a customer will churn based on their demographics and account information.

## Features
The project covers:
- Data loading and preprocessing
- Handling imbalanced datasets using class weights
- Building a logistic regression model pipeline
- Evaluating model performance using metrics, confusion matrix, and ROC curve
- Visualizing data distributions and feature correlations

## Technologies Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Dataset
The dataset contains customer information such as:
- `credit_score`
- `age`
- `balance`
- `products_number`
- `estimated_salary`
- `gender`
- `country`
- `churn` (target variable)

The data is loaded from a CSV file named `Bank Customer Churn Prediction.csv`.

## Project Highlights
1. **Preprocessing**
   - Numerical features are standardized using `StandardScaler`.
   - Categorical features are encoded using `OneHotEncoder`.

2. **Model Building**
   - A logistic regression model is trained using a pipeline.
   - Class weights are computed to address imbalanced data.

3. **Evaluation**
   - Model predictions are evaluated using a classification report and confusion matrix.
   - A Receiver Operating Characteristic (ROC) curve is plotted to visualize the model's performance.

4. **Visualizations**
   - Distribution plots of numerical features segmented by churn status.
   - Correlation heatmap of numerical features.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bank-customer-churn-prediction.git
   cd bank-customer-churn-prediction
