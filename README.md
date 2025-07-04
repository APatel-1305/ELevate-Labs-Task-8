# 🧠 K-Means Clustering on Mall Customer Dataset

This project demonstrates unsupervised machine learning using **K-Means Clustering** to identify customer segments from the **Mall Customer Segmentation Dataset**. It includes exploratory data analysis (EDA), clustering using the Elbow Method, dimensionality reduction using PCA, and evaluation using Silhouette Score.

---

## 🎯 Objective

- Perform **unsupervised learning** to group mall customers based on common characteristics.
- Use **K-Means** algorithm to identify natural clusters in the dataset.

---

## 🛠️ Tools and Libraries

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## 📁 Dataset

- `Mall_Customers.csv`  
- Contains 200 customer records with the following fields:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 📊 Workflow

### 1. Exploratory Data Analysis (EDA)
- Summary statistics
- Distribution plots for `Age`, `Income`, `Spending Score`
- Gender distribution analysis
- Null value check

### 2. Preprocessing
- Dropping `CustomerID`
- Encoding `Gender` to numeric values (Male → 1, Female → 0)

### 3. Elbow Method
- Determines the optimal number of clusters (`k`) using WCSS plot.

### 4. K-Means Clustering
- Applying K-Means with chosen `k` (typically `k=5`)
- Assigning cluster labels to each data point

### 5. Cluster Visualization
- Using **PCA** to reduce features to 2D
- Plotting clusters using color-coded scatter plot

### 6. Evaluation
- Calculating **Silhouette Score** to assess clustering quality

---

## 📈 Output

- Elbow plot for optimal `k`
- Cluster visualization using PCA
- Silhouette Score for model evaluation

---

