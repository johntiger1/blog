---
title: "Deque"
date: 2019-10-30T19:38:47-04:00
draft: False

tags: 
- exotic data structures
- pro-programming
---

A `deque` (pronounced "deck") is a doubly-ended queue data structure in Python. It is just like your regular array, but it has faster append/pop operations!


```
from collections import deque

d = deque()
d.appendleft(2)
d.popleft()
d.pop()
d.append()
```

It can also support rotation, and other nice features! 