## Types of Loops In Python

In Python, there are **three main types of loops** used for repeating a block of code:

---

### **1. `for` loop**

Used to iterate over a **sequence** (like a list, tuple, string, or range).

**Syntax:**

```python
for item in sequence:
    # code block
```

**Example:**

```python
for i in range(5):
    print(i)
```

---

### **2. `while` loop**

Repeats as long as a **condition is true**.

**Syntax:**

```python
while condition:
    # code block
```

**Example:**

```python
i = 0
while i < 5:
    print(i)
    i += 1
```

---

### **3. Nested Loops**

A loop inside another loop.

**Example:**

```python
for i in range(3):
    for j in range(2):
        print(i, j)
```

---

### Optional: `loop control statements`

* **`break`** – Exit the loop early.
* **`continue`** – Skip the current iteration.
* **`pass`** – Do nothing (placeholder).

**Example:**

```python
for i in range(5):
    if i == 3:
        break
    print(i)
```


