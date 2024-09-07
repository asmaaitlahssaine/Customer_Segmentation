# Customer Segmentation using KMeans Clustering

## Project Overview
This project applies the KMeans clustering algorithm to segment customers from the Mall_Customers dataset. The goal is to identify customer segments based on their spending habits, annual income, age, and gender. Such segmentation can help businesses make better decisions for targeted marketing.

## Dataset
The dataset used is `Mall_Customers.csv` which contains the following features:
- CustomerID: Unique ID for each customer.
- Gender: Gender of the customer (Male/Female).
- Age: Age of the customer.
- Annual Income (k$): Annual income of the customer in thousands of dollars.
- Spending Score (1-100): A score assigned based on customer behavior and spending patterns.

## Key Steps in the Project:
1. Data Preprocessing: Handling missing values (if any), feature selection, and transforming the data for analysis.
2. Exploratory Data Analysis (EDA):
   - Visualization of the distributions of age, income, and spending scores.
   - Gender distribution of the customers.
3. KMeans Clustering:
   - Applying the KMeans algorithm to segment the customers into clusters.
   - Choosing the optimal number of clusters using the elbow method.
   - Analyzing the characteristics of the identified customer segments.
4. Cluster Visualization:
   - Visualizing customer segments using 2D and 3D plots for better understanding.

## Libraries Used
- Pandas: For data manipulation and analysis.
- Seaborn and Matplotlib: For data visualization.
- Scikit-learn: For implementing the KMeans clustering algorithm.

## How to Run
1. Clone this repository to your local machine.
2. Install the required libraries by running:
   ```bash
   pip install -r requirements.txt
 ## Result
The KMeans algorithm segments customers into distinct groups based on spending patterns and income. The results provide valuable insights into customer behavior, allowing businesses to target different customer segments more effectively.

