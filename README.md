# Personal_vs_Promotional

## Objective
Create a binary classifier that can classify email into personal email or promotional email base on the metadata extracted from the email. 
Datasets used in this project is from kaggle competition Personal vs Promotional.
https://www.kaggle.com/c/csaisummerschool/overview

## Motivation
Nowadays, Email is one of the most important ways for us to communicate. It could be a disaster if we missed an important email. For example, a email from our boss. But, the emails we receive are not all that important. As a matter of fact, more than half of the emails I received are promotional emails from various stores. Therefore, I believe it is very convenient if we could classify our emails with the help of technology.

## Difference from class mail filter
Most classic mail filter use an algorithm called Naive Bayes Classifier. In Naive Bayes Classifier, it uses bag of words features to identify spam e-mail. However, in this project, we are not given the text content of the emails in our traning data or test data. Therefore, we need to use differenct features, such as organisation of the sender, number of images in the mail body, number of urls in the mail body etc. After building our model, we can see how well our model did compare to the Naive Bayes Classifier.