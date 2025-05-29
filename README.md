# 🧠 K-Means Clustering on Healthcare Data (Diabetes Dataset)

This project applies **K-Means Clustering** to the diabetes dataset from `scikit-learn`. The goal is to segment patients into clusters based on clinical features, enabling insights into patterns or risk groups. The project also shows how to assign a new patient to a predicted cluster.

---

## 📌 Features

- ⚙️ Data preprocessing using `StandardScaler`
- 📊 Clustering with `KMeans`
- 📈 Cluster evaluation using Silhouette Score
- 🧬 PCA for 2D visualization
- 🩺 Predict the cluster of a new patient
- 💾 Optional model saving using `joblib`

---

## 📁 Dataset

We use the built-in `diabetes` dataset from `sklearn.datasets`, which contains:
- 10 clinical feature variables (e.g., age, BMI, blood pressure)
- 442 samples
- Data is already mean-centered and scaled such that the sum of squares of each feature is 1

---

## 🧪 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/kmeans-healthcare.git
cd kmeans-healthcare

