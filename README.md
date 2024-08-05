# Churn Rate Data Analysis & ML Development

This Jupyter Notebook contains data analysis and machine learning implementation on customer details from a bank to accurately predict churn rate or customer retention.

- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing & Feature Engineering](#data-preprocessing-&-feature-engineering)
- [Model Selection](#model-selection)
- [Model Evaluation](#model-evaluation)
- [Predictive Analysis](#predictive-analysis)

## Exploratory Data Analysis

In this section, we explore the dataset to gain a deeper understanding of the data and uncover any potential issues or insights:

- **Columns with Null Values:** Inspected columns containing null values to decide on appropriate handling methods.
- **Dispersion and Central Tendency:** Analyzed statistics such as mean, median, and standard deviation for numerical columns.
- **Correlation Matrix:** Used a correlation matrix to analyze relationships between numerical columns.
- **Data Visualization:** Utilized histograms, bar charts, and heat map to visually represent data relationships.

## Data Preprocessing & Feature Engineering

In the data preprocessing & feature engineering phase, we cleaned and prepared the data for analysis:

- **Label Encoding:** Applied label encoding to convert categorical columns into numerical format.
- **Removal of Irrelevant Columns:** Removed columns deemed irrelevant to the analysis to enhance data clarity.
- **Handling Null Values:** Filled numerical columns with null values using their corresponding medians to maintain data integrity.
- **Handling Dataset Imbalance:** Synthetically increased minority classes for a more balanced dataset.
- **Removing Outliers:** Removed outliers in the dataset for more accurate model predictions.

## Model Selection

Selected and trained multiple machine learning models on the training data:

- **Stochastic Gradient Descent Classifier** 
- **Logistic Regression** 
- **Random Forest Classifier** 
- **Support Vector Machine**
- **K-Neighbours Classifier**
- **Gradient Boosting Classifier**
- **Decision Tree Classifier**
- **Multilayer Perceptron**

## Model Evaluation

In this section, we evaluated each model's performance against metrics such as:

- **Accuracy**
- **Recall**
- **Precision**
- **F1 Score**

In this section we also performed **Grid Search** on the models that performed poorly to determine what hyperparameters were the best to choose for each model.

## Predictive Analysis

The trained models made predictions on unseen data and performance metrics were inspected.

