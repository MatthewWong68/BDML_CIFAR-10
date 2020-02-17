# BDML_CIFAR-10
Performing Supervised Learning on CIFAR-10 dataset

# Data
The CIFAR-10 dataset can be donwloaded at https://www.cs.toronto.edu/~kriz/cifar.html

# Introduction
In this report, we will compare 2 learning algorithms using the given CIFAR-10 dataset. We will study the time used, percentage accuracy and with more different angles of the classifier.

# Method
Since the labels of the data are given, so we will use the supervised learning classifications. The methods used are Support Vector Machine (SVM) and Neural Networks. 

# Results (included in notebook)
We can observe that Neural Networks have a better accuracy. On the other hand, Support Vector Network has a slightly lower accuracy, but using less time than Neural Networks.

Moreover, we discovered that ships are often classified as airplane or automobile. Cats and deer are often classified as bird. Since ships are built by human, they usually have sharp edges, same as automobile and airplane. Therefore, the above problem occurs. The animals also have the same case. Cats, deer, dogs have ears which are also above the head. Thus, the machine learning algorithm may classify them wrongly since their similarities.

In addition, the confusion matrix shows Neural Networks are better than SVM in classifying houses and trucks. Neural Networks got 6% or more accurate than SVM in these 2 classes. However, Neural Networks have a worse predication on classifying automobile compare to SVM. Neural Networks classified 11% of automobile as a ship and another 11% as a truck while SVM got only 0.1% for both.


# Conclusion
To conclude, different classifiers have their advantages. In order to choose the best fit algorithm for a specific project, we need to understand their benefits and drawbacks of the classifier
