# 🧩 Python Functions – Cheatsheet Notes

---

## 📌 Defining a Function

Use `def` to create a function.

```python
def my_function(x):
    return x + 1

print(my_function(2))
print(my_function(3 + 5))
```

---

## 📥 Function Parameters

Parameters are inputs of a function.

```python
def write_a_book(character, setting, special_skill):
    print(character + " is in " + setting + " practicing her " + special_skill)
```

---

## 📦 Multiple Parameters

Functions can take multiple inputs.

```python
def ready_for_school(backpack, pencil_case):
    if backpack == 'full' and pencil_case == 'full':
        print("I'm ready for school!")
```

---

## 🔁 Calling a Function

Call function using its name + parentheses.

```python
doHomework()
```

Example with arguments:

```python
def sales(grocery_store, item_on_sale, cost):
    print(grocery_store + " is selling " + item_on_sale + " for " + cost)

sales("The Farmer’s Market", "toothpaste", "$1")
```

---

## 📏 Function Indentation

All code inside function must be indented.

```python
def testfunction(number):
    print("Inside the testfunction")
    sum = 0
    for x in range(number):
        sum += x
    return sum

print("This is not part of testfunction")
```

---

## 🔑 Keyword Arguments

Arguments can be passed by name.

```python
def findvolume(length=1, width=1, depth=1):
    print("Length = " + str(length))
    print("Width = " + str(width))
    print("Depth = " + str(depth))
    return length * width * depth

findvolume(1, 2, 3)
findvolume(length=5, depth=2, width=4)
findvolume(2, depth=3, width=4)
```

---

## 🔢 Returning Multiple Values

```python
def square_point(x, y, z):
    x_squared = x * x
    y_squared = y * y
    z_squared = z * z
    return x_squared, y_squared, z_squared

three_squared, four_squared, five_squared = square_point(3, 4, 5)
```

---

## 🔄 Lambda Function

Short anonymous function (one line).

Syntax:
```
lambda arguments: expression
```

Example:

```python
square = lambda x: x * x
print(square(4))
```

---

## 🔙 return Keyword

Returns value from function.

```python
def check_leap_year(year):
    if year % 4 == 0:
        return str(year) + " is a leap year."
    else:
        return str(year) + " is not a leap year."

year_to_check = 2018
returned_value = check_leap_year(year_to_check)
print(returned_value)
```

---

## 🌍 Global Variables

Defined outside function. Can be accessed inside.

```python
a = "Hello"

def prints_a():
    print(a)

prints_a()
```

---

## 🏠 Local Variables

Defined inside function. Cannot be used outside.

```python
a = 5

def f1():
    a = 2
    print(a)

print(a)
f1()
```

---

## 📌 Parameters as Local Variables

Parameters only exist inside function.

```python
def my_function(value):
    print(value)

my_function(7)

print(value)  # This causes error
```

---

