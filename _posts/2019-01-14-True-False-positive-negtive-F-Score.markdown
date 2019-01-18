---
layout: post
title:  "True False Positive Negative, Precision Recall and  F Score"
date:   2019-01-14 11:14:03 -0700
categories: probability/concepts
---

### What does True/False/Positive/Negetive means?

#### Positive/Negative means for your prediction whether your predcited result is the thing you intended or not?

#### True/False means for your prediction, is your prediction correct or not?
#### True Positive and True Negative:
You have a model to predict **DOGS** in the pictures.  Dogs are what your model love,  So whenever your modle predict it is a dog, it will be <b>POSITVIE</b>.  For one object in the picture,your model predicts the object is a dog and in real world it is a dog, and your model is correct,right?  So, it is a TRUE. Also it is POSITIVE because your prediction is a dog, animals your modle like.  That is where **True Positive** comes from.
Similiarly, True Negative means your model predict something not a dog and in real world it is not a dog.  Your model corrects again, it is a True prediction.  And also a Negative prediction because it is not a dog.

<!-- ### Type I error and Type II error
#### False Positive is Type I error. False Negative is Type II error
Still dog prediction.  False Positive, false means your prediction is not correct.  There are two situations here.  One is your prediction is a dog but in real world it is a cat.  This is incorrect prediction so it is False.  Also your model predicts it as a dog so it is Positive.  Another one is your prediciton is not a dog (negative), but there is a dog there(False).  This is False Negative.
#### Why boring have different names for this two error?
It seems the influence of this two kinds of error are different.  Type I error (False Positive) usually have less impact on Type II error(False Negtive).  For example, you suspect yourself have cancer after a long and tired coding, so you go to buy some test papers to test yourself.  Those papers fails the test(False). And there are two situations here: Type I: you test paper result say you have cancer (Positive) and you went to a big hospital to do some other tests,  after you get out of the hospital you swear to the God and happily went to Hawaii.  Type II: you test paper say you don't have this disease(Negative) and you happily went to Hawaii....
Most people may want to have a type I error rather than a type II error. -->
### Precision vs recall
#### Start from the fomular
$\{precision=TP/(TP + FP)\}$
$\{recall=TP/(TP + FN)\}$
\precision=\frac{TP}{TP+FP}
$\{precision=TP/(TP + #Type I error)\}$
$\{recall=TP/(TP + #Type II error)\}$

$\{precision=TP/(For your model, all positive predition)\}$
$\{recall=TP/(In real world, all positive there)\}$

<!-- ### why should we care about such defination?
    You want to build a model to predict a very rare disease. In real world 99% people will not have this disease. With long and hard work, you built this model and it has 97% accuracy. 100 diseast people come, this will tell 97 people they have disease, and rest 3 are ok.
    Another guy build another model only predict the people are OK. If 100 disease people come, it will predict none of them have this disease. But in real world, 99% people will not have this disease and only 1% person may have,  this model seems better than the previous one.
    To envalue this two models we can caculate the precision and recall.
    In real world,10000 people came, on average there is 100 people have this disease, and 9900 are ok.
    For the first one:
    precision=97/(97+) -->




