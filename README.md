# ⚽ FIFA 20 Player Analysis & Clustering

## 📌 Project Overview
This project performs an in-depth analysis of FIFA 20 player data to group players with similar skills and attributes using Unsupervised Machine Learning techniques. By analyzing player statistics like pace, shooting, passing, and dribbling, the system identifies distinct player profiles and performance patterns.

---

## 🎯 Project Objectives
- To perform Exploratory Data Analysis (EDA) on elite football player datasets.
- To group players based on their diverse skill sets using Clustering algorithms.
- To reduce data complexity for better visualization using PCA (Principal Component Analysis).
- To provide data-driven insights for player scouting and tactical team management.

---

## 🚀 Key Features & Workflow
- **Data Preprocessing:** Managed missing values and standardized numerical features using `StandardScaler`.
- **Dimensionality Reduction:** Utilized **PCA** to transform high-dimensional skill data into 2D/3D visualizations without losing core information.
- **Advanced Clustering Implementation:**
  - **K-Means Clustering:** Optimized using the **Elbow Method**.
  - **DBSCAN:** Used for density-based grouping.
  - **Hierarchical Clustering:** Visualized through **Dendrograms** for better understanding of player relationships.
- **Deep Visualization:** - Skill heatmaps for different clusters.
  - Correlation heatmaps of player attributes.
  - Performance vs. Age and Wage distribution analysis.

---

## 🛠 Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Scipy
- **Visualization:** Matplotlib, Seaborn
- **Algorithms:** K-Means, DBSCAN, Agglomerative Clustering, PCA

---

## 📊 Evaluation Metrics
- **Silhouette Score:** To measure cluster separation.
- **Davies-Bouldin Score:** To evaluate the compactness of clusters.
- **Elbow Method:** For optimal 'K' value selection.

---

## 👩‍💻 Author
**Deepasri** MCA Graduate | Aspiring AI/ML Engineer | Data Science Enthusiast
