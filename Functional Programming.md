# Functional Programming

### Pure Fuctions

1. Same impurt results the same output
2. Doesn't have side effect

### map

```python
map(function, *iterable object)
想要執行的function 加上iterable資料
```

### filter

```python
filter(function, *iterable object)
可判斷成boolean的function
```

### zip

```python
zip(iterable1, iterable2, ....)
變成一組一組的tuple
```

### reduce

```python
from functools import reduce
reduce(function, sequence(data), initial value)
```

### Lamda

```python
lamda param: action(param)
```

### List comprehension

```python
append the item into list, set, dict

li = [x for x in (iterable data), if statement]
li_2 = li = [x*2(要對x做的運算) for x in (iterable data), if statement]
```