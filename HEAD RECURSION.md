# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
```
def fun(n):
    if n == 0:
        return
    fun(n - 2)        
    print(n, end=' ') 

n = int(input())

if n % 2 != 0:
    n += 1

fun(n)
```

## OUTPUT
![image](https://github.com/user-attachments/assets/231d80e5-e0f1-4799-8de5-fceff2d9be43)

## RESULT
Thus, the program is verified successfully.
