# Customer Segmentation using Hierarchical Clustering (MST Approach)

This project performs **customer segmentation** on the Mall Customers dataset using **Single-Linkage Hierarchical Clustering** implemented via a **Minimum Spanning Tree (MST)** approach.

The goal is to group customers based on demographic and spending behavior to extract meaningful business insights.

---

## 📌 Project Overview

Customer segmentation is a crucial task in marketing and business analytics.  
In this notebook, we:

- Preprocess customer data
- Encode categorical variables
- Scale numerical features
- Construct a **distance matrix**
- Build a **Minimum Spanning Tree (MST)**
- Perform **single-linkage hierarchical clustering**
- Analyze cluster characteristics for insights

This project demonstrates both **theoretical understanding** and **practical implementation** of hierarchical clustering concepts.

---

## 📊 Dataset

- **Dataset:** Mall_Customers.csv  
- **Features Used:**
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

The dataset is commonly used for customer analytics and segmentation problems.

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:**
  - pandas
  - numpy
  - scikit-learn
  - scipy
  - matplotlib
- **Environment:** Jupyter Notebook

---

## 🔍 Methodology

1. **Data Inspection**
   - Checked structure, statistics, and missing values

2. **Data Preprocessing**
   - Dropped unnecessary columns (`CustomerID`)
   - Encoded categorical feature (`Gender`)
   - Feature scaling using `StandardScaler`

3. **Distance Matrix Calculation**
   - Computed pairwise distances between data points

4. **Minimum Spanning Tree (MST) Construction**
   - Built MST from the distance matrix

5. **Hierarchical Clustering**
   - Applied **single-linkage clustering**
   - Removed largest edges from MST to form clusters

6. **Cluster Analysis**
   - Analyzed properties of each cluster
   - Derived insights about customer behavior

---

## 📈 Results & Insights

- Customers are grouped based on spending patterns and income levels
- Clear separation of:
  - High-income high-spending customers
  - Budget-conscious customers
  - Younger vs older spending behavior
- Useful for targeted marketing and personalization strategies

---

## 🧠 Key Learnings

- Practical implementation of **hierarchical clustering**
- Understanding MST-based single linkage clustering
- Importance of feature scaling in distance-based algorithms
- Translating clustering results into business insights

---

## 🔮 Future Enhancements

- Compare with K-Means and DBSCAN clustering
- Visualize dendrograms for better interpretation
- Automate optimal cluster selection
- Deploy as a simple analytics dashboard

---

## 👨‍💻 Author

**Mohammed Saif**  
- M.Tech Computer Science & Engineering  
- Interested in Data Engineering, ML, Cloud 

---

## 📜 License

This project is for educational and learning purposes.
