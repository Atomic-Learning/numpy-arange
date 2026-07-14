You can generate a 1D array of evenly spaced integer values with `np.arange()`{.python}.

```py-cell
import numpy as np

print(np.arange(3))
print(np.arange(3, 5))
print(np.arange(4, 13, 3))
```

The syntax for this is similar to that of the built-in `range()`{.python} function:

* A single argument gives values from zero up to, but not including, that value
* Two arguments give a start and stop value - values are generated from the start value up to, but not including, the stop value
* A third argument adds a step - values are generated from the start value up to, but not including, the stop value, in increments of the step.

This function is useful when you want a predictable sequence of integers for later reshaping or indexing.