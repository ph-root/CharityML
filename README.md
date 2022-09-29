# Project Summary

Our model is supposed to predict if the person's income is more than 50K per year or not based on some data, i.e., age, education, country, etc. This will help the charity detect which people are more likely to donate. Our model employs an algorithm known as AdaBoostClassifier, which simply takes our data set and tries to train and learn by a technique known as decision trees, in which leaves represent class labels and branches represent conjunctions of features that lead to those class labels. To simplify it, it tries plotting these data points in a graph and attempting to find a function to divide them into two portions, "<=50K" and ">50K," based on some features and criteria, After training our model, it will be able to predict any other new data. It just takes some information about the person like age,education, country of origin, etc. as inputs. The output will be 0 or 1, where 1 refers to the person whose income is over 50K/year and 0 is not.


