# iris-ML-project

Author- Rishav Kumar

# Iris Dataset Analysis 🌸

## Overview

This project involves an in-depth analysis of the famous Iris dataset. The goal is to understand the characteristics of different iris species by exploring, visualizing, and modeling the data. The Iris dataset is widely used as a beginner's dataset in data science and machine learning.

## Dataset

The Iris dataset consists of 150 samples from three species of Iris flowers: Setosa, Versicolor, and Virginica. Each sample has four features:

- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**

The dataset can be found from seaborn .

## Project Structure
├── data
│ └── iris.csv # Dataset file
├── notebooks
│ └── iris_analysis.ipynb # Jupyter notebook with analysis
├── src
│ └── data_preprocessing.ipynb # Data preprocessing script
│ └── data_visualization.ipynb # Data visualization script
│ └── model_training.ipynb # Model training script
└── README.md # Project README file


## Analysis Steps

1. **Data Loading and Exploration**
   - Load the dataset and understand its structure.
   - Perform basic statistical analysis.

2. **Data Visualization**
   - Visualize the data to understand the distribution of features.
   - Create scatter plots, histograms, and pair plots.

3. **Data Preprocessing**
   - Handle missing values (if any).
   - Standardize/normalize the features.

4. **Model Training and Evaluation**
   - Split the data into training and testing sets.
   - Train machine learning models (e.g., K-Nearest Neighbors, Decision Tree, SVM).
   - Evaluate the models using accuracy.

## Results

The best-performing model in this analysis is the Support Vector Machine (SVM) with an accuracy of 95%. Detailed results and visualizations can be found in the [Jupyter notebook].
