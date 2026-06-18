# Customer Segmentation Using K-Means Clustering

## Project Overview
This project uses the K-Means Clustering algorithm to group retail store customers based on their demographic information and purchasing behavior. The goal is to identify customer segments that can help businesses make data-driven marketing decisions.

## Dataset Features
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn

## Workflow
1. Load the dataset.
2. Encode categorical features.
3. Scale the data using StandardScaler.
4. Determine the optimal number of clusters using the Elbow Method.
5. Apply K-Means Clustering.
6. Visualize customer segments.

## Results
Customers are grouped into clusters based on similarities in age, income, gender, and spending patterns. These clusters can be used for:
- Targeted marketing
- Customer behavior analysis
- Personalized recommendations
- Business decision-making

## Output
- Elbow Method graph
- Customer segmentation visualization
- Cluster labels assigned to each customer
