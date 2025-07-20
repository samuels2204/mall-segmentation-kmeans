# mall-segmentation-kmeans
This project performs customer segmentation using the K-Means Clustering algorithm on a mall customer dataset. The goal is to group customers based on their purchasing behavior, helping businesses better understand customer profiles and target marketing efforts effectively.
# 🛍️ Mall Customer Segmentation using K-Means Clustering

This project performs customer segmentation using the **K-Means Clustering** algorithm on a mall customer dataset. The goal is to group customers based on their purchasing behavior, helping businesses better understand customer profiles and target marketing efforts effectively.

---

## 📌 Overview

Customer segmentation is a crucial task in marketing analytics. By analyzing customer data, companies can:
- Personalize their campaigns
- Increase customer satisfaction
- Improve sales

This project uses two important customer features: **Annual Income** and **Spending Score** to group similar customers into clusters.

---

## 🧠 Features of the Project

- Determine the optimal number of clusters using the **Elbow Method**
- Apply **K-Means Clustering** to form customer groups
- Visualize clusters in both 2D and interactive 3D plots
- Understand business insights from customer groupings

---

## 📂 Dataset

- **Source**: [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial)
- **Features**:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🧰 Tech Stack

| Library      | Purpose                          |
|--------------|----------------------------------|
| `numpy`      | Numerical operations             |
| `pandas`     | Data manipulation                |
| `matplotlib` | Static visualizations            |
| `seaborn`    | Enhanced visualizations          |
| `scikit-learn` | Machine learning model (K-Means)|
| `plotly`     | Interactive 3D cluster plots     |

---

## 📈 Visualizations Included

- Elbow Method plot (for choosing K)
- 2D cluster scatter plots
- 3D cluster visualization with Plotly
- Cluster interpretation for business insights

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/mall-customer-segmentation.git
cd mall-customer-segmentation
