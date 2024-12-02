
# Project: Support Vector Machines with Iris Dataset and Other Examples

This repository contains two Jupyter notebooks that demonstrate the implementation of Support Vector Machines (SVM) for classification tasks on different datasets, including the famous Iris dataset and Breast Cancer dataset.

## Contents

### 1. `Iris_flower_dataset_with_svm.ipynb`
This notebook provides an in-depth analysis of the Iris dataset using SVM. 

#### Key Sections:
- **Import Libraries**: Essential packages like pandas, NumPy, matplotlib, and seaborn.
- **Exploratory Data Analysis (EDA)**: Visualizations and data exploration.
- **Train-Test Split**: Dividing the dataset for training and testing purposes.
- **Training the SVM Model**: Implementation of SVM classifier.
- **Model Evaluation**: Performance metrics and confusion matrix.
- **GridSearch for Hyperparameter Tuning**: Optimizing SVM parameters using GridSearchCV.

#### Example Code Snippets:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
```python
# The Iris Setosa
from IPython.display import Image
url = 'http://upload.wikimedia.org/wikipedia/commons/5/56/Kosaciec_szczecinkowaty_Iris_setosa.jpg'
Image(url, width=300, height=300)
```

### 2. `SVM.ipynb`
This notebook demonstrates SVM on the Breast Cancer dataset.

#### Key Sections:
- **Import Libraries**: Standard libraries for data manipulation and visualization.
- **Data Loading and Preparation**: Loading and exploring the Breast Cancer dataset.
- **Train-Test Split**: Preparing data for model training.
- **Training SVM Classifier**: Implementing SVM for classification.
- **Evaluations**: Predictions and evaluation metrics.
- **Hyperparameter Tuning**: Using GridSearchCV for parameter optimization.

#### Example Code Snippets:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
```python
from sklearn.datasets import load_breast_cancer
cancer = load_breast_cancer()
```

## How to Run
1. Ensure you have Python installed.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebooks in Jupyter or any compatible environment and run the cells.

## Outputs
- **Performance Metrics**: Accuracy, confusion matrix, and classification reports.
- **Visualizations**: Graphs and plots showcasing the data and model decisions.

## License
This project is licensed under the MIT License.
