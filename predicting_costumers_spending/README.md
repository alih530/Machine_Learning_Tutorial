# README

## Project: Predicting Customer Spending Using Linear Regression

This project demonstrates the use of **Linear Regression** to predict the amount of money spent by users based on the time they spend on a website and a mobile app. The goal is to identify how users' online activities influence their spending habits.

## Problem Statement

We aim to predict the **Yearly Amount Spent** by a user using the following features:
- **Time on Website**: The amount of time a user spends on the website.
- **Time on App**: The amount of time a user spends on the mobile app.
- **Other Features**: (Optional) Additional predictors such as session counts, customer age, etc.

## Workflow

### 1. **Data Loading and Preprocessing**
   - Load the dataset into a DataFrame.
   - Inspect and clean the data (e.g., handle missing values or outliers).

### 2. **Exploratory Data Analysis (EDA)**
   - Visualize relationships between features using scatter plots and correlation heatmaps.
   - Gain insights into how **Time on Website** and **Time on App** correlate with **Yearly Amount Spent**.

### 3. **Splitting Data**
   - Split the dataset into training and testing sets.

### 4. **Model Training**
   - Fit a **Linear Regression** model on the training set.

### 5. **Model Evaluation**
   - Evaluate the model's performance using:
     - **Mean Absolute Error (MAE)**
     - **Mean Squared Error (MSE)**
     - **R² Score**
   - Analyze residual plots to check model assumptions.

### 6. **Conclusion**
   - Interpret the coefficients to understand how each feature impacts spending.
   - Suggest actionable insights for optimizing user engagement.

## Outputs
- **Model Coefficients**: Impact of each feature on the predicted amount spent.
- **Performance Metrics**: MAE, MSE, and R² values.
- **Visualizations**: Plots showing the relationships between features and the target variable.

## License
This project is licensed under the MIT License.