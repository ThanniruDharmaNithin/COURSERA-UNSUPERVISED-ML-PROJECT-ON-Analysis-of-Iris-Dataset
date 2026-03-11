# 🌸 Unsupervised Learning Analysis of Iris Dataset: Comparing Clustering Algorithms

**Course:** Coursera – Unsupervised Machine Learning  
**Author:** THANNIRU DHARMA NITHIN  

---

## 🎯 Objective
The main objective of this analysis is to apply unsupervised learning techniques, specifically clustering, on the Iris dataset. The goal is to identify underlying patterns and groupings within the data, providing insights into the distinct species of iris flowers based on their morphological characteristics.

---

## 📊 Dataset Overview
The Iris dataset contains measurements of various features of iris flowers, along with their species labels.

**Features:**
- Sepal Length (cm)  
- Sepal Width (cm)  
- Petal Length (cm)  
- Petal Width (cm)  
- Species (Setosa, Versicolor, Virginica)  

**Dataset Summary:**
- Total entries: 150  
- Data types: 4 numerical features, 1 categorical label  
- No missing values; clean dataset  

**Key Statistics (numerical features):**
- Sepal Length: mean ≈ 5.84, min = 4.3, max = 7.9  
- Sepal Width: mean ≈ 3.05, min = 2.0, max = 4.4  
- Petal Length: mean ≈ 3.76, min = 1.0, max = 6.9  
- Petal Width: mean ≈ 1.20, min = 0.1, max = 2.5  

---

## 🧐 Data Exploration
- Visualized feature distributions for sepal length, sepal width, petal length, and petal width.  
- Observed clear separation in feature ranges for the three species.  
- Checked for missing values: dataset is complete and clean.  

---

## 🧠 Model Training: Clustering Algorithms
Three unsupervised clustering algorithms were applied and compared:

1. **K-means Clustering**
   - **Advantages:** Simple, scalable  
   - **Disadvantages:** Requires specifying the number of clusters; sensitive to centroid initialization  
   - **Result:** Identified 3 well-separated clusters corresponding to the species  
   - **Silhouette Score:** 0.501  

2. **Hierarchical Clustering**
   - **Advantages:** No need to specify cluster count; captures hierarchy  
   - **Disadvantages:** Computationally expensive for large datasets; less effective with irregular clusters  
   - **Result:** Revealed hierarchical relationships between species  
   - **Silhouette Score:** 0.499  

3. **DBSCAN (Density-Based Spatial Clustering)**
   - **Advantages:** Detects clusters of arbitrary shape; robust to outliers  
   - **Disadvantages:** Sensitive to parameters; struggles with varying densities  
   - **Result:** Identified clusters and outliers, revealing density variations  
   - **Silhouette Score:** 0.446  

**Conclusion on Algorithms:**  
K-means performed slightly better in terms of silhouette score and provided clearly separated clusters.

---

## 📌 Cluster Visualization
- K-means: Clear, distinct clusters representing Setosa, Versicolor, and Virginica  
- Hierarchical: Illustrated similarity patterns and hierarchical relationships  
- DBSCAN: Highlighted outliers and dense regions  

Visualizations confirmed that K-means clustering effectively partitions the data based on iris flower characteristics.

---

## 🏆 Key Findings & Insights
- **K-means:** Best performance; identified 3 distinct clusters matching the species.  
- **Hierarchical Clustering:** Captured hierarchical structure and relationships.  
- **DBSCAN:** Effective at detecting outliers and dense clusters.  
- **Feature Patterns:** Petal and sepal dimensions strongly differentiate species.  

---

## 🔮 Suggestions for Next Steps
- Experiment with other clustering algorithms and hyperparameters for improved cluster quality.  
- Apply dimensionality reduction techniques (PCA or t-SNE) to visualize clusters in 2D or 3D space.  
- Incorporate domain knowledge to validate clusters and interpret biological significance.  

---

## 📝 Conclusion
This project demonstrates the application of unsupervised learning on the Iris dataset to uncover inherent groupings of iris flowers. K-means clustering slightly outperformed Hierarchical and DBSCAN algorithms in this dataset, providing meaningful insights into species differentiation based on morphological features.  

The analysis highlights the value of clustering techniques for pattern discovery, data exploration, and understanding underlying structures in biological datasets.

---
