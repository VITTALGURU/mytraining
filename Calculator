def calculator():
    print("Simple Calculator")
    print("Operations: +  -  *  /")

    # Take inputs
    num1 = float(input("Enter first number: "))
    op = input("Enter operator (+, -, *, /): ")
    num2 = float(input("Enter second number: "))

    # Perform calculation
    if op == '+':
        result = num1 + num2
    elif op == '-':
        result = num1 - num2
    elif op == '*':
        result = num1 * num2
    elif op == '/':
        if num2 != 0:
            result = num1 / num2
        else:
            return "Error: Cannot divide by zero!"
    else:
        return "Invalid operator!"

    return f"Result: {result}"

print(calculator())
