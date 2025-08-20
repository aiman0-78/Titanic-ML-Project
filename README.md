# Titanic Survival Prediction (ML Project)

## Project Overview
This project predicts whether a passenger survived the Titanic disaster using machine learning.  
It covers **data cleaning**, **feature encoding**, and **dataset preparation** for ML models.  
The project was developed in **Google Colab** for easy reproducibility.

---

## Steps Completed
1. **Data Loading**
   - Loaded Titanic dataset using Seaborn.  
2. **Data Cleaning**
   - Filled missing `age` with median.  
   - Filled missing `embarked` with mode.  
   - Dropped `deck` (too many missing values).  
   - Dropped rows with missing `embark_town`.  
3. **Encoding**
   - `sex` encoded using **LabelEncoder**.  
   - `embarked` encoded using **OneHotEncoding**.  
4. **Final Cleaned Dataset**
   - Dataset ready for ML training.  

---

## Tech Stack
- Python  
- Google Colab  
- Pandas, Numpy  
- Seaborn, Matplotlib  
- Scikit-learn


## How to Run
Click below to open the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/titanic_project.ipynb)


## Next Steps
- Train ML models (Logistic Regression, Decision Trees, Random Forest).  
- Compare accuracy & performance.  
- Deploy the best model as a web app.  
