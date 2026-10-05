# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project focuses on customer segmentation using **K-means clustering,** an unsupervised machine learning algorithm.

The objective is to group customers with **similar spending behavior** based mainly on their **annual income and spending score**. This type of segmentation can help businesses understand different customer groups and develop targeted marketing strategies.

---

## 🎯 Problem Statement

A financial firm wants to understand the spending behavior of its customers.

The available customer information includes:

* Age
* Gender
* Annual Income
* Customer Spending Score

The goal is to identify groups of customers with similar characteristics using **K-means clustering.**

---

## 📊 Dataset

The dataset contains **200 observations and 5 variables**.

| Column             | Description               |
| ------------------ | ------------------------- |
| `Cust_Number`      | Unique customer ID        |
| `Yearly_Income`    | Annual income of customer |
| `Age`              | Age of customer           |
| `Cust_Spend_Score` | Customer spending score   |
| `Sex`              | Gender of customer        |

---

## 🛠️ Technologies & Libraries

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📊 Matplotlib
* 🎨 Seaborn
* 🤖 Scikit-learn
* 📓 Jupyter Notebook / Google Colab

---

## 🔄 Project Workflow

The complete project follows these major steps:

### 1. Import Libraries

Required Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn are imported.

### 2. Data Preparation

The dataset is loaded, and basic information about the data is checked.

### 3. Data Type Checking

Data types of all variables are examined and corrected where required. The `Sex` variable is converted to a categorical/object type.

### 4. Remove Insignificant Variables

`Cust_Number` is removed because it is only a unique customer identifier and does not contribute to customer segmentation.

### 5. Outlier Analysis

Outliers are identified using visualization and statistical analysis. Appropriate treatment is performed before applying clustering.

### 6. Missing Value Analysis

The dataset is checked for missing/null values before model building.

### 7. Feature Scaling

`StandardScaler` is used to scale the selected numerical variables so that features with different ranges do not dominate the clustering algorithm.

### 8. K-Means Clustering

K-Means is applied to group customers based on their characteristics.

### 9. Finding Optimal K

Two techniques are used to determine a suitable number of clusters:

* Elbow Method
* Silhouette Score

### 10. Cluster Analysis

After creating the clusters, each customer segment is analyzed to understand its income, age, and spending behavior.

---

## 📈 Data Visualizations

The project includes several important graphs and visualizations:

### 📦 Outlier Analysis

Boxplots are used to identify possible outliers in the numerical variables.

### 📉 Elbow Plot

The elbow method is used to compare the within-cluster sum of squares (WCSS) for different values of K.

### 📊 Silhouette Score Plot

Silhouette scores are calculated for different cluster values to evaluate the quality of clustering.

### 📊 Cluster Size Visualization

A bar chart is used to show the number of customers present in each cluster.

### 🎯 Customer Cluster Scatter Plot

A scatter plot is used to visualize customer groups based on:

* Yearly Income
* Customer Spending Score

---

## 🤖 Machine Learning Model

### K-Means Clustering

**K-Means** is an unsupervised machine learning algorithm that divides data into a predefined number of clusters.

In this project, different values of K are evaluated, and **K = 5** is selected as the optimal clustering solution based on the analysis.

The best observed silhouette score is approximately **0.5582**.

---

## 👥 Customer Segments

The final K-means model identifies **5 customer segments**:

| Cluster   | Customer Segment                |
| --------- | ------------------------------- |
| Cluster 0 | High Income – High Spending     |
| Cluster 1 | Low Income – Low Spending       |
| Cluster 2 | High Income – Low Spending      |
| Cluster 3 | Low Income – High Spending      |
| Cluster 4 | Medium Income – Medium Spending |

These segments provide a simple way to understand different customer behaviors.

---

## 💡 Key Insights

The segmentation helps identify different types of customers, such as

* 💰 Customers with **high income and high spending**
* 💤 Customers with **low income and low spending**
* 💳 Customers with **high income but low spending**
* 🛍️ Customers with **low income but high spending**
* 👥 Customers with **medium income and medium spending**

Businesses can use these segments for targeted marketing, customer profiling, and personalized offers.

---

## 📂 Project Structure

```text
Customer-Segmentation/
│
├── Customer_Segmentation.ipynb
├── customer.csv
├── README.md
└── images/
    ├── elbow_plot.png
    ├── silhouette_plot.png
    ├── cluster_distribution.png
    └── customer_clusters.png
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open the Jupyter Notebook or Google Colab.
3. Keep `customer.csv` in the correct project directory.
4. Install the required libraries if needed.
5. Run the notebook cells step by step.
6. Review the graphs and final customer clusters.

---

## 📌 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Outlier Detection
* Missing Value Analysis
* Feature Scaling
* Data Visualization
* K-Means Clustering
* Elbow Method
* Silhouette Analysis
* Customer Segmentation
* Business Insight Generation

---

## 🏁 Conclusion

This project demonstrates how **K-means clustering** can be used to segment customers based on their income and spending behavior.

The analysis identifies **5 meaningful customer groups**, which can help businesses better understand their customers and make data-driven marketing decisions.

### ⭐ Project Highlights

**Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | EDA | Data Visualization | K-Means Clustering | Customer Segmentation**
