# Kaggle Competition Submission: Binary Prediction with a Rainfall Dataset

## Overview

This repository contains my submission for the Kaggle competition "Binary Prediction with a Rainfall Dataset" (Playground Series - Season 5, Episode 3). The objective of the competition is to develop a model that accurately predicts binary outcomes based on a provided rainfall dataset.

## Repository Contents

- `Rainfall.ipynb`: Jupyter Notebook containing the data analysis, preprocessing steps, model development, and evaluation.
- `submissionrainfall_logreg`: CSV file with the predicted results formatted according to the competition's submission guidelines.
- `submissionrainfall_logreg_featureselection.csv`: CSV file with the predicted results formatted according to the competition's submission guidelines.
- `README.md`: This document providing an overview of the project and instructions for replication.

## Data Source

The dataset for this competition was generated from a deep learning model trained on the Rainfall Prediction using Machine Learning dataset.  
[Kaggle Competition Link](https://www.kaggle.com/competitions/playground-series-s5e3/data)

## Approach

1. **Data Exploration**: Conducted an initial analysis to understand the structure and characteristics of the dataset.  
2. **Data Preprocessing**: Handled missing values and performed feature scaling as necessary.  
3. **Feature Selection**: Selected the most predictive features based on correlation with the target variable, using a threshold of ±0.1 for the theta coefficient to determine inclusion as an additional test.  
4. **Model Selection**: Used logistic regression to estimate the probability of classification as 1.  
5. **Evaluation**: Assessed model performance using appropriate metrics.

## Results

The final model achieved a performance metric of 0.86

## Reproducing the Results

To replicate the results:

1. Clone this repository.
2. Install the required packages listed in `requirements.txt`.
3. Open and execute `Rainfall.ipynb` in Jupyter Notebook or Jupyter Lab.

