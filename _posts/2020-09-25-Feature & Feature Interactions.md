---
title: Feature & Feature Interactions
categories: [dev]
comments: true
---


# 显式特征交互 and 隐式特征交互

存在两个特征xi, xj
若经一定变化后得到 wij * (xi * xj)，则为显式特征交互
否则为隐式特征交互


# bit-wise or vector-wise

以两个向量为例
bit-wise : f (w1 * a1 * a2, w2 * b1 * b2, w3 * c1 * c2)
vector-wise : f（w * (a1 * a2, b1 * b2, c1 * c2 )）
```python
xDeepFM:显式特征交互: CIN  压缩交互网络
隐式特征交互: DNN  典型的bit-wise
```


