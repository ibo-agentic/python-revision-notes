# 🔀 Python Control Flow – Cheatsheet Notes

---

## ⚠️ Errors

### SyntaxError
Wrong format in code.

```python
age = 7 + 5 = 4
```

---

### TypeError
Using wrong data types together.

```python
result = "hello" + 5
```

---

### NameError
Using variable that was not defined.

```python
str = "Hello World"
print(x)
```

---

## 🔁 if Statement

Runs code only if condition is True.

```python
test_value = 100

if test_value > 1:
    print("This code is executed!")

if test_value > 1000:
    print("This code is NOT executed!")

print("Program continues.")
```

---

## 🔄 else Statement

Runs when if condition is False.

```python
test_value = 50

if test_value < 1:
    print("Value is < 1")
else:
    print("Value is >= 1")
```

---

## 🔂 elif Statement

Checks another condition after if.

```python
pet_type = "fish"

if pet_type == "dog":
    print("You have a dog.")
elif pet_type == "cat":
    print("You have a cat.")
elif pet_type == "fish":
    print("You have a fish")
else:
    print("Not sure!")
```

---

## ⚖️ Comparison Operators

```
==   equal
!=   not equal
<    less than
>    greater than
<=   less than or equal
>=   greater than or equal
```

Example:

```python
a = 2
b = 3

a < b
a > b
a >= b
a <= b
```

---

## 🟢 Equal Operator (==)

```python
if 'Yes' == 'Yes':
    print('They are equal')

if (2 > 1) == (5 < 10):
    print('Both expressions give same result')
```

---

## 🔴 Not Equals Operator (!=)

```python
if "Yes" != "No":
    print("They are NOT equal")

val1 = 10
val2 = 20

if val1 != val2:
    print("They are NOT equal")
```

---

## 🔗 and Operator

Returns True only if BOTH conditions are True.

```python
True and True
True and False
1 == 1 and 1 < 2
```

---

## 🔗 or Operator

Returns True if at least one condition is True.

```python
True or False
False or False
1 < 2 or 3 < 1
```

---

## 🔄 not Operator

Reverses Boolean value.

```python
not True
not False

not 1 > 2
not 1 == 1
```

---

## 🟢 Boolean Values

Only two values:

```
True
False
```

Example:

```python
is_true = True
is_false = False

print(type(is_true))
```

---
