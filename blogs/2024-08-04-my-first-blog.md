---
layout: page
permalink: /blogs/2024-08-04-my-first-blog/index.html
title: My First Blog
---

## Test formula

$$
\begin{align*}
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
\end{align*}
$$

## Test tag for formula

$$
\begin{align}
\int_{-\infty}^{\infty} \exp\left\{-\frac{x^2}2\right\} dx = \sqrt{2\pi}
\label{eq:gaussian}
\tag{1}
\end{align}
$$

We can refer to the formula \eqref{eq:gaussian}.

## Test tag for code

```python
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(-10, 10, 100)
y = np.exp(-x**2)

plt.plot(x, y)
plt.show()
```

## Test tag for image

![Klee](https://chia202.github.io/images/klee1.png)

## Test Footnote

This is a test footnote[^1].

[^1]: This is a test footnote.
