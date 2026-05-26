# 🎯 Customer Segmentation using Hierarchical Clustering

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37726?style=for-the-badge&logo=jupyter&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

## Project Overview

It is very important to understand customer behavior if you are a businesses that want to make informed decisions and build stronger relationships with their customers. Instead of treating all customers as one large group, businesses can create targeted strategies by dividing their customer base into meaningful segments.

In this project , similar to the previos K-means Clustering project , I explored mall customer data using unsupervised machine learning technique: Hierarchical Clustering. The purpose of the project is to identify distinct customer segments and generate actionable business insights.

My analysis focused mainly on customer annual income and spending behavior to uncover meaningful customer groups that could provide useful business insights.

## Business Problem

Businesses often have access to customer data but may not fully understand the different behaviors that exist within their customer base. Without proper segmentation, marketing strategies and customer engagement efforts may not be optimized for different customer types.

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

### Dendrogram Analysis

I used the dendrogram to determine the optimal number of clusters by identifying the largest vertical distance between cluster merges.

<div align="center">

![Dendrogram Analysis](images/dendrogram.png)

*Figure 1: Hierarchical Clustering Dendrogram - Shows the hierarchical structure of customer clusters*

</div>

Interestingly, the dendrogram also suggested 5 clusteres as in the K-means algorithm.
This indicated consistency between both clustering approaches and strengthened confidence in the segmentation results.

## Key Findings

Both clustering algorithms identified similar customer patterns:

<div align="center">

![Customer Segmentation Visualization](images/Visualising_segmentation.png)

*Figure 2: Customer Segmentation - Visualization of the 5 distinct customer segments based on Income and Spending Score*

</div>

### 🎯 High Income — High Spending Customers
**Potential premium customers and strong targets for loyalty programs.**

### 💡 High Income — Low Spending Customers
**Customers with purchasing potential that may benefit from personalized marketing.**

### ⭐ Low Income — High Spending Customers
**Customers who show strong purchasing engagement despite lower income.**

### 🛍️ Low Income — Low Spending Customers
**Customers who may respond better to cost-sensitive offers.**

### 📊 Moderate Income — Moderate Spending Customers
**Represents average customer behavior.**

## Comparison Between Algorithms

Although both methods work differently, they produced the same number of customer groups in this project, suggesting that the segmentation patterns within the data were relatively stable.

## Technologies Used

- **Python** - Programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Scikit-Learn** - Machine learning library
- **SciPy** - Scientific computing
- **Jupyter Notebook** - Interactive development environment

## Future Improvements

For future enhancements I could include:

- Include additional customer variables
- Test other clustering techniques
- Build an interactive dashboard
- Evaluate cluster quality metrics
- Deploy the analysis as a business analytics application

## Author

**Neo Mohlomi**  
*Data Scientist | Machine Learning Enthusiast*

---

<div align="center">

⭐ If you found this project helpful, please consider giving it a star!

</div>
