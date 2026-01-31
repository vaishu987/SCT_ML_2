# Mall Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means clustering** to segment customers of a retail mall based on their **Annual Income** and **Spending Score**.

The goal is to help businesses identify target customer groups for effective marketing strategies.

## 📊 Dataset
**Mall Customers Dataset**
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

Source: Kaggle

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 📈 Steps Involved
1. Data loading and preprocessing
2. Feature selection
3. Elbow Method to find optimal clusters
4. K-Means model training
5. Visualization of customer segments

## 📌 Output
Customers are grouped into meaningful clusters such as:
- High income, high spenders
- Low income, low spenders
- Careful customers
- Potential loyal customers

## 🚀 How to Run
```bash
pip install -r requirements.txt
python src/kmeans_clustering.py
