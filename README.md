# Subspace Classifiers: PCA & LDA for Pose Estimation

## Author
Steve Nathan de Sa  
CSC 448 - Machine Learning  
Due: March 24, 2025  

## Overview

This project explores the power of **subspace learning** techniques, particularly:
- **Principal Component Analysis (PCA)**
- **Linear Discriminant Analysis (LDA)**

These are applied to real-world classification problems, including pose (orientation) estimation from image data.

## Objectives

- Understand and implement dimensionality reduction techniques.
- Apply PCA and LDA to high-dimensional datasets.
- Evaluate classifier performance in low-dimensional spaces.
- Gain insights into optimization, linear algebra, and data representation.

## Dataset

The project primarily uses a dataset titled `Boat.zip`, which contains images labeled by their orientation. The objective is to classify the pose of each image using subspace projection methods.

## Tasks

- Load and preprocess image data.
- Implement PCA and LDA from scratch.
- Visualize the projections in 2D/3D subspaces.
- Train simple classifiers (e.g., logistic regression, nearest neighbor) in these projected spaces.
- Compare classification accuracy between PCA and LDA approaches.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- (Optional) scikit-learn for benchmarking

## Running the Project

To run the project:
```bash
jupyter notebook Project3.ipynb
