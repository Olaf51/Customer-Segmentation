# Customer Segmentation Using K-Means Clustering
## Project Overview
This project applies K-Means Clustering to segment customers based on their demographic and spending behavior. By analyzing features such as Age, Gender, Annual Income, and Spending Score, we identify distinct customer groups to provide insights that can guide personalized marketing strategies.

## Dataset
The dataset consists of 200 records of mall customers, with the following features:

CustomerID: Unique identifier for each customer.

Gender: Gender of the customer (Male/Female).

Age: Age of the customer (years).

Annual Income (k$): Annual income of the customer in thousands of dollars.

Spending Score (1-100): A score representing customer spending behavior, where 1 is the lowest and 100 is the highest.


Visualized distributions of demographic features.

Analyzed relationships between variables like Age, Income, and Spending Score.


K-Means Clustering:


Determined the optimal number of clusters using the Elbow Method.

Evaluated clustering quality with the Silhouette Score (0.55) and Inertia (SSE) (250.3).

Measured cluster compactness using the Davies-Bouldin Index (0.89).

Results Visualization:

Plotted clusters using scatter plots and heatmaps to display customer segments and their behavior.

## Insights
Silhouette Score (0.55) and Davies-Bouldin Index (0.89) confirmed good cluster separation.

Customers were grouped into distinct segments, allowing targeted marketing campaigns based on income and spending patterns.

## Technologies Used
Python: For data processing and clustering.

Pandas: Data manipulation.

Matplotlib & Seaborn: Data visualization.

Scikit-learn: Clustering algorithms and evaluation metrics.


## Conclusion

This project demonstrates the effectiveness of using K-Means Clustering to segment customers, allowing businesses to make data-driven decisions for targeted marketing strategies.

