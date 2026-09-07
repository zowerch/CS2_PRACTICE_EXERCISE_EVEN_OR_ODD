# CS2_PRACTICE_EXERCISE_EVEN_OR_ODD
A Computer Science practice activity!

# Description
This program asks the user to enter a number and determines whether the number is even or odd.

# How It Works
The program...
1. Gets a number from the user.
2. Uses the modulo operator `%` to check if the number is divisible by 2.
3. Prints `Even` if the remainder is 0.
4. Otherwise, it prints `Odd`.

# Code
```python

n = int(input("Enter a number:"))

if n % 2 == 0:
     print("Even")
else:
     print("Odd")




