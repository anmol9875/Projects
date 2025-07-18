# Clustering Project: Unsupervised Learning with K-Means, DBSCAN, and K-Prototypes

## Project Overview
This project explores unsupervised clustering techniques using three popular algorithms:
- **K-Means**: for numerical data clustering.
- **DBSCAN**: for density-based spatial clustering.
- **K-Prototypes**: for mixed (categorical + numerical) data.

The goal is to compare these algorithms on different datasets and understand how they can help in segmenting data meaningfully, which is a critical part of many business analytics tasks.

---

## Algorithms Used

### 1. K-Means Clustering
- Applied to the Iris dataset.
- Features were scaled using `StandardScaler`.
- Evaluation done via **Silhouette Score**.

### 2. DBSCAN (Density-Based Spatial Clustering)
- Applied to the same dataset with tuned `eps` and `min_samples`.
- Visualized clusters to understand density-based segmentation.
- Detected noise and outliers effectively.

### 3. K-Prototypes
- Applied on a sample mixed-type dataset (containing categorical and numerical columns).
- Used `kmodes` library for K-Prototypes.
- Cluster assignments visualized and interpreted.
- Helped group data without requiring conversion of categorical features.
- Demonstrated ability to work with real-world categorical data.

---

## Tools & Libraries
- Python
- Jupyter Notebook
- `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- `kmodes` (for K-Prototypes)

---

## Key Learnings
- Clustering reveals hidden patterns when labels are not available
- **K-Means** is effective but sensitive to scale and requires predefined `k`
- **DBSCAN** can find arbitrarily shaped clusters and detect outliers, no need to specify number of clusters
- **K-Prototypes** is ideal for datasets that contain both numerical and categorical data

---

## Business Applications
- **Customer Segmentation** for marketing personalization
- **Product Categorization** based on sales/usage patterns
- **Fraud Detection** using anomaly detection (via DBSCAN)
