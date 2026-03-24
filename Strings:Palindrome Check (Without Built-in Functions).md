# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
string = "google"
reversed_string = string[::-1]

if string == reversed_string:
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")
```


## Output

<img width="1552" height="989" alt="image" src="https://github.com/user-attachments/assets/51029bf9-6336-49d4-b82f-2ba90d493c30" />



## Result
The program successfully checked that "google" is not a palindrome.
