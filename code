def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Error: Can't divide by zero."
    return x / y

def calculator():
    print(" ------Command Line Calculator------ ")

    while True:

        print("\nselect an operation:")
        print("1. Addition (+)")
        print("2. Subtraction (-)")
        print("3. Multiplication (*)")
        print("4. Division (/)")
        print("5. Exit")

        choice = input("Enter your option(1/2/3/4/5): ").strip()

        if choice == '5':
            print(" Exiting the calculator. Thank you!")
            break

        if choice not in ('1', '2', '3', '4'):
            print("Invalid choice !. Please enter a number from 1 to 5.")
            continue

        try:
            num1 = float(input("Enter the first number: ").strip())
            num2 = float(input("Enter the second number: ").strip())
        except ValueError:
            print("Invalid input !. Please enter valid numbers.")
            continue

        if choice == '1':
            result = add(num1, num2)
            print(f" Result: {num1} + {num2} = {result}")
        elif choice == '2':
            result = subtract(num1, num2)
            print(f" Result: {num1} - {num2} = {result}")
        elif choice == '3':
            result = multiply(num1, num2)
            print(f" Result: {num1} * {num2} = {result}")
        elif choice == '4':
            result = divide(num1, num2)
            print(f" Result: {num1} / {num2} = {result}")

if __name__ == "__main__":
    calculator()
