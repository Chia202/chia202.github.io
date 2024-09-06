---
layout: page
permalink: /blogs/2024-09-05-RNN-zh/index.html
date: 2024-09-05
title: 循环神经网络
---

# 循环神经网络

常见的神经网络结构有多层感知机（MLP）、卷积神经网络（CNN）和循环神经网络（RNN）。MLP 和 CNN 是相对简单的，而 RNN 在处理序列数据时有独特的优势、也是比较难理解的模型。本文将介绍 RNN 的基本概念和应用。

## RNN 的定义

假设我们现在有一个序列数据，比如一句话“I want to eat an apple”，我们把每个词看作一个时间点，那么这个序列就可以看作一个长度为 $6$ 的时间序列，为了能够输入到神经网络中，我们还要把每个词转换成向量，这里我们先跳过词向量化的过程，放在后面再仔细讲，假设我们已经得到了一个长度为 $T$ 的序列 $(\mathbf{x_1}, \mathbf{x_2}, \cdots, \mathbf{x_T})$，其中 $\mathbf{x_t}$ 是一个向量，$t$ 表示时间点。

$$
\begin{align}
y_t = f(\mathbf{x_t}, \mathbf{h_{t-1}})
\label{eq:rnn}
\end{align}
$$

## RNN 的构建、训练与预测

## 长短期记忆网络

## 应用——图片标题生成
