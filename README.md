task 1 :-

def factorial(n):
    result = 1
    for i in range(1, n+1):
        result *= i
    return result

num = int(input("Enter a number: "))

print(f"Factorial of {num} is: {factorial(num)}")

task 2:- 

num = float(input("Enter a number: "))

square_root = math.sqrt(num)
logarithm = math.log(num)
sine = math.sin(num)

print(f"Square root: {square_root}")
print(f"Logarithm: {logarithm}")
print(f"Sine: {sine}")
