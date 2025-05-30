🧠 Breast Cancer Classification — Logistic Regression
This project is part of an AI & ML Internship focused on implementing binary classification using logistic regression with the Breast Cancer dataset.

📄 Objective
To build and evaluate a logistic regression model that classifies tumors as malignant or benign based on various medical features.

📋 Steps:
1. Loaded the dataset using Pandas
2. Dropped unnecessary columns (id, Unnamed: 32)
3. Converted diagnosis to binary labels (M = 1, B = 0)
4. Split data into training and testing sets
5. Standardized features using StandardScaler
6. Trained a Logistic Regression model
7. Evaluated performance using:
      Confusion Matrix
      Precision, Recall, F1-score
      ROC Curve and AUC Score
8. Explored effect of threshold tuning
9. Explained the sigmoid function used in logistic regression

🛠 Tools Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn

✅ Files
data.csv – Breast Cancer dataset
Task_04.ipynb – Python notebook with code and analysis
README.md – Project summary
