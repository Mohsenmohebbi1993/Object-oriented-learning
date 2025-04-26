# Object-oriented-learning

## Part 1
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
7. for and while
```
for i in range(10):
    print(i, end=" ")
print("\n-----")
j = 0
while j < 10:
    print(j ,end=" ")
    j+=1
```
8. String Function 1
```
print("---------string---------")
word = "python"
number = "128746684"
print(f"---The word is {word}---")
print(f"---The number is {number}---")
print(f"len word = {len(word)}")
print(f"is there 'th' in word ? {"th" in word}")
print(f"is lower ? {word.islower()}")
print(f"is alphabet ? {word.isalpha()}")
print(f"is digit ? {word.isdigit()}")
print(f"is number ? {number.isdigit()}")
print(f"find 'o' ? place is {word.find("o")}")
print(f"count 'o' ? count o is  {word.count("o")}")
print(f"titel word: {word.title()}")
print(f"upper word: {word.upper()}")
print(f"ljust word: {word.ljust(9,"*")}")
print(f"startswith word by 'py'?: {word.startswith("py")}")
print(f"replace 'thon' by 'Mohsen' : {word.replace("thon","_Mohsen")}")
```
9. String Function 2
```
word = "$python_$$_A_$$"
print(f"print word : {word}")
print(f"strip $ : {word.strip("$")}")
sentence = "I am Mohsen Mohebbi"
print(f"print sentence : {sentence}")
print(f"split by ' ' : {sentence.split(" ")}")
split_sentence = sentence.split(" ")
print(f"new_sentence by join = {" ".join(split_sentence)}")
```
10. Print
```
word = "python"
print(f"name {word}")
print("name {}".format(word))
```
11. list Function 1
```
a = [8, 2, 12]
print(f"type a is {type(a)}")
print(f"len a is {len(a)}")
print(f"index 12 is {a.index(12)}")
print(f"number of index 1 is {a[1]}")
a[1] = 7
print(f"change index 1 - 2 by 7 - a[1]=7 and a[1] is {a[1]}")
```
12. list Function 2
```
a = [13, 5, 30, 8, 6, 25]
print("---------slicing-----------")
print(f"---list is {a}---")
print(f"a[1:4] = {a[1:4]}")
print(f"a[:3] = {a[:3]}")
print(f"a[3:] = {a[3:]}")
print(f"a[::-1] = {a[::-1]}")
print(f"a[0:7:2] = {a[0:7:2]}")
print(f"a[7:0:-2] = {a[7:0:-2]}")
```
13. list Function 3
```
a = [3, 5]
print(f"a is {a} and a*2 is {a*2}")
b = ["R", "g"]
print(f"a is {a} and b is {b} and a+b is {a+b}")

c = [15, 5, 23, 3, 20]
print(f"c is {c} and Max c is {max(c)}")
print(f"c is {c} and min c is {min(c)}")
print(f"c is {c} and count 5 in c is {c.count(5)}")
print(f"c is {c} and sum c is {sum(c)}")
c.insert(2,8)
print(f"c is {c} and inset a number c is {c}")
c.remove(8)
print(f"c is {c} and remove 8 c is {c}")
print(f"c is {c} and last number in c is {c.pop()} and c is {c} remove last number")
print(f"c is {c} and c[1] is {c[1]} in c is {c.pop(1)} and c is {c} remove index 1")
print(f"c is {c} befor del")
del c[1]
print(f"c is {c} and del 8 c is {c}")
```
14. list Function 4
```
a = [7, 8, 5, 15, 23]
print(f"--- a is {a}---")
a.reverse()
print(f"reverse a is {a}")
a.sort()
print(f"sort {a}")
a. append(1000)
print(f"append 1000 to list is {a}")
b = ["a", "b"]
a.append(b)
print(f"append a list to list {a}")
a.extend(b)
print(f"append a Members of a list to list {a}")
b.clear()
print(f"clear list's b {b}")
```
15. list Function 5
```
a=[]
print(f"list a is {a}")
for i in range(3):
    a.append(i)
print (f"list a with append by for {a}")
a=[]
a = [i for i in range(3)]
print (f"other way i for i in range(3) {a}")
```
16. Tupel Function 1
```
print(f"------Tupel is {t}--------")
print(f"type t is {type(t)}")
print(f"len t is {len(t)}")
print(f"t[1] is {t[1]}")
print(f"t[1:3] is {t[1:3]}")
print(f"index atr is {t.index("art")}")
```
17. Tupel Function 2
```
t = (1, 7, 5)
print(f"tupel is {t}")
print(f"sum is {sum(t)}")
print(f"Max is {max(t)}")
print(f"min is {min(t)}")
print(f"count 7 is {t.count(7)}")
print(f"reverse is {tuple(reversed(t))}")
print(" how to append a number to tuple")
a = list(t)
a.append(3)
t = tuple(a)
print(f"append 3 to tuple {t}")
```
17. Tuple Function 3
```
a = (1, 3)
b = ("a", "b")
c = zip(a,b)
x = list(c)
print(f"zip 2 tupel is {x}")
# unzipe
u = list(zip(*x))
print(f" unzipe is {u}")
```
18. Dictionary Function 1
```
d = {
    "brand" : "b",
     "model" : "m",
     "color" : "red",
     "year" : 2025
     }
# or
# d = dict(brand = "b", model = "m", color = "red", year = 2025)

print(f"---dictionary is {d}---")
```
19. Dictionary Function 2
```
d = {"x": 14,
     "y": 32,
     "z":11,
     "w": 7}

print(f"---dictionary is {d}---")
print(f"type d is {type(d)}")
print(f"len d is {len(d)}")
print(f"key is y and value is {d["y"]}")
print(f"key is y and value is {d.get("y")}")
print(f"list of keys is {list(d.keys())}")
print(f"liost of values is {(list(d.values()))}")
print(f"liost of each items of dic is {list(d.items())}")
print("---print key and value in rows---")
for k,v in d.items():
    print(k,":",v)

d.pop("y")
print(f" pop and remove a item (y) -- {d}")
d.popitem()
print(f" pop and remove a last item -- {d}")
d.clear()
print(f" clear and empty dic -- {d}")
del d
print(f" del dic - not found")

d = {"x": 14,
     "y": 32,
     "z":11,
     "w": 7}
print("---sort dic by operator lib---")
import operator
k = operator.itemgetter(1) # setting sort by items = 1 or keys 0
print(f"sorted dic by values {sorted(d.items(),key = k)}")
```
20. Dictionary Function 3
```
# combine
d1 = {'x' : 3 , 'y': 2 , 'z':1}
d2 = {'w' : 8 , 't': 7 }
d = {}
d = d1.copy()
d.update(d2)
print(f" combine 2 dict {d}") 

#or
d = {**d1, **d2}
print(f" combine 2 dict {d}") 

# create new dict by 2 parameters
k = ['a' , 'b'] 
v = [4 , 8]
z = zip(k,v)
d = dict(z)     
print(f" create dict by 2 parameters {d}")

### Nested dict
myfamily = {
        'child1': {'name':'taha'  , 'age' : 8}  ,      
        'child2': {'name':'mahsa' , 'age' : 20}              
        }
print(f"nested dict {myfamily}")
p = {
     'name'     : 'farshid', 
     'children' : ['mahsa', 'taha'],
     'phone'    : {'home':'021-4455', 'mobile':'0912-1972028'}
    }
print(f"--- print dict {p}")
print(f"len dict {len(p)}")
print(f"phone + mobile is {p['phone']['mobile']}")
print(f"children 1 is {p['children'][0]}")
```

