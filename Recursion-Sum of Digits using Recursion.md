# #  Recursion:Sum of Digits using Recursion in Python

##  AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

##  ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## PROGRAM:

```
def sum_of_digits(n): 
     # Base case: if n is 0, return 0 
           if n == 0: 
               return 0 
           else: 
             # Recursive case: last digit + sum of remaining digits 
             return n % 10 + sum_of_digits(n // 10) 
# Input from the user 
number = int(input()) 
# Handling negative numbers 
number = abs(number)
```

## OUTPUT
![image](https://github.com/user-attachments/assets/c336916c-d051-45f4-a874-898a444100fe)

## RESULT
Thus the program has been successfully executed 
