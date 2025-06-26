# 🧠 Customer Segmentation using K-Means Clustering

This project applies unsupervised machine learning to perform customer segmentation based on purchasing behavior from e-commerce data. It helps identify groups like loyal buyers, new users, big spenders, etc.

---

## 📊 Project Summary

- **Objective**: Group customers into behavior-based segments
- **Technique**: K-Means Clustering
- **Visualization**: PCA for cluster plotting
- **Output**: Segmented customer data (`Segment` column)

---

## 🧾 Dataset Features

| Column               | Description                        |
|----------------------|------------------------------------|
| Purchase Date        | Date of transaction                |
| Product Price        | Price of the item purchased        |
| Quantity             | Number of items                    |
| Total Value          | Derived: Price × Quantity          |
| Payment Method       | Categorical: Card, Cash, etc.      |
| Customer Age         | Age of the customer                |
| Gender               | Male/Female/Other                  |
| Returns              | Number of returns (optional)       |
| ...                  | Others cleaned/encoded             |

---

## 🔧 How It Works

1. **Data Cleaning**
   - Strip spaces, fix data types
   - Handle nulls and inconsistent columns

2. **Feature Engineering**
   - Total Value
   - Recency (last purchase gap)
   - Categorical Encoding (Gender, Payment Method)

3. **K-Means Clustering**
   - Used `Elbow Method` to find optimal clusters
   - `K=4` gives meaningful separation

4. **PCA Visualization**
   - Dimensionality reduction for plotting
   - Color-coded cluster scatterplot

---

## 📷 Visualizations

### 📍 Elbow Method
![Elbow Plot](assets/elbow_plot.png)

### 🧬 PCA Cluster Plot
![PCA Clusters](assets/pca_clusters.png)



