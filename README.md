# Book-recommendation-system

![image](https://user-images.githubusercontent.com/102281845/190617328-da558ddd-837d-4b9d-afcd-d1a04194200f.png)
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
# Introduction

During the last few decades, with the rise of Youtube, Amazon, Netflix, and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys. In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries). Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective is to create a book recommendation system for users.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
# Data Pre-processing and EDA

In the given dataset after loading them proper data pre-processing has been done in all three given datasets where the null values are corrected with appropriate terms, then by using excellent visualizations many inferences are founded such as the age distribution of readers and we can see that people with the age group of around 30-40 years are higher compared to all other age groups, then we saw which rating people tend to give more and we founded that people usually give the rating of 8 more compared to other ratings, we also plotted the year of publication from 1950-2005 and we founded that there is a drastic increase from 2000-2005 in publication counts.    
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
# Modelling

By using collaborative filtering using K-Means we tried to analyze which book are most liked and also which authors are most liked using k-means clustering, for dimensionality reduction we used PCA, for the selection of K, we used silhouette analysis instead of elbow method for accurate results and we founded that for k=2 the silhouette score was higher compared to all other values,
we applied clustering using the obtained k value and also depicted the clustering in 3d for visual analysis and later by analyzing each cluster we obtained the results such as which were the top 5 books and authors and which items should be recommended to the users according to their places has been completed and analyzed as per required by the objective.


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
# Conclusion
The main objective which was to create a book recommendation system for users has been successfully done.
With collaborative filtering using K-Means we have successfully obtained the results. 
The top 5 books and authors for each type of audience have been obtained successfully for specific user types. 
By using two clusters we have obtained the results and they are clearly explained using respective visualisations.

