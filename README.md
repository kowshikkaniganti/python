# Python program to find the greatest of two numbers

# Taking input from the user
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

# Checking which number is greater
if num1 > num2:
    print(num1, "is the greatest number.")
elif num2 > num1:
    print(num2, "is the greatest number.")
else:
    print("Both numbers are equal.")
