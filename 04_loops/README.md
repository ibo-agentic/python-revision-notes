# 🔁 Python Loops – Cheatsheet Notes

---

## 🔄 for Loop

Used to iterate over a list.

```python
nums = [1, 2, 3, 4, 5]

for num in nums:
    print(num)
```

---

## 🔢 range()

Used to repeat something specific number of times.

```python
# Print 0, 1, 2
for i in range(3):
    print(i)

# Print "WARNING" 3 times
for i in range(3):
    print("WARNING")
```

---

## ⏭ continue

Skips current iteration and moves to next one.

```python
big_number_list = [1, 2, -1, 4, -5, 5, 2, -9]

for i in big_number_list:
    if i < 0:
        continue
    print(i)
```

---

## 🛑 break

Stops the loop immediately.

```python
numbers = [0, 254, 2, -1, 3]

for num in numbers:
    if num < 0:
        print("Negative number detected!")
        break
    print(num)
```

---

## 🔁 while Loop

Runs as long as condition is True.

```python
hungry = True

while hungry:
    print("Time to eat!")
    hungry = False
```

Example:

```python
i = 1

while i < 6:
    print(i)
    i = i + 1
```

---

## 🔁 Nested Loops

Loop inside another loop.

```python
groups = [["Jobs", "Gates"], ["Newton", "Euclid"], ["Einstein", "Feynman"]]

for group in groups:
    for name in group:
        print(name)
```

---

## ♾ Infinite Loop

Loop that never stops (be careful).

```python
while True:
    print("This runs forever")
```

Stop with:
```
Ctrl + C
```

---

## 🧠 List Comprehension

Short way to create lists.

Format:
```
[expression for item in list if condition]
```

Example:

```python
result = [x**2 for x in range(10) if x % 2 == 0]
print(result)
```

---

