def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n-1)

def main():
    print("Factorial Calculator")
    
    # Get user input
    num = int(input("Enter a positive integer: "))
    
    if num < 0:
        print("Please enter a positive integer.")
    else:
        result = factorial(num)
        print(f"The factorial of {num} is {result}")

if __name__ == "__main__":
    main()
