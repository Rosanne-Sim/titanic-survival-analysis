# 🛳️ Titanic Survival Prediction

A simple machine learning project based on the Kaggle competition “Titanic: Machine Learning from Disaster.”  

This notebook predicts passenger survival using Python, Pandas, and a Random Forest Classifier.

---

## Project Overview
The goal is to build a predictive model that determines whether a passenger survived the Titanic disaster, based on features such as class, gender, and number of siblings/spouses on board.

---

## Dataset
Source: [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)

Files used:
- `train.csv` – training dataset with survival labels  
- `test.csv` – testing dataset (no labels)  
- `gender_submission.csv` – sample submission file  

---

## Key Steps
1. **Import Libraries & Load Data**  
   Read train and test datasets with Pandas.  

2. **Data Exploration**  
   Checked survival rates by gender:  
   - About 74% of women survived.  
   - About 19% of men survived.  

3. **Feature Selection & Encoding**  
   Selected features: `Pclass`, `Sex`, `SibSp`, `Parch`  
   Converted categorical variables to numeric using `pd.get_dummies()`.

4. **Model Training**  
   Used `RandomForestClassifier` with 100 estimators and max depth of 5.  
   Trained on the full training set and predicted survival on test data.  

5. **Submission File**  
   Created a `submission.csv` with columns:
   - `PassengerId`
   - `Survived`

   The notebook prints:  
   `"Your submission was successfully saved!"`

---

## Tools Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## Result
Generated a valid submission file for Kaggle.  
The model achieved around 75–80% accuracy (depending on parameters and seed).

---

## Author
**Rosanne Sim**  
📧 rosannesimtongenn@gmail.com  
[LinkedIn](https://linkedin.com/in/rosannesim) | [GitHub](https://github.com/rosannesim)
