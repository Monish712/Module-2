# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
x=16
y=bin(x)
print(y)
```

## Output
![image](https://github.com/user-attachments/assets/748f0062-c803-4fd0-aea9-00dc4568e854)


## Result
Thus the python program is executed successfully


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
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))
```

## Output
![image](https://github.com/user-attachments/assets/e9dece7f-876b-442d-a868-abe0f7008174)


## Result
Thus the python code is executed successfully


# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```i=int(input())
j=int(input())
z=int(input())

f = lambda a, b,c: a+b+c

print(f(i, j,z))
```

## Output
![image](https://github.com/user-attachments/assets/dbe750b9-0bff-4147-bb94-aa4f2481a378)

## Result
Thus,the Python program that defines a lambda function which takes two arguments a and b, and returns their sum is created successfully.

