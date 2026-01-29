# 🛍️ Customer Segmentation Using K-Means Clustering

## 📌 Overview (Internship Task)
Customer segmentation helps businesses understand customer behavior and design targeted marketing strategies.  
This Task uses **unsupervised machine learning (K-Means clustering)** to segment mall customers based on their **spending behavior and annual income**.

The Task includes **Exploratory Data Analysis (EDA)**, **K-Means clustering**, **PCA-based visualization**, and **business-driven insights** for each identified customer segment.

---

## 🎯 Objective
- Segment customers based on spending habits  
- Identify meaningful customer groups using K-Means clustering  
- Visualize clusters using PCA  
- Propose marketing strategies for each segment  

---

## 📂 Dataset
- **Name:** Mall Customer Segmentation Dataset  
- **Source:** Kaggle  
- **File:** `Mall_Customers.csv`  

### Features:
- `CustomerID` – Unique customer identifier  
- `Gender` – Male / Female  
- `Age` – Customer age  
- `Annual Income (k$)` – Annual income in thousands  
- `Spending Score (1–100)` – Spending behavior score  

---

## 🧪 Exploratory Data Analysis (EDA)
EDA was performed to understand data distribution and relationships:
- Checked dataset shape, data types, and missing values  
- Analyzed gender distribution  
- Visualized age distribution  
- Explored the relationship between annual income and spending score  

### Key Insights:
- Dataset contains 200 customers with no missing values  
- Customers with similar income often show very different spending behaviors  
- Younger customers tend to have higher spending scores  
- Annual income alone does not determine spending patterns  

---

## 🤖 K-Means Clustering

### Feature Selection:
- Annual Income (k$)  
- Spending Score (1–100)  

### Preprocessing:
- Features were standardized using StandardScaler  

### Optimal Number of Clusters:
- Determined using the Elbow Method  
- Optimal value found: **K = 5**

### Model:
- K-Means clustering was applied to segment customers into five distinct groups  

---

## 📉 Dimensionality Reduction & Visualization
- Principal Component Analysis (PCA) was used to reduce dimensionality  
- Clusters were visualized in 2D space  
- PCA confirmed clear separation between customer segments  

---

## 🧩 Customer Segments & Marketing Strategies

### 🔴 High Income – High Spending
- Premium memberships  
- Loyalty programs  
- Exclusive product launches  

### 🔵 High Income – Low Spending
- Personalized promotions  
- Discounts to increase engagement  
- Product awareness campaigns  

### 🟢 Low Income – High Spending
- Affordable bundles  
- Cashback offers  
- EMI and installment options  

### 🟡 Low Income – Low Spending
- Budget-friendly products  
- Seasonal discounts  
- Minimal marketing investment  

### 🟣 Moderate Income – Moderate Spending
- Cross-selling and upselling  
- Personalized recommendations  
- Reward-based engagement  

---

## ✅ Conclusion
- K-Means clustering effectively segmented customers into five meaningful groups  
- Spending behavior is influenced by multiple factors, not just income  
- PCA visualization validated the clustering results  
- These insights can help businesses optimize marketing strategies and improve customer engagement  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---
