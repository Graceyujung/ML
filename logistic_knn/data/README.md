# 📊 Pima Indian Diabetes Dataset

This dataset contains medical records of **768 patients** from the Pima Indian population. The goal is to predict whether a patient has diabetes (`Outcome = 1`) or not (`Outcome = 0`) based on several medical measurements.

## 📂 File Information
- **File Name:** `pima_diabetes.csv`
- **Size:** ~24 KB
- **Number of Rows:** 769
- **Number of Features:** 8
- **Target Column:** `Outcome` (0 = No Diabetes, 1 = Diabetes)

## 📌 Features Description
| Feature Name              | Description                                |
|---------------------------|--------------------------------------------|
| `Pregnancies`            | Number of times pregnant                  |
| `Glucose`                | Plasma glucose concentration               |
| `BloodPressure`          | Diastolic blood pressure (mm Hg)           |
| `SkinThickness`          | Triceps skin fold thickness (mm)           |
| `Insulin`                | 2-Hour serum insulin (mu U/ml)             |
| `BMI`                    | Body mass index (weight in kg/m²)         |
| `DiabetesPedigreeFunction` | Diabetes pedigree function (genetics)   |
| `Age`                    | Age in years                              |

## 📥 Dataset Source
- 📌 [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
  
This dataset is commonly used for **classification problems** in machine learning.

---

## 🔧 How to Use the Dataset
1. Place `pima_diabetes.csv` in the `data/` folder.
2. Load it into Python using:
   ```python
   import pandas as pd
   df = pd.read_csv("data/pima_diabetes.csv")
 
