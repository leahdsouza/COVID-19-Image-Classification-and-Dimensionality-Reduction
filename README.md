# COVID-19-Image-Classification-and-Dimensionality-Reduction
This project explores dimensionality reduction, unsupervised learning, and neural networks applied to chest X-ray images to classify and cluster images of COVID-19, Viral Pneumonia, and Normal conditions.

## Overview
The project involves:
- Dimensionality Reduction: Applying Principal Component Analysis (PCA) to reduce the complexity of image data while preserving 90% of the variance. Visualization includes comparing original images to their PCA-reconstructed versions.

- Unsupervised Learning: Using techniques such as PCA, t-SNE, LLE, and MDS to visualize and cluster images. The goal is to explore if dimensionality reduction can reveal distinct clusters among the different categories of images.

- Clustering: Implementing K-Means and Expectation-Maximization (EM) clustering algorithms to group images. The optimal number of clusters is determined, and clustering accuracy is evaluated.

- Data Generation: Using the trained models to generate and visualize new images in the original space.

## Dataset
The dataset used in this project is available on Kaggle: [COVID-19 Image Dataset on Kaggle](https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset)
