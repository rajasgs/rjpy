---
title: Bag-Of-Words
date: 2024-11-17
author: Your Name
cell_count: 5
score: 5
---

```python
import re
from nltk.tokenize import word_tokenize
from collections import Counter
```


```python
word_counter = Counter(word_tokenize("""The cat is in the box. The cat likes the box. The box is over the cat."""))
```


```python
word_counter
```




    Counter({'The': 3,
             'cat': 3,
             'is': 2,
             'in': 1,
             'the': 3,
             'box': 3,
             '.': 3,
             'likes': 1,
             'over': 1})




```python
word_counter.most_common(4)
```




    [('The', 3), ('cat', 3), ('the', 3), ('box', 3)]




```python

```


---
**Score: 5**