# Machine Learning

Machine Learning is the field of study that gives computers the capability to learn without being explicitly programmed. It is a method of data analysis that automates analytical model building. It is a branch of artificial intelligence based on the idea that systems can learn from data, identify patterns and make decisions with minimal human intervention.

> Machine Learning is the science of getting computers to learn and act like humans do, and improve their learning over time in autonomous fashion, by feeding them data and information in the form of observations and real-world interactions.

# Types of Machine Learning

<img src="https://miro.medium.com/max/1200/1*FUZS9K4JPqzfXDcC83BQTw.png" width="550" height="400" />

 - Supervised Learning 
 - Unsupervised Learning
 - Reinforcement learning
 
 ---

## Supervised Learning

> Supervised learning is the machine learning task of learning a function that maps an input to an output based on example input-output pairs. It infers a function from labeled training data consisting of a set of training examples.

Supervised machine learning algorithms are designed to learn by example. The name “supervised” learning originates from the idea that training this type of algorithm is like having a teacher supervise the whole process. Supervised learning is the most popular paradigm for machine learning. It is the easiest to understand and the simplest to implement.
 
 
#### Why is Supervised Learning used?

Supervised learning allows collecting data and produce  data output from the previous experiences.
Helps to optimize performance criteria with the help of experience.
Supervised machine learning helps to solve various types of real-world computation problems.

#### Application of supervised learning 
 - Spam Filtration
 - Sentiment Analysis
 - Speech Recognition 

### Types of Supervised Learning
 - Regression
 - Classification

#### Regression

> Regression is a statistical method used in finance, investing, and other disciplines that attempts to determine the strength and character of the relationship between one dependent variable (usually denoted by Y) and a series of other variables (known as independent variables).

Regression analysis is the primary technique to solve the regression problems in machine learning using data modelling. It involves determining the best fit line, which is a line that passes through all the data points in such a way that distance of the line from each data point is minimized.

# Linear Regression

> Linear regression is one of the most basic types of regression in machine learning. The linear regression model consists of a predictor variable and a dependent variable related linearly to each other.

In case the data involves more than one independent variable, then linear regression is called multiple linear regression models. 

> y=mx+c+e  is used to denote the linear regression model

where m is the slope of the line, c is an intercept, and e represents the error in the model.

## Preparing Data For Linear Regression

Linear regression is been studied at great length, and there is a lot of literature on how your data must be structured to make best use of the model.

As such, there is a lot of sophistication when talking about these requirements and expectations which can be intimidating. In practice, you can uses these rules more as rules of thumb when using Ordinary Least Squares Regression, the most common implementation of linear regression.

Try different preparations of your data using these heuristics and see what works best for your problem.

### Linear Assumption

Linear regression assumes that the relationship between your input and output is linear. It does not support anything else. This may be obvious, but it is good to remember when you have a lot of attributes. You may need to transform data to make the relationship linear (e.g. log transform for an exponential relationship).

### Remove Noise

Linear regression assumes that your input and output variables are not noisy. Consider using data cleaning operations that let you better expose and clarify the signal in your data. This is most important for the output variable and you want to remove outliers in the output variable (y) if possible.

### Remove Collinearity

Linear regression will over-fit your data when you have highly correlated input variables. Consider calculating pairwise correlations for your input data and removing the most correlated.

### Gaussian Distributions

Linear regression will make more reliable predictions if your input and output variables have a Gaussian distribution. You may get some benefit using transforms (e.g. log or BoxCox) on you variables to make their distribution more Gaussian looking.
Rescale Inputs: Linear regression will often make more reliable predictions if you rescale input variables using standardization or normalization.


## Classification

Classification is a process of categorizing a given set of knowledge into classes,,it can be performed on both structured or not structured data.The process starts with predicting the class of given data points.The classes are often referred to as target,label or categories. The classification predicting modelling is the task of approximating the mapping function from input variables to discrete output variables.The main goal is to identify which class or category the new data will fall into.

---

## Unsupervised Learning

> Unsupervised learning works by analyzing the data without its labels for the hidden structures within it, and through determining the correlations, and for features that actually correlate two data items. It is being used for clustering, dimensionality reduction, feature learning, density estimation, etc.

**Now we will see why unsupervised learning is important for real world solving problem ?**

 - They find pattern which are previously unknown
 - Patterns help in categorization or finding association
 - They can detect anomalies & detects in the data
 - They work on unlabeled data which makes our work easier
 

Important clustering types are
 - Hierarchical clustering 
 - K-means clustering 
 - K-NN 
 - Principal Component Analysis
 - Singular Value Decomposition 
 - Independent Component Analysis
 
**Application of unsupervised learning**

 - Dimension reduction
 - Image compression
 - Anomaly detection

Written By **Allen Manoj**
### Connect with me at [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='20'>](https://www.linkedin.com/in/allenmanoj/) [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg' alt='twitter' height='20'>](https://twitter.com/allenmanoj17)
