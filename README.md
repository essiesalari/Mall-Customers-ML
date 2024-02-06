# Mall Customers Clustering Project

## Project Overview

This project aims to segment customers into different groups based on their shopping habits at a mall. The dataset used in this project is the Mall Customers Dataset, which contains information about mall customers such as their age, gender, annual income, and spending score.

## Dataset

The Mall Customers Dataset consists of the following features:

- `CustomerID`: Unique ID assigned to the customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

## Methodology

The project uses clustering algorithms to segment customers into different groups. The steps involved in the project are:

1. **Data Preprocessing**: The data is cleaned and preprocessed for the model.
2. **Exploratory Data Analysis (EDA)**: EDA is performed to understand the data and find any interesting patterns.
3. **Model Building**: Clustering algorithms are applied to the data.
4. **Evaluation**: The performance of the model is evaluated.

## Findings
A variety of clustering models were applied to the dataset in this study. The performance of each model was evaluated using the Silhouette score, a metric that measures how similar an object is to its own cluster compared to other clusters.

To aid in visualizing the results in a lower-dimensional space, the t-Distributed Stochastic Neighbor Embedding (t-SNE) method was employed for dimensionality reduction.

Upon analysis, it was found that the SpectralClustering model provided the best fit for the dataset. This conclusion was drawn based on the model’s superior performance in terms of the Silhouette score and the visual inspection of the t-SNE plot.

This study demonstrates the effectiveness of SpectralClustering in identifying meaningful patterns within the dataset. Future work may explore the application of this model to other datasets or the optimization of its parameters for improved performance.
