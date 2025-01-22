# Data Mining Projects (CS-535)

This repository contains three projects completed as part of the CS-535 Data Mining course. Each project focuses on different data mining techniques and their applications to real-world datasets.

## Project 1: Dimensionality Reduction

In this project, we implemented two dimensionality reduction techniques: Principal Component Analysis (PCA) and Discrete Cosine Transform (DCT). We applied these techniques to three datasets and compared the resulting dimensionalities. Additionally, we explored Singular Value Decomposition (SVD) as a third dimensionality reduction method.

Key findings:
- PCA and DCT yielded different dimensionalities due to their distinct mechanisms for capturing data variance.
- SVD showed the greatest variation in dimensional reduction, indicating its sensitivity to the underlying data structure.
- The reconstructed images from reduced dimensions demonstrated the effectiveness of these methods in capturing core information while minimizing dimensionality.

For detailed information, please refer to the [Project 1 Report](DM_Project_1.pdf).

## Project 2: Classification

This project focused on classification using the Adult dataset from the UCI Machine Learning Repository. We implemented a Random Forest classifier and compared its performance with other well-known classification methods.

Key steps and findings:
1. Data cleaning: Handled missing values in the dataset using imputation with mode for categorical variables.
2. Implemented Random Forest classifier and evaluated its performance.
3. Compared results with reported error rates of other classifiers.
4. Applied hyperparameter tuning to improve the model's performance.
5. Conducted random downsampling experiments to analyze the impact of training set size on model accuracy.
6. Proposed a single classifier solution using a Decision Tree with hyperparameter tuning, which outperformed classic classifiers.

For detailed information, please refer to the [Project 2 Report](DM_Project_2.pdf).

## Project 3: Clustering

In this project, we implemented a modified K-means clustering algorithm with the elbow method for time-series data. We applied this algorithm to the Synthetic Control dataset and a financial transaction dataset.

Key steps and findings:
1. Implemented modified K-means with the elbow method to determine the optimal number of clusters.
2. Applied the algorithm to the Synthetic Control dataset and evaluated the results using Adjusted Rand Index (ARI) and Normalized Mutual Information (NMI).
3. Prepared the financial transaction dataset for clustering by extracting, parsing, and engineering relevant features.
4. Applied the modified K-means algorithm to the financial transaction dataset and analyzed the resulting clusters.
5. Demonstrated the effectiveness of the modified K-means algorithm for both datasets through high Silhouette Scores, effective normalization, strategic feature engineering, and autonomous determination of cluster numbers.

For detailed information, please refer to the [Project 3 Report](DM_Project_3.pdf).

## Repository Structure

- `DM_Project_1.pdf`: Project 1 report on dimensionality reduction
- `DM_Project_2.pdf`: Project 2 report on classification
- `DM_Project_3.pdf`: Project 3 report on clustering
- `README.md`: This file, providing an overview of the repository and its contents
