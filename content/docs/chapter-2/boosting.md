# Boosting

### What is AdaBoost?

AdaBoost is the abbreviation of *Adaptive Boosting*. It is proposed by *Yoav Freund* and *Robert Schapire* in 1995. As it focuses on the classification problem, so we use this as an example. The AdaBoost method is a classifier consists of many *weak classifier*, and it aims to convert and combine these weak classifiers into a *strong classifier* and use this strong classifier to solve the classification problem. This process can be denoted as:

$$ F(x)=\sum_{i=1}^n w _i f _i (x) $$

where \\(f _i\\) stands for the \\(i\\)-th weak classifier and the \\(w _i\\) represents the corresponding weight.

It is clear that the adaptive boosting method is exactly the weighted combination of \\(n\\) weak classifiers.

Now let's see its procedure.

Given a dataset containing n points, some of them are -1 (negative), while others are 1 (positive). In the beginning, we assume all the weights equal to \\(\frac{1}{n}\\). It can be denoted as \\(w _i=\frac{1}{n}, i=1,...,n\\).

**Step 1.** Find several weak classifiers to the dataset (simply use linear regression or etc.), and select one with the lowest weighted classification error.

**Step 2.** Calculate the weight for the \\(i\\)-th weak classifier:

**Step 3.** 

It is adaptive because it can adapt to wrongly classified objects, and the adapted parameters could be used to train the next classifier.

### What is GDBT (a.k.a Gradient Boosting Decision Tree)?

GDBT is a *Decision Tree* trained by Gradient Boosting.

### What is Gradient Boosting?

Gradient Boosting is a machine learning algorithm that can be used to handle multiple tasks, including regression, classification, ranking and etc.

As in its name, gradient boosting is the combination of gradient descent and boosting. 