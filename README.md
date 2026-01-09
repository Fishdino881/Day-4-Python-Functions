# Day-4-Python-Functions

Topics Covered

* Defining functions using `def`
* Passing parameters to functions
* Conditional logic inside functions
* Returning values using `return`
* Formatting output
* Using `pass` as a placeholder

---

Practice Examples

Example 1: Display Invoice

```python
def display_invoice(username, amount, due_date):
    print(f"Hello {username}")
    print(f"Your bill of ${amount:.2f} is due: {due_date}")

display_invoice("BroCode", 42.50, "01/02")
display_invoice("JoeSchmo", 100.99, "02/03")
```

---

Example 2: Create Full Name (Using Return)

```python
def create_name(first, last):
    first = first.capitalize()
    last = last.capitalize()
    return first + " " + last

full_name = create_name("spongebob", "squarepants")
print(full_name)
```

---

Example 3: Calculate Mean

```python
def calculateGmean(a, b):
    mean = (a * b) / (a + b)
    print(mean)
```

---

Example 4: Compare Two Numbers

```python
def isGreater(a, b):
    if a > b:
        print("First number is greater")
    else:
        print("Second number is greater or equal")
```

---

Example 5: Placeholder Function

```python
def isLesser(a, b):
    pass
```

---

Example 6: Function Calls

```python
a = 9
b = 8
isGreater(a, b)
calculateGmean(a, b)

c = 8
d = 74
isGreater(c, d)
calculateGmean(c, d)
```

---

Key Learnings

* Functions improve code reusability and clarity
* Parameters make functions flexible
* `return` allows functions to produce outputs
* `pass` is useful when designing future logic
* Clean function design improves maintainability

---

Author

Kunal
Learning Python fundamentals for AI & Data Science
Building consistency through daily practice



Just say the word.
