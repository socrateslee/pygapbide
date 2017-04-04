# pygapbide

Migrated from [Google Code Archive](https://code.google.com/archive/p/pygapbide/). Python implementation of [Gap-Bide algorithm](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.140.6278&rep=rep1&type=pdf).

To use the code: 

```
from pygapbide import *
sdb = [[1, 2, 3, 4],
       [1, 4, 2, 3, 5],
       [1, 2, 4, 3, 1, 2, 3, 1],
       [1, 2, 4, 3, 1],
       [1, 3, 5],
       [2, 3, 4],
       [2, 1, 5],
       [3, 5, 3, 1],
       [2, 4, 1, 5, 2, 3, 3]]
g = Gapbide(sdb, 3, 0, 2)
g.run()
```
