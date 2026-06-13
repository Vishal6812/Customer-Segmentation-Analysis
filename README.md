# Customer Segmentation using K-Means Clustering

## Project Overview

Customer Segmentation is the process of dividing customers into different groups based on their purchasing behavior, demographics, and spending patterns.

In this project, K-Means Clustering is used to identify distinct customer segments. These segments help businesses understand customer behavior and create targeted marketing strategies.

---

## Objective

The main objectives of this project are:

* Analyze customer purchasing behavior.
* Identify different customer groups.
* Apply K-Means Clustering for segmentation.
* Visualize customer clusters.
* Generate business insights for targeted marketing.

---

## Dataset

Dataset: Customer Personality Analysis Dataset

The dataset contains customer information such as:

* Income
* Age
* Spending Amount
* Number of Purchases
* Product Purchases
* Campaign Responses
* Marital Status
* Education Level

Dataset Size:

* Records: 2021
* Features: 39

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Power BI
* GitHub

---

## Exploratory Data Analysis

The following analyses were performed:

### 1. Customer Age Distribution

Analyzed customer age groups.

### 2. Income Distribution

Studied customer income patterns.

### 3. Product Sales Analysis

Analyzed spending across product categories.

### 4. Correlation Analysis

Identified relationships among customer features.

---

## Machine Learning Model

Algorithm Used:

* K-Means Clustering

Steps Performed:

1. Data Loading
2. Data Cleaning
3. Feature Selection
4. Data Scaling
5. Elbow Method
6. K-Means Clustering
7. Cluster Assignment
8. Cluster Analysis
9. Visualization

---

## Elbow Method

The Elbow Method was used to determine the optimal number of clusters.

Optimal Clusters Selected:

```text
K = 4
```

---

## Cluster Distribution

| Cluster   | Customers |
| --------- | --------- |
| Cluster 0 | 507       |
| Cluster 1 | 486       |
| Cluster 2 | 540       |
| Cluster 3 | 488       |

---

## Cluster Insights

### Cluster 0

* High Income Customers
* Highest Spending Group
* Premium Customers

### Cluster 1

* Low Spending Customers
* Lower Income Group
* Budget Buyers

### Cluster 2

* Moderate Income Customers
* Regular Buyers
* Potential Loyal Customers

### Cluster 3

* Low Spending and Less Active Customers
* Need Marketing Attention

---

## Cluster Summary

| Cluster | Income | Age   | Spending |
| ------- | ------ | ----- | -------- |
| 0       | 75,877 | 51.59 | 1367.80  |
| 1       | 32,976 | 46.48 | 77.32    |
| 2       | 59,165 | 55.61 | 657.99   |
| 3       | 36,914 | 50.27 | 108.71   |

---

## Visualizations

The following visualizations were created:

### 1. Age Distribution

Customer age analysis.

### 2. Income Distribution

Income analysis across customers.

### 3. Product Sales Distribution

Sales contribution by product category.

### 4. Elbow Method Graph

Optimal cluster selection.

### 5. Customer Segmentation Scatter Plot

Visualization of customer clusters.

---

## Model Results

* Successfully segmented customers into 4 groups.
* Identified high-value and low-value customer segments.
* Generated business insights for targeted marketing.
* Visualized customer behavior using clustering techniques.

---

## Project Structure

Customer-Segmentation/
│
├── data/
│   └── marketing_campaign.csv
│
├── notebook/
│   └── customer_segmentation.ipynb
│
├── images/
│   ├── age_distribution.png
│   ├── income_distribution.png
│   ├── product_sales_distribution.png
│   ├── elbow_method.png
│   └── customer_segments.png
│
├── customer_segments.csv
│
└── README.md


## Power BI Dashboard

Dashboard Features:

* Total Customers
* Customer Segments
* Income Analysis
* Spending Analysis
* Cluster Distribution
* Income vs Spending Scatter Plot

---

## Future Improvements

* Hierarchical Clustering
* DBSCAN Clustering
* Real-Time Customer Segmentation
* Marketing Recommendation System
* Interactive Web Dashboard

---

## Dataset Source

Customer Personality Analysis Dataset available on Kaggle.

---

## Author

Vishal Kumar


