# Chapter II Machine Learning Fundamentals

In this chapter, we will discuss some *basic knowledge about machine learning*

### What is Machine Learning?



###  What is supervised learning? What is semi-supervised learning? What is weakly-supervised learning? What is unsupervised learning?

Supervised Learning is where you have both the input and output variables, and Unsupervised Learning is where you only have the input data and no corresponding output data.

In supervised learning, you use an algorithm to learn a mapping function from the input to the output: \\(Y=f(x)\\). With the mapping function, you will be able to approximately predict the output variables for new input data that do not exists in training dataset.

It is called *Supervised* learning because we know the correct output of input data, and thus, our algorithms are able to correct the predictions on the training data. The process of this kind of machine learning is like a teacher supervising the process.

Controversially, the goal for unsupervised learning is to learn more about the data itself, by model the structure or distribution of the data. There is no correct outputs, and therefore we are unable to correct the algorithms and predictions. In other words, algorithms are left to their own devises to discover the structure of the data.

###  What is regression? What is classification?

Regression and Classification are categorized under the supervised learning, in other word, both of them are a specific task of supervised learning.

Regression is about predicting a label and classification is about predicting a quantity. In other word, the result of regression are continuous quantities while the result of classification are discrete class labels.

Let's take an example about the housing. There are two different algorithms, one is for predicting the type of house and another is for estimating the prices. According to our definition above, the former algorithm is predicting a discrete class (the type of house) and the latter is predicting a continuous number or quantity (the price of house). Therefore, the former is classification while the latter is regression.

### What is clustering? What is association?

Clustering, as its name shows, is grouping a set of objects in such a manner that objects in the same group are more similar than to those objects belonging to other groups.

Association rule learning is about finding associations and relations amongst items within large databases. It is intended to identify strong rules discovered in databases using some measures of interestingness. The ultimate goal is to help a machine mimic the human brain's feature extraction and abstract association (which we will explain later for these terms) capabilities from new un-categorized data.

Clustering is about grouping data points according to their similarities while association is about discovering some relationships between the attributes of those data points.

### What is the relation between machine learning, supervised learning/unsupervised learning and regression/classification?

As seen below:

![Relations Between Machine Learning and etc.](http://i66.tinypic.com/55jzvp.jpg)

###  What are the steps for a supervised learning?

For supervised learning, there are some general steps to solve the given problem.

* Determine the type of training data. Before doing anything else, you need to decide what kind of data is to be used as a training set. 

* Prepare the training set, validation set and test set.

* Determine the input feature representation of the learned function.

* Determine the structure of the learned function and corresponding learning algorithm.

* Complete the design.

* Evaluate the accuracy of the learned function.

###  What is the learned function 

###  What is multi instance learning?

###  What is K-Nearest-Neighbor or KNN? What is SVM?  

###  What is neural network? What are the types of difference neural networks?

###  What is local optimum? What is global optimum?

> One day, Plato asked Socrates: what is love? Socrates said: I ask you to cross this piece of rice fields, to pick one of the largest and most golden wheat back, but there is a rule: you can not go back, and you can only pick once. So Plato went on. After a long time, he was back with empty hand. Socrates ask him why come back with empty? Plato said: When I walked in the field, I had seen a few particularly special bright wheat, but I always think there may be bigger and better in front, so there is no pick; but when I continue walking, see the wheat, always feel it is not better than the previous which i had seen, so I did not pick anything finally. Socrates said meaningfully: this is love.

###  What are the advantages and disadvantages of common classification algorithms, such as Bayes, Decision Tree or SVM?

###  Can the accuracy be a great and comprehensive measurement for classification?

###  If not, what are the measurements for classification algorithm? and what are for regression algorithm?

###  What is a good enough classification algorithm?

###  What is logistic regression? What is Poisson regression?

###  What are the differences between logistic regression and naïve bayes?

###  What are the differences between linear regression and logistic regression?

Linear Regression: \\(f(x)=\theta ^{T}x=\theta _{1}x _{1}+\theta _{2}x _{2}+...+\theta _{n}x _{n}\\)

Logistic Regression: \\(f(x)=P(y=1|x;\theta )=g(\theta ^{T}x)\\)，where，\\(g(z)=\frac{1}{1+e^{-z}}\\)

###  What is cost function? Why we need it?

###  Why cost function can work?

###  Why cost function have to have a lower bound? or why most cost functions cannot be minus?

###  What are some common cost function?

###  Why we use cross entropy to replace quadratic cost?

###  What is loss function? Why we need it?

###  What are some common loss function?

###  Why we use log loss function in logistic regression?

###  How log loss function measures the loss?

###  What is gradient decent? why we need it?

###  What are the advantages and drawbacks of gradient decent?

###  Still unclear, is there any graph or description?

###  What are the steps of gradient decent?

###  How to optimize gradient decent?

###  What is random gradient decent and batch gradient decent? What are the differences between them?

###  What is computation graph? How to calculate its derivatives?

###  What is Linear Discriminant Analysis or LDA?

###  What are the steps of LDA?

###  What is PCA (Principal Component Analysis)? and its steps?

###  What are the differences between LDA and PCA?

###  What are the advantages and drawbacks of LDA and PCA?

###  Why we need to reduce the dimension?

###  What is Kernelized Principal Component Analysis or KPCA?

###  For machine learning models, what are the usually used measurements?

###  What are the relations between bias, error, variance and covariance?

###  What is empirical and generalization error?

###  What is overfitting? What is underfitting? How to solve them respectively?

###  What is the purpose of cross validation?

###  What is k-fold cross validation?