
# 🧮 Basic Functions Programming Challenge

## 📋 Overview
In this assignment, you will implement several basic Python functions to practice working with:

- Arithmetic operations  
- Control flow and conditionals  
- Loops and recursion  
- Error handling  
- String and list manipulation  

All your functions will be tested automatically using the **`unittest`** framework.  
Your goal is to **write the code** so that all tests pass successfully.

---

## 🧠 Functions to Implement

All functions must be written in `basic_functions.py`.  
Do **not** rename any of the functions or change their parameters.

---

### ⚠️ Important Rules
- Do **not** modify the test file.  
- Do **not** hardcode answers.  
- Ensure your code runs without errors.  
- Keep your code clean and readable.

---

### 1. `add(a, b)`
**Description:**  
Return the sum of two numbers.

**Examples:**
```python
add(1, 1) ➜ 2
```



### 2. `subtract(a, b)`
**Description:**  
Return the result of subtracting b from a.

**Examples:**
```python
subtract(2, 1) ➜ 1
```

---

### 3. `multiply(a, b)`
**Description:**  
Return the product of two numbers.

**Examples:**
```python
multiply(3, 3) ➜ 9
```

---

### 4. `divide(a, b)`
**Description:**  
Return the result of dividing a by b.  
If `b` is 0, raise a `ValueError`.

**Examples:**
```python
divide(10, 2) ➜ 5
divide(5, 0) ➜ ❌ raises ValueError
```

---

### 5. `fizz_buzz(n)`
**Description:**  
Return:
- `"Fizz"` if the number is divisible by 3  
- `"Buzz"` if the number is divisible by 5  
- `"FizzBuzz"` if divisible by both 3 and 5  
- Otherwise, return the number itself.

**Examples:**
```python
fizz_buzz(3)  ➜ "Fizz"
fizz_buzz(5)  ➜ "Buzz"
fizz_buzz(15) ➜ "FizzBuzz"
fizz_buzz(7)  ➜ 7
```

---

### 6. `fibonacci(n)`
**Description:**  
Return the n-th Fibonacci number.

The Fibonacci sequence starts as:
```
0, 1, 1, 2, 3, 5, ...
```

Each number is the sum of the two before it:
```
F(0) = 0  
F(1) = 1  
F(n) = F(n-1) + F(n-2)
```

**Examples:**
```python
fibonacci(0)  ➜ 0
fibonacci(1)  ➜ 1
fibonacci(10) ➜ 55
```

---

### 7. `triangle(n)`
**Description:**  
Return a list of strings representing a triangle made of asterisks (`*`).  
Each level of the triangle increases by two `*` characters.

**Examples:**
```python
triangle(0) ➜ []
triangle(1) ➜ ["*"]
triangle(2) ➜ ["*", "***"]
triangle(3) ➜ ["*", "***", "*****"]
triangle(4) ➜ ["*", "***", "*****", "*******"]
```
```
