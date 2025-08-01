# Breast-cancer_detection_using_logistic_regression

🧪 Breast Cancer Detection with Logistic Regression

📌 Project Overview

This project uses a logistic regression model to predict whether a tumor is benign (0) or malignant (1) using the Breast Cancer Wisconsin dataset. The model aims to assist in early breast cancer detection based on relevant tumor features.

📊 Dataset

Source: Breast Cancer Wisconsin Diagnostic Data

Rows: 569

Features: 30 numerical tumor characteristics + 1 label (diagnosis)

Target: diagnosis (Malignant = 1, Benign = 0)

🧹 Data Preprocessing

Dropped irrelevant column: id

Encoded diagnosis from M/B to 1/0

Checked for null values – none found

Selected 4 most correlated features:

concave points_mean

radius_worst

perimeter_worst

concave points_worst

⚙️ Modeling Approach

Model Used: Logistic Regression (Scikit-learn)

Scaling: StandardScaler

Balancing: SMOTE to address class imbalance

Train/Test Split: 80/20

✅ Model Performance

Accuracy: 97.3%

Precision (Malignant): 95%

Recall (Malignant): 98%

Confusion Matrix:

[[69 2]]
[[1 42]]

📌 Key Takeaways

Logistic Regression performed well with few features

SMOTE helped balance the minority class (Malignant)

Model shows potential for clinical decision support in breast cancer diagnosis

📂 Future Improvements

Test with other algorithms (SVM, Random Forest, XGBoost)

Try hyperparameter tuning (e.g. regularization strength C)

Deploy using Flask or Streamlit for web interface

Add cross-validation for more robust evaluation

👩🏾‍💻 Author

Kabi Veronicah

3rd Year Data Science Student
Cooperative University of Kenya

