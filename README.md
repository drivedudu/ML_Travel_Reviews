# ML_Travel_Reviews

#### By: Alejandra Pimentel, Danielle Steede, Eduardo Silva, Ishwarya Sundhararajan 

In this project, we utilize sophisticated machine learning algorithms to analyze large volumes of user travel reviews from Google. By revealing unique patterns in travel preferences, we aim to craft custom-tailored itineraries that align with the specific interests and needs of our customers, significantly enhancing their travel experiences.

## Table of Contents
1. [Objectives](#objectives)
2. [Data Sources](#data)
3. [Analysis Approach](#analysis)
4. [Results](#results)
5. [Conclusion](#conclusion)
6. [Links](#links)

## Objectives
- To predict travel preferences based on user feedback.
- To identify significant patterns and trends in travel data.
- To enhance user experience by providing personalized travel recommendations and itenaries.
- To learn and apply various machine learning techniques including supervised learning and feature engineering.

## Data Sources
The analysis is conducted on a travel dataset, which includes various features extracted from user feedback. The data is cleaned, preprocessed, and used to train and evaluate our machine learning models.
- Dataset: [Travel Review Ratings](https://archive.ics.uci.edu/dataset/485/tarvel+review+ratings)

## Analysis Approach
The analysis was performed using the following approaches:

Clustering Analysis
- Objective: Identify distinct traveler profiles based on user feedback.
- Method: K-means clustering.
- Evaluation: Determination of the optimal number of clusters (k) using the Elbow Method and  Silhouette Score.
  
Feature Engineering
- Objective: Enhance the dataset with meaningful features that improve model performance.
- Methods: Creation of new features from existing data, such as sentiment analysis of user feedback and categorization of travel activities.

Heatmap Analysis
- Objective: Visualize the correlation between different features.
- Method: Generation of heatmaps to identify strong and weak correlations, aiding in feature selection.
  
Itinerary Recommendations
- Objective: Generate personalized travel itineraries for each identified cluster.
- Method: Analysis of key preferences for each cluster to create tailored itineraries.

## Results
Our clustering analysis revealed distinct patterns in user preferences, allowing us to create tailored itineraries for different traveler profiles. These personalized recommendations can significantly enhance the user travel experience by aligning activities with their specific interests.

## Conclusion
This project provided valuable insights into travel preferences by leveraging machine learning techniques. The clustering analysis helped us understand different traveler profiles and craft personalized itineraries. Future work could involve refining the clustering models and exploring additional data sources to further improve the accuracy of the recommendations.


## Links
- Trello Board: [Trello Board](https://trello.com/invite/b/bnJTW6Vc/ATTI0610ff103d980bb6dc4709845efb6e11ABDFA25E/ml-project-digital-nomads)
- Presentation: [Google Slides Presentation](https://docs.google.com/presentation/d/19IMmLf8ibvodeUkBlr3ySBNneP-CGkiZS6yPm03bXhc/edit?usp=sharing)
