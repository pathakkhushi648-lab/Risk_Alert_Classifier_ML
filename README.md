# Risk_Alert_Classifier_ML

# Financial Risk Classification using Machine Learning

## Project Overview

This project focuses on developing a Machine Learning model to classify customers into Low Risk and High Risk categories based on their financial and credit-related information. The objective is to help financial institutions assess customer risk accurately and support better lending decisions.

The project follows a complete Machine Learning workflow, including data preprocessing, missing value handling, exploratory data analysis (EDA), feature scaling, handling class imbalance, model building, model evaluation, feature importance analysis, and model saving.

---

## Project Objectives

- Build a Machine Learning model for financial risk classification.
- Perform data cleaning and preprocessing.
- Handle missing values using the KNN Imputer.
- Perform Exploratory Data Analysis (EDA).
- Handle class imbalance using SMOTE.
- Train multiple Machine Learning models.
- Compare model performance.
- Identify the most important features.
- Save the final trained model for future use.

---

## Dataset

The dataset contains customer financial and credit-related information used to predict financial risk.

Example features include:

- Age
- Annual Income
- Credit Score
- Employment Status
- Loan Amount
- Debt Balance
- Monthly Spending
- Credit Utilization Ratio
- Savings Balance
- Payment History
- Existing Loans
- Risk Status (Target Variable)

---

## Project Workflow

### 1. Import Libraries

Imported all required Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn, and Joblib.

### 2. Load Dataset

- Loaded the dataset.
- Displayed the first few records.
- Checked dataset information.
- Verified data types.

### 3. Data Preprocessing

- Checked missing values.
- Checked duplicate records.
- Removed unnecessary columns (if required).
- Prepared the dataset for analysis.

### 4. Missing Value Handling

Missing values were handled using the KNN Imputer to estimate missing values based on neighboring observations.

### 5. Exploratory Data Analysis

Performed various visualizations to understand the dataset, including:

- Histograms
- Box Plots
- Count Plots
- Pie Charts
- Correlation Heatmap
- Distribution Plots

### 6. Feature Scaling

StandardScaler was applied to standardize numerical features before model training.

### 7. Train-Test Split

The dataset was divided into training and testing datasets.

### 8. Handle Class Imbalance

Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the training dataset.

### 9. Model Building

The following Machine Learning models were developed:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 10. Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

### 11. Feature Importance

Feature importance analysis was performed using the Random Forest model to identify the most influential features affecting financial risk prediction.

### 12. Model Saving

The final Random Forest model was saved using the Joblib library.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Joblib

---

## Python Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn


---

## Machine Learning Algorithms

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## Project Structure

```
Financial Risk Dataset → Data Collection → Data Understanding → Data Preprocessing → Missing Value Analysis → KNN Imputer → Exploratory Data Analysis → Feature Selection → StandardScaler → Train-Test Split → SMOTE → Logistic Regression → Model Evaluation → Error Analysis → Decision Tree → Random Forest → Model Comparison → Feature Importance → Hyperparameter Tuning → Best Model Selection → Save Model .
```

---
## Results

- Successfully cleaned and preprocessed the dataset.
- Handled missing values using the KNN Imputer.
- Balanced the dataset using SMOTE.
- Built and evaluated multiple Machine Learning models.
- Compared model performance using standard evaluation metrics.
- Identified the most important features affecting customer risk.
- Saved the best-performing Random Forest model for future prediction.

---

## Future Scope

- Perform Hyperparameter Tuning.
- Build an XGBoost model.
- Deploy the model using Streamlit.
- Develop a web application for real-time prediction.
- Deploy the project on a cloud platform.

---

## Conclusion

This project successfully developed a Machine Learning-based Financial Risk Classification System capable of predicting whether a customer belongs to the Low Risk or High Risk category. The project followed a systematic workflow that included data preprocessing, missing value treatment using the KNN Imputer, exploratory data analysis, feature scaling, handling class imbalance with SMOTE, and building multiple classification models. Logistic Regression, Decision Tree, and Random Forest models were trained and evaluated using Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and Classification Report.

Among the evaluated models, the Random Forest Classifier achieved the best overall performance and was selected as the final model. Feature importance analysis provided valuable insights into the factors influencing financial risk prediction. The trained model was successfully saved using Joblib, making it suitable for future prediction and deployment. This project demonstrates the practical application of Machine Learning techniques in supporting financial institutions with accurate credit risk assessment and informed decision-making.

---

## Author

Name: Swarna Ajay Pathak
