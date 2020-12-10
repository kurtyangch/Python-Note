# Python Basic II

### Conditional Logic

```python
if:
elif:
else:
```

### Truthy vs Falsey (A "truthy" value will satisfy the check performed by if or while statements)

```python
All values are considered "truthy" except for the following, which are "falsy":

None
False
0
0.0
0j
Decimal(0)
Fraction(0, 1)
[] - an empty list
{} - an empty dict
() - an empty tuple
'' - an empty str
b'' - an empty bytes
set() - an empty set
an empty range, like range(0)
objects for which
obj.__bool__() returns False
obj.__len__() returns 0

A "truthy" value will satisfy the check performed by if or while statements. We use "truthy" and "falsy" to differentiate from the bool values True and False.
```

### Ternary operators

```python
and 
or
not
```

### Logical operators

```python
>
<
>=
<=
==
```

### is vs ==

```python
is --> 想像是在記憶體中相同的位置 (兩個空的list 存放在不同位置 所以[] is [] == False)

== --> 只要value相同就可以
```

### Iterable

```python
list, dict, tuple, set, string
-->iterated: one by one check each item in the collection

dict --> 會抓出key
dict.items() --> 會抓出一對key value(tuple 形式)
dict.values() --> 會抓出value
dict.keys() --> 會抓出value

frequently used-->  for key, value in dict.items:
												print(key, value) --> 此時回傳兩個但不是tuple
```

### For Loops

```python
for i in sth iterable:
```

### enumerate

```python
for i,j in range(10):
	print(i, j)

0, 1
1, 2...
```

### While Loops

```python
while condition:
	
	break

else: 
-------------
while True:
	

	if xxx:
		break
```

### break, continue, pass

```python
break --> 停止
continue --> 繼續執行
pass --> placeholder, 常用在未寫完的function, class 避免error
```

### Function

```python
def function:
	

parameter and argument
(定義時)       (呼叫時)

positional argument --> 按照順序填寫
key word argument --> 按照parameter名稱填寫

default parameter --> 不輸入時自動帶入
```

### Return

```python
function 要有return 才會回傳值, 否則print出None

若要顯示fn結果要print出 否則只會運算不會顯示
```

### Methods vs Funciton

```python
mehtod 附屬在obj後 不可獨立使用

function 可獨立使用
```

### Docstring

```python
def fn():
	'''
	info about the function
	'''
```

### *arg and *kwarg

```python
*arg let the function can be put the iterable arguments
*kwarg let the function can be put the keyword arguments

# rules
params, *arg, default params, *kwarg
```

### Scope

```python
global
local

scope rule
1. start with local
2. Parent local (nonlocal)
3. Global (global)
4. built in python functions
```