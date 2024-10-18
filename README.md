# Customer Conversion Prediction Using Decision Tree & Logistic Regression

## 👋 Introduction

This project focuses on predicting customer conversion using two machine learning models: **Decision Tree** and **Logistic Regression**. The dataset is based on customer demographics and marketing campaign interactions. The models help to predict whether a customer will respond positively to a given marketing campaign.

## 🚀 Project Overview

- **Project Title**: Customer Conversion Prediction
- **Technologies**: Python, Machine Learning (Decision Tree, Logistic Regression)
- **Tools**: Google Colab, Scikit-learn, Matplotlib, Seaborn
- **Data Source**: The dataset consists of customer details and their interaction with previous marketing campaigns.
  
The project includes:
- Data Preprocessing and Exploratory Data Analysis (EDA)
- Building and comparing the performance of Decision Tree and Logistic Regression models
- Prediction based on user input
- ## ⚙️ Installation & Setup

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/HARXHTIWARI/Customer-Conversion-Prediction.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd Customer-Conversion-Prediction
    ```

3. **Install the Required Libraries**:
    Run the following command to install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. **Dataset**:
    The dataset `bank-full.csv` is included in the `data/` folder. You can also use your own dataset, provided it follows a similar structure.

---

## 🛠️ Usage

1. **Run the Model Training**:
    - Train the models using the provided dataset:
    ```bash
    python code/model_training.py
    ```

2. **Make Predictions**:
    - Run the prediction script to input customer data and make predictions using both models:
    ```bash
    python code/prediction.py
    ```

3. **Results**:
    - The script will provide predictions with insights into whether the customer is likely to convert based on both models.

    **Example Output**:
    ```bash
    Decision Tree Prediction: Low chances of getting converted
    Logistic Regression Prediction: High chances of getting converted
    ```

---

## 🧠 Models Used

- **Decision Tree**: A tree-based model that works by splitting data into subsets based on the most informative features.
  
- **Logistic Regression**: A linear model that estimates the probability of a binary outcome, making it suitable for classification problems like customer conversion.

---

## 📊 Exploratory Data Analysis (EDA)

Before training the models, the dataset was thoroughly explored:
- **Age Distribution**: A visual breakdown of customer ages.
- **Job Type vs. Conversion**: A bar chart showing conversion rates across different job types.

---

## ✨ Future Enhancements

- Implement additional machine learning models such as **Random Forest** or **XGBoost** to improve accuracy.
- Deploy the model using a web framework like **Flask** for a more interactive user experience.
- Add more features to the dataset, such as social media engagement metrics, to improve predictive performance.

---

## 🤝 Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. We appreciate contributions that enhance the accuracy, add new features, or improve the code structure.


## 📂 Folder Structure

```bash
├── code/                   # Python code for model training and predictions
│   ├── model_training.py    # Training code for Decision Tree and Logistic Regression
├── data/                   # Dataset folder
│   └── bank-full.csv        # Dataset file
└── README.md                # Project documentation

