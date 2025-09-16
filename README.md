# Customer Segmentation using K-Means Clustering  


## Author  
👩‍💻 **Name:** Tashfah Ashraf  
🎓 **Role:** Internee  
🏢 **Company:** Arch Technologies  


## Overview  
This project is part of my internship at **Arch Technologies**.  
I, **Tashfah Ashraf**, implemented **Customer Segmentation** using the **K-Means Clustering** algorithm to group mall customers based on their purchasing behavior.  

The goal of this task is to identify distinct customer groups that can help businesses in **targeted marketing, customer retention, and personalized engagement strategies**.  

---

## Dataset  
The dataset used is **Mall_Customers.csv**, which contains customer details such as:  
- Customer ID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1-100)  

---

## Steps Performed  
1. **Importing libraries** and **loading the dataset**.  
2. Viewing dataset details (shape, info, missing values, etc.).  
3. Selecting features **Annual Income** and **Spending Score** for clustering.  
4. Using the **Elbow Method** to determine the optimal number of clusters.  
5. Training the **K-Means model** with `k=5`.  
6. **Visualizing the clusters** along with centroids.  
7. **Enhancements** added beyond the tutorial:  
   - Step 11: **Silhouette Score** for model evaluation.  
   - Step 12: **Cluster Profiling** to describe characteristics of each customer group.  
   - Step 13: **3D Visualization** (Age, Income, Spending Score) for deeper insights.  

---

## Results  
- Optimal number of clusters: **5**  
- Customer groups identified include:  
  - Premium Customers (High Income, High Spending)  
  - Potential Customers (High Income, Low Spending)  
  - Young Enthusiastic Shoppers (Low Income, High Spending)  
  - Budget-Conscious Customers (Low Income, Low Spending)  
  - Average Customers (Moderate Income & Spending)  

---

## Tools & Libraries  
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-learn**  

---

## Conclusion  
This project demonstrates how clustering techniques can be applied to real-world data for meaningful **business insights**.  
It not only replicates the base tutorial but also includes **evaluation, profiling, and visualization enhancements** to make the analysis more comprehensive and professional.  

---
