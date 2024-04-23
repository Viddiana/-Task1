# FIBONACCI CODE
def fibonacci(n):
    fib_series = [0, 1]
    for i in range(2, n):
        fib_series.append(fib_series[i-1] + fib_series[i-2])
    return fib_series[:n]
#VALUE THAT YOU WANT FIND FIBONACCI 
n = int(input("Enter the number of Fibonacci numbers to generate: "))
print(fibonacci(n))
