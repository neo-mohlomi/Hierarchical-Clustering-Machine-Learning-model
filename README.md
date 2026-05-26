# Customer Segmentation using Hierarchical Clustering
## Project Overview

It is very important to nderstand customer behavior if you are a businesses that want to make informed decisions and build stronger relationships with their customers. Instead of treating all customers as one group, businesses can use data analysis techniques to identify different customer categories and understand how people interact with products and services.

In this project , similar to the previos K-means Clustering project , I explored mall customer data using unsupervised machine learning technique: Hierarchical Clustering. The purpose of the project was not only to segment customers, but also to compare how different clustering approaches identify patterns within the same dataset.

My analysis focused mainly on customer annual income and spending behavior to uncover meaningful customer groups that could provide useful business insights.

## Business Problem
Businesses often have access to customer data but may not fully understand the different behaviors that exist within their customer base. Without proper segmentation, marketing strategies and customer engagement efforts can become too broad ,less effective and costly.

In this project I attempts to answer questions such as:

- Which customers spend the most?
- Are high income customers always high spenders?
- Which customer groups could benefit from targeted marketing?
- Can different clustering methods produce similar customer segments?

## Project Objectives
The objectives of this project were:

- Identify customer groups based on income and spending behavior
- Discover hidden patterns within customer data
- Compare K-Means and Hierarchical Clustering approaches
- Evaluate whether both algorithms produce similar segmentation outcomes
- Generate insights that could support business decisions

## Dataset
The dataset contains mall customer information with features including:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

I seleced the following features for clustering:

- Annual Income
- Spending Score

## Approach
### Data Preparation

I prepared and cleaned the dataset before analysis:

- Imported customer data
- Selected relevant features
- Checked for missing values
- Prepared variables for clustering

**Dendrogram Analysis**

I used the dendrogram to determine the optimal number of clusters by identifying the largest vertical distance between cluster merges.

Interestingly, the dendrogram also suggested 5 clusteres as in the K-means algorithm.
This indicated consistency between both clustering approaches and strengthened confidence in the segmentation results.

## Key Findings

Both clustering algorithms identified similar customer patterns:

### High Income — High Spending Customers
Potential premium customers and strong targets for loyalty programs.

### High Income — Low Spending Customers
Customers with purchasing potential that may benefit from personalized marketing.

### Low Income — High Spending Customers
Customers who show strong purchasing engagement despite lower income.

### Low Income — Low Spending Customers
Customers who may respond better to cost-sensitive offers.

### Moderate Income — Moderate Spending Customers
Represents average customer behavior.

## Comparison Between Algorithms
Although both methods work differently, they produced the same number of customer groups in this project, suggesting that the segmentation patterns within the data were relatively stable.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- SciPy
- Jupyter Notebook

## Future Improvements
For future enhancements I could include:

- Include additional customer variables
- Test other clustering techniques
- Build an interactive dashboard
- Evaluate cluster quality metrics
- Deploy the analysis as a business analytics application

## Author
Neo Mohlomi
| Data Scientist | Machine Learning Enthusiast 
