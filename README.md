# Forage-BCG-Data-Science-Job-Simulation

This project focuses on predicting customer churn for PowerCo, a client of BCG X, by utilizing a Random Forest classification model.

## Objectives

- **Analyze Price Sensitivity**: Investigate if price sensitivity is the most significant factor in customer churn and assess its impact.
- **Feature Engineering**: Develop new features from existing data to enhance churn prediction, such as the difference in off-peak prices between December and January.
- **Predictive Modeling**: Use a Random Forest classifier to predict customer churn, leveraging both engineered features and existing data.

## Concepts

### Data Science at BCG X
A Data Scientist at BCG X delivers business value by predicting outcomes based on data, combining:
- **Statistics and Mathematics**: For in-depth data analysis.
- **Programming**: To build and test predictive models.
- **Communication**: To effectively convey insights to clients and stakeholders.

### Price Sensitivity
Price sensitivity measures how customer demand for energy consumption varies with price changes. This project explores how price sensitivity affects customer churn.

### Price Elasticity of Demand
Price elasticity quantifies how consumption changes when prices fluctuate. Understanding elasticity is crucial for modeling customer behavior based on price variations.

### Feature Engineering
Feature engineering enhances machine learning models by creating or modifying features. Examples:
- Calculating off-peak price differences between December and January for each customer.
- Adding, transforming, or removing variables to improve churn prediction.

### Classification Model
As churn is a binary outcome (True/False), this project employs a classification model to predict whether a customer will churn. The Random Forest classifier was selected for its ability to handle large datasets and its resilience to overfitting.

### Random Forest Classifier
Random Forest is an ensemble learning technique that uses multiple decision trees to make predictions. It aggregates results from various trees (via majority voting) to predict outcomes like churn.

## Project Workflow

1. **Data Analysis and Price Sensitivity Investigation**
   - **Goal**: Assess if price sensitivity is a major driver of churn.
   - **Steps**:
     - Conduct exploratory data analysis to understand relationships between features and churn.
     - Measure the impact of price sensitivity using metrics like price elasticity.

2. **Feature Engineering**
   - **Goal**: Create new features based on off-peak price differences to enhance churn prediction.
   - **Steps**:
     - Extract relevant price data.
     - Calculate and add new feature columns for each customer based on price differences.
     - Ensure data completeness and accuracy after transformation.

3. **Churn Prediction with Random Forest**
   - **Goal**: Build and evaluate a Random Forest classifier for churn prediction.
   - **Steps**:
     - Train the model on historical data with churn labels.
     - Evaluate performance using metrics like accuracy, precision, and recall.
     - Tune hyperparameters to optimize model accuracy and reduce overfitting.

## Tools and Technologies Used
- **Python**: For data analysis, feature engineering, and machine learning.
- **Pandas**: For data manipulation and transformation.
- **Scikit-learn**: For machine learning algorithms, including Random Forest classifiers.
- **Matplotlib/Seaborn**: For data visualization during exploratory analysis.

## Deliverables
- **Exploratory Data Analysis**: Insights gained from analyzing PowerCo’s data, focusing on price sensitivity and churn.
- **Engineered Features**: New columns representing calculated off-peak price differences between December and January.
- **Random Forest Model**: A trained classification model to predict customer churn, along with performance evaluation metrics.
