# Experiment-0

## LAB REPORT: INTRODUCTION TO PYTHON BASICS

**Student Name:** Vedant Trivedi

**PRN:** 25070123121

**Experiment No:** 0

**Date:** February 3, 2026

---

### 1. AIM:

To understand the fundamentals of Python programming, specifically variable assignment, handling diverse data types (integers, lists, and strings), and utilizing the `print()` function with custom separators.

---

### 2. THEORY:

Python is a dynamically typed language, meaning variables do not need an explicit declaration to reserve memory space.

* **Integers (`int`):** Used for whole numbers.
* **Lists (`list`):** An ordered, mutable collection of elements.
* **Strings (`str`):** A sequence of characters used for text.
* **The `print()` Function:** A built-in function to output data. The `sep` parameter allows users to define how multiple objects are separated in the output (e.g., `\n` for a new line).

---

### 3. LOGIC:

The script initializes three distinct variables:

1. **Scalar Assignment:** An integer `x` is assigned a numeric value.
2. **Collection Assignment:** A list `y` is created containing three integers.
3. **String Assignment:** A string `z` stores the student's name.
4. **Formatted Output:** All three variables are passed into a single print statement, using the newline separator to ensure each value appears on its own line for better readability.

---

### 4. ALGORITHM:

**Step 1:** Start.

**Step 2:** Assign the value `2` to variable `x`.

**Step 3:** Initialize variable `y` as a list containing `[1, 2, 5]`.

**Step 4:** Assign the string `"vedant"` to variable `z`.

**Step 5:** Call the `print()` function with arguments `x`, `y`, and `z`.

**Step 6:** Set the `sep` parameter to `"\n"` to insert a line break between each variable.

**Step 7:** End.

---

### 5. CODE & OUTPUT:

**Code:**

```python
x = 2
y = [1, 2, 5]
z = "vedant"
print(x, y, z, sep="\n")

```

**Output:**

```text
2
[1, 2, 5]
vedant

```

---

### 6. CONCLUSION:

In this experiment, I successfully demonstrated the basics of Exploratory Data Analysis by initializing and displaying different data structures. The use of the `sep="\n"` parameter showed how Python provides concise control over output formatting. This foundational step is essential for managing more complex data manipulations in future experiments.

---
