# E-commerce Dataset Analysis

## Overview
This project involves a comprehensive analysis of an e-commerce dataset, focusing on user ratings, reviews, and product details. The analysis is divided into three parts, covering data cleaning and exploratory analysis, predictive modeling with linear regression, and classification modeling using logistic regression and KNN.

## Project Details
- **Part 1: Data Cleaning and Exploratory Analysis**
  - Cleaned the dataset by removing missing values and irrelevant reviews.
  - Conducted exploratory data analysis (EDA) to uncover insights into user behavior, product categories, and rating trends.
  - Visualized correlations between gender, categories, ratings, and helpfulness.

- **Part 2: Predictive Modeling**
  - Trained linear regression models to predict user ratings based on other features.
  - Explored the impact of feature selection and varying train-test splits on model performance.
  - Evaluated the models using standard metrics like mean squared error (MSE).

- **Part 3: Classification Modeling**
  - Converted ratings into binary labels: likes (1) and dislikes (0).
  - Trained and evaluated logistic regression and KNN models for classification.
  - Conducted hyperparameter tuning for KNN to optimize performance.
  - Compared the accuracy and performance of the two models.

## Tools & Technologies
- **Languages & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Machine Learning Models:** Linear Regression, Logistic Regression, KNN

## Repository Structure
- `Part1_Data_Cleaning_EDA.ipynb`: Notebook for data cleaning and exploratory analysis.
- `Part2_Predictive_Modeling.ipynb`: Notebook for training and evaluating linear regression models.
- `Part3_Classification_Modeling.ipynb`: Notebook for classification modeling using logistic regression and KNN.
- `README.md`: Documentation for the repository.
- `Datasets/`: Contains the cleaned datasets used for analysis.

## Key Features
- **Data Cleaning:** Handled missing values and outliers, and performed feature encoding for analysis and modeling.
- **Exploratory Analysis:** Identified patterns in user behavior and product performance through visualizations and statistics.
- **Predictive Modeling:** Built regression models to predict ratings and analyzed feature impact on model performance.
- **Classification Modeling:** Implemented logistic regression and KNN to predict user preferences and optimized KNN hyperparameters.

## Results
- Gained actionable insights into e-commerce user behavior and product performance.
- Demonstrated the effectiveness of logistic regression and KNN for binary classification tasks.
- Highlighted the trade-offs between different models and hyperparameter tuning.
