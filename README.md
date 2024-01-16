# Accommodation Price Prediction Project

## Table of Contents
1. [Overview](#overview)
2. [Files](#files)
3. [Mission Steps](#mission-steps)
    - [1. Exploration and Preprocessing](#1-exploration-and-preprocessing)
    - [2. Feature Engineering](#2-feature-engineering)
    - [3. Model Training](#3-model-training)
    - [4. Model Evaluation](#4-model-evaluation)
    - [5. Predictions and Submission](#5-predictions-and-submission)
    - [6. Optional: Supplementary Analysis with metaData.csv](#6-optional-supplementary-analysis-with-metadatacsv)
4. [Instructions](#instructions)
5. [Dependencies](#dependencies)
6. [Contact](#contact)

## Overview

This project involves building a predictive model to determine whether rental accommodations have an expensive daily rental price or not. The dataset includes a training set for model training and a test set for evaluating model performance on unseen data.

## Files

- **train.csv:** Contains labeled data used for training the predictive model. Each row represents information about different apartments, and the labels indicate whether they have an expensive daily rental price or not.

- **test.csv:** A set of data points without corresponding labels, used to evaluate the model on unseen data. Similar to the training set but lacks information about whether the apartments have an expensive daily rental price or not.

- **sample_submission.csv:** Provides a sample submission template in the correct format. Use this file as a guide when formatting your predictions for the test set.

- **metaData.csv:** Contains supplemental information that can aid in understanding the context and characteristics of the main dataset.

- **test_lab.csv:** Contains labeled data for the test set, including the ground truth labels.


## Project Steps

1. **Exploration and Preprocessing:**
   - Explore the training set to understand the distribution of features and labels.
   - Perform data preprocessing steps such as handling missing values, encoding categorical variables, and scaling numeric features.

2. **Feature Engineering:**
   - Implement feature engineering techniques to enhance the predictive power of the model.
   - Consider creating new features or transforming existing ones based on domain knowledge.

3. **Model Training:**
   - Select a suitable classification model.
   - Train the model using the labeled training data.

4. **Model Evaluation:**
   - Evaluate the model's performance on the test set to ensure generalization to unseen data.
   - Consider metrics such as ROC AUC.

5. **Predictions and Submission:**
   - Make predictions on the test set using the trained model.
   - Format the predictions according to the sample_submission.csv file.
   - Submit the predictions for evaluation.

6. **Optional: Supplementary Analysis with metaData.csv:**
   - Explore additional information provided in metaData.csv for a deeper understanding of the dataset.
   - Consider how supplementary information can enhance the analysis.

## Dependencies

- Python 3.x
- Libraries: NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn (for visualization)

## Contact

For any inquiries or assistance, contact [Your Name] at [your.email@example.com].
