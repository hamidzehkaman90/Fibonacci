# Fibonacci
Numbers of the Fibonacci sequence

# i=for certine number fibonacci


def fibo(n):
    if n == 1:
        return 1
    if n == 2:
        return 1
    return fibo(n - 2) + fibo(n - 1)


def main():
    n = int(input('please enter number fibo:'))
    print('result is :')
    for i in range(1, n + 1):
        print(fibo(i), end="  ")


if __name__ == '__main__':
    main()
