# Elevatelabs-task8
Customer Segmentation using K-Means & DBSCAN

This project performs Customer Segmentation using two clustering algorithms: K-Means and DBSCAN.
It includes Data Preprocessing, Missing Value Handling, Exploratory Data Analysis (EDA), Feature Scaling, Clustering, and Visualization.

📌 Project Overview

Customer segmentation helps businesses understand different groups of customers based on their behavior.
In this project:

We use the Mall Customers Dataset (loaded from a URL)

Perform mean, median, mode based missing value imputation

Conduct full EDA with visualizations

Apply K-Means Clustering

Apply DBSCAN Clustering for improved accuracy

Compare clustering performance using Silhouette Scores

Visualize and interpret the clusters

📂 Dataset Used

Dataset is loaded directly from URL for reproducibility:

https://raw.githubusercontent.com/shwetapal/mall-customer-segmentation/master/Mall_Customers.csv

🧹 Data Preprocessing

Includes:

Handling missing values

Mean → Age

Median → Annual Income

Mode → Gender

Feature selection

Scaling using StandardScaler

Removing noise points for DBSCAN evaluation

📊 Exploratory Data Analysis

EDA includes:

Gender distribution

Age distribution

Annual Income distribution

Spending Score distribution

Pairwise relationships

Outlier checks

🤖 Models Implemented
1️⃣ K-Means Clustering

Number of clusters fixed at k = 5

Performs well for compact, circular clusters

Produces a Silhouette Score for evaluation

2️⃣ DBSCAN Clustering

Automatically detects number of clusters

Detects noise/outliers

Works on arbitrarily shaped clusters

Often gives better accuracy

Silhouette Score calculated after removing noise

📈 Performance Comparison
Model	Strength	Weakness
K-Means	Simple & fast	Requires k, sensitive to outliers
DBSCAN	Detects noise, no need for k	Sensitive to eps & min_samples

Silhouette score comparison is printed in output.

🖥 Example Outputs

Silhouette Score for K-Means

Silhouette Score for DBSCAN

K-Means cluster scatter plot

DBSCAN cluster scatter plot

Dataset after assigning clusters

🧪 Technologies Used

Python

Pandas

NumPy

Seaborn

Matplotlib

Scikit-learn

▶️ How to Run

Open Google Colab

Upload the notebook or paste your code

Run all cells

View clustering visualizations and scores

No installation required — dataset loads directly from URL ✔️

📜 Code Used (Summary)

The project includes:

Data loading

Preprocessing

EDA

K-Means

DBSCAN

Evaluation

Visualization

⭐ Conclusion

This project shows how both K-Means and DBSCAN can be used to segment customers.
DBSCAN often provides better accuracy because it handles outliers and detects clusters of any shape.

🙌 Author

Project completed as part of AI & ML Internship – Elevate Labs
Feel free to connect and explore my work!
