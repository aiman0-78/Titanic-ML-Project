# Titanic Survival Prediction (ML Project)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24.2-orange)

## Project Overview
This project predicts whether a passenger survived the Titanic disaster using machine learning.  
It covers **data cleaning**, **feature encoding**, and **dataset preparation** for ML models.  
The project is developed in **Google Colab** for easy reproducibility.

---

## Dataset
- Source: Seaborn’s built-in Titanic dataset  
- Number of rows: 891  
- Number of columns: 15  
- Target variable: `survived` (0 = did not survive, 1 = survived)

---

## Steps Completed

1. **Data Loading**
   - Loaded Titanic dataset using Seaborn.  

2. **Data Cleaning**
   - Filled missing `age` with median.  
   - Filled missing `embarked` with mode.  
   - Dropped `deck` column (too many missing values).  
   - Dropped rows with missing `embark_town`.  

3. **Encoding**
   - `sex` encoded using **LabelEncoder**.  
   - `embarked` encoded using **OneHotEncoder**.  

4. **Final Cleaned Dataset**
   - Dataset ready for ML training.  

---

## Tech Stack
- Python  
- Google Colab  
- Pandas, Numpy  
- Seaborn, Matplotlib  
- Scikit-learn  

---

## Model Training & Evaluation
- **Model:** Logistic Regression  
- **Accuracy:** ~78%  
- **Confusion Matrix:**

| Actual \ Predicted | 0 | 1 |
|-------------------|---|---|
| 0                 | 85 | 24 |
| 1                 | 15 | 54 |

- **Most Predictive Features:** `sex`, `pclass`, `sibsp`, `fare`, `embarked`

---

## Visualizations
- Confusion Matrix Heatmap  
- Feature Importance Bar Chart  

*Check the Colab notebook for detailed visualizations and step-by-step code.*

---

## How to Run
Click below to open the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aiman0-78/Titanic-ML-Project/blob/main/titanic_project.ipynb)

---

## Next Steps
- Train additional ML models (Decision Trees, Random Forest).  
- Compare accuracy & performance across models.  
- Deploy the best model as a web app (e.g., using Streamlit or Flask).  

---

## Contribution
- Feel free to fork this repository, modify, and submit PRs.
