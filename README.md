# SCT_ML_2 - Customer Segmentation using K-Means Clustering

## 📌 Overview

This project implements the K-Means Clustering algorithm to segment retail store customers based on their Annual Income and Spending Score. Customer segmentation helps businesses understand customer behavior and create targeted marketing strategies.

## 🎯 Objective

To group customers into distinct clusters based on their purchasing patterns and income levels using an unsupervised machine learning approach.

## 📊 Dataset

The dataset contains customer information such as:

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1-100)

Dataset Source:
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## 🔍 Project Workflow

1. Import required libraries
2. Load and explore the dataset
3. Select Annual Income and Spending Score as features
4. Apply the Elbow Method to determine the optimal number of clusters
5. Train the K-Means Clustering model
6. Predict customer clusters
7. Visualize customer segments and centroids
8. Analyze customer behavior patterns

## 📈 Results

The K-Means algorithm successfully segments customers into different groups, including:

* High Income, High Spending Customers
* High Income, Low Spending Customers
* Low Income, High Spending Customers
* Low Income, Low Spending Customers
* Average Customers

These insights can help businesses improve customer targeting and marketing strategies.

## Project Structure

SCT_ML_2/

├── customer_segmentation.py

├── Mall_Customers.csv

├── Customer_Segments.csv

├── README.md

└── requirements.txt

## How to Run

1. Clone the repository

git clone https://github.com/your-username/SCT_ML_2.git

2. Navigate to the project folder

cd SCT_ML_2

3. Install required libraries

pip install -r requirements.txt

4. Run the Python script

python customer_segmentation.py

## Output

* Elbow Method Visualization
* Customer Segmentation Scatter Plot
* Cluster Centroids
* Segmented Customer Dataset

## Learning Outcomes

* Unsupervised Machine Learning
* K-Means Clustering
* Data Visualization
* Customer Segmentation
* Business Analytics

## 🏷️ Tags

#MachineLearning #Python #DataScience #KMeans #CustomerSegmentation #Clustering #ScikitLearn #Pandas #NumPy #Matplotlib
