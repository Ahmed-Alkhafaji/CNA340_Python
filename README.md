# CNA340_Python #

def lone_sum(a, b, c):
    if a >= b:
        return c
    elif a == c:
        return b
    elif b == c:
        return a
    elif a == b and a == c and b == c:
        return 0
    else:
        print(a+b+c)
