## Data-set examination

### Marketing Department

![marketing](https://user-images.githubusercontent.com/57914889/88213545-7fc44d80-cc76-11ea-8b6a-d7204b1621a4.png)

### AIM:
Marketing is crucial for the growth and sustainability of any business, Marketers can help build the company’s brand, engage customers, grow revenue, and increase sales.
This case requires to develop a customer segmentation to define marketing strategy. The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

Link to dataset : https://www.kaggle.com/arjunbhasin2013/ccdata
  
### Apporach:
* Understood how to leverage the power of data science to perform market segmentation and perform exploratory data analysis and visualize customers data set.

* Understood intuition behind K Means clustering algorithms.

* Learned how to find the optimal number of clusters using the Elbow Method.

* Applied k-means algorithms and cycle learn to perform market segmentation understand the theory.

* Understood the intuition behind principle component analysis.

* Applied PCA to perform dimensionality reduction using real world data set.


![Capture33](https://user-images.githubusercontent.com/57914889/88211969-1ba08a00-cc74-11ea-9e76-8eb6eafdc2d8.PNG)


# Theory

## Principal component analysis (PCA)
Given a collection of points in two, three, or higher dimensional space, a "best fitting" line can be defined as one that minimizes the average squared distance from a point to the line. The next best-fitting line can be similarly chosen from directions perpendicular to the first. Repeating this process yields an orthogonal basis in which different individual dimensions of the data are uncorrelated. These basis vectors are called principal components, and several related procedures principal component analysis (PCA).

![pca](https://user-images.githubusercontent.com/57914889/88213553-818e1100-cc76-11ea-9a52-f2d57796837b.png)

## K-means clustering
k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells. It is popular for cluster analysis in data mining. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances. For instance, better Euclidean solutions can be found using k-medians and k-medoids.

![kmeans](https://user-images.githubusercontent.com/57914889/88213538-7e932080-cc76-11ea-99b1-2410b8a6762f.png)

# Working enviroment
Jupyter Notebook
  - Keras 2.1.6
  - Python 3
  - sklearn 0.19.2
  - Matplotlib
  - Seaborn