## Part 2
 list is []
 Tuple is ()
 dicttionary is {--:--}
 set is {}

21. Set Function 1
```
S = {"a", "e", "o", "i"}
print(f"set is {S}")
print(f"type of S is {type(S)}")
print(f"len of S is {len(S)}")
print(f"u in S ? {"u" in S}")
S.add("u")
print(f"add u in S ? {S}")
S.add("a")
print(f"add another a to S ? {S} one a is in S")
S.remove("i")
print(f"remove i in S ? {S}")
C = S.copy()
print(f"make a copy from S : C is {C} and S is {S} location not important in set")
print(f"C = S ? {C == S}")

X = {1, 5,8, 9, 12, 10}
Y = {8, 10}
print (f"x is {X} and y is {Y} - Is y intersection x ? {X.intersection(Y)}")
print (f"x is {X} and y is {Y} - Is y & x ? {X & Y}")
print (f"x is {X} and y is {Y} - Is y union x ? {X.union(Y)}")
print (f"x is {X} and y is {Y} - Is y | x ? {X | Y}")
print (f"x is {X} and y is {Y} - Is y difference x ? {X.difference(Y)}")

X = {'A', 'M'}
Y = {'A','C','M','F'}
print(f"X is {X} And Y is {Y} - X issubset Y {X.issubset(Y)}") 
```
22. Function 1
```
def f():
    print("Mohsen Mohebbi")


def f1():
    return"Mohsen Mohebbi"

print(f"def f is")
f()
print(f"def f1 is {f1()}")

def f2(name):
    print(name)
f2("MOHSEN")

def f3(x: float, y: float) -> float:
    """
    f3() is max Number  
    x : A Number  
    y : A number  
    return : A number  
    """
    if x < y:
        return y
    else:
        return x
print (f"f3 Return(min) is {f3(8.2,23.9)}")

def f4(x : float, y : float, z : float) -> float:
    """
    Use a Function in Function   
    x : A Number  
    y : A Number  
    z : A Number  
    return : Max(x, y , z)  
    Fisrt find Max (y, z) and second Max (x, max(y, z))
    """
    return f3(x, f3(y,z))
print(f"f4 is : {f4(20.1, 100.81, 15.3)}")

x = 7
def f5():
    global x # change vale out of function
    print(x)
    x = 3
    print(x)
f5()
print(f"print x : {x} with global can change value out of function" )
def add_more(a, b, *c):
    print(a + b + sum(c))
print("add more is")
add_more(5, 2, 7, 8, 12)

def f7(a : int, b : int, *c : int, **d : dict)-> {int, int, tuple, dict}:
    """
    a : 1st value  
    b : 2nd value
    c : Then before B until we get the variable name.
    d : Variables specified as a dictionary  
    """
    print("----- function f7() -----")
    print(f" a = {a}   and type   {type(a)}")
    print(f" b = {b}   and type   {type(b)}")
    print(f" c = {c}   and type   {type(c)}")
    print(f" d = {d}   and type   {type(d)}")
    print("----------------------------------")

f7(3, 4, 7, 1, 6, x=5, y=7, z=9)

import operator
v = operator.itemgetter(0) # setting sort by items = 1 or keys 0

def count_char(s : str)->dict:
    """
    count_char    
    s : A srting  
    return : each character with count repeat    
    give a string and craete a dict and Counts characters    
    """
    d = {}
    for i in s:
        if i in d.keys():
            d[i] += 1
        else:
            d[i] = 1
    return sorted(d.items(),key = v)
print(count_char("mohsenmohebbi"))
# find uniqe value 
def unique_list(lst):
    r = []
    for i in lst:
        if i not in r:
            r.append(i)
    return r
a = [8, 1, 2, 3, 1, 5, 3, 9, 1, 7, 8]
print(f"unique list is {unique_list(a)}")
# or
def  unique_list2(lst):
    return set(lst)
print(f"other way unique list is {unique_list2(a)}")# find uniqe value 
def unique_list(lst):
    r = []
    for i in lst:
        if i not in r:
            r.append(i)
    return r
a = [8, 1, 2, 3, 1, 5, 3, 9, 1, 7, 8]
print(f"unique list is {unique_list(a)}")
# or
def  unique_list2(lst):
    return set(lst)
print(f"other way unique list is {unique_list2(a)}")
```
23. Function 2 - PEP 484 --   
search PEP 484 and format's Function  
```
def fun(S : str, a : dict) -> {str, dict}:
    """
    Description about function   
    fun : aaaaa    
    S : A srting
    return: A string  
    print S 

    """
    return S , a

print(fun.__annotations__)
print(fun.__doc__)
```
24. Function : recursive Function
```
def fac_rec(n):
    if n == 1:
        return 1
    else:
        return n * fac_rec(n-1)

def f_rec(n,base):
    s = "0123456789ABCDEF"
    if n < base:
        return s[n]
    else:
        return f_rec(n//base, base) + s[n % base]
print(f_rec(25,16))
```
25. Lambda
```
add = lambda x, y : x * y
print(f"Lambda add {add(2,8)}")

f = lambda x, y: (x+y , x-y)
print(f"lambda f {f(8,1)}")
```
26. map
```
lst = ["ALI", "REZA"]
a = []
for i in lst:
    x = i.lower()
    a.append(x)
print(a)
print(list(map(str.lower, lst)))

a = [16, 7, 14, 6]
print(list(map(lambda x : x < 10, a)))
print(list(filter(lambda x : x < 10, a)))
```
27. sorted 
```
d = {"ali":12, "mahsa":20, "hosey":15, "mohsen": 19}
print(sorted(d.items(), key = lambda x :x[1])) # x[1] is item of dict
```
## Object Oriented or OOP

1. Class 

self is first
Class Test has two property ( a and b ) and 3 method ( set_var, add , mul)   
```
class Test:
    def set_var(self, a, b):
        self.a = a
        self.b = b

    def add (self):
        return self.a + self.b
    
    def mul (self):
        return self.a * self.b

ob1 = Test()
ob1.set_var(2,3)
print(f"print object {ob1.a} and {ob1.b}")
```

