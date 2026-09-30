# Kickstarter Success Prediction

## 1. Project Overview

This project focuses on predicting the success of Kickstarter crowdfunding campaigns using machine learning and natural language processing techniques. The system analyzes campaign-related information and predicts whether a Kickstarter project is likely to be successful.

## 2. Problem Statement

Kickstarter campaigns receive funding based on several factors such as campaign characteristics, project description, category, and other available campaign information. Predicting campaign success in advance can help project creators understand the factors associated with successful campaigns and make better decisions while planning their campaigns.

The objective of this project is to develop a machine learning-based system that uses historical Kickstarter campaign data to predict campaign success.

## 3. Dataset

The project uses a Kickstarter campaign dataset containing information about crowdfunding projects.

The dataset is preprocessed before model training. Relevant features are selected, categorical and numerical information is handled appropriately, and textual information is transformed into numerical features for machine learning.

## 4. Methodology

The overall workflow of the project is:

1. Data loading
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Feature engineering
5. Text feature extraction using TF-IDF
6. Topic extraction using Latent Dirichlet Allocation (LDA)
7. Train-test splitting
8. Machine learning model training
9. Model evaluation
10. Hyperparameter tuning
11. Kickstarter campaign success prediction

A stratified train-test split is used to maintain the distribution of the target classes in the training and testing sets.

## 5. Machine Learning Approach

The project explores multiple machine learning approaches for Kickstarter success prediction.

Textual campaign information is converted into numerical representations using TF-IDF. LDA is also used to extract topic-based information from textual features.

The machine learning models are trained using the processed campaign features. Model performance is evaluated using appropriate classification metrics.

Gradient Boosting is further tuned using GridSearchCV with 5-fold cross-validation to identify suitable hyperparameters.

## 6. Implementation

The complete implementation is provided in the Jupyter Notebook:

`Kickstarter_Success_Prediction.ipynb`

The notebook contains data preprocessing, exploratory analysis, feature extraction, model training, evaluation, and prediction steps.

## 7. How to Run the Project

### Install the required libraries

```bash
pip install -r requirements.txt
