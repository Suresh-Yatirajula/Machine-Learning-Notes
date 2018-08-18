# Machine-Learning-Notes

Links:

https://github.com/AI6-Bangalore-Chapter/2018-cycle-2/blob/master/Roadmap.md
http://www.fast.ai/
https://www.slideshare.net/TessFerrandez/notes-from-coursera-deep-learning-courses-by-andrew-ng
https://github.com/mbadry1/DeepLearning.ai-Summary


Activation Functions - Sigmoid, Tanh and Relu
Idea --> Code --> Experimentation --> Idea

In classical ML Data Set (Before 2012):
We chop off data into 3 different layers: 
1. Training Data Set (60%)
2. Development Data Set (20%)
3. Testing Data Set (20%) - Should be used only once.

In Deep Learning Era (Millions of data points):
1. Training Data Set (98%)
2. Development Data Set (1%)
3. Testing Data Set (1%)

How do we divide the data set, Randomize the data set.

Bias and Variance:

1. If the model is not able to classify correctly, three scenarios:
a. Under Fitting (High Bias)
b. Just Fitting
c. Over Fitting. THis may be adopting even to the nose, meaning outliers. The training accruracy is exteremly high, but in real scenario the accuracy is low, then we get to know this is overfitting.

How do we determine whether the model is underfitting or overfitting:
Based on Error Rates.
Compare the Training Error with Test Error.

Our model may suffer from:
High Variance (Underfitting)
High Bias
High Bias and High Variance
Low Bias and Low Variance

The objective is to find a model with Low Bias and Low Variance.


What can we do if we are suffering from High Bias:
a. Use Bigger Network
b. Train Longer

What can we do if we are suffering from High Variance: (Over Fitting)(happens frequently)
a. Do Regularization

Regularization:
1) L1 regularization 
2) L2 regularization (Frequently Used)
Can we use both L1 and L2- what is elastic net
what is euclodian norm in regularization?
3) drop out











Data Cleaning:
Pre deep learning era, we use to come across all above three problems. In deep learning era, we generally get over fitting problem only.

Once the model is ready and deployed to PROD. After the model is ready, if new data sets are coming, you can also do online learning (some engineering tric).


