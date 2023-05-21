# Introduction

Conditional statements are those statements that let us do different tasks based on a certain condition.

```py
if a > b:
  print("a is greater than b")
elif a < b>:
  print("b is greater than a")
else:
  print("a and b are equal")
```

# Questions

1. What is the output of the following code?
```py
a = 33
b = 200
if b > a:
  print("b is greater than a")
else:
  print("a is greater than b")
```

2. What is the output of this code?
```py
a = 2
b = 330
print("A") if a > b else print("B")
```

3. and, or, and not are ______ operators.

a. relational<br>
b. logical<br>
c. conditional<br>
d. ternary<br>

4. What is the output of the following code snippet:

```py
if 'bar' in {'foo': 1, 'bar': 2, 'baz': 3}:
  print(1, end=" ")
print(2, end=" ")

if 'a' in 'qux':
  print(3, end=" ")
print(4, end=" ")
```

5. What is value of this expression:

```py
print('a' + 'x' if '123'.isdigit() else 'y' + 'b')
```

a. 'axb' <br>
b. 'ax' <br>
c. 'axyb' <br>
d. 'ab' <br>

6. What gets printed with the following code?

```py
x = True
y = False
z = False
if x or y and z :
  print("yes")
else:
  print("no")
```

7. What gets printed with the following code ?

```py
x = True
y = False
z = False
if not x or y :
  print(1)
elif not x or not y and z:
  print(2)
elif not x or y or not y and x:
  print(3)
else:
  print(4)
```

# Answers

1. b is greater than a
2. B
3. (b) logical
4. 1 2 4
5. (b) 'ax'
6. yes
7. 3