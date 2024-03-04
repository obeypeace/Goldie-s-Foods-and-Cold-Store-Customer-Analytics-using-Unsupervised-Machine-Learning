# Goldie-s-Foods-and-Cold-Store-Customer-Analytics-using-Unsupervised-Machine-Learning
Welcome to the Goldie’s Foods and Cold Store Customer Personality Analysis project repository! In this project, we aim to leverage data science techniques to gain insights into customer behaviors, interests, and preferences. By analyzing customer demographics and purchasing patterns, we seek to segment customers effectively, enabling Goldie’s Foods and Cold Store to tailor marketing strategies and product offerings to individual preferences.

## Table of Contents
- [Project Objective](#Project-objective)
- [Data Scource](#data-source)
- [Data Processing](#data-processing)
- [Evaluation Metrices](#evaluation-metrices)
- [Key Insights](#key-insights)
- [conclusion and recommendations](#conclusion and recommendations)

## Project Objective
The goal of this project is to perform Exploratory Analysis and Customer Personality Analysis using unsupervised learning techniques such as Dimensionality Reduction (PCA) and Clustering. By segmenting customers based on their purchasing behavior and demographic information, we aim to identify groups with similar characteristics. These insights will empower Goldie’s Foods and Cold Store to develop targeted marketing campaigns, personalized product recommendations, and improve overall customer engagement.

## Data Source
The data for this project consists of two main datasets: People and Products. The People dataset contains information about customers, including their unique identifier, demographic details, enrollment date, and purchasing history. The Products dataset includes details on the amount spent by customers on various product categories over the past two years.
  
## Data Processing
Prior to analysis, the data will undergo preprocessing steps to handle missing values, standardize features, and address any inconsistencies. Exploratory Data Analysis (EDA) techniques will be employed to gain insights into the distribution of variables, identify correlations, and detect any anomalies in the data.

## Evaluation Metrices
For evaluating the effectiveness of our customer segmentation model, we employ several metrics and techniques. First, we utilize dimensionality reduction via PCA to reduce the feature space and enhance interpretability. We then apply the elbow method, aided by the KElbowVisualizer, to determine the optimal number of clusters for K-means clustering. Additionally, we leverage the silhouette score to assess the cohesion and separation of clusters, providing insights into their quality and distinctiveness. By integrating these evaluation techniques, we ensure robust and meaningful segmentation results, enabling Goldie’s Foods and Cold Store to effectively target and engage with their diverse customer base.

## key Insights
Customer Segmentation Analysis:
Demographics:
•	The highest proportion of customers falls within the elder age group (>= 51), while the youth (<21) represent the lowest customer segment.
•	Graduates constitute the majority of customers (50.4%), followed by postgraduates (47.2%), with undergraduates making up the smallest portion (2.4%).

Cluster Insights:
Cluster 1:
•	High-income earners and spenders across all product categories.
•	Represents 17.2% of customers.
•	Non-parents with a family size of 2.
•	Prefer purchasing from the store's catalogue.
•	Often accept offers in the 1st, 2nd, and 3rd campaigns.
•	Predominantly composed of elders (>= 51) and adults (26-40).

Cluster 4:
•	High-income earners and spenders.
•	Accounts for 11.4% of customers.
•	Non-parents with no children and a family size of 1.
•	Frequent shoppers with the shortest recency.
•	Least likely to make discounted purchases or visit the store's website.
•	Mostly accept offers in the 2nd and last campaigns.
•	Predominantly composed of elders (>= 51) and adults (26-40).

Cluster 2:
•	Low-income earners and spenders.
•	Represents 24.1% of customers.
•	Parents with a family size of 2.
•	Prefer purchasing gold and wine.
•	Accept offers in the 3rd and last campaigns.
•	Predominantly composed of elders (>= 51) and old adults (41-50).
•	Second-highest recency and website visitation rate.

Cluster 0:
•	Largest customer segment (29.7%).
•	Low-income earners.
•	All are parents, married, with a family size of 3.
•	Longest recency, highest discounted purchases, and most website visits.
•	Lowest spenders overall, but prefer purchasing gold.
•	Mostly accept offers in the last campaign.
•	Predominantly composed of old adults (41-50) and elders (>= 51).

Cluster 3:
•	Average to high-income earners and spenders.
•	Represents 17.7% of customers.
•	Mostly parents with a family size of 3.
•	Prefer purchasing directly from stores, especially wine and gold.
•	Accept offers in the 4th and 2nd campaigns.
•	Predominantly composed of elders (>= 51) and old adults (41-50).


## Conclusion and Recommendations
In conclusion, the Customer Personality Analysis provides valuable insights into customer segmentation, enabling Goldie’s Foods and Cold Store to enhance customer targeting and engagement. Recommendations based on the analysis may include refining marketing strategies, optimizing product offerings, and improving customer service to drive sales and foster long-term customer loyalty.
