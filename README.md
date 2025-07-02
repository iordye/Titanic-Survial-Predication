# Titanic Survival Prediction: A Modeling-Focused Approach

## Project Overview

This project focuses on building a predictive model for survival on the Titanic, with a unique constraint: **the entire analysis was conducted without prior Exploratory Data Analysis (EDA)**. This deliberate choice was made to challenge and showcase the robustness of direct machine learning model application, emphasizing preprocessing and model performance in a scenario where initial data insights are intentionally omitted.

## Problem Statement

The goal is to predict whether a passenger survived the Titanic disaster based on available passenger information. This is a classic binary classification problem.

## Dataset

The project utilizes the well-known **Titanic dataset**, which contains information about passengers on the ill-fated RMS Titanic, including:
* `Survived`: (Target variable: 0 = No, 1 = Yes)
* `Pclass`: Passenger Class (1st, 2nd, 3rd)
* `Sex`: Gender
* `Age`: Age in years
* `SibSp`: Number of siblings/spouses aboard
* `Parch`: Number of parents/children aboard
* `Fare`: Passenger fare
* `Embarked`: Port of embarkation

## Methodology & Skills Demonstrated

Given the constraint of no EDA, the methodology focused purely on data preparation and model building:

1.  **Data Preprocessing:**
    * **Missing Value Handling:** Imputed missing `Age` values (e.g., using median or mean) and `Embarked` (e.g., using mode).
    * **Categorical Encoding:** Converted categorical features (`Sex`, `Embarked`, `Pclass`) into numerical representations suitable for machine learning models (e.g., One-Hot Encoding).
    * **Feature Selection:** Selected relevant features for the model without relying on insights from EDA.

2.  **Model Building:**
    * A classification algorithm (e.g., Logistic Regression, Random Forest, or a Gradient Boosting Classifier) was trained on the preprocessed data.
    * The model was evaluated using standard classification metrics.

3.  **Model Evaluation:**
    * Key metrics such as **Accuracy**, **Precision**, **Recall**, and **F1-Score** were used to assess the model's performance on unseen data.

## Key Findings / Results

* [**Insert your model's primary accuracy score here, e.g., "The model achieved an accuracy of approximately XX% on the test set."**]
* [**Optionally, add one more key metric, e.g., "with a precision of YY% for predicting survival."**]

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn:** For machine learning models and preprocessing utilities.
* **fancyimpute**

## How to Run the Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Download the dataset:**
    The Titanic dataset is commonly available on Kaggle. Place `train.csv` and `test.csv` (or just the combined dataset you used) in a `data/` directory within the project root.
4.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Open `titanic_survival_prediction_no_eda.ipynb` (or your notebook's name) and execute the cells.

## Contact

Feel free to connect with me for questions, feedback, or collaborations!

iordyebarnabas12@gmail.com
