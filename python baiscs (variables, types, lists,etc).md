
# Python Basics Cheat Sheet

## 1. Variables
- Variables store data.
- No need to declare type.
```python
name = "Mantasha"
age = 21
weight=45.3
```

## 2. Data Types
### Basic Types:
- **int** → whole numbers
- **float** → decimal numbers
- **str** → text
- **bool** → True/False

```python
x = 10        # int
y = 3.14      # float
z = "Hello"   # str
is_ok = True  # bool
```

---

## 3. Lists
- Lists store multiple items.
- Mutable (can change values).

```python
fruits = ["apple", "banana", "mango"]
print(fruits[0])  # accessing
fruits.append("orange")  # add
```

### Common List Methods
- append()
- remove()
- pop()
- sort()
- reverse()

---

## 4. Dictionaries
- Store data in key-value pairs.
- Keys must be unique.

```python
student = {
    "name": "Mantasha",
    "age": 23,
    "course": "MCA (AI and ML)"
}

print(student["name"])
student["age"] = 23
```

---

## 5. For Loop
Used for iterating over lists, strings, etc.

```python
for i in range(5):
    print(i)
```

```python
for fruit in fruits:
    print(fruit)
```

---

## 6. If-Else Conditions
```python
age = 18
if age >= 18:
    print("Adult")
else:
    print("Minor")
```

---

## 7. Functions
Reusable blocks of code.

```python
def greet(name):
    print("Hello", name)

greet("Mantasha ")
```

---

## 8. Input from User
```python
name = input("Enter your name: ")
print("Welcome", name)
```

---

## 9. Basic Operators
- `+` addition  
- `-` subtraction  
- `*` multiplication  
- `/` division  
- `%` modulus  
- `//` floor division  
- `**` exponent  

---

## 10. Important Notes
- Python is indentation-based.
- Everything is an object.
- Case-sensitive language.
