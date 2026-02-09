# Stroke Prediction: Clinical Risk Analysis using Machine Learning

This project develops a predictive model to identify the probability of a stroke based on patient clinical history. Using a dataset with features like hypertension, heart disease, average glucose level, and BMI, the model aims to support early clinical decision-making.

## Technical Workflow

### 1. Data Engineering & Preprocessing
* **Missing Value Imputation:** Handled missing values in the 'bmi' column using mean imputation to maintain dataset integrity.
* **Feature Encoding:** Transformed categorical variables (gender, ever_married, work_type, etc.) into numerical format using **Label Encoding** for model compatibility.
* **Target Feature:** The model predicts the 'stroke' variable, identifying key risk patterns.

### 2. Predictive Modeling
* **Algorithm:** Implemented a **Random Forest Classifier**, chosen for its robustness and ability to handle non-linear relationships in medical data.
* **Data Splitting:** Utilized a standard Train-Test split (80/20) to validate model performance on unseen data.
* **Evaluation:** Focused on accuracy and classification metrics to ensure reliable risk assessment.

## Tech Stack
* **Language:** Python.
* **Libraries:** Pandas (Data Wrangling), Scikit-Learn (ML Framework), NumPy.
* **Environment:** Google Colab.

## Project Structure
* `Stroke_Prediction_Random_Forest.ipynb`: Complete notebook with data cleaning and model training.
* `dataset.csv`: Healthcare dataset containing 5110 observations with 12 clinical attributes.

## Key Findings
The model identifies **Age**, **Average Glucose Level**, and **BMI** as critical factors in predicting stroke risk, demonstrating the power of ensemble methods in healthcare analytics.

---
*Developed as a showcase of Machine Learning applications in Medical Engineering.*
