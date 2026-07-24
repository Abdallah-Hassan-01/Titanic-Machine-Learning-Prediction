# 🚢 Titanic - Machine Learning Survival Prediction

An end-to-end Data Science project built to predict passenger survival on the Titanic using classification algorithms, feature engineering, and hyperparameter tuning.

---

## 📌 Project Overview
This project applies machine learning techniques to the historical Titanic dataset. The primary objective is to clean the data, extract meaningful patterns through Exploratory Data Analysis (EDA), handle categorical variables, and train a predictive model using **Random Forest Classifier** optimized via **GridSearchCV**.

### 🎯 Key Performance Highlights
- **Final Model:** Random Forest Classifier
- **Optimization Strategy:** GridSearchCV Hyperparameter Tuning
- **Final Model Accuracy:** ~82.6%

---

## 🛠️ Data Science & ML Pipeline

1. **Exploratory Data Analysis (EDA):**
   - Investigated feature distributions and missing data patterns across columns (`Age`, `Cabin`, `Embarked`).
   - Analyzed correlations between passenger demographics (e.g., `Pclass`, `Sex`, `Fare`) and survival rates.

2. **Data Preprocessing & Feature Engineering:**
   - Handled missing values (`Age` imputed with median, missing categorical entries addressed).
   - Encoded categorical features into numerical variables for model compatibility.
   - Dropped non-predictive features (e.g., `PassengerId`, `Name`, `Ticket`, `Cabin`) to avoid noise and overfitting.

3. **Model Selection & Tuning:**
   - Evaluated multiple strategies and finalized **Random Forest Classifier** for strong non-linear performance and robustness against overfitting.
   - Performed systematic parameter search with **GridSearchCV** to fine-tune `n_estimators`, `max_depth`, and splitting metrics.

---

## 📽️ Execution & Demo


https://github.com/user-attachments/assets/837bfca4-9078-4a18-8c0f-a2f8cbc5a3dd



---

## 🧰 Tools & Technologies
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Environment:** Visual Studio Code / Jupyter Notebooks

---

## 📬 Contact & Connect
Developed with passion for Data Science and Machine Learning. Feel free to reach out or contribute!
