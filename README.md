❤️ Heart Disease Prediction Using Machine Learning

SUMMARY:
💔 Heart disease is a leading cause of death worldwide, often diagnosed too late.
👩‍⚕️ Traditional methods (imaging, clinical evaluation) are costly & time-consuming.
🤖 Machine Learning (ML) can identify hidden patterns in patient data, enabling early detection & risk assessment.

Objective: Leverage ML to improve prediction accuracy → support healthcare professionals in making data-driven decisions.

📊 Data Description
📂 Dataset Overview

Source: Kaggle Heart Dataset (~1,000 records)

Features: Age, Sex, Blood Pressure, Cholesterol, Heart Rate, Chest Pain Type, ECG, Angina, etc.

Target: Presence of heart disease (1 = Disease, 0 = No Disease)

🔧 Preprocessing

✔️ Checked missing values
✔️ Converted categorical → numerical
✔️ Normalized features
✔️ Dataset ready for EDA + Modeling

🔎 Exploratory Data Analysis (EDA)
📉 Univariate Analysis

📊 Age → Most patients 55–65 years

🧪 Cholesterol → Right-skewed, some extreme highs

❤️ Max Heart Rate → Skewed left, many near max levels

🔗 Bivariate Analysis

Higher cholesterol → Higher heart disease occurrence

Weak correlations → Justifies advanced ML models

⚠️ Outlier Detection

Boxplots → No major outliers → Clean dataset

🤖 Modeling
📈 Logistic Regression

🔹 Baseline, interpretable

🔹 Accuracy: 84.38%

🌳 Decision Tree

🔹 Split data using Gini Index

🔹 Accuracy: 85.55%

🌲 Random Forest

🔹 Ensemble of trees → Bagging method

🔹 Accuracy: 94.53% 🎯 (Best performer)

📏 Performance Evaluation
🎯 Accuracy Metrics

Logistic Regression → 84.38%

Decision Tree → 85.55%

Random Forest → 94.53% 🏆

🧮 Confusion Matrices

Logistic Regression & Decision Tree → Moderate recall/precision

Random Forest → High recall & specificity (>90%) 💡 Minimal false positives/negatives

📊 ROC & AUC

Logistic Regression & Decision Tree → Good but not perfect

Random Forest → AUC = 0.988 🔥 (Near perfect classification)

✅ Conclusion

🚀 ML models show huge potential in healthcare predictions.
🌲 Random Forest clearly outshines other models, making it ideal for early diagnosis & risk assessment.
💡 Future adoption → Reduced misdiagnosis, optimized treatments, better patient outcomes.

📚 References

Shah, D., Patel, S., & Bharti, S. K. (2020). Heart disease prediction using machine learning techniques.

Jindal, H., Agrawal, S., Khera, R., Jain, R., & Nagrath, P. (2021). Heart disease prediction using ML algorithms.

Bhatt, C. M., Patel, P., Ghetia, T., & Mazzeo, P. L. (2023). Effective heart disease prediction using ML.

Sharma, V., Yadav, S., & Gupta, M. (2020). Heart disease prediction using ML techniques.














<img width="468" height="414" alt="image" src="https://github.com/user-attachments/assets/296f4bdc-05b8-4487-beef-29b113d39a39" />
