# Business-Project

The project aimed at applying data science techniques to the following 4 departments: 
(1) Human Resources
(2) Marketing
(3) Sales
(4) Public Relations

* Human Resources Department: Develop an AI model to Reduce hiring and training costs of employees by predicting which employees might leave the company.
* Marketing Department: Optimize marketing strategy by performing customer segmentation
* Sales Department: Develop time series forecasting models to predict future product prices.
* Public Relations Department: Develop Natural Language Processing Models to analyze customer reviews on social media and identify customers sentiment.

## Learning Outcomes
* Develop an AI model to Reduce hiring and training costs of employees by predicting which employees might leave the company.
* Develop time series forecasting models to predict future product prices.
* Optimize marketing strategy by performing customer segmentation
* Develop Natural Language Processing Models to analyze customer reviews on social media and identify customers sentiment.

## Data-set examination

### Human Resources

Hiring and retaining employees are extremely complex tasks that require capital, time and skills.
“Small business owners spend 40% of their working hours on tasks that do not generate any income such as hiring”.
develop a model that could predict which employees are more likely to quit. 
sample of the dataset: 
JobInvolvement
Education
JobSatisfaction
PerformanceRating
RelationshipSatisfaction
WorkLifeBalance

* First understood how to leverage the power of data science to reduce employees turnover and transform human resources department.

* Second understood the theory behind logistic regression and random forest classifiers train in logistic regression classifier
and random forest classified models using cycle learn apply Sigmoid functions to obtain probability load and manipulate data set
using Panda's dataframe develop a function in Python and apply it to append this data frame perform exploratory data analysis using Matplotlib and seaborn 
libraries plot kernel density estimate plots or K the E4 short box plots and count plots convert categorical variables into dummy variables.

* Learn understand the theory and intuition behind artificial neural networks and how to apply them to
perform classification tests evaluate classification models and present results using confusion matrix
and classification reports and understand the difference between precision recall and F1 score.

## Pre-processing dataset
The training and testing images have been processed by using OpenCV libraries that extracted the plant seedling only and removed the background noise. The filtering process depending on the HSV values, retaining green HSV parameters and convert back to RGB format, which means only the green colour remains and the rest of the colour are removed.

Then the training and testing dataset have been normalized by dividing 255.0 to limit the pixel values within 0 to 1 and the labels are one-hot-encoded.

## Convolutional neural network (CNN)
CNN is a good choice while dealing with the image data. Designed CNN architecture based on personal experience, knowledge and, most important, the machine learning community and forum helps. The time spent a lot on tuning the model hyper-parameters in order to achieve higher accuracy and lower residual for model training. So that the model predicting the unseen data will have a higher chance to obtain the correct result. Of course, there is plenty of other powerful CNN available such as AlexNet, ResNet and more, those networks may also suitable applying in this data-set.

# Opinion
This Kaggle competition is challenging, because deep learning was totally new to me. I had to google numerous resources to gain intuition and understanding of how does deep learning work. Even though deep learning network is quite hard to master,it could solve the real world problems is exciting and motivating!

# Working enviroment
Google Colab
  - Keras 2.1.6
  - Python 3
  - Opencv 3.4.3
  - sklearn 0.19.2
