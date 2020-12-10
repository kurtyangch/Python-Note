# List

Data Structure

- List slicing

    mutable

    ```python
    li[0] = "A" # 直接改變第一個, 不像字串需要reassign
    ```

- matrix

    ```python
    # 處理巨量資料跟影像

    matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
    ]

    martrix[0][1] = 2
    ```

- list methods

    ```python
    len()
    # adding
    li.append()--> add a obj at the endd of list # 加入list的話就直接是list
    # changing the original list, doesn't create a new one
    li.insert(index, obj)
    li.extend(list/obj) # 加入list的話會把list中的obj拿出

    # removing
    li.pop() # 刪掉最後一個 /或是指定的index      # return the index you assign
    li.remove() # 刪掉指定的值
    li.clear() # 全部刪掉
    ```

- list methods 2

    ```python
    li.index("值", 開始找的位子, 結束找的位子 ) ---> # 輸入值 跟你說在哪個index位子
    "" in li (用來找有沒有在list裡面)
    ```

- list methods 3

    ```python
    li.sort() -->sort the list
    sorted(list) --> copy a list and sorted it, didn't change in place
    li.copy() -->copy a list
    li.reverse() -->reverse the list
    ```

- common list patterns

    ```python
    reverse the list

    li[::-1] --> create a new list not change in place

    list(range(100))
    0~99

    " ".join(["hi", "my", "name", "is", "Kurt"])

    --> hi my name is Kurt
    ```

- list unpacking

    ```python
    a, b, c, *d, e = [1, 2, 3, 4, 5, 6, 7]

    # 前面加*的會變成list

    print(a)
    print(b)
    print(c)
    print(d)
    print(e)

    1
    2
    3
    [4, 5, 6]
    7
    ```