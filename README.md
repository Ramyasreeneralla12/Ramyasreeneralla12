- 👋 Hi, I’m @Ramyasreeneralla12
# Function to add two numbers
def add(x, y):
    return x + y

# Function to subtract two numbers
def subtract(x, y):
    return x - y

# Function to multiply two numbers
def multiply(x, y):
    return x * y

# Function to divide two numbers
def divide(x, y):
    if y == 0:
        return "Cannot divide by zero!"
    return x / y

# Displaying the operations available
print("Select operation:")
print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")

# User input for operation choice
choice = input("Enter choice (1/2/3/4): ")

# User input for numbers
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

# Perform calculation based on user choice
if choice == '1':
    print("Result:", add(num1, num2))
elif choice == '2':
    print("Result:", subtract(num1, num2))
elif choice == '3':
    print("Result:", multiply(num1, num2))
elif choice == '4':
    print("Result:", divide(num1, num2))
else:
    print("Invalid input")
