# PRODIGY_ML_02

# Customer Segmentation using K-Means Clustering

## Project Overview

This project uses Machine Learning and K-Means Clustering to analyze and segment mall customers based on their purchasing behavior.

The model groups customers according to:

- Annual Income
- Spending Score

This helps businesses understand customer behavior and improve marketing strategies.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Algorithm

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm used to group similar data points into clusters.

In this project, customers are segmented into different groups based on spending habits and annual income.

---

## Dataset Information

Dataset: Mall Customers Dataset

Columns used:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## Features of the Project

- Data Analysis
- Data Visualization
- Elbow Method
- Customer Segmentation
- Cluster Visualization
- Customer Prediction
- CSV Export

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Analysis
4. Data Visualization
5. Feature Selection
6. Elbow Method
7. Apply K-Means Clustering
8. Visualize Clusters
9. Predict Customer Cluster
10. Export Clustered Dataset

---

## Elbow Method Output

The Elbow Method is used to determine the optimal number of clusters.

![Elbow Method](screenshots/elbow_method.png)

---

## Customer Segmentation Output

Final clustered customer groups visualization:

![Customer Segmentation](screenshots/customer_segmentation.png)

---

## Prediction Example

The model can also predict the cluster of a new customer based on:
- Annual Income
- Spending Score

Example:
- Income = 60
- Spending Score = 40

Predicted customer segment is displayed by the model.

---

## How to Run the Project

### Step 1: Clone Repository

```bash
git clone https://github.com/GaikwadGayatri16/PRODIGY_ML_02.git
```

---

### Step 2: Install Requirements

```bash
pip install -r requirements.txt
```

---

### Step 3: Run Jupyter Notebook

Open:

```text
customer_segmentation.ipynb
```

Run all cells sequentially.

---

## Project Structure

```text
PRODIGY_ML_02
│
├── screenshots
│   ├── elbow_method.png
│   ├── customer_segmentation.png
│
├── Mall_Customers.csv
├── Clustered_Customers.csv
├── customer_segmentation.ipynb
├── requirements.txt
└── README.md
```

---

## Applications

- Customer Analytics
- Business Intelligence
- Target Marketing
- Personalized Advertising
- Retail Analysis

---

## Conclusion

K-Means Clustering successfully segmented customers into different groups based on their purchasing behavior.

This project demonstrates the practical implementation of unsupervised machine learning techniques in customer analytics.

---

## Author
Gayatri Gaikwad
