# EX.No:7(A) Types of Recursion: Head Recursion in Python

## AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## PROGRAM:
```
def fun(n): 
    if (n >0): 
       fun(n - 2) 
       print(n-1, end=" )
x = int(input()) 
if(x%2==0): 
   fun(x ) 
else: 
   fun(x+1)
```


## OUTPUT
![image](https://github.com/user-attachments/assets/d5ed5ee1-45e8-4aba-90b1-564501896c19)

## RESULT
Thus, the given program is implemented and executed successfully.
