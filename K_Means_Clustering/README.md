
# K-Means Clustering with Python

This project demonstrates the implementation of the **K-Means Clustering** algorithm using Python and various libraries such as `scikit-learn`, `matplotlib`, and `seaborn`. The goal is to cluster generated data points into different groups based on their similarities.

## Project Overview

K-Means Clustering is an unsupervised machine learning algorithm that partitions a dataset into `K` distinct clusters. It works by iteratively updating the cluster centroids and reassigning data points to the nearest centroid until convergence.

## Key Features

- **Data Generation:** The dataset is generated using the `make_blobs` function from `scikit-learn`, allowing for easy customization of the number of samples, features, and clusters.
- **Visualization:** The data is visualized before and after clustering using `matplotlib` and `seaborn`.
- **K-Means Clustering:** The algorithm is applied to both scaled and unscaled versions of the data.
- **Silhouette Score Analysis:** A function is provided to determine the optimal number of clusters using the Silhouette Score, helping to find the most appropriate value for `K`.

## Requirements

The following libraries are required to run the notebook:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## How to Run

1. Clone the repository or download the notebook file.
2. Open the notebook in Jupyter Notebook or any compatible environment (e.g., Google Colab).
3. Run each cell sequentially to execute the code and visualize the results.

## Notebook Structure

1. **Import Libraries:** Import the necessary Python libraries for data manipulation and visualization.
2. **Data Generation:** Generate synthetic data using the `make_blobs` function.
3. **Data Visualization:** Visualize the raw data points.
4. **K-Means Clustering:** Apply K-Means clustering to both unscaled and scaled datasets.
5. **Silhouette Score:** Evaluate the clustering performance and determine the optimal number of clusters.

## Results

- The notebook demonstrates how scaling the data affects the clustering results.
- It provides insights into how to choose the optimal number of clusters using the Silhouette Score.

