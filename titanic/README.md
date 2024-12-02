# Titanic

## Description

# Logistic Regression with Python

### About Logistic Regression

Logistic Regression is a statistical method used in machine learning for binary classification problems. In the context of the Titanic dataset, the algorithm predicts whether a passenger survived (1) or not (0) based on various features like age, gender, class, and more.

#### How Logistic Regression Works:
1. **Model Basics**:
   - Unlike linear regression, logistic regression predicts probabilities that lie between 0 and 1 using the sigmoid function:
     \[
     \sigma(z) = \frac{1}{1 + e^{-z}}
     \]
     where \(z = \beta_0 + \beta_1x_1 + \beta_2x_2 + \ldots + \beta_nx_n\).

2. **Binary Output**:
   - The output is a probability, which is then converted into a binary classification based on a threshold (e.g., 0.5).

3. **Feature Importance**:
   - Logistic regression calculates weights (\(\beta\)) for each feature, indicating their contribution to the outcome.

4. **Assumptions**:
   - The features should have a linear relationship with the log-odds of the dependent variable.
   - Multicollinearity among features should be minimal.

#### Applications in Titanic Dataset:
- Predicting survival status based on features like:
  - Passenger class (Pclass)
  - Gender (Sex)
  - Age
  - Number of siblings/spouses aboard (SibSp)
  - Number of parents/children aboard (Parch)

#### Advantages:
- Simple and interpretable.
- Works well for linearly separable datasets.
- Provides probabilities, not just classifications.

#### Limitations:
- Assumes linearity between features and the log-odds of the outcome.
- Performance decreases with highly complex or non-linear relationships.

By using Logistic Regression, you can understand how individual features influence survival and make predictions on new or unseen data effectively.

---

## Libraries Used

- matplotlib
- numpy
- pandas
- seaborn
- sklearn

## How to Run

1. Ensure you have Python installed.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Open the notebook using Jupyter Notebook or Jupyter Lab.
