# Day 06 Lecture Notes – Principles of Computing  
## Topic: Python – Advanced Printing, Variables, Literals, and Comments

---

## 🧠 Section 1: Variables

### 🔤 What is a Variable?
- A variable is a **name** that refers to a **value** stored in memory.
- Variables allow programs to remember and reuse information.

### ✅ Syntax
```python
name = "Jordan"
age = 16
height = 5.9
```

### 🧠 Naming Rules
- Must start with a letter or underscore (`_`)
- Can contain letters, digits, and underscores
- Cannot be a reserved Python keyword (`if`, `print`, `while`, etc.)

---

## 🔢 Section 2: Literals

### 📘 What is a Literal?
A literal is a **fixed value** used in Python code.

### 🧱 Types of Literals

| Type        | Example         |
|-------------|------------------|
| String      | `"hello"`        |
| Integer     | `42`             |
| Float       | `3.14`           |
| Boolean     | `True`, `False`  |

### ✅ Code Examples
```python
greeting = "Hello!"
year = 2024
pi = 3.14159
is_active = True
```

---

## 💬 Section 3: Comments

### 📗 What is a Comment?
- A comment is ignored by Python.
- Used to explain what your code is doing.

### ✅ Syntax
```python
# This is a comment
name = "Jordan"  # This sets the name
```

- Use comments to:
  - Describe code sections
  - Disable a line temporarily
  - Explain why something is done

---

## 🖨️ Section 4: Advanced Printing

### 🔹 `print()` with Commas
```python
print("Name:", name)
print("Age:", age)
```

### 🔹 String Concatenation
```python
print("Name: " + name)
```
- You **must** use `+` with string variables only.

### 🔹 f-Strings (Formatted Strings)
```python
print(f"Name: {name}, Age: {age}")
```
- Recommended style in Python 3.6+

---

## 🧪 Practice Demo Code

```python
# Store some personal information
name = "Maya"
grade = 10
gpa = 3.8
favorite_subject = "Math"

# Print it 3 ways
print("Name:", name, "| Grade:", grade, "| GPA:", gpa)
print("Name: " + name + " | Favorite Subject: " + favorite_subject)
print(f"{name} is in grade {grade} and loves {favorite_subject}.")
```

---

## 🎯 Key Vocabulary

| Term      | Definition |
|-----------|------------|
| Variable  | A named value that can change |
| Literal   | A fixed value in the code |
| Comment   | A line ignored by Python, used to explain code |
| f-string  | A formatting method using `{}` to insert values in strings |

---

## 📝 Bio Card Assignment

Ask students to create a Python program that:
- Uses 5 variables (e.g., name, age, hobby, dream job, favorite food)
- Prints a “bio” using all three formatting styles
- Includes at least 3 comments

**Example Output:**
```
Name: Sasha
Age: 15
Dream Job: Game Developer
Hobby: Drawing
Favorite Food: Sushi
```

---

## ❓ Exit Ticket Discussion

**Ask students:**
1. What is a variable?
2. What happens when you forget quotes around a string?
3. What was your favorite way to use `print()`?