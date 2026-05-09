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
def find_modulo(a, b):
    return a % b
    
x = int(input("Enter first number: "))
y = int(input("Enter second number: "))
result = find_modulo(x, y)
print("Modulo:", result)
```
## Output
<img width="1209" height="225" alt="Screenshot 2026-05-09 204141" src="https://github.com/user-attachments/assets/faef4ac9-1bf0-40dc-9e8b-5fcbeb690662" />

## Result
The program was executed successfully. It accepts two integers, computes their modulo using the % operator inside a function, and prints the correct result.
