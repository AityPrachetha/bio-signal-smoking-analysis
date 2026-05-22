# Bio Signal Smoking Analysis

## Project Overview
This project predicts whether a person is a smoker or non-smoker using bio-signal health data and machine learning algorithms. The dataset contains biological and health-related attributes collected from individuals.

The objective of this project is to analyze the health data and build machine learning models that can accurately classify smoking status.

---

## Dataset Information
The dataset contains around 55,000 records with multiple health-related features such as:

- Age
- Gender
- Height
- Weight
- Waist circumference
- Blood Pressure
- Cholesterol
- Triglyceride
- HDL
- LDL
- Hemoglobin
- AST
- ALT
- GTP
- Dental Caries
- Tartar
- Smoking Status

Target Column:
- `smoking`
  - 0 → Non-Smoker
  - 1 → Smoker

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

1. Importing Libraries
2. Loading Dataset
3. Data Cleaning
4. Handling Missing Values
5. Data Visualization
6. One Hot Encoding
7. Feature Selection
8. Train-Test Split
9. Feature Scaling
10. Model Building
11. Model Evaluation

---

## Machine Learning Models Used

- Logistic Regression
- Decision Tree Classifier
- Bagging Classifier
- Extra Trees Classifier
- Random Forest Classifier

---

## Accuracy Results

| Model | Accuracy |
|---|---|
| Logistic Regression | 74.40% |
| Decision Tree | 79.25% |
| Bagging Classifier | 81.19% |
| Extra Trees Classifier | 83.02% |
| Random Forest Classifier | 83.10% |

---

## Best Model

Random Forest Classifier achieved the highest accuracy of **83.10%**.

---

## Conclusion

This project demonstrates that ensemble learning algorithms such as Random Forest and Extra Trees provide better performance for smoking prediction using bio-signal data when compared to traditional machine learning algorithms.

The project can be further improved using:
- Hyperparameter Tuning
- Deep Learning Models
- Cross Validation
- Feature Engineering

---

## Author

Aity Prachetha
