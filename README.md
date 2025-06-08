# Customer Segmentation using K-Means Clustering

This project performs **customer segmentation** using the **K-Means Clustering** algorithm on the Mall Customers dataset.

## 📂 Dataset
- `Mall_Customers.csv` contains:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

## 🔍 Objective
Group customers into segments based on:
- **Annual Income**
- **Spending Score**

## 🧪 Steps
1. Load and explore the data
2. Select relevant features
3. Use Elbow Method to find optimal clusters
4. Train K-Means model with `n_clusters=5`
5. Visualize customer segments

## 📊 Output
- WCSS Elbow Plot
- Clustered scatter plot with centroids

## 💡 Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## ✅ Result
Successfully segmented customers into 5 distinct clusters based on purchasing behavior.
