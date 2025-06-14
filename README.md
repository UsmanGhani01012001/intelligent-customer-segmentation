# 🧠 RFM-Based Customer Segmentation using K-Means Clustering

## 📊 Project Overview

This project performs advanced **Customer Segmentation** using **RFM (Recency, Frequency, Monetary)** analysis combined with **K-Means Clustering**. It's a complete end-to-end machine learning pipeline designed to help businesses **identify distinct customer profiles**, **optimize marketing strategies**, and **improve customer retention** using real-world retail data.

---

## 🎯 Business Objective

Enable e-commerce or retail businesses to:
- Identify high-value and at-risk customers
- Design targeted campaigns for each segment
- Optimize marketing spend using data-driven insights

---

## 🧪 Technologies Used

| Stack        | Tools/Libraries                               |
|--------------|------------------------------------------------|
| Language     | Python                                         |
| Data Handling| Pandas, NumPy                                  |
| Visualization| Matplotlib, Seaborn                            |
| Modeling     | scikit-learn (KMeans), StandardScaler          |
| Date Handling| `datetime`, Pandas built-ins                   |
| Deployment   | Pickle (for model export), GitHub              |

---

## 🛠️ Features

✅ Full RFM Feature Engineering  
✅ Outlier Removal using IQR Method  
✅ Feature Scaling (StandardScaler)  
✅ Optimal K Selection using Elbow Method  
✅ K-Means Clustering for Unsupervised Learning  
✅ Beautiful 2D Segmentation Visualization  
✅ Production-Ready Code and Modular Structure

---

## 🧷 Dataset

- **Source**: `customerSegmentation.csv`  
- Contains retail transaction data with the following key fields:
  - `CustomerID`
  - `InvoiceDate`
  - `Quantity`, `UnitPrice`
  - `InvoiceNo`, `Description`

---

## 📌 RFM Definitions

| Feature     | Description                                                        |
|-------------|--------------------------------------------------------------------|
| **Recency** | Days since last purchase (how recently a customer bought)         |
| **Frequency** | Total number of transactions (how often a customer buys)         |
| **Monetary** | Total amount spent (how much a customer spends)                   |

---

## 🔍 How It Works

1. **Load and Clean Data**
2. **Calculate RFM Features**
3. **Remove Outliers (IQR Method)**
4. **Normalize RFM Features**
5. **Find Optimal Clusters (Elbow Method)**
6. **Train KMeans Model**
7. **Visualize Customer Segments**
8. **Export Model (Optional)**

---
## 🚀 Run Locally

```bash
git clone https://github.com/yourusername/rfm-customer-segmentation-kmeans.git
cd rfm-customer-segmentation-kmeans
pip install -r requirements.txt
python rfm_segmentation_kmeans.py
