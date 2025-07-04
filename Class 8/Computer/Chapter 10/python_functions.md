## Python Functions

### 🔹 **Python Functions – Explanation with Examples**

A **function** in Python is a **block of reusable code** that performs a specific task.

---

## ✅ 1. **Why Use Functions?**

* To **organize code** better.
* To **avoid repeating code**.
* To make programs **easier to understand and manage**.

---

## ✅ 2. **Defining a Function**

You define a function using the `def` keyword.

```python
def greet():
    print("Hello, welcome to Python!")
```

---

## ✅ 3. **Calling a Function**

After defining it, you can call it by its name followed by parentheses:

```python
greet()
```

**Output:**

```
Hello, welcome to Python!
```

---

## ✅ 4. **Function with Parameters**

You can pass values (called **arguments**) to a function using **parameters**:

```python
def greet(name):
    print("Hello", name)
```

```python
greet("Alice")
```

**Output:**

```
Hello Alice
```

---

## ✅ 5. **Function with Return Value**

A function can **return** a value using the `return` keyword:

```python
def add(a, b):
    return a + b

result = add(5, 3)
print(result)
```

**Output:**

```
8
```

---

## ✅ 6. **Types of Functions**

| Type                       | Example                                         |
| -------------------------- | ----------------------------------------------- |
| **Built-in functions**     | `print()`, `len()`, `range()`                   |
| **User-defined functions** | Functions you create using `def`                |
| **Lambda functions**       | Small anonymous functions, e.g. `lambda x: x*2` |

---

## ✅ 7. **Default Parameter Value**

```python
def greet(name="Guest"):
    print("Hello", name)

greet()          # uses default
greet("Ravi")    # uses given value
```

**Output:**

```
Hello Guest
Hello Ravi
```

---

## ✅ 8. **Keyword Arguments**

You can name the arguments while calling:

```python
def student(name, age):
    print(name, "is", age, "years old.")

student(age=12, name="Asha")
```

**Output:**

```
Asha is 12 years old.
```

---

## ✅ 9. **Variable-Length Arguments**

* `*args` for any number of **positional arguments**.
* `**kwargs` for any number of **keyword arguments**.

```python
def total(*numbers):
    return sum(numbers)

print(total(1, 2, 3, 4))  # Output: 10
```

---