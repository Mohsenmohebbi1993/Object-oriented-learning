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