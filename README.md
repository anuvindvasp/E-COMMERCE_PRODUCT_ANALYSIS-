# E-COMMERCE PRODUCT ANALYSIS
![ciobulletin-amazon-gains-ecommerce-market](https://github.com/user-attachments/assets/fac242bf-ada5-4629-bd90-43b3f9eda8bb)


## INTRODUCTION

This project focuses on leveraging data science techniques to analyze e-commerce product data(Amazon), with the goal of uncovering market trends and customer preferences. 
And also, techniques to enhance the company’s product offerings and marketing strategies.

The process includes web scraping, data cleaning, data storage in a relational database, performing analysis, unsupervised learning for clustering similar products, supervised learning for classification, and hyperparameter tuning for performance optimization. 


## WORK FLOW

### Web Scraping ⛓️‍💥
* Extracted fields: Product Name, Price, Rating, Number of Reviews
 
### Data Cleaning 🧹
* Handled missing or null values by removing them
* Converted data types for consistency
* Applied normalization and standardization techniques to prepare data for clustering
  
### Data Storage 📥
* Created a SQLite database engine
* Data frame stored in the database

### Exploratory Data Analysis (EDA) 📊
* Created visualizations to explore the distribution of product prices and ratings
* Conducted analysis to identify patterns and correlations between price and customer ratings
 
### Unsupervised Learning ⚒️
* Used Clustering (KMeans) to group similar products
* Applied the Elbow Method to determine the optimal number of clusters (k) for effective segmentation
  
### Supervised Learning 🔩
* model is trained on a labeled dataset
* Algorithm used:
  ○ Logistic Regression
  ○ Decision Trees
  ○ Random Forest
  ○ Support Vector Machines (SVM)
  ○ K-Nearest Neighbors (KNN)

### Hyperparameter Tuning ⚙️
* demonstrated Random Search
* Tuned the best model

### Dataset :
HTML dataset from e-commerce website Amazon

## Conclusion
* This end-to-end project provided critical insights into the workings of a complete data science pipeline applied to real-world e-commerce product data
* Identified top-performing product segments through data analysis
* Discovered how ratings and reviews affect pricing and product popularity
* Demonstrated how data science can solve real business problems with scalable, deployable solutions.
