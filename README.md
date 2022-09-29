# Finding Donors for CharityML

in this project, we will employ several supervised algorithms of our choice to accurately model individuals' income using data collected from the 1994 U.S. Census. You will then choose the best candidate algorithm from preliminary results and further optimize this algorithm to best model the data. our goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000. This sort of task can arise in a non-profit setting, where organizations survive on donations. Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with. While it can be difficult to determine an individual's general income bracket directly from public sources, we can (as we will see) infer this value from other publically available features.

# Project Summary

Our model is supposed to predict if the person's income is more than 50K per year or not based on some data, i.e., age, education, country, etc. This will help the charity detect which people are more likely to donate. Our model employs an algorithm known as AdaBoostClassifier, which simply takes our data set and tries to train and learn by a technique known as decision trees, in which leaves represent class labels and branches represent conjunctions of features that lead to those class labels. To simplify it, it tries plotting these data points in a graph and attempting to find a function to divide them into two portions, "<=50K" and ">50K," based on some features and criteria, After training our model, it will be able to predict any other new data. It just takes some information about the person like age,education, country of origin, etc. as inputs. The output will be 0 or 1, where 1 refers to the person whose income is over 50K/year and 0 is not.




