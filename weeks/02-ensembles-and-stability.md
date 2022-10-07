---
layout: week
title: Week 02
doodle: /doodle.png
---

# Why are ensembles useful?

## Topics

This week's assignments will guide you through the following topics:
* I will add here an explanation for why ensemble averaging improves stability and the utility of margins.
* topic 2

## Tasks

Complete the following tasks:
* Download the newsgroups dataset
```py
from sklearn.datasets import fetch_20newsgroups
newsgroups_train = fetch_20newsgroups(subset='train')
newsgroups_test = fetch_20newsgroups(subset='test')
```
* Make the problem binary by defining assigning the label "1" to the politics-relatedd groups:
```
'talk.politics.guns',
 'talk.politics.mideast',
 'talk.politics.misc',
 'talk.religion.misc'
 ```
 * train a random forests with 100 trees using the training set (features = word appears/does not appear in the document).
 * For each example on the training set and test set compute the number of trees that predict 1 out of the 100, call this number the `score`.
 * partition the data into four according to train/test and true label 0/1
 * Generate a four histograms of the score: one for each of the four parts.
 * Check by hand a few of the test examples: 
    * Examples for which the score is close to 50.
    * Examples where the score is close to 100 but the true label is 0
    * Examples where the score is close to 0 but the true label is 1.
## Weekly Questions

Answer the following questions
1. Can you find examples where the assigned label is clearly wrong?
