# 📖 Python Dictionaries – Cheatsheet Notes

---

## 📌 What is a Dictionary?

Unordered collection of key:value pairs.  
Written inside `{ }`.

```python
my_dictionary = {"song": "Estranged", "artist": "Guns N' Roses"}
```

---

## 🔑 Accessing Values

Use key inside square brackets.

```python
print(my_dictionary["song"])
```

⚠️ Accessing non-existing key → KeyError

---

## ✏️ Updating Values

Overwrite existing value using key.

```python
my_dictionary["song"] = "Paradise City"
```

---

## 🧱 Dictionary Syntax

```python
dictionary = {
 1: 'hello',
 'two': True,
 '3': [1, 2, 3],
 'Four': {'fun': 'addition'},
 5.0: 5.5
}
```

- Keys must be immutable (string, number, tuple)
- Values can be any data type

---

## 🔄 Merging Dictionaries (.update)

```python
dict1 = {'color': 'blue', 'shape': 'circle'}
dict2 = {'color': 'red', 'number': 42}

dict1.update(dict2)

# dict1 becomes:
# {'color': 'red', 'shape': 'circle', 'number': 42}
```

---

## 🔍 Dictionary Methods

```python
ex_dict = {"a": "anteater", "b": "bumblebee", "c": "cheetah"}

ex_dict.keys()
ex_dict.values()
ex_dict.items()
```

- `.keys()` → returns all keys  
- `.values()` → returns all values  
