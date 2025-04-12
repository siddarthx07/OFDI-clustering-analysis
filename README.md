# 🌐 OFDI Clustering Analysis

This project performs clustering-based analysis on **Outward Foreign Direct Investment (OFDI)** data to uncover investment patterns across countries and regions. Using unsupervised learning techniques, the goal is to group countries based on economic and investment indicators to better understand global investment trends.

---

## 📌 Objectives

- Analyze Outward Foreign Direct Investment (OFDI) data
- Use clustering techniques (K-Means, Hierarchical, DBSCAN) to group countries
- Visualize clusters and regional patterns in global investment
- Interpret clustering results using principal component analysis (PCA)

---

## 🧠 Key Features

- 📊 **Data Preprocessing**: Handling missing values, scaling, encoding
- 🧮 **Clustering Algorithms**:
  - K-Means
  - Agglomerative Clustering
  - DBSCAN
- 📉 **Dimensionality Reduction**: PCA for cluster visualization
- 🌍 **Geospatial Visualizations** of clustered countries
- 📈 **Elbow Method** and **Silhouette Score** for optimal cluster selection

---

## 📁 Project Structure

```bash

⚙️ Setup Instructions
1. Clone the Repository
git clone https://github.com/siddarthx07/OFDI-clustering-analysis.git
cd OFDI-clustering-analysis

2. Create a Virtual Environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt
Common packages include:
pip install pandas numpy matplotlib seaborn scikit-learn plotly

📊 Sample Outputs
<table> <tr> <td><img src="docs/kmeans_clusters.png" alt="KMeans Clustering" width="300"/></td> <td><img src="docs/pca_clusters.png" alt="PCA Visualization" width="300"/></td> </tr> </table>
🔍 Analysis Workflow
Load and clean the OFDI dataset

Normalize features and handle missing data

Perform clustering using K-Means, Agglomerative, and DBSCAN

Visualize clusters with PCA and t-SNE (optional)

Evaluate clustering performance and interpret results

🛠️ Tools & Technologies
Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn, Plotly

PCA for feature compression

📬 Author
Siddarth Bandi


