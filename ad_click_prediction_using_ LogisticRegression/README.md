
# Ad Click Prediction Using Logistic Regression

This project focuses on predicting whether a user will click on an advertisement based on various features using **Logistic Regression**. The dataset used is `advertising.csv`.

## Project Overview
The notebook performs the following tasks:
1. **Data Loading and Exploration**  
   - Loads the dataset using `pandas`.
   - Visualizes relationships between different features using `seaborn`.
  
2. **Data Preprocessing**  
   - Converts the `Timestamp` feature into the day of the week.
   - Creates dummy variables for categorical data.
   - Drops irrelevant features to prepare the dataset for model training.

3. **Model Building**  
   - Splits the dataset into training and testing sets using `train_test_split`.
   - Trains a Logistic Regression model using `sklearn`.

4. **Model Evaluation**  
   - Evaluates the model's accuracy on the test set.

## Installation
To run this project, you need to have the following libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Dataset
The dataset `advertising.csv` contains the following columns:
- **Daily Time Spent on Site**: Time spent on the site by the user.
- **Age**: Age of the user.
- **Area Income**: Income of the user based on their geographical area.
- **Daily Internet Usage**: Time spent on the internet daily.
- **Ad Topic Line**: The topic of the ad.
- **City**: The user's city.
- **Country**: The user's country.
- **Timestamp**: Time the ad was clicked.
- **Clicked on Ad**: Whether the user clicked on the ad (1) or not (0).

## Results
The accuracy of the model on the test data is printed as a simple performance metric.

## Future Improvements
Some potential areas for improvement:
- Add feature engineering and normalization.
- Test different classification algorithms.
- Perform hyperparameter tuning for better accuracy.
