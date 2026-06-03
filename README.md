```
DONE BY: JAYASHREE J
REGISTER NUMBER: 212225040145
```
# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

```
a = 16
print(bin(a))
```

## Output
<img width="916" height="208" alt="image" src="https://github.com/user-attachments/assets/b220bdbc-2b9b-4c6b-91b1-f528493fbef2" />


## Result
Hence the task to write a Python program to convert the number **16** into its **binary representation** using built-in Python functions has been done successfully.

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program

```
def result(a, b):
    print(a % b)

a = int(input())
b = int(input())

result(a, b)
```
## Output
<img width="920" height="283" alt="image" src="https://github.com/user-attachments/assets/b1289d10-bf76-48da-8ef7-d11aad4602f6" />


## Result
Hence the task to write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator has been done successfully.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a = int(input())
b = int(input())

f = lambda a, b: a + b

print(f(a, b))
```
## Output
<img width="917" height="264" alt="image" src="https://github.com/user-attachments/assets/a4d10b73-f13d-4925-8160-5a9097969563" />

## Result
Hence the task to write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum has been executed successfully.

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
import math

rows = int(input())

for n in range(rows):
    for s in range(rows - n - 1):
        print(" ", end="")
    
    for k in range(n + 1):
        value = math.factorial(n) // (math.factorial(k) * math.factorial(n - k))
        print(value, end=" ")
    
    print()
```

## Sample Output
<img width="914" height="365" alt="image" src="https://github.com/user-attachments/assets/d6397f8e-e93e-49d9-a1dc-49ca3d281ca9" />

## Result
Hence the task to write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user has been done successfully.

