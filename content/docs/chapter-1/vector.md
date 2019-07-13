# Chapter I Mathematics Fundamentals

In this chapter, we will discuss some basic mathematics knowledge that you need to know for further study.

## Scalar, vector, matrix, and tensor.

A *vector* is an ordered finite list of numbers. Vectors are usually written as vertical arrays, surrounded by square or curved brackets, as seen below.

$$\begin{pmatrix}-1.1 \\\ 0.0 \\\ 3.6 \\\ -7.2 \end{pmatrix} or \begin{bmatrix}-1.1 \\\ 0.0 \\\ 3.6 \\\ -7.2 \end{bmatrix}$$

Sometimes, they are written as numbers separated by commas and surrounded by parentheses. As seen below.

$$(-1.1, 0.0, 3.6, -7.2)$$

Vector is often denoted by a lowercase symbol \\(a\\). We can get the element (also known as entries, coefficients or components) of a vector by the index, and the \\(i\\)-th element of the vector \\(a\\) is therefore denoted as \\(a_i\\) where the subscript \\(i\\) is an integer index of the vector. (Obviously, \\(0<i<n\\).)

If two vectors have the same size, and more importantly, each of the corresponding entries is the same, then the two vectors are equal, which is denoted as \\(a=b\\).

A *scalar* is a number or a value. In most applications, scalars are real numbers. We usually use an italic lowercase symbol to denote a scalar. For example, \\(\textit{a}\\) is a scalar.

A *matrix* is a rectangular array, which means it is a 2-dimensional data table at the same time. Matrix is a collection of items that have the same feature and character. In a matrix, a column indicates a feature, and a row indicates an item. Matrix is usually denoted as a capital letter, \\(A\\) for example.

A *tensor* is an array with more than 2 dimensions. Generally, if the elements of an array are distributed in a regular grid with several dimensions, we would call it a *tensor*. We use a capital letter to denote a tensor, same with the matrix. \\(A\\) for example. An element in a tensor is denoted as \\(A_(i,j,k)\\).

**Relations between them**

*Scalar* is a 0-dimensional tensor. *Vector* is a 1-dimensional tensor. For example, with a scalar, we could get the length of a rod, but we cannot know the direction of this rod.

With a vector, we could know both the length and direction of a rod.

With a tensor, we may be able to know both the length and direction of a rod, and we could even know more about the rod. (for example, the degree of deflection)

### Relations between tensor and matrix.

From the aspect of algebra, the matrix is a generation of the vector, the matrix is a 2-dimensional table. \\(n\\)-dimensional is a so-called \\(n\\)-dimensional table. Noted that this is not a strict definition of the tensor. 

For the aspect of geometry, a matrix is a geometric sense value. It does not change with the coordinate transformation of the frame of reference. the vector has this feature too.

The tensor can be represented by a \\(3\\)x\\(3\\) matrix or an \\(n\\)x\\(n\\) matrix.

A scalar can be regarded as a \\(1\\)x\\(1\\) matrix while a vector with \\(n\\) items can be regarded as \\(1\\)x\\(n\\) matrix.

### What will happen if I multiply a matrix and a tensor?

*A*. You can only multiply an \\(m\\)x\\(n\\) matrix and a \\(n\\) items vector. Then you will get a \\(m\\) items vector. The key to this is regarded each row of the matrix as a vector, and multiply the given vector.

For example, If you are going to multiply the following:

$$\begin{bmatrix}1, 2 \\\ 0.0, 1 \\\ 3.6, 3 \\\ -7.2,2 \end{bmatrix}$$ and $$\begin{bmatrix}-1.1 \\\ 0.0 \\\ 3.6 \\\ -7.2 \end{bmatrix}$$

### Norm.

Norm is a measure of its magnitude or length.

In mathematics, a norm is ***a function that assigns a strictly positive length or size to each vector in a vector space***. There are many different types of norms for a vector or a matrix. For example,

*L1-norm*: $L_1$ norm is also called the taxicab norm or the manhattan norm. This is because it uses manhattan distance as the length.

$ L_1(v) = ||v||_1 $, and

$ L_1(v) = |a_1| + |a_2| + ... + |a_n| $

For example, the $L_1$ form of vector $[1,2,3]$ is:

$ L_1(v) = 1 + 2 + 3 = 6$

*L2-norm*: $L_2$ norm is also called Euclidean norm since it uses euclidean distance.

$ L_2(v) = ||v||_2 $, and

$ L_2(v) =   \sqrt{a_1^2 + a_2^2 + ... + a_n^2} $

*Ln-norm*: 

###  What is the positive definite matrix?

###  How to judge if a matrix is the positive definite matrix?

###  What is eigenvalue? What is eigenvector? What is eigenvalue decomposition?

###  What is the singular value? What is singular value decomposition?

###  What are the differences between singular value and eigenvalue? and what about their decomposition?

###  What is the probability?

###  What are the differences between variable and random variable?

###  What are the common probability distribution?

###  What is the conditional probability?

###  What is joint distribution? What is marginal distribution? What are their relations?

###  What is the chain rule for conditional probability?

###  What is independence and conditional independence?

###  What is the expectation? What is variance? What is covariance? What is the correlation coefficient?