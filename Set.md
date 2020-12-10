# Set

unorder  collection of unique objects

A set is created by placing all the items (elements) inside curly braces {}, separated by comma, or by using the built-in set() function.

```python
{}
set.add(value)
set(list)--> 把list變set (unique obj)
```

### Set methods

```python
set1.difference(set2) # 以set1為基準比較跟set2的差別
set.discard(值) # 把值去掉
set1.difference_update(set2) #以set1為基準把不同的保留 把跟set2相同的去掉
set1.intersection(set2) = set1 & set2 # 顯示相同的
set1.isdisjoint(set2) # return True 如果兩個沒有交集
set1.union(set2) = set1|set2 # 把兩個set加起來
set1.issubset(set2) #set1是不是set2的子集合
set1.issuperset(set2) #
```