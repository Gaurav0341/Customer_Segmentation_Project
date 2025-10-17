# 🧠 Customer Segmentation using K-Means Clustering

## 📄 Overview
This project demonstrates how to use **Unsupervised Machine Learning** for customer segmentation.  
Using the **K-Means Clustering algorithm**, we group customers based on their demographic and spending behavior data.  
This type of analysis is essential for businesses to understand their customer base and make data-driven marketing decisions.

---

## 📊 Objective
To segment mall customers into meaningful groups using **K-Means Clustering**, so that marketing strategies can be tailored for each group.

---

## 🧩 Dataset
**Dataset Used:** Mall_Customers.csv  
You can download it from [Kaggle - Mall Customers Dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

**Dataset Features:**
- `CustomerID` — Unique ID for each customer  
- `Gender` — Male / Female  
- `Age` — Age of the customer  
- `Annual Income (k$)` — Annual income of the customer  
- `Spending Score (1–100)` — Score assigned based on customer behavior and spending nature  

---

## ⚙️ Technologies Used
- **Python**
- **Pandas** — Data Manipulation
- **NumPy** — Numerical Operations
- **Matplotlib / Seaborn** — Data Visualization
- **Scikit-learn** — Machine Learning Library

---

## 🚀 Steps Involved
1. **Import Libraries**  
2. **Load and Explore Dataset**  
3. **Data Preprocessing** (handling missing values, selecting features)  
4. **Elbow Method** to find optimal `k` value  
5. **Apply K-Means Algorithm**  
6. **Visualize Clusters**  
7. **Interpret Results**

---

## 📈 Results & Insights
- The Elbow method suggested **k = 5** as the optimal number of clusters.  
- The customers were grouped into 5 clusters based on **Annual Income** and **Spending Score**.  
- Each cluster represents a unique customer segment:
  - **Cluster 1:** High Income, High Spending → “Target Customers”  
  - **Cluster 2:** Low Income, Low Spending → “Careful Customers”  
  - **Cluster 3:** High Income, Low Spending → “Savers”  
  - **Cluster 4:** Average Income, Average Spending → “Moderate Customers”  
  - **Cluster 5:** Low Income, High Spending → “Impulsive Buyers”

---

## 📉 Visualization
- Elbow curve to determine optimal clusters  
- Scatter plots of customer groups  
- Distribution graphs for income & spending patterns  

---

## 💡 Conclusion
This project demonstrates how **K-Means Clustering** can be effectively used for **customer segmentation**.  
Businesses can leverage these insights to:
- Design targeted marketing campaigns  
- Offer personalized services  
- Improve customer satisfaction and loyalty  

---

## 🧰 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
