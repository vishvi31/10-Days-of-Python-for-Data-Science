# Day 01 - Variables, Data Types and Conditionals

Date: 2026-05-27
Author: Vishvi

---

## What to Practice Today

Write all of this yourself in Jupyter Notebook first!
Then push this file to GitHub.

---

## 1. Variables and Data Types

```python
# Strings
name = 'Vishvi'
course = 'Data Science'
print(name, 'is learning', course)
print(type(name))

# Integers and Floats
age = 23
gpa = 8.9
print(age, type(age))
print(gpa, type(gpa))

# Boolean
is_student = True
print(is_student, type(is_student))

# List, Tuple, Set, Dict
skills = ['Python', 'SQL', 'ML', 'NLP']
coords = (28.6, 77.2)
unique = {1, 2, 2, 3, 3}
person = {'name': 'Vishvi', 'age': 23}

print(skills)
print(coords)
print(unique)
print(person)
```

---

## 2. String Methods (important for NLP later!)

```python
text = '  Hello Data Science World  '

print(text.strip())
print(text.strip().lower())
print(text.strip().upper())
print(text.strip().replace('World', 'Vishvi'))
print(text.strip().split())
print(len(text.strip()))
print('Data' in text)
```

---

## 3. Conditionals

```python
score = 78

if score >= 90:
    print('Grade A')
elif score >= 75:
    print('Grade B')
elif score >= 60:
    print('Grade C')
else:
    print('Grade F')

# One-liner
result = 'Pass' if score >= 60 else 'Fail'
print(result)

# Nested
age = 23
has_degree = True
if age >= 21 and has_degree:
    print('Eligible for Data Science role')
else:
    print('Keep building skills!')
```

---

## 4. Practice Exercises (write these yourself!)

1. Create a variable for your name, age, and favourite language.
2. Write a conditional that prints your study level based on hours studied.
3. Create a dictionary of your top 3 Data Science projects with their AUC scores.
4. Use string methods to clean this: '  data SCIENCE is FUN  '

---

## What I Learned Today

Write your own notes here after practicing!

---

## Tomorrow - Day 02

Topic: Loops and List Comprehensions
