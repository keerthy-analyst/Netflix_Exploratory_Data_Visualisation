# EDA ON NETFLIX DATA:

## Install necessary libraries required for the project:
``` python
Seaborn
Matplotlib
Wordcloud
Scikit-learn
Mlxtend
termcolor
```

#ABOUT THE PROJECT:

## Introduction:

Netflix is a popular online streaming platform with a wide variety of movies and TV shows. 
This EDA (Exploratory Data Analysis) project is focused on analyzing the Netflix dataset using Python's pandas,
seaborn, and matplotlib libraries. The goal is to gain insights into the Netflix data, and answer some interesting questions related 
to the movies and TV shows on the platform.

## Data:

The Netflix dataset used for this project was obtained from Kaggle. 
It contains information about movies and TV shows available on Netflix as of 2021. 
The dataset includes attributes such as title, director, cast, release year, rating, duration, and country of origin.

## Data Cleaning:

The dataset contained missing values that were handled by dropping any row containing a missing value. 
Some columns were also converted to the appropriate data type, and certain columns were split into multiple columns for better analysis.

# Exploratory Data Analysis:

The following questions were explored using the Netflix dataset:

What are the top genres of movies and TV shows on Netflix?
Which countries produce the most content on Netflix?
How has the number of movies and TV shows on Netflix changed over the years?
What are the most popular ratings on Netflix?
What is the distribution of movie durations on Netflix?

## Visualization:

The seaborn and matplotlib libraries were used to create various visualizations to support the EDA. 
Some of the plots created include bar charts, pie charts, countplots, and boxplots.

## Algorithm Used:

## Naive Bayes Classifiers Algorithm:
The Naive Bayes algorithm is a classification algorithm that is based on Bayes' theorem,
which states that the probability of an event occurring given some prior knowledge about the conditions related to the event.
This algorithm is commonly used in natural language processing and text classification problems.
In the Netflix EDA project, the Naive Bayes algorithm was used to classify movies and TV shows based on their rating. 
The ratings were classified as either "good" or "bad" based on a threshold value.
The algorithm was trained on a subset of the dataset, and then used to predict the rating of the remaining data.
The accuracy of the algorithm was then evaluated using various metrics, such as accuracy, precision, recall, and F1 score.

## K-Nearest Neighbor(KNN) Algorithm:
The K-Nearest Neighbor (KNN) algorithm is a classification algorithm that works by identifying the K closest training 
examples in the feature space and assigning the class label based on the majority vote of their neighbors. 
The value of K is a hyperparameter that can be tuned to improve the performance of the algorithm.


## Apriori Algorithm:
The Apriori algorithm is an unsupervised machine learning algorithm used for mining frequent itemsets and association rules. 
It works by generating candidate itemsets of increasing size based on the support threshold, and then pruning itemsets that 
do not meet the minimum support requirement. The resulting frequent itemsets are then used to generate association rules that
can be used for market basket analysis.
In the Netflix EDA project, the Apriori algorithm was used to find frequent itemsets of genres and countries.
This was done by setting a minimum support threshold and mining the dataset for itemsets that meet the requirement.
The resulting frequent itemsets were then used to generate association rules that can be used to gain insights into the relationships 
between genres and countries.

## View of Netflix Dashboard
![NETFLIX DASHBORAD](https://user-images.githubusercontent.com/115634164/229337906-51cf39c7-d4d0-48a6-99da-6a59744c96b8.png)

## Conclusion:
The Netflix EDA project provided insights into the movies and TV shows on Netflix. 
It was observed that Drama, Comedy, and Action are the top genres on the platform, with the United States producing the most content.
The number of movies on Netflix has increased significantly in recent years, with the 2010s being the decade with the most movie releases.
TV shows, on the other hand, have been more consistently released over time. 
TV-MA is the most popular rating on Netflix, and the majority of movies on the platform have a duration of 90-120 minutes.

Overall, the project demonstrated the power of exploratory data analysis in providing insights into large datasets,
and how visualizations can aid in communicating these insights.




