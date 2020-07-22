# Business-Projects

![business](https://user-images.githubusercontent.com/57914889/88213527-7c30c680-cc76-11ea-90df-e193e5c1616d.jpg)

These projects are aimed at applying data science techniques to the following 4 departments through different datasets from kaggle: 
(1) Human Resources
(2) Marketing
(3) Sales
(4) Public Relations

* Human Resources Department: Develop an AI model to Reduce hiring and training costs of employees by predicting which employees might leave the company.
* Marketing Department: Optimize marketing strategy by performing customer segmentation.
* Sales Department: Develop time series forecasting models to predict future product prices.
* Public Relations Department: Develop Natural Language Processing Models to analyze customer reviews on social media and identify customers sentiment.

## Learning Outcomes
* Develop an AI model to Reduce hiring and training costs of employees by predicting which employees might leave the company.
* Develop time series forecasting models to predict future product prices.
* Optimize marketing strategy by performing customer segmentation
* Develop Natural Language Processing Models to analyze customer reviews on social media and identify customers sentiment.

## Data-set examination

### Human Resources Department

![human](https://user-images.githubusercontent.com/57914889/88213534-7dfa8a00-cc76-11ea-8793-074a063bcad2.jpg)

### AIM: 
Hiring and retaining employees are extremely complex tasks that require capital, time and skills, Small business owners spend 40% of their working hours on tasks that do not generate any income such as hiring. Develop a model that could predict which employees are more likely to quit. 

Link to dataset : https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset

### Apporach:
* First understood how to leverage the power of data science to reduce employees turnover and transform human resources department.

* Second understood the theory behind logistic regression and random forest classifiers.

* Train logistic regression classifier and random forest classifier models using sklearn.

* Apply Sigmoid functions to obtain probability.

* Load and manipulate data set using Panda's dataframe.

* Develop a function in Python and apply it to pandas data frame.

* Perform exploratory data analysis using Matplotlib and seaborn libraries.

* Plot kernel density plots, box plots and count plots.

* Convert categorical variables into dummy variables.

* Learn understand the theory and intuition behind artificial neural networks and apply them to perform classification tests.

* Evaluate classification models and present results using confusion matrix and classification reports and understand the difference between precision recall and F1 score.


![Capture66](https://user-images.githubusercontent.com/57914889/88211970-1c392080-cc74-11ea-9553-f42b161a3c9a.PNG)

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

### Sales Department

![sales](https://user-images.githubusercontent.com/57914889/88213559-8357d480-cc76-11ea-86b6-7e84c7d2be9d.jpg)

### AIM:
We are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

Link to dataset : https://www.kaggle.com/c/rossmann-store-sales/data
  
### Apporach:
* Understood how to leverage the power of data science to predict future product sales.

* Understood the theory and intuition behind time series forecasting models.

* Understand the concept of additive regression.

* Listed the advantages of Facebook prophet.

* Applied Facebook prophet to predict future sales using real world data set. 

* Predict future Weekly monthly and yearly trends.

![Capture22](https://user-images.githubusercontent.com/57914889/88211954-15121280-cc74-11ea-9ca3-7be544d49882.PNG)

### Public Relations Department

![pubrela](https://user-images.githubusercontent.com/57914889/88213556-82bf3e00-cc76-11ea-9e41-6c3b6c5c9bd3.jpg)

### AIM:
This dataset consists of a nearly 3000 Amazon customer reviews (input text), star ratings, date of review, variant and feedback of various amazon Alexa products like Alexa Echo, Echo dots, Alexa Firesticks etc. for learning how to train Machine for sentiment analysis.

Link to dataset : https://www.kaggle.com/sid321axn/amazon-alexa-reviews/kernels
  
### Apporach:
* Learned how to leverage the power of data science to deal with text data perform exploratory data analysis and learn how to create world cloud visualizations.

* Learn the basics of natural language processing.

* Apply natural language processing toolkit.

* Apply feature extraction using count vectors to understand the theory behind naive based classifiers.

* Understand the difference between likelihood prior probability and marginal likelihood.

* Train a logistic regression classifier to make predictions on encoded text data.

![Capture31](https://user-images.githubusercontent.com/57914889/88211962-180d0300-cc74-11ea-98c9-769323804763.PNG)

# Theory

## Logistic regression
Logistic regression is the appropriate regression analysis to conduct when the dependent variable is dichotomous (binary).  Like all regression analyses, the logistic regression is a predictive analysis.  Logistic regression is used to describe data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent variables.

![Logit](https://user-images.githubusercontent.com/57914889/88213542-7e932080-cc76-11ea-8455-a5e857996453.png)

## Random forest
The random forest is a supervised learning algorithm that randomly creates and merges multiple decision trees into one “forest.” The goal is not to rely on a single learning model, but rather a collection of decision models to improve accuracy. The primary difference between this approach and the standard decision tree algorithms is that the root nodes feature splitting nodes are generated randomly.

![randomfor](https://user-images.githubusercontent.com/57914889/88213558-82bf3e00-cc76-11ea-8d20-b34823138d48.jpg)

## K-means clustering
k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells. It is popular for cluster analysis in data mining. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances. For instance, better Euclidean solutions can be found using k-medians and k-medoids.

![kmeans](https://user-images.githubusercontent.com/57914889/88213538-7e932080-cc76-11ea-99b1-2410b8a6762f.png)

## Neural network
A neural network is a series of algorithms that endeavors to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates. In this sense, neural networks refer to systems of neurons, either organic or artificial in nature. Neural networks can adapt to changing input; so the network generates the best possible result without needing to redesign the output criteria. The concept of neural networks, which has its roots in artificial intelligence, is swiftly gaining popularity in the development of trading systems.

![neural](https://user-images.githubusercontent.com/57914889/88213547-7fc44d80-cc76-11ea-998c-27b859fe13f2.png)

## Principal component analysis (PCA)
Given a collection of points in two, three, or higher dimensional space, a "best fitting" line can be defined as one that minimizes the average squared distance from a point to the line. The next best-fitting line can be similarly chosen from directions perpendicular to the first. Repeating this process yields an orthogonal basis in which different individual dimensions of the data are uncorrelated. These basis vectors are called principal components, and several related procedures principal component analysis (PCA).

![pca](https://user-images.githubusercontent.com/57914889/88213553-818e1100-cc76-11ea-9a52-f2d57796837b.png)

## Natural language processing (NLP)
Natural language processing (NLP) is a subfield of linguistics, computer science, information engineering, and artificial intelligence concerned with the interactions between computers and human (natural) languages, in particular how to program computers to process and analyze large amounts of natural language data.Challenges in natural language processing frequently involve speech recognition, natural language understanding, and natural language generation.

![nlp](https://user-images.githubusercontent.com/57914889/88213549-80f57a80-cc76-11ea-9163-44d4ffbdb731.jpg)

## Facebook Prophet
Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

![prophet](https://user-images.githubusercontent.com/57914889/88213554-8226a780-cc76-11ea-9a84-b3242fe4b7a8.png)

# Working enviroment
Google Colab
Jupyter Notebook
  - Keras 2.1.6
  - Python 3
  - sklearn 0.19.2
  - NLTK
  - Facebook Prophet
  - Matplotlib
  - Seaborn
  
