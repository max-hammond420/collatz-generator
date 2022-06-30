def collatz(n):
    l = [n]
    if n == 1:
        return [1]
    elif n % 2 == 0:
        l.extend(collatz(n//2))
    else:
        l.extend(collatz(3*n + 1))
    return l

assert collatz(6) == [6, 3, 10, 5, 16, 8, 4, 2, 1]
assert collatz(3) == [3, 10, 5, 16, 8, 4, 2, 1]
assert collatz(10) == [10, 5, 16, 8, 4, 2, 1]
assert collatz(1) == [1]
