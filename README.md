# Divide-two-Integers
dividend=int(input())
divisor=int(input())
Max = 2**31 - 1
Min = -2**31
if dividend == Min and divisor == -1:
    print(Max)
result = int(dividend / divisor)
if result < Min:
        print(Min)
if result > Max:
    print(Max)
print(result)
