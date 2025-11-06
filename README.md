# 🛳️ Titanic Survival Analysis

> **Predicting passenger survival on the Titanic using Python, Pandas, and Scikit-Learn.**

---

## Objective
This project aims to predict whether a passenger survived the Titanic disaster using demographic and socio-economic features such as age, gender, class, and fare.

---

## Dataset
Data source: [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)

- `train.csv` – training data with survival labels  
- `test.csv` – testing data without survival labels  
- `gender_submission.csv` – sample submission file  

---

## Data Cleaning & Feature Engineering
- Handled missing values for `Age` and `Embarked`  
- Encoded categorical variables (`Sex`, `Embarked`)  
- Created new features:  
  - `FamilySize` = `SibSp` + `Parch` + 1  
  - `IsAlone` flag  
- Normalized continuous features

---

## Model Development
- **Baseline:** Logistic Regression  
- **Advanced Models:** Random Forest, XGBoost  
- Evaluated using cross-validation and accuracy metrics  

**Best model:** Random Forest with ~80% accuracy  

---

## 🧰 Tech Stack
`Python` • `Pandas` • `NumPy` • `Matplotlib` • `Seaborn` • `Scikit-Learn` • `Jupyter Notebook`

---

## Key Insights
- Gender and passenger class were the strongest predictors of survival.  
- Feature engineering improved model interpretability and performance.  
- Handling missing data was critical for achieving stable accuracy.

---

## Author
**Rosanne Sim**  
rosannesimtongenn@gmail.com  
[LinkedIn](https://linkedin.com/in/rosannesim) | [GitHub](https://github.com/rosannesim)

