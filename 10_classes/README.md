# 🏗 Python Classes (OOP) – Cheatsheet Notes

---

## 📌 What is a Class?

A class is a blueprint for creating objects.

```python
class Car:
    pass

ferrari = Car()
```

---

## 🏗 Defining a Class

```python
class Animal:
    def __init__(self, name, number_of_legs):
        self.name = name
        self.number_of_legs = number_of_legs
```

---

## 🚀 __init__ Method

Runs automatically when object is created.

```python
class Animal:
    def __init__(self, voice):
        self.voice = voice

cat = Animal('Meow')
print(cat.voice)

dog = Animal('Woof')
print(dog.voice)
```

---

## 🔧 Class Methods

Functions inside a class.  
First parameter is always `self`.

```python
class Dog:
    def bark(self):
        print("Ham-Ham")

charlie = Dog()
charlie.bark()
```

---

## 🖨 __repr__ Method

Defines how object is printed.

```python
class Employee:
    def __init__(self, name):
        self.name = name

    def __repr__(self):
        return self.name

john = Employee('John')
print(john)
```

---

## 📦 Class Variables

Shared by all instances.

```python
class MyClass:
    class_variable = "I am a Class Variable!"

x = MyClass()
y = MyClass()

print(x.class_variable)
print(y.class_variable)
```

---

## 🔎 type() Function

Returns data type.

```python
a = 1
print(type(a))

a = 1.1
print(type(a))

a = 'b'
print(type(a))

a = None
print(type(a))
```

---

## 📂 dir() Function

Returns list of attributes.

```python
print(dir())

print(dir(Employee))
```

---

## 🧠 __main__

Indicates current script context.

Example output:

```
<class '__main__.CoolClass'>
```

Means class was defined in current file.

---

## 📞 Calling Methods

```python
class Employee:
    def __init__(self, name):
        self.name = name

    def print_name(self):
        print("Hi, I'm " + self.name)

emp = Employee("Ibo")
emp.print_name()
```

---

