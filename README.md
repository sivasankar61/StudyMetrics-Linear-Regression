# StudyMetrics-Linear-Regression
An end-to-end Python data science workflow that analyzes student demographics and habits to predict final exam scores based on daily study hours. Built inside a Jupyter Notebook using Scikit-Learn, Pandas, and Matplotlib

# 📚 StudyMetrics — Student Performance Predictor (Linear Regression)

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

**StudyMetrics** is a Machine Learning project that predicts a student's **Final Exam Score** based on their **daily study hours** using a **Simple Linear Regression** model.

The goal is to understand the relationship between study time and academic performance, and to build a model that can predict scores for new unseen inputs.

---

## 🎯 Objectives

- Explore and visualize the relationship between study hours and exam scores
- Build and train a Linear Regression model using Scikit-Learn
- Evaluate the model's performance using standard regression metrics
- Predict final scores for new study hour inputs

---

## 📂 Project Structure

```
StudyMetrics-Linear-Regression/
│
├── project.ipynb          # Main Jupyter Notebook (EDA + Model + Prediction)
├── README.md              # Project documentation
```

---

## 📊 Dataset

The dataset used in this project is a **custom-generated realistic student dataset** containing:

| Feature | Description |
|---|---|
| `study_hours` | Number of hours a student studies per day |
| `final_score` | Final exam score obtained (out of 100) |

- **Records:** 50 students
- **Type:** Supervised Learning — Regression
- **Source:** Custom generated (realistic simulation)

---

## 🔧 Technologies Used

| Tool | Purpose |
|---|---|
| Python 3.x | Core programming language |
| Pandas | Data loading and manipulation |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Data visualization |
| Scikit-Learn | Model building and evaluation |
| Jupyter Notebook | Development environment |

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/sivasankar61/StudyMetrics-Linear-Regression.git
cd StudyMetrics-Linear-Regression
```

**2. Install required libraries**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**3. Launch Jupyter Notebook**
```bash
jupyter notebook project.ipynb
```

**4. Run all cells** — the notebook will train the model and display predictions.

---

## 🧠 ML Workflow

```
Data Generation
      ↓
Exploratory Data Analysis (EDA)
      ↓
Feature Selection (Study Hours → Final Score)
      ↓
Train-Test Split (80/20)
      ↓
Linear Regression Model (Scikit-Learn)
      ↓
Model Evaluation (R², MAE, MSE)
      ↓
Prediction on New Input
```

---

## 📈 Model Performance

| Metric | Value |
|---|---|
| Algorithm | Simple Linear Regression |
| R² Score | ~0.90+ |
| Mean Absolute Error | Low |
| Train/Test Split | 80% / 20% |

> *Exact values are generated dynamically in the notebook.*

---

## 🔮 Sample Prediction

```python
new_hours = 9
predicted_score = model.predict([[new_hours]])
print("Predicted final score for new hour is", predicted_score)
```

**Output:** A student studying **9 hours/day** is predicted to score approximately **~90+** marks.

---

## 📉 Visualizations Included

- 📌 Scatter plot — Study Hours vs Final Score
- 📌 Regression line over actual data points
- 📌 Residual plot — checking model errors
- 📌 Prediction output for custom input

---

## 💡 Key Insights

- A strong **positive linear correlation** exists between study hours and final scores
- Students studying **5+ hours/day** consistently scored above **75 marks**
- Students studying **less than 2 hours/day** were at higher risk of scoring below **50**
- The Linear Regression model captures this trend with high accuracy

---

## 🙋 Author

**Shiva Sankar**
MBA — Finance & Business Analytics

[![GitHub](https://img.shields.io/badge/GitHub-sivasankar61-black?logo=github)](https://github.com/sivasankar61)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
