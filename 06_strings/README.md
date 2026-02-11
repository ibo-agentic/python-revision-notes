# 🔤 Python Strings – Cheatsheet Notes

---

## 📌 What is a String?

Sequence of characters (text).  
Strings are immutable (cannot change after creation).

```python
x = 'One fish, '
y = 'two fish.'
z = x + y
print(z)
```

---

## 🔗 String Concatenation

Join strings using `+`.

```python
x = 'One fish, '
y = 'two fish.'
z = x + y
print(z)
```

---

## 🧱 .format()

Replace `{}` placeholders.

```python
msg1 = 'Fred scored {} out of {} points.'
print(msg1.format(3, 10))

msg2 = 'Fred {verb} a {adjective} {noun}.'
print(msg2.format(adjective='fluffy', verb='tickled', noun='hamster'))
```

---

## 🔡 .lower()

Convert to lowercase.

```python
greeting = "Welcome To Chili's"
print(greeting.lower())
```

---

## 🔠 .upper()

Convert to uppercase.

```python
dinosaur = "T-Rex"
print(dinosaur.upper())
```

---

## 🧹 .strip()

Remove characters from beginning and end.

```python
text1 = ' apples and oranges '
print(text1.strip())

text2 = '...+...lemons and limes...-...'
print(text2.strip('.'))
print(text2.strip('.+'))
print(text2.strip('.+-'))
```

---

## 🏷 .title()

Capitalize first letter of each word.

```python
my_var = "dark knight"
print(my_var.title())
```

---

## ✂️ .split()

Split string into list.

```python
text = "Silicon Valley"

print(text.split())
print(text.split('i'))
```

---

## 🔎 .find()

Find first index of substring.

```python
mountain_name = "Mount Kilimanjaro"
print(mountain_name.find("o"))
```

---

## 🔄 .replace()

Replace substring.

```python
fruit = "Strawberry"
print(fruit.replace('r', 'R'))
```

---

## 🔗 .join()

Join list of strings with delimiter.

```python
x = "-".join(["Codecademy", "is", "awesome"])
print(x)
```

---

## 🔐 Escaping Characters

Use backslash `\`.

```python
txt = "She said \"Never let go\"."
print(txt)
```

---

## 🔍 in Keyword

Check if substring exists.

```python
game = "Popular Nintendo Game: Mario Kart"

print("l" in game)
print("x" in game)
```

---

## 🔢 Indexing and Slicing

```python
str_value = 'yellow'

print(str_value[1])
print(str_value[-1])
print(str_value[4:6])
print(str_value[:4])
print(str_value[-3:])
```

---

## 🔁 Iterate Through String

```python
str_value = "hello"

for c in str_value:
    print(c)
```

---

## 📏 len()

Get length of string.

```python
length = len("Hello")
print(length)

colors = ['red', 'yellow', 'green']
print(len(colors))
```

---

## ⚠️ IndexError

Accessing invalid index causes error.

```python
fruit = "Berry"
indx = fruit[6]
```

---

