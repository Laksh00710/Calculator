def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Cannot divide by zero"
    return x / y

if __name__ == "__main__":
    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))
    op = input("Choose operation (+, -, *, /): ")

    if op == '+':
        print(f"Result: {add(a, b)}")
    elif op == '-':
        print(f"Result: {subtract(a, b)}")
    elif op == '*':
        print(f"Result: {multiply(a, b)}")
    elif op == '/':
        print(f"Result: {divide(a, b)}")
    else:
        print("Invalid operator")
