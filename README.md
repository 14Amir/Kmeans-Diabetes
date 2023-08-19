# Kmeans-Diabetes
Kmeans clustering on 'Diabetes' dataset  
First, let's take a look at the difference between classification and clustering:
Classification means separating labeled data into separate groups with their own labels.
But in our data clustering, they don't have labels, and we don't need to separate the training and testing sections, and the goal is to separate the data into separate groups.
In this article, to achieve these goals, after importing the data into the implementation with the help of the Pandas library, we got to know a little more about the data. (The size of the data, the features in the data, the number of different values available for each feature, etc.) Then we illustrated the data and examined the various graphs related to the features of these data. In the following, we put the pre-processing of the model on the agenda and also tried to add an additional feature to the existing features to make the model work better. Finally, after numericalizing the non-numerical values in the data as well as standardization, we modeled and performed classification and clustering by decision tree and kmeans algorithms and evaluated, analyzed and compared the obtained results.
