# Task 6: Customer Segmentation Analysis using K-Means Clustering

**Goal:**  
Apply K-Means clustering on the *Mall Customers* dataset to identify distinct customer segments based on spending habits and demographics.

---

## 🔑 Objectives

### 1. Dataset Preparation
- Load *Mall Customers* dataset  
- Clean and prepare relevant features for clustering  
- Handle categorical data if included (e.g., Gender)  

### 2. K-Means Clustering & Optimization
- Apply K-Means clustering algorithm  
- Determine optimal `k` using:  
  - **Elbow Method** (plot inertia vs k)  
  - **Silhouette Score** (plot score vs k)  

### 3. Cluster Analysis & Visualization
- Train final K-Means model with optimal clusters  
- Assign customers to clusters  
- Visualize clusters:  
  - 2D/3D scatter plot with color-coded segments  

---

## 📂 Deliverables
- Notebook: `kmeans_customer_segmentation.ipynb`  
- Elbow Method plot (`elbow_method.png`)  
- Silhouette Score plot (`silhouette_scores.png`)  
- Final customer clusters plot (`customer_clusters.png`)  
- Interpretation of segments (who the customers are in each group)  

---

## ✅ Success Criteria
- K-Means applied successfully  
- Optimal cluster count justified (Elbow & Silhouette)  
- Clear and correct visualizations  
- Interpretation of customer groups provided  
- Code clean, structured, reproducible  

---

## 🛠 Tools
- Python (3.x)  
- Pandas, NumPy  
- Scikit-learn (KMeans, silhouette_score)  
- Matplotlib, Seaborn  
