
# **Assignment 1**

**Machine Learning**

**Holden C**

# Q1. (1)

$J = \sum_{i=1}^{n} (x_i - b)^2$

$dJ/db = d/db \sum (x_i - b)^2$

$dJ/db = \sum 2(x_i - b)(-1)$

$dJ/db = -2 \sum (x_i - b)$

The minimum of J occurs where the derivative with respect to b is equal to 0.

$-2 \sum (x_i - b) = 0$

$\sum x_i - nb = 0$

$\sum x_i = nb$

$b = (1/n)\sum_{i=1}^{n} x_i$

The optimal value of $b$ that minimizes $J$ is the average of all $x_i$.
