# EX.No:7(B) Recursion:Palindrome Checker Using Recursion in Python

## AIM:
To write a Python program to check whether a given string is a **palindrome** using **recursion**.

---

## ALGORITHM:

1. **Start**
2. Define a recursive function `is_palindrome(word)`
   - **Base Case:** If the string length is less than 1, return `True`
   - **Recursive Case:** If the first and last characters match, call the function recursively on the substring without first and last characters
   - Else, return `False`
3. Get input from the user
4. Call the recursive function
5. Print whether the string is a palindrome
6. **Stop**

---

## PROGRAM:
```
def is_palindrome(word):
    if len(word)<1: 
        return True 
    else: 
      if word[0]==word[-1]: 
           return is_palindrome(word[1:-1]) else: 
           return False
word = str(input())
if is_palindrome(word)==True:
    print("String is a palindrome") 
else: 
   print("String is not a palindrome") 
```

## OUTPUT
![image](https://github.com/user-attachments/assets/8a54d379-5f90-4151-90f2-20338813e56c)

## RESULT
Thus, the given program is implemented and executed successfully . 
