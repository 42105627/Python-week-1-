# Python-week-1-

# Task 1: Greeting Message
name = input("Enter your name: ")
print(f"Hello, {name}! Welcome to Python programming.\n")

# Task 2: Area and Perimeter of a Rectangle
length = float(input("Enter the length of the rectangle: "))
width = float(input("Enter the width of the rectangle: "))

area = length * width
perimeter = 2 * (length + width)

print(f"Area of the rectangle: {area}")
print(f"Perimeter of the rectangle: {perimeter}\n")

# Task 3: Check if a Number is Even or Odd
number = int(input("Enter a number to check if it's even or odd: "))

if number % 2 == 0:
    print(f"{number} is even.\n")
else:
    print(f"{number} is odd.\n")

# Task 4: First 10 Square Numbers
print("The first 10 square numbers are:")
for i in range(1, 11):
    print(i**2)
print()  # Print a blank line for spacing

# Task 5: List of Student Names
students = ["Alice", "Bob", "Charlie"]

# Add a new student
students.append("Diana")

# Remove a student
students.remove("Bob")

# Sort the list
students.sort()

# Print the final student list
print("Final student list:", students)

