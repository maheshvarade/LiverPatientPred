# LiverPatientPred
Project Overview
This project aims to build a predictive model to classify individuals as liver patients or not based on blood test results and demographic data. The insights can help in early diagnosis and better healthcare planning.

📊 Dataset
Source: UCI Machine Learning Repository

Features:

Age

Gender

Total Bilirubin

Direct Bilirubin

Alkaline Phosphotase

Alamine Aminotransferase

Aspartate Aminotransferase

Total Proteins

Albumin

Albumin and Globulin Ratio

Target: Liver Patient (1) or Not (0)

📌 Correlation Insights
From the heatmap:

Total and Direct Bilirubin are highly correlated (0.87).

Liver enzyme levels (ALT, AST) show positive correlations.

Albumin and Globulin Ratio, Total Proteins, and Albumin are weakly but positively correlated with the target.

⚙️ Workflow
Data Cleaning & EDA
Handle missing values, explore distributions, check correlations.

Feature Selection
Drop redundant features and highly correlated ones (e.g., keep one of Total/Direct Bilirubin).

Modeling

Models used: Logistic Regression, Random Forest, XGBoost

Evaluation metrics: Accuracy, Precision, Recall, ROC-AUC

Visualization

Correlation heatmap

ROC curves

Confusion matrices

Deployment

(Optional) Flask or Streamlit-based web app for real-time prediction.

🧪 Example Model Results
Model	Accuracy	ROC-AUC
Logistic Regression	76.5%	0.81
Random Forest	79.2%	0.85
XGBoost	82.3%	0.88

🛠️ Tech Stack
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook

Optional: Flask / Streamlit for deployment
