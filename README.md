# SmartCart: E-commerce Customer Segmentation

## About the Project

SmartCart is a machine learning mini-project focused on understanding e-commerce customers through unsupervised learning.

The project explores customer demographics, spending habits, purchase channels, website activity, and campaign response. Using clustering, it groups customers with similar behaviour and examines how these groups differ.

## Problem Statement

An e-commerce platform may use the same marketing and engagement approach for all customers, despite differences in their purchasing behaviour and engagement.

SmartCart explores customer data to identify meaningful segments that could help a business better understand its customers and consider more targeted marketing and retention strategies.

## Project Objectives

- Explore customer demographics and purchasing behaviour.
- Perform exploratory data analysis (EDA).
- Prepare and engineer features for clustering.
- Apply dimensionality reduction using PCA.
- Explore cluster selection using the Elbow Method and Silhouette Score.
- Apply K-Means and Agglomerative Clustering.
- Interpret the resulting customer groups.

## Project Workflow

1. Data inspection and preprocessing
2. Missing-value handling and outlier filtering
3. Feature engineering
4. Exploratory data analysis and visualization
5. Categorical encoding and feature scaling
6. Principal Component Analysis (PCA)
7. Cluster evaluation
8. K-Means and Agglomerative Clustering
9. Cluster comparison and interpretation

## Methods and Libraries

**Methods**
- Principal Component Analysis (PCA)
- K-Means Clustering
- Agglomerative Clustering (Ward linkage)
- Elbow Method (WCSS)
- Silhouette Score

**Libraries**
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Kneed

## Customer Segments

The notebook uses four clusters and analyzes their average characteristics.

| Cluster | Summary |
|---|---|
| Cluster 0 | Partnered customers with comparatively lower income and spending, more children on average, and more monthly website visits. |
| Cluster 1 | Partnered customers with comparatively higher income and spending, frequent catalog and store purchases, and fewer children on average. |
| Cluster 2 | Customers living alone with comparatively lower income and spending, more children on average, and more monthly website visits. |
| Cluster 3 | Customers living alone with comparatively higher income and spending, frequent catalog and store purchases, and the strongest campaign response among the clusters. |

These profiles are exploratory interpretations of the cluster averages. Cluster IDs are arbitrary labels and should not be treated as fixed customer categories.

## Key Observations

- The clusters show differences in customer income and total spending.
- Higher-spending groups also show more catalog and in-store purchasing activity.
- Monthly website visits alone do not indicate higher spending.
- Campaign response differs between the identified segments.

## Repository Contents

- `smart_cart.ipynb` — notebook containing the analysis and clustering workflow.
- `README.md` — project overview and documentation.


## Limitations

- The results depend on the features, preprocessing choices, and clustering configuration.
- PCA reduces dimensionality and may discard information.
- Cluster descriptions are interpretations of observed averages, not validated business rules.
- This is an exploratory notebook project; it has not been deployed as a production application.

## Future Improvements

- Evaluate clustering stability and compare additional clustering approaches.
- Refine the preprocessing and evaluation workflow.
- Build an interactive interface for exploring customer segments.
- Validate potential marketing actions against actual business outcomes.

## Author

**Vivek Pansuriya**  
Artificial Intelligence and Machine Learning  
L.D. College of Engineering, Ahmedabad
