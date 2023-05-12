# PCA Seed Classification Comparison

This repository contains the implementation of a seed classification model using Principal Component Analysis (PCA) for dimensionality reduction. The project demonstrates the application of PCA to preprocess the dataset and compares the performance of various classification algorithms.
## Overview
The Seeds dataset consists of measurements of geometrical properties of kernels belonging to three different varieties of wheat: Kama, Rosa, and Canadian. The dataset contains 210 samples, with 70 samples for each variety. Each sample includes seven features describing the geometrical properties of the kernels. The goal is to build a classifier that can predict the wheat variety based on these features.
## Dependencies
- Python 3.x
- scikit-learn
- pandas
- matplotlib
- seaborn
- numpy
## Getting Started
1- Clone this repository to your local machine.
2- Install the required dependencies using pip: pip install -r requirements.txt
3- Run the main script: python pca_seed_classification_comparison.py
## Project Structure
- pca_seed_classification_comparison.py: Main script for loading the dataset, applying PCA, and comparing the performance of different classification algorithms.
- requirements.txt: Contains the required dependencies for this project.
## PCA for Dimensionality Reduction
Principal Component Analysis (PCA) is used as a dimensionality reduction technique, transforming the seven-dimensional feature space into a lower-dimensional space. In this case, the transformed space has two dimensions, which helps visualize the data and reduces the computational complexity of the models.
## Model Evaluation and Comparison
The performance of various classification algorithms (such as Logistic Regression, K-Nearest Neighbors, Decision Trees, and Support Vector Machines) is evaluated and compared after applying PCA to the dataset. The comparison is based on accuracy, precision, recall, and F1-score metrics.
## Results
The classification models demonstrate varying levels of accuracy in predicting the wheat variety based on the PCA-transformed measurements. The results, along with the reduced-dimensionality data visualization, are displayed in the form of plots.
