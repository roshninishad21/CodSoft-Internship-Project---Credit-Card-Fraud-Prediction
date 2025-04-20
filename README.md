💳 Credit Card Fraud Detection

This project is a part of my CodSoft Data Science Internship, where I built a machine learning model to detect fraudulent credit card transactions using Logistic Regression and Random Forest Classifier.

📌 Objective

To accurately identify fraudulent credit card transactions from an imbalanced dataset using classification techniques and evaluate their performance.

📁 Dataset

Source: Kaggle - Credit Card Fraud Detection

The dataset contains 284,807 transactions, among which only 492 are frauds.

Features include:

. 28 anonymized features (V1 to V28)

. Time and Amount

. Class (Target variable: 0 = Non-Fraud, 1 = Fraud)

⚙️ Workflow

. Data Exploration & Visualization

. Checked class imbalance

. Analyzed transaction patterns for fraud vs. non-fraud

. Data Preprocessing

. Feature scaling for Amount and Time

Optional: 

. SMOTE / Undersampling (to address class imbalance)

. Model Building

Logistic Regression: 

A linear baseline classifier

Random Forest Classifier: 

A robust ensemble classifier

Model Evaluation

Metrics used:

Precision, Recall, F1-Score

Confusion Matrix

ROC-AUC Score

Special focus on minimizing False Negatives (i.e., missed frauds)

🧪 Results

Model	ROC-AUC Score	Precision	Recall
Logistic Regression	~0.93	High	Medium
Random Forest	~0.97	High	High
Random Forest performed better in detecting fraud with higher recall and better balance between precision and recall.

🧰 Technologies & Libraries

. Python

. Pandas, NumPy – Data manipulation

. Matplotlib, Seaborn – Data visualization

. Scikit-learn – Machine Learning modeling & evaluation

. Imbalanced-learn (optional) – Handling imbalanced data using SMOTE or resampling

🧠 Key Learnings

. Working with highly imbalanced datasets

. Importance of choosing the right evaluation metrics (beyond accuracy)

. Performance difference between simple linear models and ensemble methods

. Practical application of machine learning to financial fraud detection

📌 Conclusion

This project demonstrates how machine learning can be effectively used to combat financial fraud by identifying suspicious transactions with high precision and recall. The combination of Logistic Regression and Random Forest provides both a baseline and an improved model for fraud detection tasks.
