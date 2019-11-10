---
title: "Ordered Dict"
date: 2019-10-30T19:42:04-04:00
draft: False
---


An OrderedDict is a dictionary that remembers insertion order. Sweet and simple! 
**when comparing OrderedDicts, Python will check the order of the elements, as the name suggests!**
```

from collections import OrderedDict
od = OrderedDict()
od["a"] = 99
od["b"] = 100
od.pop() #pops the most recently entered entry!
...

```

It also has some minor methods relating to this order:

```
od.move_to_end('b', last=True) # moves key b to end of ordering
od.move_to_end('b', last=False) # moves key b to beginning of ordering
```
