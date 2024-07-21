# Customer_Segmentation-KMeans

## Introduction
This project utilizes the K-means clustering algorithm to segment customers based on two key features: `Annual Income` and `Spending Score`. The goal is to group customers into distinct segments to enable more targeted marketing and personalized strategies.  

## About the Dataset
The dataset used in this project contains customer data with the following features:  
- **Annual Income**: The yearly income of the customers.  
- **Spending Score**: A score assigned to customers based on their purchasing behavior and spending patterns.  

The dataset may also include additional demographic and behavioral features, but the focus here is on clustering based on `Annual Income` and `Spending Score`.

## Tools and Libraries
- **Python**: Programming language used for data processing and clustering.  
- **Pandas**: For data manipulation and analysis.  
- **NumPy**: For numerical operations.  
- **Scikit-learn**: For implementing the K-means clustering algorithm.  
- **Matplotlib**: For visualizing clusters.  
- **Seaborn**: For enhanced data visualization.  

## Steps
1. **Data Loading and Preprocessing**:
   - Load the dataset from a CSV file.  
   - Handle any missing values.  
   - Normalize or standardize `Annual Income` and `Spending Score` if necessary.  

2. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of `Annual Income` and `Spending Score`.  
   - Examine relationships between these two features.  

3. **K-Means Clustering**:
   - Use the Elbow Method to determine the optimal number of clusters.  
   - Apply the K-means algorithm to segment customers into clusters based on `Annual Income` and `Spending Score`.  

4. **Cluster Evaluation and Visualization**:
   - Evaluate the clustering results.  
   - Visualize the clusters using scatter plots to show how customers are grouped.  

## Outcome
The project segments customers into distinct clusters based on their `Annual Income` and `Spending Score`. This segmentation can help in tailoring marketing campaigns and understanding customer behavior patterns.  

## Conclusion
The K-means clustering algorithm effectively segments customers into meaningful groups based on `Annual Income` and `Spending Score`. These insights can be leveraged to design targeted marketing strategies and improve customer engagement.  

## Metrics
- **Elbow Method**: Determines the optimal number of clusters by plotting the sum of squared distances (inertia) from each point to its assigned cluster center.  
- **Cluster Visualization**: Scatter plots of `Annual Income` vs. `Spending Score` with cluster centroids to visually assess the clustering outcome.  

