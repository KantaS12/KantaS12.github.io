---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Linear Regression From Scratch"
date: 2025-03-01
published: true
labels:
  - Linear Regression
  - Python
  - PCA
summary: "A Python implementation of linear regression without using scikit-learn's built-in regression models. This project demonstrates the fundamental concepts of linear regression through a stock price prediction model for Apple Inc. (AAPL)."
---

Even though it is important to know how to implement linear regression for different tasks, it is also important to understand the backbone of the implementation. In this project, I used Yahoo API to predict the AAPL stock prices. I used various techniques including PCA which reduces feature space while maintaing the important components. I also used gradient descent with regularization to maintain bias and variation while lowering the overal cost function. 

It might be easy to understand what linear regression is, it is really hard to make it as accurate as possible which takes a lot of time and evaluation. The goal for this was to learn different techniques to limit bias and variation while performing linear regression. There might not be much evaluation which is an important part of this and could be improved far more than this. However, this project was just for learning experience while using real life stock values.

Here is some code that illustrates gradient descent that uses l1 and l2 regularization:

```cpp
for _ in range(iterations):
    y_pred = x_train_reduced @ w + b
    
    dw = (-2/n) * x_train_reduced.T @ (y_train - y_pred) + lambda_l1 * np.sign(w) + 2 * lambda_l2 * w
    db = (-2/n) * np.sum(y_train - y_pred)
    
    w -= LR * dw
    b -= LR * db
```

You can learn more in my GitHub!(https://github.com/KantaS12/self_regression_model/blob/main/README.md).
