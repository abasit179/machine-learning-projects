# Task 5: Hyperparameter Optimization for Titanic Survival Classifier

**Goal:**  
Optimize the hyperparameters of a chosen machine learning model (Logistic Regression or Decision Tree) for Titanic survival prediction, and compare tuned performance against default settings.

---

## 🔑 Objectives

### 1. Model Selection & Baseline
- Choose Logistic Regression or Decision Tree  
- Train with **default parameters**  
- Record baseline metrics  

### 2. Hyperparameter Search Strategies
- **Grid Search CV:** test predefined hyperparameter grid  
- **Randomized Search CV:** sample hyperparameters from distributions  
- Both with cross-validation  

### 3. Model Evaluation
- Train best models from each search method  
- Evaluate with metrics on test set:  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  

### 4. Performance Comparison
- Compare **Default vs Grid Search vs Randomized Search**  
- Document best hyperparameters found  
- Summarize improvement in metrics  

---

## 📂 Deliverables
- Notebook: `hyperparameter_optimization.ipynb`  
- Metrics for:  
  - Default model  
  - Best Grid Search model  
  - Best Randomized Search model  
- Documentation of search spaces & rationale  
- Performance summary (table/plot)  

---

## ✅ Success Criteria
- Both Grid and Randomized Search implemented correctly  
- Optimal hyperparameters identified  
- Performance improvement clearly shown  
- Code clean, efficient, and reproducible  

---

## 🛠 Tools
- Python (3.x)  
- Pandas, NumPy  
- Scikit-learn (LogisticRegression, DecisionTreeClassifier, GridSearchCV, RandomizedSearchCV, metrics)  
