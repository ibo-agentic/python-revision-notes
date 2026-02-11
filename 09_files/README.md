# 📁 Python Files – Cheatsheet Notes


---

## 📌 Opening a File

Use `open()` with `with` and `as`.

```python
with open('somefile.txt') as file_object:
    print(file_object)
```

---

## 📖 Reading Entire File (.read)

Returns entire content as a string.

```python
with open('mystery.txt') as text_file:
    text_data = text_file.read()

print(text_data)
```

---

## 📄 Reading One Line (.readline)

Reads one line at a time.

```python
with open('story.txt') as story_object:
    print(story_object.readline())
```

---

## 📑 Reading All Lines (.readlines)

Returns list of lines.

```python
with open('lines.txt') as file_object:
    file_data = file_object.readlines()

print(file_data)

for line in file_data:
    print(line)
```

---

## ✍️ Writing to a File ('w')

Overwrites existing content.

```python
with open('diary.txt', 'w') as diary:
    diary.write('Special events for today')
```

---

## ➕ Appending to a File ('a')

Adds content without deleting old data.

```python
with open('shopping.txt', 'a') as shop:
    shop.write('Tomatoes, cucumbers, celery\n')
```

---

## 🗂 Working with JSON

Read JSON file into dictionary.

```python
import json

with open('file.json') as json_file:
    python_dict = json.load(json_file)

print(python_dict.get('userId'))
```

---

## 📊 Working with CSV (csv.DictWriter)

```python
import csv

with open('companies.csv', 'w') as csvfile:
    fieldnames = ['name', 'type']
    writer = csv.DictWriter(csvfile, fieldnames=fieldnames)

    writer.writeheader()
    writer.writerow({'name': 'Codecademy', 'type': 'Learning'})
    writer.writerow({'name': 'Google', 'type': 'Search'})
```

---

