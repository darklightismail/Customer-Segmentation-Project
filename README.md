# Customer-Segmentation-Project

I contributed to the analysis of a database of customer data from a supermarket and their segmentation.
The implementation of classification algorithms in order to segmenting customers and analyzing its results.
The analysis is based on the “PYTHON” language.

# Exploratory Data Analysis :

![Figure_10](https://user-images.githubusercontent.com/47457939/183471067-a0f24948-f414-44de-ac2f-3b77ffa891dd.png)
![Figure_11](https://user-images.githubusercontent.com/47457939/183471071-843864bd-c198-4bb0-8205-63061b8a8b2c.png)
![Figure_1](https://user-images.githubusercontent.com/47457939/183471083-140138c6-9804-4dd7-8e0e-5a5c1e0f2008.png)
![Figure_2](https://user-images.githubusercontent.com/47457939/183471087-3d4a6a6a-f60a-4574-a792-905bd19f5612.png)
![Figure_3](https://user-images.githubusercontent.com/47457939/183471093-de9556be-a41c-4426-a194-f6cacfacd3fe.png)
![Figure_4](https://user-images.githubusercontent.com/47457939/183471102-87d37a42-741b-4e16-85c6-6ef4f3b822c0.png)
![Figure_7](https://user-images.githubusercontent.com/47457939/183471043-c73f3b45-c64d-4f14-bd1c-68af203ed995.png)
![Figure_8](https://user-images.githubusercontent.com/47457939/183471049-b5a84fc7-787d-43b0-99d9-f9a1fdf5f9a5.png)
![Figure_9](https://user-images.githubusercontent.com/47457939/183471050-acc4e1e3-ffb8-4929-b569-2056bc6dd98b.png)

# Implimentation of Clustering Algorithms :
  
# Kmeans Algorithm :

![Figure_13](https://user-images.githubusercontent.com/47457939/183472024-877a7550-5e80-4790-ab0b-93ddb7d75393.png)

- Elbow Method : 


The Elbow method runs k-means clustering on the dataset for a range of values for k (say from 1-10) and then for each value of k computes an average score for all clusters. By default, the distortion score is computed, the sum of square distances from each point to its assigned center.
When these overall metrics for each model are plotted, it is possible to visually determine the best value for k. If the line chart looks like an arm, then the “elbow” (the point of inflection on the curve) is the best value of k. The “arm” can be either up or down, but if there is a strong inflection point, it is a good indication that the underlying model fits best at that point.
We use the Elbow Method which uses Within Cluster Sum Of Squares (WCSS) against the the number of clusters (K Value) to figure out the optimal number of clusters value. 
WCSS measures sum of distances of observations from their cluster centroids which is given by the below formula.

![1_aSeXkf9At7WSbGy5s_d4vw](https://user-images.githubusercontent.com/47457939/183473211-a58503c8-4385-4a7d-9d96-b1fcdf6522c3.png)


![Figure_16](https://user-images.githubusercontent.com/47457939/183471841-67cd96a9-7977-45d4-b577-1b33a1c94c49.png)

# Hierarchic Clustering Algorithm :
![Figure_15](https://user-images.githubusercontent.com/47457939/183472634-8e7f326a-089f-45df-94de-eebe86efb01d.png)
![Figure_14 - Copie](https://user-images.githubusercontent.com/47457939/183472643-bbb377ce-8e44-42f7-8bf0-cbe06ba7af16.png)


# Cluster Analysis :

1. Cluster Orange - Balanced Customers:
They earn less and spend less. We can see people have low annual income and low 
spending scores, this is quite reasonable as people having low salaries prefer to buy less, 
in fact, these are the wise people who know how to spend and save money. The 
shops/mall will be least interested in people belonging to this cluster.
19
2. Cluster Blue - Pinch Penny Customers:
Earning high and spending less. We see that people have high income but low spending 
scores, this is interesting. Maybe these are the people who are unsatisfied or unhappy by 
the mall’s services. These can be the prime targets of the mall, as they have the potential 
to spend money. So, the mall authorities will try to add new facilities so that they can 
attract these people and can meet their needs.
3. Cluster Purple - Normal Customer:
Customers are average in terms of earning and spending An Average consumer in terms 
of spending and Annual Income we see that people have average income and an average 
spending score, these people again will not be the prime targets of the shops or mall, but 
again they will be considered and other data analysis techniques may be used to increase 
their spending score.
4. Cluster Red - Spenders:
This type of customers earns less but spends more Annual Income is less but spending 
high, so can also be treated as potential target customer we can see that people have low 
income but higher spending scores, these are those people who for some reason love to 
buy products more often even though they have a low income. Maybe it’s because these 
people are more than satisfied with the mall services. The shops/malls might not target 
these people that effectively but still will not lose them.
5. Cluster Green - Target Customers:
Earning high and also spending high Target Customers. Annual Income High as well as 
Spending Score is high, so a target consumer. we see that people have high income and 
high spending scores, this is the ideal case for the mall or shops as these people are the 
prime sources of profit. These people might be the regular customers of the mall and are 
convinced by the mall’s facilities.

# Result :
We have explored the five segments based on customers Annual Income and 
Spending Score which are reportedly the best factors/attributes to determine the segments 
of a customer in a Mall. They include; Pinch Penny Customers, Balanced Customers,
Target Customers, Spender and the normal customer. We can put Target Customers into 
some alerting system where SMS and emails can be sent to them on daily basis regarding 
the offers and discounts that they can get at the Mall; while the rest we can set once per 
week in a month for blast SMSs to notify them about our products.
Similarly, now we know customers behavior depending upon their Annual Income 
and Spending Score. There can be many marketing strategies applied for Customers on 
these Cluster Analysis. High income and High spending score customers are our target 
customers and we would always want to retain them as they give the most profit margin 
to our organization. High Income and Less spending score customers can be attracted 
with wide range of products in their life style demands and it might attract them towards 
the Mall Supermarket. Less Income Less Spending Score can be given extra offers and 
constantly sending them the offers and discounts will attract them towards spending. We 
can also have a cluster analysis done on what kind of products customers tend to buy and 
can make other marketing strategies accordingly. The data set did not have enough data 
to carry out more analytics on the same.
