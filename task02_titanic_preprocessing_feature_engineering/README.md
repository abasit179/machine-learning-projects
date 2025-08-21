# Task 2: Titanic Dataset Preprocessing and Feature Engineering

**Goal:**  
Prepare the Titanic dataset for machine learning by applying preprocessing and feature engineering steps to transform raw data into a clean, normalized, and enriched format.

---

## 🔑 Objectives

### 1. Missing Value Imputation
- Age → filled with median  
- Categorical features (e.g., Embarked) → filled with mode  

### 2. Categorical Feature Encoding
- One-Hot Encoding for nominal variables (e.g., Sex, Embarked)  
- Label Encoding (if needed) for ordinal categories  

### 3. Numerical Feature Scaling
- StandardScaler or MinMaxScaler applied depending on distribution  

### 4. Feature Engineering
- **Title Extraction:** parsed from the `Name` column (Mr, Mrs, Miss, Master, etc.), grouped similar/rare titles  
- **Family Size:** created from `SibSp + Parch + 1`  

---

## 📂 Deliverables
- `titanic_preprocessing.ipynb` → full pipeline notebook
- Clean dataset (output DataFrame ready for ML)
- Documentation via comments/markdown explaining choices

---

## ✅ Success Criteria
- No missing values remain in critical features  
- Encoded categorical variables properly  
- Numerical features scaled  
- New features (`Title`, `FamilySize`) correctly added  

---

## 🛠 Tools
- Python  
- Pandas  
- Scikit-learn (imputation, encoding, scaling)  
