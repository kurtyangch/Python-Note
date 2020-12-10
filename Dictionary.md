# Dictionary

Keys—>immuatable(string, int, boolean, tuple), (list is not allowed) and unique

### Dictionary Methods

```python
Check if the key in the dictionary—> 

use dict.get("key you want to check", default value) 
#回傳 找到的value ,如果沒有default 就會回傳none (使用這個方法避免error)

create a dict
dict(key=values)-->創造所填的值

dict.keys()-->找key值
dict.values()-->找values值
dict.item()-->找一整組key, value 且以tuple的形式回傳
dict.copy()-->複製一個dict
dict.clear()-->清空dict
dict.pop()-->回傳pop值後再刪除
dict.popitem()
dict.update({key:new_value})
```