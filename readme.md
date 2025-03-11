# Object-oriented-learning

1. data type : int, float, str, complex, bool , ...  
2. print("2a".isidentifier()) : The name is true or not
3. Is keyword:

```
from keyword import iskeyword
print(iskeyword("if"))
```

4. Assign y value to x and x value to y
```
x = 1  , y = 2
x , y = y ,  x
```
5. Conditional Expression
```
a = 10
b = 12
m = a if a < b else b
```
6. Math Lib
7. If / elif / else
```
score = 83
if score > 90:
    print("A")
elif score > 80:
    print("B")
elif score > 70:
    print("C")
else:
    print("D")
```