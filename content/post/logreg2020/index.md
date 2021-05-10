---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Logistic Regression"
subtitle: ""
summary: "Logistic Regression as Neural Network"
authors: []
tags: ["data science", "machine learning"]
categories: []
date: 2020-11-26T13:44:25+01:00
lastmod: 2020-11-26T13:44:25+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
### Logistic Regression as Neural Network

Logistic Regression is used to predict the probability for a certain event to occur or a certain class to be true. 
The event is assigned a probability (= value between 0 and 1).

Logistric Regression can be interpreted as neural network without hidden layer and a logistic (e.g. sigmoid) activation function. 
The number of input nodes is determined by the number of features. The number of classes to predict determines the number of output nodes. 
Thus, we differentiate between binary (or binomial) and multinomial regression.

#### Binary Linear Regression
<img src="/post/binary_linreg.png" width="350" alt="binary linear regression">

#### Binary Logistic Regression
<img src="/post/binary_logreg.png" width="350" alt="binary logistic regression">

#### Multinomial Logistic Regression
<img src="/post/multinomial_logreg.png" width="350" alt="multinomial logistic regression">