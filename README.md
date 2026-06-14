# Titanic Data Science Project: EDA & Predictive Modeling
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/isabel-2006/titanic-data-science-project/blob/main/TITANICDATASETANALYSIS%20(1).ipynb)

This repository contains an end-to-end Data Science workflow implemented in Python using Google Colab. The project follows a structured lifecycle to clean data, explore patterns, and build predictive models to determine passenger survival rates.

## 📋 Project Workflow (Based on Project Guidelines)
1. **Data Collection & Understanding:** Working with structural features, identifying attributes, and mapping categorical dimensions.
2. **Data Cleaning & Preprocessing:** Handling missing data via median/mode imputation and transforming variables (e.g., creating `FamilySize`, mapping `Sex_Code`).
3. **Exploratory Data Analysis (EDA):** Generating statistical summaries and building a multi-plot visualization grid to catch hidden trends.
4. **Predictive Modeling:** Training Classification algorithms to predict survival status.

---

## 📊 Visualizations & Insights
The project generates a visual dashboard analyzing:
- Overall baseline survival vs. deceased rates.
- Survival splits across Ticket Class Tiers (`Pclass`).
- Age distributions segmented by survival outcome.
- Exact categorical survival probabilities across gender metrics.

---

## 🤖 Models & Evaluation Results
We trained and evaluated two separate machine learning classifiers:

| Algorithm | Model Accuracy |
| :--- | :--- |
| **Logistic Regression** | ~81.01% |
| **Decision Tree Classifier** | ~80.45% |

---

## 🛠️ Tools & Libraries Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Environment:** Google Colab / Jupyter Notebooks
