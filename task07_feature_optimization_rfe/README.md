# Task 7: Feature Optimization for Classification using RFE

**Goal:**  
Optimize feature selection for a Titanic survival prediction classifier using **Recursive Feature Elimination (RFE)**, and compare performance between full-feature and reduced-feature models.

---

## 🔑 Objectives

### 1. Dataset Preparation
- Use preprocessed Titanic dataset  
- Define features (X) and target (`y = Survived`)  

### 2. Recursive Feature Elimination
- Apply **RFE** with a chosen estimator (e.g., Logistic Regression, Decision Tree)  
- Use **cross-validation** to find the optimal number of features  
- Select the subset of most important features  

### 3. Model Training & Evaluation
- **Baseline Model:** train on all features, evaluate with metrics:  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
- **Optimized Model (RFE):** train on selected features, evaluate with same metrics  

### 4. Results Analysis
- Present list of selected features  
- Compare performance of baseline vs optimized models  
- Discuss benefits of feature reduction (speed, generalization, interpretability)  

---

## 📂 Deliverables
- Notebook: `feature_optimization_rfe.ipynb`  
- List of selected features  
- Metrics for both baseline and optimized models  
- Visualization/table comparing performance  
- Analysis of impact of feature selection  

---

## ✅ Success Criteria
- RFE correctly applied  
- Both models trained and evaluated  
- Performance comparison provided  
- Insights on model complexity and generalization discussed  
- Code is clean and reproducible  

---

## 🛠 Tools
- Python (3.x)  
- Pandas, NumPy  
- Scikit-learn (RFE, RFECV, LogisticRegression, DecisionTreeClassifier, metrics)  
