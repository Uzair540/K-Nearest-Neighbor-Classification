# K-Nearest Neighbor Classification
## Implementing Machine Learning Algorithm : K Nearest Neighbor Classification on the data-set of Social Network Advertisement
### A Gentle Introduction…
The k-NN algorithm is among the simplest of all machine learning algorithms. The input consists of the k closest training examples in the feature space while the output depends on whether k-NN is used for classification or regression:
In k-NN classification, the output is a class membership. An object is classified by a majority vote of its neighbors, with the object being assigned to the class most common among its k nearest neighbors (k is a positive integer, typically small). If k = 1, then the object is simply assigned to the class of that single nearest neighbor.
In k-NN regression, the output is the property value for the object. This value is the average of the values of its k nearest neighbors

#### HOW DOES THE ALGORITHM WORK?
Step.1)Choose the number K of neighbours
Step.2)Take the K nearest neighbours of the new data point, according to Euclidean Distance
Step.3)Among these K neighbours, count the number of data points in each category
Step.4)Assign the new data point to the category where you counted the most neighbors
