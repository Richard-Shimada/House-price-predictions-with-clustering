# Housing Price Predictions

### Exploratory Data Analysis:

![image](https://github.com/Richard-Shimada/House-price-predictions-with-clustering/blob/main/Data/bar_graphs.png)


1) Cluster 3 has the highest average sale price, Clusters 1 and 2 are lower but similar to each other, and finally Cluster 0 has the lowest average sale price.

2) The typical metrics of Total Square feet, average bedrooms, and average bathrooms follow this same pattern seen in sale price.

3) One exception is Cluster 1 - these homes have a similar average Sale Price as Cluster 2 despite being smaller and having fewer bedrooms and bathrooms. By drilling down, I discovered that Cluster 1 has the largest deck and enclosed porches on average which helps explain the higher Sales Price.


![image](https://github.com/Richard-Shimada/House-price-predictions-with-clustering/blob/main/Data/lmplot.png)


1) Cluster 3 has the largest 2nd floors that are increasing with newer builds. Cluster 3 also comprises the majority of new homes with larger 2nd floors. 

2) On the other hand, the average size of the 2nd floor for Clusters 0-2 are similar and have not changed much over time.

3) Cluster 0 is distinguished in that Cluster 0 houses tend to be older.

4) Cluster 1 is unique in that most of these homes are newer builds with smaller 2nd floors than Cluster 3.

5) Cluster 2 is distinct in that it has the most homes with no 2nd floor as indicated by the 0 values.


## RMSE of tuned model:

![image](https://github.com/Richard-Shimada/House-price-predictions-with-clustering/blob/main/Data/RMSE_tuned_model.png)


