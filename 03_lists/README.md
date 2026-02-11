# 📋 Python Lists – Cheatsheet Notes
---

## 📌 What is a List?

Ordered collection of items.  
Written inside square brackets `[ ]`.

```python
primes = [2, 3, 5, 7, 11]
print(primes)

empty_list = []
```

Lists can contain different data types:

```python
numbers = [1, 2, 3, 4, 10]
names = ['Jenny', 'Sam', 'Alexis']
mixed = ['Jenny', 1, 2]
list_of_lists = [['a', 1], ['b', 2]]
```

---

## ➕ Adding Lists Together

```python
items = ['cake', 'cookie', 'bread']
total_items = items + ['biscuit', 'tart']
print(total_items)
```

---

## ➕ .append()

Adds one item to the end of list.

```python
orders = ['daisies', 'periwinkle']
orders.append('tulips')
print(orders)
```

---

## 🔢 Indexing (Zero-Based)

Index starts at 0.

```python
berries = ["blueberry", "cranberry", "raspberry"]

berries[0]
berries[2]
```

---

## 🔙 Negative Indexing

Access from the end.

```python
soups = ['minestrone', 'lentil', 'pho', 'laksa']

soups[-1]
soups[-3:]
soups[:-2]
```

---

## 🧱 2D Lists (List inside List)

### Access element:

```python
heights = [["Noelle", 61], ["Ali", 70], ["Sam", 67]]

noelles_height = heights[0][1]
print(noelles_height)
```

### Modify element:

```python
class_name_hobbies = [
    ["Jenny", "Breakdancing"],
    ["Alexus", "Photography"],
    ["Grace", "Soccer"]
]

class_name_hobbies[0][1] = "Meditation"
print(class_name_hobbies)
```

---

## ➖ .remove()

Removes first matching value.

```python
shopping_line = ["Cole", "Kip", "Chris", "Sylvana", "Chris"]

shopping_line.remove("Chris")
print(shopping_line)
```

---

## 🔢 .count()

Counts how many times a value appears.

```python
backpack = ['pencil', 'pen', 'notebook', 'textbook', 'pen', 'highlighter', 'pen']

numPen = backpack.count('pen')
print(numPen)
```

---

## 📏 len()

Returns number of elements.

```python
knapsack = [2, 4, 3, 7, 10]

size = len(knapsack)
print(size)
```

---

## 🔀 .sort()

Sorts list (modifies original list).

```python
exampleList = [4, 2, 1, 3]

exampleList.sort()
print(exampleList)
```

---

## 🔀 sorted()

Returns new sorted list (does NOT modify original).

```python
unsortedList = [4, 2, 1, 3]

sortedList = sorted(unsortedList)
print(sortedList)
```

---

## ✂️ List Slicing

Format:

```
list[start:end]
```

Includes start index, excludes end index.

```python
tools = ['pen', 'hammer', 'lever']

tools_slice = tools[1:3]
tools_slice[0] = 'nail'

print(tools)
```

---

## 📍 .insert()

Insert element at specific index.

```python
store_line = ["Karla", "Maxium", "Martim", "Isabella"]

store_line.insert(2, "Vikor")
print(store_line)
```

---

## 📤 .pop()

Removes and returns element.

```python
cs_topics = ["Python", "Data Structures", "Balloon Making", "Algorithms", "Clowns 101"]

removed_element = cs_topics.pop()
print(cs_topics)
print(removed_element)

cs_topics.pop(2)
print(cs_topics)
```

---

## 🧊 Tuples

Like lists but immutable (cannot change).

```python
my_tuple = ('abc', 123, 'def', 456, 789, 'ghi')

len(my_tuple)
max(my_tuple)
min(my_tuple)
my_tuple.index(123)
my_tuple.count('abc')
```

---
