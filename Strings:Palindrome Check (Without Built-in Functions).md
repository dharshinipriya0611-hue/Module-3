# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"malayalam"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"malayalam"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
~~~
n=str(input())
if n==n[::-1]:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
~~~

## Output
<img width="828" height="75" alt="image" src="https://github.com/user-attachments/assets/741d091a-ebb9-45fa-8a5c-91ddb3a0bdf9" />


## Result
Thus the output is verified
