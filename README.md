KMeans is an unsupervised machine learning algorithm. No target variable is present, no sampling is possible and no predictions are made. In KMeans, K stands for no. of clusters and it is a hyperparameter. User needs to choose the appropriate value of K. Clusters will be formed based on similarity among data points by using the Euclidean distance principle. I have worked on the mall dataset and used the elbow plot here, where the k value on x-axis and ssd (sum square distance) value on y-axis is plotted. Whichever k value corresponds to a point on the plateau effect curve, such that before that point, there is a steep decline in slope and after that point, the curve is on the verge of becoming stable, that k value will be selected. 

Clusters formed will have a centroid and the centroid is the mean of the cluster values. These iterations continue with clusters formed at each iteration until the cluster points stop flowing from one cluster to another and that their centroid/mean becomes stable & constant. 

Once this stage is achieved, we say that the convergence is successful and Kmeans is completed. Labels are then assigned to the datapoints based on the clusters to which they belong which can actually help in selective targeting and informed decision making for businesses. 


I have also built the model on Hierarchial/Agglomerative Clustering for the same mall dataset and using the scatterplot am able to visualize those clusters getting a clear cut idea about what has been performed.

