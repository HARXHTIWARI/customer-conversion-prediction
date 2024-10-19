# Dataset README

## Overview
This folder contains the dataset used for the **Customer Conversion Prediction** project. The primary dataset is **`bank-full.csv`**, which includes information about customers and their responses to marketing campaigns.

## Dataset Description

### `bank-full.csv`
- **Source**: This dataset is sourced from the UCI Machine Learning Repository.
- **Content**: The dataset includes demographic information and marketing campaign interactions for bank customers. It is used to predict whether a customer will convert (i.e., respond positively to a marketing campaign).

### Features
| Column Name       | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `age`             | Age of the customer                                         |
| `job`             | Type of job (e.g., admin, technician, entrepreneur, etc.)  |
| `marital`         | Marital status (e.g., single, married, divorced)           |
| `education`       | Education level (e.g., primary, secondary, tertiary)       |
| `default`         | Whether the customer has credit in default (yes/no)        |
| `balance`         | Account balance in euros                                    |
| `housing`         | Whether the customer has a housing loan (yes/no)           |
| `loan`            | Whether the customer has a personal loan (yes/no)          |
| `contact`         | Type of communication (e.g., cellular, telephone)         |
| `day`             | Last contact day of the month (1-31)                       |
| `month`           | Last contact month of the year (e.g., 'jan', 'feb', ...)   |
| `duration`        | Duration of the last contact in seconds                     |
| `campaign`        | Number of contacts performed during this campaign           |
| `pdays`           | Number of days since the client was last contacted          |
| `previous`        | Number of contacts performed before this campaign           |
| `poutcome`        | Outcome of the previous marketing campaign (e.g., success, failure, other) |
| `y`               | Target variable (yes/no) indicating whether the customer converted |

## Data Structure
- **Format**: CSV (Comma-Separated Values)
- **Rows**: 41,188 entries
- **Columns**: 17 features including the target variable

## Usage
This dataset is utilized in the **Customer Conversion Prediction** project to build machine learning models (Decision Tree and Logistic Regression) that predict customer responses based on the features provided. 

### Notes
- Ensure proper data preprocessing steps are followed before using this dataset for model training or evaluation.
- Be mindful of any missing values or inconsistencies in the data.
- ## Data Visualizations

Here are some visualizations from the analysis:

1. **Count of Jobs**:
   
   ![Count of Jobs](images/download%20(1).png)

2. **Job Type vs. Conversion**:

   ![Job Type vs. Conversion](images/download%20(2).png)


## License
This dataset is available for use under the terms of the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing).


