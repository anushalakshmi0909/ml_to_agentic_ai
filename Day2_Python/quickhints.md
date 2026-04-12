# Python Quick Notes – Day 2

Fast revision notes for interviews.

---

# Print Statement

Displays output to console.

```python
print("Hello World")
```

Strings must use quotes.

---

# Variables

Variables store values.

Example:

```python
a = 10
name = "Anu"
```

Python variables are **dynamically typed**.

---

# Data Types

Common beginner data types:

| Type | Example |
| ---- | ------- |
| int  | 10      |
| str  | "Hello" |

---

# Arithmetic Operators

| Operator | Example |
| -------- | ------- |
| +        | a + b   |
| -        | a - b   |
| *        | a * b   |
| /        | a / b   |

Example:

```python
a = 10
b = 5
print(a + b)
```

---

# User Input

Used to get data from user.

```python
name = input("Enter name: ")
```

Important:

`input()` **always returns a string**

---

# Type Casting

Convert one data type to another.

Example:

```python
age = int(input("Enter age: "))
```

Common conversions:

```
int()
float()
str()
```

---

# Small Program Example

```python
name = input("Enter name: ")
age = int(input("Enter age: "))

print("My name is", name)
print("My age is", age)
```

---

# Core Programming Pattern

```
Input → Process → Output
```

Example:

```python
a = int(input())
b = int(input())

print(a + b)
```

---

# Interview Tip

Common beginner mistake:

```
a = input()
b = input()

print(a + b)
```

Output:

```
23
```

Why?

Because input is stored as **string**.

Correct way:

```python
a = int(input())
b = int(input())

print(a + b)
```

---

# Day 2 Summary

* print() → display output
* variables → store data
* data types → int, str
* arithmetic operators → + - * /
* input() → user input
* type casting → convert types

These are **core fundamentals for Python programming**.
