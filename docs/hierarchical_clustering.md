# Hierarchical clustering method

Ward's method is a commonly used agglomerative hierarchical clustering method that seeks to minimize the variance within clusters when merging them.

When using Ward's method, the height of each branch in the dendrogram represents the increase in the sum of squares that results from merging the two clusters that are connected by that branch. The higher the branch, the greater the increase in the sum of squares, and therefore the greater the dissimilarity between the clusters being merged.

In Ward's method, the height of the branches is calculated as the squared Euclidean distance between the means of the two clusters being merged. This means that the distance between two clusters is proportional to the sum of squares of the differences between the values of the variables in the two clusters.

By examining the dendrogram, you can determine how many clusters are appropriate for your data by selecting a height threshold that best suits your needs. You may choose to cut the dendrogram at a certain height to form different numbers of clusters, depending on your research questions.

Dendrogram with a 1.3 clustering level:
![hc_clevel](/docs/static/hc.png)