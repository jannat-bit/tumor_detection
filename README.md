🧪 Tumor Detection Project
📌 Overview
This project classifies breast tumors as Malignant (M) or Benign (B) using the Breast Cancer Wisconsin dataset.
The workflow covers data cleaning, exploratory data analysis (EDA), preprocessing, model training, evaluation, and comparison of multiple machine learning models.
⚙️ Steps Performed
Data Cleaning
Dropped irrelevant id column
Converted diagnosis labels (M → 1, B → 0)
Exploratory Data Analysis (EDA)
Count plot of diagnosis
Correlation heatmap of features
Preprocessing
Train-test split (80/20)
Feature scaling with StandardScaler
Model Training & Evaluation
Logistic Regression
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Random Forest
Each model evaluated using:
Accuracy Score
Classification Report
Confusion Matrix
Model Comparison
Accuracy of all models printed for easy comparison
📊 Results
All models performed well, with Random Forest achieving the highest accuracy on test data.
Feature scaling improved SVM and KNN performance.
🛠️ Technologies Used
Python (Pandas, NumPy, Scikit-learn)
Seaborn & Matplotlib (visualization)
Jupyter Notebook
