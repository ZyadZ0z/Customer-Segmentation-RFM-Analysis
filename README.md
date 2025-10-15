# 🧠 Customer Segmentation & RFM Analysis Project

## 📄 Project Overview
This project performs advanced **RFM (Recency, Frequency, Monetary) Analysis** and **Customer Segmentation** using a marketing dataset.  
The goal is to identify valuable customer groups, understand their spending behavior, and provide insights for better marketing strategies.

---

## 🧰 Tools & Technologies
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**

---

## ⚙️ Steps & Methodology

### 1️⃣ Data Preparation
- Loaded and cleaned the dataset.
- Handled missing values.
- Created total spending (`Total_Spent`) and total accepted campaigns.

### 2️⃣ RFM Analysis
- **Recency:** Days since last purchase/join date  
- **Frequency:** Number of accepted marketing campaigns  
- **Monetary:** Total amount spent  
- Segmented customers into 4 quantiles for each metric.  
- Calculated `RFM_Score` and `RFM_Score_Num`.

### 3️⃣ Customer Segmentation
- Divided customers into:
  - `Low Income`, `Mid Income`, `High Income`
  - `Low Spender`, `Mid Spender`, `High Spender`
- Created a **heatmap** to visualize income vs. spending behavior.

---

## 📊 Key Insights
- Customers with **RFM ≥ 10** are the most loyal and profitable.
- **High Income + High Spender** customers are the premium segment — highest priority for retention.
- **Low Income + High Spender** customers respond well to discounts.
- **High Income + Low Spender** need targeted campaigns to increase engagement.

---

## 🏁 Results
- Built a complete RFM scoring system using Python.
- Visualized customer distribution and segmentation insights.
- Delivered clear business actions for marketing strategy.

---

## 📂 Project Structure
