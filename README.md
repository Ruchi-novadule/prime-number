🔢 Prime Number Checker in Python

This is a simple Python program that checks whether a given number is a prime number or not.
The program takes input from the user and prints the result.

📌 Features

Takes user input

Checks if the number is prime

Uses loop and conditional statements

Beginner-friendly logic

Easy to understand

💻 Technology Used

Python 3

🚀 How It Works

The program takes an integer input from the user.

If the number is less than or equal to 1, it is not prime.

Otherwise, it checks divisibility from 2 to num - 1.

If any number divides it completely, it is not prime.

If no divisor is found, the number is prime.

📝 Code
num = int(input("Enter a number: "))

if num <= 1:
    print("Not a Prime Number")
else:
    is_prime = True
    
    for i in range(2, num):
        if num % i == 0:
            is_prime = False
            break
    
    if is_prime:
        print("Prime Number")
    else:
        print("Not a Prime Number")
▶️ Example

Input:

Enter a number: 7

Output:

Prime Number

Input:

Enter a number: 10

Output:

Not a Prime Number
🎯 Learning Concepts

Conditional statements (if-else)

Loops (for)

Boolean variables

Basic number logic

User input handling

