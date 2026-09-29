# Customer Segmentation using K-Means

## Project Overview

The **Customer Segmentation Project** uses the **K-Means clustering algorithm** to group customers into different segments based on their **Annual Income** and **Spending Score**.

The project demonstrates how Python and unsupervised machine learning can be used to understand customer behavior and identify meaningful customer groups for business analysis.

## Objectives

* Load and explore customer data.
* Check the dataset structure, missing values, and duplicate records.
* Analyze customer demographics and spending patterns.
* Standardize the data using `StandardScaler`.
* Determine the appropriate number of clusters using the Elbow Method.
* Perform customer segmentation using K-Means clustering.
* Evaluate the clustering using the Silhouette Score.
* Analyze the characteristics of each customer segment.
* Visualize customer segments.
* Export the final segmentation results to CSV files.

## Dataset

The project uses the **Mall Customers dataset**.

The main columns used for segmentation are:

| Column                 | Description               |
| ---------------------- | ------------------------- |
| Age                    | Age of the customer       |
| Annual Income (k$)     | Customer's annual income  |
| Spending Score (1-100) | Customer's spending score |

The project performs segmentation using:

* `Annual Income (k$)`
* `Spending Score (1-100)`

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* K-Means Clustering
* Google Colab / Jupyter Notebook

## Project Workflow

```text
Load Dataset
     ↓
Data Exploration
     ↓
Data Cleaning Checks
     ↓
Exploratory Data Analysis
     ↓
Feature Selection
     ↓
Data Standardization
     ↓
Elbow Method
     ↓
K-Means Clustering
     ↓
Silhouette Score
     ↓
Customer Segmentation
     ↓
Business Insights
     ↓
Export Results
```

## Data Exploration

The project checks:

* Number of rows and columns
* Dataset columns
* Missing values
* Duplicate records
* Descriptive statistics

It also visualizes:

* Customer distribution by gender
* Age distribution
* Annual income distribution
* Spending score distribution

## K-Means Clustering

The selected features are:

```text
Annual Income (k$)
Spending Score (1-100)
```

The features are standardized using `StandardScaler`.

The **Elbow Method** is used to determine the number of clusters, and the project applies **5 clusters** using K-Means.

## Customer Segments

The project identifies five customer segments:

1. **Average Customers**
2. **High-Value Customers**
3. **Young High-Spending Customers**
4. **High-Income Low-Spending Customers**
5. **Low-Income Low-Spending Customers**

## Business Insights

### Average Customers

* Largest customer segment with 81 customers.
* Customers have moderate income and moderate spending scores.
* Regular offers and loyalty programs can help maintain engagement.

### High-Value Customers

* Contains 39 customers.
* Customers have high annual income and high spending scores.
* Premium offers and personalized promotions can be used for customer retention.

### Young High-Spending Customers

* Contains 22 customers.
* Customers have relatively lower income but high spending scores.
* Trend-based products, discounts, and digital marketing may attract this group.

### High-Income Low-Spending Customers

* Contains 35 customers.
* Customers have high income but low spending scores.
* Personalized offers and targeted campaigns could encourage higher engagement.

### Low-Income Low-Spending Customers

* Contains 23 customers.
* Customers have lower income and low spending scores.
* Budget-friendly products and discounts may be suitable for this group.

## Model Evaluation

The project evaluates the clustering using the **Silhouette Score** to measure how well the customers are separated into clusters.

## Visualizations

The project includes visualizations for:

* Customer distribution by gender
* Age distribution
* Annual income distribution
* Spending score distribution
* Elbow Method
* Customer segmentation using K-Means
* Number of customers in each cluster
* Number of customers in each segment
* Income vs. spending score by customer segment

## Output Files

The project generates:

```text
customer_segmentation_results.csv
customer_segmentation_final.csv
```

These files contain the customer data along with their assigned clusters and segments.

## Conclusion

The Customer Segmentation Project successfully groups customers into five distinct segments using the **K-Means clustering algorithm**.

The segmentation is based on customers' annual income and spending score and helps identify different customer behaviors. These segments can support targeted marketing strategies, personalized offers, customer engagement, and business decision-making.

Overall, this project demonstrates the practical application of **Python, Pandas, Scikit-learn, Matplotlib, and Seaborn** for customer analytics and unsupervised machine learning.

## Author

**Bala Bhargavi**
