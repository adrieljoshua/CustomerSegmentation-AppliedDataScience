## Customer Segmentation using DataScience
**Project Title:** Customer Segmentation with Data Science

**Problem Statement:** Implement data science techniques to segment customers based on their behaviour, preferences, and demographic attributes, enabling businesses to personalize marketing strategies and enhance customer satisfaction.

**Dataset Link:** https://www.kaggle.com/datasets/akram24/mall-customers

<div align=center>Phase 1: Problem Definition and Design Thinking</div>

**Problem Definition:** The problem is to implement data science techniques to segment customers based on their behavior, preferences, and demographic attributes. The goal is to enable businesses to personalize marketing strategies and enhance customer satisfaction. This project involves data collection, data preprocessing, feature engineering, clustering algorithms, visualization, and interpretation of results.

**Design Thinking:**

**Data Collection:** Collect customer data, including attributes like purchase history, demographic information, and interaction behavior.

**Data Preprocessing:** Clean and preprocess the data, handle missing values, and convert categorical features into numerical representations.

**Feature Engineering:** Create additional features that capture customer behavior and preferences, such as total spending, frequency of purchases, etc.

**Clustering Algorithms:** Apply clustering algorithms like K-Means, DBSCAN, or hierarchical clustering to segment customers.

**Visualization:** Visualize the customer segments using techniques like scatter plots, bar charts, and heatmaps.

**Interpretation:** Analyze and interpret the characteristics of each customer segment to derive actionable insights for marketing strategies.

<div align=center>Phase 2: Innovation</div>

**Problem Explanation:** You own the mall and want to understand the customers, like those who can easily converge [Target Customers], so that sense can be given to the marketing team and the strategy can be planned accordingly.

**Columns used for the Customer Segmentation Dataset:**

- Customer ID:
 A unique identifier for each customer. 

- Gender:
 Gender helps identify the customer's biological sex.

- Age: 
It indicates the customer’s age group.

- Annual income:
 It represents the customer’s yearly earnings.

- Spending Score:
 Spending score reflects the customer’s tendency to spend money.

**Libraries used:**
Pandas
Numpy
Matplotlib and Seaborn
Os

Explained about training, testing and metrics used for accuracy check.

<div align=center>Phase 3: Development Part 1</div>

3.1 Dataset:  https://www.kaggle.com/datasets/akram24/mall-customers

 This dataset is used in retail and marketing analytics to understand customer behavior and preferences. It includes the following types of information:
Customer ID
Gender
Age
Annual Income
Spending Score

A "customer ID" (Customer Identification) is a unique identifier assigned to each customer in a database or system. It is used to distinguish one customer from another and track their activities, purchases, interactions, and other relevant information.

Gender is one of the key factors in segmenting customers into distinct groups. For example, stores may tailor their product offerings and marketing strategies differently for male and female customers.

 Age is a fundamental factor for segmenting customers into groups. Different age groups may have distinct preferences, shopping behaviors, and income levels. For example, retailers often distinguish between teenagers, young adults, middle-aged individuals, and seniors.

The annual income of mall customers is a crucial demographic variable that helps businesses and mall operators understand the spending capacity and shopping preferences of their customer base.

Spending score is a metric used to assess and quantify a customer's purchasing behavior within a mall.


3.2  Loading the dataset

3.3  Preprocessing Dataset

3.4  Performing different analysis


<div align=center>Phase 4: Development Part 2</div>

Performing K-Means Clustering on given data

K-Means Clustering: 


K-Means Clustering is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters. Here K defines the number of predefined clusters that need to be created in the process, as if K=2, there will be two clusters, and for K=3, there will be three clusters, and so on.


Cost Function: Inertia is a metric used to evaluate the quality of a clustering algorithm, particularly the K-means algorithm. It measures the sum of squared distances between each data point and its assigned centroid. In other words, it measures how far the data points are from their assigned cluster centers.


The K-means algorithm tries to minimize the inertia by iteratively updating the cluster centers until the inertia cannot be reduced any further. A lower inertia value indicates that the clusters are more compact and well-separated, while a higher inertia value indicates that the clusters are more spread out and overlapping.





