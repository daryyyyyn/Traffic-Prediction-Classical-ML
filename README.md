# 🚦 Traffic Prediction using Classical Machine Learning

### 👋 Introduction
Welcome to my first Machine Learning project! In this repository, I explore various classical ML algorithms to solve a time-series regression problem: predicting traffic volume based on historical data.

### 🎯 Goal
The objective is to predict the hourly traffic volume at four different junctions using historical data features like hour, day, month, and year.

### 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

### 🧠 Models Implemented
I compared the performance of four different approaches:
1.  **Linear Regression** (Baseline)
2.  **Random Forest Regressor**
3.  **Gradient Boosting Regressor**
4.  **Stacking Regressor** (Ensemble of the above)

### 📊 Results
After training and evaluating the models, the **Stacking Ensemble** and **Random Forest** performed the best, achieving high accuracy.

| Model | RMSE (Lower is better) | R² Score (Higher is better) |
| :--- | :--- | :--- |
| Linear Regression | ~12.77 | 0.60 |
| Gradient Boosting | ~6.32 | 0.90 |
| **Random Forest** | **~3.55** | **0.97** |
| **Stacking** | **~3.54** | **0.97** |

### 📈 Key Takeaways
* **Time matters:** The "Hour" of the day was the most critical feature (morning/evening rush hours).
* **Non-linearity:** Traffic patterns are complex and non-linear, which is why the Random Forest and Stacking models significantly outperformed simple Linear Regression.
* **Ensembling:** Combining models (Stacking) provided the most stable and accurate predictions.

---
*This project marks the beginning of my journey into Data Science and AI.*
