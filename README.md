# study_of_sets_and_dictionary
learning sets and dictionary
# 📘 Study of Sets and Dictionaries in Python

**Name:** Dev Anand
**PRN:** 25070123039
**Batch:** A2
**Title:** To Study Sets and Dictionaries in Python

---

## 📌 Introduction to Python Collections

Python provides **four main built-in collection data types**:

1. **List** – Ordered, changeable, allows duplicates
2. **Tuple** – Ordered, unchangeable, allows duplicates
3. **Set** – Unordered, unchangeable*, no duplicates
4. **Dictionary** – Ordered, changeable, no duplicate keys

Each data type is used for different purposes depending on how data must be stored, accessed, and processed.

---

# 🔹 PART 1: SETS IN PYTHON

## ✅ What is a Set?

A **set** is a collection of unique elements stored in a single variable.

### Properties of a Set:

* ❌ No duplicate values allowed
* ❌ Unordered (no fixed position)
* ❌ Unindexed (no index numbers)
* ✅ Mutable (elements can be added/removed)
* ✅ Can store multiple data types

Syntax:

```python
set_name = {value1, value2, value3}
```

---

## 🧱 Creation of Set

```python
seett = {"chocolate","vanilla","pista"}
```

📌 Output may appear in any order because sets are **unordered**.

---

## 🚫 Duplicate Values Not Allowed

```python
seett = {"chocolate","vanilla","pista","chocolate"}
```

✔ Output contains only unique values.

---

## ⚠ True and 1 Behavior in Sets

```python
seett = {"chocolate","vanilla","pista",True,1,2}
```

📘 Explanation:

* `True` and `1` are considered equal in Python
* Boolean `True` = 1, `False` = 0

---

## 🎭 Mixed Data Types in Set

```python
set1 = {"abc",34,True,78,"female",10.5}
```

📌 Sets can store different data types together.

---

## 🔍 Membership Check

```python
print("chocolate" in seett)
```

✔ Used to check if element exists in set

---

## ➕ Adding Elements

```python
seett.add("mango")
```

📘 Sets are mutable → elements can be added

---

## ➖ Removing Elements

```python
seett.remove("pista")
```

📌 `remove()` throws error if item not found
📌 `discard()` does not throw error

---

# 🔁 Set Operations

Let:

```python
A = {12,13,14,15,16}
B = {16,17,18,19,20}
```

### 🔹 Union

```python
A | B
```

📘 Combines all elements

### 🔹 Intersection

```python
A & B
```

📘 Common elements

### 🔹 Difference

```python
A - B
```

📘 Elements in A but not in B

### 🔹 Symmetric Difference

```python
A ^ B
```

📘 Elements in either A or B but not both

---

# ❄ Frozenset

## What is Frozenset?

A **frozenset** is an immutable version of a set.

### Properties:

* ❌ Cannot add elements
* ❌ Cannot remove elements
* ❌ Cannot modify
* ✅ Supports set operations

```python
x = frozenset({"chocolate","vanilla","pista"})
```

📌 Used for security, data integrity, and fixed datasets

---

# 🧠 Problem Statements Using Sets

## 1️⃣ Unique Event Participants

### Concept Used: `set()` for removing duplicates

```python
registered = ["Dev","Ram","Riya","Manas","Rohan","Dev","Manas","Amit","Riya"]
uniqregistered = set(registered)
```

📘 Set automatically removes duplicates

---

## 2️⃣ Common Electives

### Concept Used: Intersection

```python
common = Dev & Asit & Akshu
```

📘 Finds common subjects

---

## 3️⃣ Club Membership

* Both clubs → `&`
* Only one club → `^`

---

## 4️⃣ Absent Students

```python
total - present
```

📘 Difference gives absent students

---

## 5️⃣ Remove Invalid Course

```python
course.remove("english112")
course.discard("EG115")
```

📘 `remove()` → error if not found
📘 `discard()` → safe removal

---

# 🔹 PART 2: DICTIONARIES IN PYTHON

## ✅ What is a Dictionary?

A **dictionary** stores data in **key : value pairs**.

Syntax:

```python
dict_name = {key1:value1, key2:value2}
```

---

## 📌 Properties of Dictionary

* ✅ Ordered (Python 3.7+)
* ✅ Mutable
* ❌ No duplicate keys
* ✅ Fast data access

---

## 🧱 Dictionary Creation

```python
thisdict = {
  "brand":"Porche",
  "model":"GTR",
  "year":1978
}
```

---

## 🔍 Retrieving Values

```python
thisdict["brand"]
```

---

## 🚫 Duplicate Keys

```python
"year":1978,
"year":2026
```

📘 Latest value overwrites old value

---

## ➕ Adding Elements

```python
car["color"] = "green"
```

---

## 🔄 Updating Elements

```python
student["name"] = "Dev"
```

---

## ➖ Removing Elements

```python
student.pop("branch")
```

---

# 🧠 Dictionary Problem Statements

## 1️⃣ Product Price Update

📘 Key-based update

---

## 2️⃣ Student Marks Finder

```python
stud.get(name, "Student not found")
```

📘 `get()` prevents error

---

## 3️⃣ Login Validation System

### Logic:

```python
if dataa.get(username) == password:
```

📘 Compares stored password with input password

---

## 4️⃣ Highest Marks Finder

```python
topper = max(marks, key=marks.get)
```

📘 Uses value comparison instead of keys

---

# 🎯 Educational Value

This practical demonstrates:

* Real-world use of sets
* Data cleaning using sets
* Logical filtering
* Authentication logic
* Data modeling using dictionaries
* Efficient searching
* Academic problem solving

---

# ✅ Conclusion

Sets and dictionaries are **core data structures** in Python.

### Sets are used for:

* Removing duplicates
* Membership testing
* Data comparison
* Filtering

### Dictionaries are used for:

* Databases
* Authentication systems
* Student records
* Product management
* Configuration files

---

📚 This experiment builds strong fundamentals for:

* Data Science
* AI/ML
* Backend development
* Cybersecurity
* Competitive programming
* Software engineering

---

## ✍ Author

**Dev Anand**
B.Tech ENTC – Symbiosis Institute of Technology, Pune

---
