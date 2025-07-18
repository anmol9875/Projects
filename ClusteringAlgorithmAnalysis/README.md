# Clustering Project: Unsupervised Learning with K-Means, DBSCAN, and K-Prototypes

## 📌 Project Overview
This project explores unsupervised clustering techniques using three popular algorithms:
- **K-Means**: for numerical data clustering.
- **DBSCAN**: for density-based spatial clustering.
- **K-Prototypes**: for mixed (categorical + numerical) data.

The goal is to compare these algorithms on different datasets and understand how they can help in segmenting data meaningfully, which is a critical part of many business analytics tasks.

---

## 📂 Algorithms Used

### 1. K-Means Clustering
- Applied to the Iris dataset.
- Features were scaled using `StandardScaler`.
- Optimal clusters determined using the **Elbow Method**.
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

---

## 🔧 Tools & Libraries
- Python
- Jupyter Notebook
- `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- `kmodes` (for K-Prototypes)

---

## 📊 Key Learnings
- Each algorithm has strengths depending on the data type and business case.
- **K-Means** is efficient but assumes spherical clusters.
- **DBSCAN** is powerful for noise detection and non-globular clusters.
- **K-Prototypes** handles real-world datasets with categorical features without one-hot encoding.

---

## 💡 Business Applications
- **Customer Segmentation** for marketing personalization
- **Product Categorization** based on sales/usage patterns
- **Fraud Detection** using anomaly detection (via DBSCAN)

---

## 📁 Files
- `Clusttering.ipynb`: Main notebook with EDA, implementation, and visualizations

---

## 🚀 Next Steps
- Apply these clustering methods to real business datasets (e.g., e-commerce, telecom).
- Build a dashboard to visualize clusters and their characteristics.
- Integrate cluster results with business KPIs.

---

## 🧠 Author
**Anmol Amin**  
Beginner Data Analyst with interest in ML-assisted analytics and business intelligence.
