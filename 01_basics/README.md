# 🐍 Python Basics – Full Cheatsheet Notes

---

## 📌 Comments

Used to explain code. Python ignores comments.

```python
# Comment on a single line
user = "JDoe"  # Comment after code
```

---

## 📌 Arithmetic Operations

Operators:
+ addition  
- subtraction  
* multiplication  
/ division  
% remainder (modulo)  
** exponent (power)

```python
result = 10 + 30
result = 40 - 10
result = 50 * 5
result = 16 / 4
result = 25 % 2
result = 5 ** 3
```

---

## 📌 Plus-Equals Operator (+=)

Adds value and updates variable in one line.

```python
counter = 0
counter += 10

# Same as
counter = 0
counter = counter + 10

# Works with strings
message = "Part 1 of message "
message += "Part 2 of message"
```

---

## 📌 Variables

Used to store data.

```python
user_name = "codey"
user_id = 100
verified = False

# Value can change
points = 100
points = 120
```

---

## 📌 Modulo Operator (%)

Returns remainder.

```python
zero = 8 % 4
nonzero = 12 % 5

4 % 2   # 0
7 % 3   # 1
```

---

## 📌 Integers

Whole numbers (no decimal).

```python
chairs = 4
tables = 1
broken_chairs = -2
sofas = 0
```

---

## 📌 Floating Point Numbers

Numbers with decimals.

```python
pi = 3.14159
meal_cost = 12.99
tip_percent = 0.20
```

---

## 📌 Strings

Text inside quotes.

```python
user = "User Full Name"
game = 'Monopoly'

# Multi-line string
longer = "This string is broken up \
over multiple lines"
```

---

## 📌 String Concatenation

Joining strings using + operator.

```python
first = "Hello "
second = "World"
result = first + second
long_result = first + second + "!"
```

---

## 📌 print() Function

Displays output.

```python
print("Hello World!")
print(100)

pi = 3.14159
print(pi)
```

---

## ⚠️ Errors

### SyntaxError

```python
if False ISNOTEQUAL True:
age = 7 + 5 = 4
```

---

### ZeroDivisionError

```python
numerator = 100
denominator = 0
bad_results = numerator / denominator
```

---

### NameError

```python
misspelled_variable_name
```

---

