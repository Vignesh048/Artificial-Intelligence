## 1. Implementation of Naive Bayes Classifier:

The code consists of EDA, preprocessing using seaborn and Sckit-learn libraries and Naive Bayes is implemented without using Sckit-learn library.
Gaussian Naive Bayes is applied for numerical variable and direct formula is used for categorical variable.
With standardization and without standardization, the model is compared both the data gave same accuracy.
So standardization has no effect on Gaussian Naive Bayes Model.
The model is compared with Sckit-learn's GaussianNB model and found that accuracy is more for the model implemented than Sckit-Learn's model.
The reason is GaussianNB takes the categorical features also a normally distributed feature.

## 2. K- means Clustering
### Solving the given problem which involves implementation of K- means clustering Algorithm
#### 1) Create synthetic data
a) Use the random number generator numpy.random.randn to to create 5 clusters of size (100,2) each. The cluster
centers are [(0,0), (0,2), (1, 1),(2,0),(2,2)].
b) Visualize the data using scatter plot from matplotlib package.

#### 2) Clustering using K-mean algorithm:
a) In real data, we do not know the number of clusters can be there. Hence, we will perform
b) Consider there are K number of means. Assign data points randomly to each cluster from your synthetic data. Compute
the mean of each cluster.
c) Find the distance of each datapoint from all the K clusters. Assign the datapoint with the label of its nearest mean center.
(Use euclidian distance computation method).
d) Repeat the steps a and b untill the stopping criteria met.
e) Stopping criteria: change in average of the K means is less than a threshold (e.g., 0.5. Appropriately change the
threshold by verifying whether yours clusters are converging or not).
f) Visualize your output for K = 2, 3,...,10.


## 3. Search Methods Artificial-Intelligence
The code has implementation of Breadth first search, Depth First Search, Uniform Cost Search and A* Search.
The final code is about creating a own tree using the user input
