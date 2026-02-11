# 📦 Python Modules – Cheatsheet Notes

---

## 📌 Importing Modules

Three ways to import:

```python
# 1️⃣ Import full module
import module
module.function()

# 2️⃣ Import specific function
from module import function
function()

# 3️⃣ Import everything (not recommended)
from module import *
function()
```

---

## 🎲 random Module

Used to generate random values.

### randint()

Returns random integer between start and end (inclusive).

```python
import random

r1 = random.randint(0, 10)
print(r1)
```

---

### choice()

Returns random element from a list.

```python
import random

seq = ["a", "b", "c", "d", "e"]
r2 = random.choice(seq)
print(r2)
```

---

## 📅 datetime Module

Used to work with date and time.

```python
import datetime

# Date
feb_16_2019 = datetime.date(2019, 2, 16)
print(feb_16_2019)

# Time
time_13_48min_5sec = datetime.time(13, 48, 5)
print(time_13_48min_5sec)

# Date and Time
timestamp = datetime.datetime(2019, 2, 16, 13, 48, 5)
print(timestamp)
```

---

## 🏷 Aliasing with `as`

Give module a shorter name.

```python
from matplotlib import pyplot as plt
plt.plot(x, y)

import calendar as c
print(c.month_name[1])
```

---

## 📂 Importing from Another File

If files are in same folder:

```python
# file1.py
# def f1_function():
#     return "Hello World"

# file2.py
import file1

file1.f1_function()
```

---

