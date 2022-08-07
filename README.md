# K-Means-Clustering:
<p> K-Means clustering is an unsupervised learning algorithm. There is no labeled data for this clustering, unlike in supervised learning. K-Means performs the division of objects into clusters that share similarities and are dissimilar to the objects belonging to another cluster. 

The term ‘K’ is a number. You need to tell the system how many clusters you need to create. For example, K = 2 refers to two clusters. There is a way of finding out what is the best or optimum value of K for a given data. </p>
#### Source: "https://www.simplilearn.com/tutorials/machine-learning-tutorial/k-means-clustering-algorithm"


# Explanation of the Project:

<p> In this project, data from World Bank is obtained and different indicators are analyzed for different countries. My task was to divide the regions, based on these indicators. For intuition, normally when applying k-means, you have to draw scatter ploot between different features, and based on that, one selects a 'K' value for the algorithm. </p>

<p> What I did was I took the year as an x-axis, and on the y-axis, I took one other feature, for instance, GDP per capita in this case. So it is obvious that the GDP will be different for different regions. And from the plot, it seemed good to go for K=4, which will divide the data into 4 clusters. Then I labeled each region with a cluster obtained after applying the algorithm. And analyzed the data for different timeframes.</p>


<p> The optimized value of K can be obtained by applying a for loop for given ranges of K, and through "Elbow method", optimum value of K can be selected. Also, one other indicator Silhoutte Score gives whether the data is divided into proper clusters or not.</p>

<p> K-means clustering is an important unsupervised learning algorithm. It is also used in ecommerce data for customer segmentation, etc. Feel free to clone this repo and apply K-means clustering yourself. </p>


