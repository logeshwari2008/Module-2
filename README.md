## Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim

To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

## 🧠 Algorithm

Assign the value 16 to a variable a.
Use the built-in bin() function to convert the number to binary.
Print the result.

## 🧾 Program

```
a=16
b=bin(a)
print(b)
```
## Output:

<img width="477" height="191" alt="image" src="https://github.com/user-attachments/assets/3f582685-2196-40b2-a120-886ba7a263cf" />

## Result:

Thus to write a Python program to convert the number 16 into its binary representation using built-in Python functions is done successfully.

## Functions in Python: Modulo Calculator

## 🎯 Aim

To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

## 🧠 Algorithm

Define a function called result that takes two arguments a and b.
Inside the function, compute the modulo using a % b.
Print the result of the modulo operation.
Get two integer inputs from the user.
Call the result function with the user-provided values.

## 🧾 Program

```
def result(a,b):
    modulo=a%b
    return modulo
    
a=int(input())
b=int(input())
modulo=result(a,b)
print("modulo is",modulo)

```
## Output:

<img width="563" height="253" alt="WhatsApp Image 2026-06-01 at 9 00 26 AM" src="https://github.com/user-attachments/assets/30b56e45-beec-4cb8-9bae-62338d5e03d4" />

## Result:

Thus to write a Python program that defines a function which accepts two values and returns their modulo using the % operator is done successfully.

## Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim

To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

## 🧠 Algorithm

Get two integer inputs from the user.
Use a lambda function to define a function f that returns a + b.
Call the function with the user inputs and print the result.
## 🧾 Program

```
f = lambda a, b: a + b

a = int(input())
b = int(input())

print(f(a, b))
```
## Output:

<img width="379" height="247" alt="WhatsApp Image 2026-06-01 at 9 05 04 AM" src="https://github.com/user-attachments/assets/10e7848d-77db-49fc-a23a-41fe43c92947" />

## Result:

Thus to write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum is done successfully.

## 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

## 🎯 Aim

To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

## 🧠 Algorithm

Start the program.
Input the number of rows from the user.
Loop from 0 to the number of rows.
For each row:
Print appropriate spaces to shape the triangle.
Compute values using the formula:
[ C(n, k) = \frac{n!}{k!(n-k)!} ]
Print all rows of Pascal’s Triangle.
End the program.

## 🧪 Program

```
import math
def pascal_triangle(rows):
    for n in range(rows):
        print(" " * (rows - n), end="")

        for k in range(n + 1):
            value = math.factorial(n) // (math.factorial(k) * math.factorial(n - k))
            print(value, end=" ")

        print()

rows = int(input("Enter the number of rows: "))
pascal_triangle(rows)
```
## Sample Output:

<img width="663" height="550" alt="image" src="https://github.com/user-attachments/assets/eeb5bf27-ad9c-43cd-bdfd-357c112cca05" />

## Result:

Thus to write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is done successfully.

## Loops in Python: Palindrome Number Checker

🎯 Aim

To write a Python program that checks whether a given number is a palindrome using loops.

## 🧠 Algorithm

Get input from the user and assign it to a variable num.
Assign the value of num to a temporary variable temp.
Initialize a variable rev to 0 (used to store the reversed number).
Use a while loop to reverse the digits:
While temp > 0:
rev = (10 * rev) + temp % 10
temp = temp // 10
After the loop, compare rev with num:
If equal, print that the number is a palindrome.
Else, print that it is not a palindrome.

## 🧾 Program

```
num=int(input())
rev=0
temp=num
while temp>0:
    r= temp %10
    rev = rev*10 + r
    temp //=10
if rev == num :
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))

```
## Output:
<img width="1076" height="287" alt="image" src="https://github.com/user-attachments/assets/fead2f35-6c6e-447f-beec-4485f325027c" />

## Result:
Thus to write a Python program that checks whether a given number is a palindrome using loops is done successfully.


