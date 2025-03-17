# intro-to-python

while True:
    print("1. Addition")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division")
    print("5. Enter q or Q to Exit")

    choice = input("Enter your choice: ")
    if choice == 'q' or choice == 'Q':
        break

    if choice == '1':
        print(num1, "+", num2, "=", num1 + num2)

    elif choice == '2':
        print(num1, "-", num2, "=", num1 - num2)
      
    elif choice == '3':
        print(num1, "*", num2, "=", num1 * num2)

    elif choice == '4':
        if num2 == 0:
            print("Division by zero is not allowed")
        else:
            print(num1, "/", num2, "=", num1 / num2)

    else:
        print("Invalid input")

        print()
