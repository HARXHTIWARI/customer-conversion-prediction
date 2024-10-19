# Results

This folder contains the results of the Customer Conversion Prediction project. The results showcase the performance of both Decision Tree and Logistic Regression models and their ability to predict customer conversion based on various input features.

## Contents

- **Model Evaluation Metrics**
  - Summaries of key metrics for both models, including accuracy, precision, recall, F1 score, and ROC-AUC scores.

- **Visualizations**
  - Charts and graphs illustrating the insights derived from the dataset and the performance of both models.

- **Test Cases**
  - Examples of various customer profiles used for testing, along with the predictions from both models.

---

### Key Model Performance Metrics

| Metric          | Decision Tree | Logistic Regression |
|------------------|---------------|---------------------|
| Accuracy         | 0.85          | 0.82                |
| Precision        | 0.78          | 0.80                |
| Recall           | 0.76          | 0.74                |
| F1 Score         | 0.77          | 0.77                |
| ROC-AUC Score    | 0.84          | 0.81                |

---

### Visualizations

- **Decision Tree**: Visualization showing the number of correct and incorrect predictions for the Decision Tree model.

  ![Decision Tree](https://github.com/HARXHTIWARI/customer-conversion-prediction/blob/main/Results./Decision%20Tree.png)

- **Logistic Regression**: Visualization showing the number of correct and incorrect predictions for the Logistic Regression model.

  ![Logistic Regression](https://github.com/HARXHTIWARI/customer-conversion-prediction/blob/main/Results./Logistic%20Regression.png)

- **Job Distribution**: Job type distribution across the dataset.
  
  ![Job Distribution](https://github.com/HARXHTIWARI/customer-conversion-prediction/blob/main/Dataset/images/Count%20of%20Jobs.png)

- **Job Type vs Conversion**: A comparison of job type against conversion rates.
  
  ![Job Type vs Conversion](https://github.com/HARXHTIWARI/customer-conversion-prediction/blob/main/Dataset/images/Job%20Type%20vs.%20Conversion.png)

---

### Test Cases

Below are some sample test cases with their input data and expected output from both models:

#### Test Case 1: A Young Single Professional
*   **Input Data:**
    *   Age: 25
    *   Job: "student"
    *   Marital Status: "single"
    *   Education Level: "tertiary"
    *   Default: "no"
    *   Balance: 500
    *   Housing: "no"
    *   Loan: "no"
    *   Contact: "cellular"
    *   Day: 5
    *   Month: "may"
    *   Duration: 180
    *   Campaign: 1
    *   Pdays: -1
    *   Previous: 0
    *   Poutcome: "unknown"
*   **Expected Output:**
    *   Decision Tree Prediction: `No`
    *   Logistic Regression Prediction: `No`

#### Test Case 2: An Older Married Customer
*   **Input Data:**
    *   Age: 55
    *   Job: "management"
    *   Marital Status: "married"
    *   Education Level: "secondary"
    *   Default: "no"
    *   Balance: 1000
    *   Housing: "yes"
    *   Loan: "yes"
    *   Contact: "telephone"
    *   Day: 15
    *   Month: "jun"
    *   Duration: 120
    *   Campaign: 3
    *   Pdays: 5
    *   Previous: 2
    *   Poutcome: "success"
*   **Expected Output:**
    *   Decision Tree Prediction: `Yes`
    *   Logistic Regression Prediction: `Yes`

#### Test Case 3: A Middle-Aged Divorced Customer with Loans
*   **Input Data:**
    *   Age: 45
    *   Job: "blue-collar"
    *   Marital Status: "divorced"
    *   Education Level: "secondary"
    *   Default: "yes"
    *   Balance: 1500
    *   Housing: "yes"
    *   Loan: "yes"
    *   Contact: "cellular"
    *   Day: 25
    *   Month: "apr"
    *   Duration: 300
    *   Campaign: 2
    *   Pdays: 0
    *   Previous: 1
    *   Poutcome: "failure"
*   **Expected Output:**
    *   Decision Tree Prediction: `Yes`
    *   Logistic Regression Prediction: `No`

#### Test Case 4: A Wealthy Retired Individual
*   **Input Data:**
    *   Age: 65
    *   Job: "retired"
    *   Marital Status: "married"
    *   Education Level: "tertiary"
    *   Default: "no"
    *   Balance: 5000
    *   Housing: "yes"
    *   Loan: "no"
    *   Contact: "telephone"
    *   Day: 20
    *   Month: "jan"
    *   Duration: 200
    *   Campaign: 1
    *   Pdays: -1
    *   Previous: 0
    *   Poutcome: "unknown"
*   **Expected Output:**
    *   Decision Tree Prediction: `No`
    *   Logistic Regression Prediction: `Yes`

#### Test Case 5: A Young Customer with High Balance and Loans
*   **Input Data:**
    *   Age: 30
    *   Job: "technician"
    *   Marital Status: "single"
    *   Education Level: "tertiary"
    *   Default: "no"
    *   Balance: 3000
    *   Housing: "no"
    *   Loan: "yes"
    *   Contact: "cellular"
    *   Day: 10
    *   Month: "aug"
    *   Duration: 150
    *   Campaign: 1
    *   Pdays: -1
    *   Previous: 0
    *   Poutcome: "unknown"
*   **Expected Output:**
    *   Decision Tree Prediction: `Yes`
    *   Logistic Regression Prediction: `Yes`

---

Feel free to explore the results in this folder, including the test case scenarios and visualizations, to better understand how the models are performing and how predictions are made. For further details on the code, please refer to the `project_code` folder.

