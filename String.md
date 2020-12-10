# String

- String

    ```python
    long_string = '''
    hi
    I am
    Kurt
    ''' #前後各'''

    str1 + " " + str2
    ```

- String Concatenation

    ```python
    print("Hello" + "World") #字串相加
    ```

- Type Conversion

    ```python
    str(100)--> # int-->str
    ```

- Escape Sequences

    ```python
    # \後面的預設為str
    "i'am\"cool\""
    --> i'am"cool"
    ```

- formatted strings

    ```python
    # 把變數放入字串中 f
    name = "Kurt"
    age = 28
    print(f"hi {name}. You are {age} years old")
    hi Kurt. You are 28 years old
    ```

- string indexing/slicing

    ```python
    [start:stop:step over]
    [1:] 1 to the end
    [:2] start from zero
    [::2] whoe string with 2 step over
    [-1] the last one
    [::-1] reverse order
    ```

- immutability

    —> need to reassign th change

- Built-in function/methods

    ```python
    len()
    string.upper()
    string.lower()
    string.capitalize() # 大寫第一個字
    string.find("hi") # 找hi有沒有在字串
    string.replace("old", "new")
    ```