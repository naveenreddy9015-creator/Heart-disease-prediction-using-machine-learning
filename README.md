❤️ Heart Disease Prediction Using Machine Learning

❤️ Heart Disease Prediction using Machine Learning
📌 Project Overview

This is a machine learning project where I worked on predicting heart disease using patient health data. The dataset (from Kaggle) has a little over 1,000 records with details like age, cholesterol, blood pressure, chest pain type, and maximum heart rate.

The main idea was to test out different machine learning models and see which one performs the best at detecting whether a patient has heart disease or not.

⚙️ What I Did

Data Preprocessing – cleaned the dataset, handled missing values, and normalized the features.

Exploratory Data Analysis (EDA) – explored patterns in age, cholesterol, and heart rate, and checked how these relate to heart disease.

Modeling – trained three models: Logistic Regression, Decision Tree, and Random Forest.

Evaluation – compared them using accuracy, confusion matrices, ROC curves, and AUC scores.

📊 Results

Logistic Regression → Accuracy ~ 84.38%

Decision Tree → Accuracy ~ 85.55%, but prone to overfitting

Random Forest → Accuracy ~ 94.53%, AUC ~ 0.988 ✅

👉 Random Forest clearly performed the best, with higher accuracy and better recall/specificity. Logistic Regression was still helpful for understanding risk factors, while Decision Tree gave simple visual explanations but wasn’t as reliable.

🛠️ Tools & Libraries

Python

Pandas, NumPy

Matplotlib, Seaborn (for EDA & visuals)

Scikit-learn (for ML models)

📂 Project Structure
├── data/                # Dataset
├── notebooks/           # Jupyter notebooks
├── src/                 # Code for preprocessing & models
├── results/             # Plots and model outputs
├── README.md            # This file

🚀 How to Run

Clone this repo:

git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction


Install the required libraries:

pip install -r requirements.txt


Open and run the notebook:

jupyter notebook notebooks/Heart_Disease_Prediction.ipynb

✅ Conclusion

From this project, I learned that ensemble methods like Random Forest are the most effective for heart disease prediction because they reduce errors and capture patterns more accurately. Logistic Regression is still great for interpretability, and Decision Trees help with visualization, but Random Forest provided the most reliable results overall.

In the future, I’d like to:

Try deep learning models

Do more feature engineering

Test on larger, real-world datasets

📌 Dataset

Kaggle Heart Disease Dataset → Click Here














<img width="468" height="414" alt="image" src="https://github.com/user-attachments/assets/296f4bdc-05b8-4487-beef-29b113d39a39" />
