---
title: tensorflow
categories: [dev]
comments: true
---

### 载入整个模型结构 h5
```python
from tensorflow.python.keras.models import load_model, save_model
model = load_model('model.h5', custom_objects)
# model.h5  存储的整个模型
# custom_objects  可选的字典name
```


