# Codsoft-task-2
def calculator():
    print("Simple Calculator")
    print("Available operations: +, -, *, /")
    
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))
    
    operation = input("Enter the operation (+, -, *, /): ")

    if operation == '+':
        result = num1 + num2
        print(f"Result: {num1} + {num2} = {result}")
    elif operation == '-':
        result = num1 - num2
        print(f"Result: {num1} - {num2} = {result}")
    elif operation == '*':
        result = num1 * num2
        print(f"Result: {num1} * {num2} = {result}")
    elif operation == '/':
        if num2 == 0:
            print("Error: Cannot divide by zero.")
        else:
            result = num1 / num2
            print(f"Result: {num1} / {num2} = {result}")
    else:
        print("Invalid operation selected.")

calculator()
